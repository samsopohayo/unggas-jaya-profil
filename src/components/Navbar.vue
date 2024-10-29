<template>
  <header :class="{ 'scrolled-up': isScrolledUp }">
    <nav class="navbar navbar-expand-lg navbar-light">
      <div class="container-fluid d-flex justify-content-between">
        <a class="navbar-brand" href="#home">
          <img
            src="./../assets/logo-naf.png"
            alt="Logo Unggas Jaya"
            class="logo-img"
          />
        </a>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div
          class="collapse navbar-collapse justify-content-end"
          id="navbarSupportedContent"
        >
          <div class="d-flex">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
              <li class="nav-item" v-for="(item, index) in navItems" :key="index">
                <a
                  class="nav-link"
                  :href="`#${item}`"
                  :class="{ active: activeItem === item }"
                  @click="setActive(item)"
                >{{ capitalize(item) }}</a>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </nav>
  </header>
</template>

<script>
export default {
  data() {
    return {
      activeItem: 'home',
      isScrolledUp: true,
      lastScrollPos: 0,
      navItems: ['home', 'about', 'services', 'testimonials', 'gallery', 'contact'],
    };
  },
  methods: {
    setActive(item) {
      this.activeItem = item;

      // Hide the navbar temporarily
      this.isScrolledUp = false;
      
      // Scroll to the target section
      const section = document.getElementById(item);
      if (section) {
        section.scrollIntoView({ behavior: 'smooth' });
      }

      setTimeout(() => {
        this.isScrolledUp = false;
      }, 1000); // Sesuaikan waktu berdasarkan durasi scroll
    },
    handleScroll() {
      const currentScrollPos = window.pageYOffset;
      this.isScrolledUp = currentScrollPos > this.lastScrollPos;
      this.lastScrollPos = currentScrollPos;
    },
    capitalize(text) {
      return text.charAt(0).toUpperCase() + text.slice(1);
    }
  },
  mounted() {
    window.addEventListener('scroll', this.handleScroll);
  },
  beforeDestroy() {
    window.removeEventListener('scroll', this.handleScroll);
  },
};
</script>

<style scoped>
header {
  position: fixed;
  width: 100%;
  top: 0;
  transition: top 0.4s;
  z-index: 1000;
}
header.scrolled-up {
  top: -80px;
}
.navbar {
  background-color: rgba(255, 255, 255, 0);
  transition: background-color 0.3s;
}
.nav-item{
  margin-right: 1rem;
}
.navbar .nav-link {
  border-radius: 10px;
  color: #ffffff;
  padding: 0.5rem 1rem;
  transition: color 0.3s ease, background-color 0.3s ease, border-radius 0.3s ease;
  font-weight: 600;
}
.navbar .nav-link.active,
.navbar .nav-link:hover {
  border-radius: 10px;
  background-color: #f0f0f0;
  color: rgb(115, 24, 24);
  font-weight: 600;
}
</style>

