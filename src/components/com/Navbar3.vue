<template>
    <nav>
      <div class="navbar-logo">Logo</div>
      <button class="navbar-toggle" @click="toggleNavbar">
        <span class="navbar-toggle-icon"></span>
      </button>
      <ul class="navbar-links" :class="{ 'active': isOpen }">
        <li><a href="#">Home</a></li>
        <li><a href="#">About</a></li>
        <li class="navbar-dropdown" @click="toggleDropdown">
          <a href="#">Dropdown</a>
          <ul class="navbar-dropdown-menu" :class="{ 'active': isDropdownOpen }">
            <li><a href="#">Item 1</a></li>
            <li><a href="#">Item 2</a></li>
            <li><a href="#">Item 3</a></li>
          </ul>
        </li>
        <li><a href="#">Contact</a></li>
      </ul>
    </nav>
  </template>
  
  <script>
  export default {
    data() {
      return {
        isOpen: false,
        isDropdownOpen: false
      };
    },
    methods: {
      toggleNavbar() {
        this.isOpen = !this.isOpen;
      },
      toggleDropdown() {
        this.isDropdownOpen = !this.isDropdownOpen;
      }
    }
  };
  </script>
  
  <style scoped>
  nav {
    display: flex;
    align-items: center;
    justify-content: space-between;
    background-color: #333;
    color: #fff;
    padding: 10px;
  }
  
  .navbar-logo {
    font-weight: bold;
  }
  
  .navbar-links {
    display: flex;
    list-style: none;
    margin: 0;
    padding: 0;
  }
  
  .navbar-links.active {
    display: block;
  }
  
  .navbar-links li {
    margin-right: 10px;
    position: relative;
  }
  
  .navbar-links a {
    color: #fff;
    text-decoration: none;
  }
  
  .navbar-toggle {
    display: none;
    background-color: transparent;
    border: none;
    cursor: pointer;
  }
  
  .navbar-toggle-icon {
    display: block;
    width: 20px;
    height: 2px;
    background-color: #fff;
    position: relative;
  }
  
  .navbar-toggle-icon::before,
  .navbar-toggle-icon::after {
    content: "";
    position: absolute;
    width: 20px;
    height: 2px;
    background-color: #fff;
  }
  
  .navbar-toggle-icon::before {
    top: -6px;
  }
  
  .navbar-toggle-icon::after {
    top: 6px;
  }
  
  @media (max-width: 768px) {
    .navbar-links {
      display: none;
    }
  
    .navbar-toggle {
      display: block;
    }
  
    .navbar-links.active {
      display: block;
    }
    
    .navbar-dropdown {
      position: relative;
    }
    
    .navbar-dropdown .navbar-dropdown-menu {
      display: none;
      position: absolute;
      top: 100%;
      left: 0;
      background-color: #333;
      padding: 10px;
    }
    
    .navbar-dropdown .navbar-dropdown-menu.active {
      display: block;
    }
    
    .navbar-dropdown .navbar-dropdown-menu li {
      margin: 0;
    }
  }
  </style>