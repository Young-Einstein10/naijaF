<template>

  <div class="menu-container">

    <!-- root level itens -->
    <ul class="menu">

      <li class="menu__top">
        <center><router-link to="/" class="menu__logo">
          <img src="/Group 95.png" alt="icon">
        </router-link></center>
        <a
        href="#"
        @click.prevent="openProjectLink"
        class="menu__title"
        > 
        </a>
      </li>

      <li class="padli">
        <a
        href="#"
        @click.prevent="updateMenu('home')"
        :class="highlightSection('home')"
        >
            <i class="fa fa-th-large menu__icon" aria-hidden="true"></i>
            <label>Overview</label>
        </a>
      </li>

      <li class="padli">
        <a
        href="#"
        @click.prevent="updateMenu('menu')"
        :class="highlightSection('menu')"
        >
          <i class="fa fa-tag menu__icon"  aria-hidden="true"></i>
          <label>Menu</label>
          
        </a>
      </li>

      <li class= "padli">
        <a
        href="#"
        @click.prevent="updateMenu('transaction')"
        :class="highlightSection('transaction')"
        >
          <i class="fa fa-usd menu__icon" aria-hidden="true"></i>
          <label>Transaction</label>
        </a>
      </li>

      <li class="padli">
        <a
        href="#"
        @click.prevent="updateMenu('signup')"
        :class="highlightSection('signup')"
        >
          <i class="fa fa-user menu__icon" aria-hidden="true"></i>
          <label>Sign Up</label>
        </a>
      </li>

      <li class="padli">
        <a
        href="#"
        @click.prevent="updateMenu('login')"
        :class="highlightSection('login')"
        >
          <i class="fa fa-users menu__icon" aria-hidden="true"></i>
          <label>Login</label>
        </a>
      </li>


      <li class="padli">
        <a
        href="#"
        @click.prevent="updateMenu('faq')"
        :class="highlightSection('faq')"
        >
          <i class="fa fa-question-circle menu__icon" aria-hidden="true"></i>
          <label>FAQ</label>
        </a>
      </li>
      
      <div class="details-container" style="">
          <div class="address">
            25 Montgomery road, Yaba Lagos, Nigeria.
          </div>
          <div class="phonemail">
          <p>+234 7036188527</p>
          <p>hello@naijafries.com</p>
          </div>
      </div>
    
    </ul>

    
  </div>

</template>


<script>

import menuData from './support/menu-data';
import kebabCase from 'lodash/kebabCase';

export default {
  name: 'Menu',

  data(){
    return {
      contextSection: '',

      menuItens: [],

      menuData: menuData,

      activeSubMenu: ''
    }
  },

  methods: {

    openProjectLink() {
      alert('You could open the project frontend in another tab here, so the logged admin could see changes made to the project ;)');
    },

    updateMenu(context) {
      this.contextSection = context;
      this.menuItens = this.menuData[context];

      if (context === 'home') {
        this.$router.push('/');
        window.bus.$emit('menu/closeMobileMenu');
      }
    },

    highlightSection(section) {
      return {
        'menu__link': true,
        'menu__link--active': section === this.contextSection,
      };
    },



  },

  computed: {
    showContextMenu() {
      return this.menuItens.length;
    },
  }

}
</script>
