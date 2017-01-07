<template>
  <div id="app">

    <home></home>
    <about></about>
    <tech></tech>
    <work></work>
    <contact></contact>
    <links :links="socialLinks"></links>
  </div>
</template>

<script>
  import Home from './components/Home.vue'
  import About from './components/about.vue'
  import Tech from './components/tech.vue'
  import Work from './components/work.vue'
  import Contact from './components/contact.vue'
  import Links from './components/links.vue'

  export default {
    data: {
      socialLinks: [
        {
          name: 'Google +',
          link: 'http://google.com',
          logo: 'github'
        },
        {
          name: 'Github',
          link: 'http://google.com',
          logo: 'github'
        },
        {
          name: 'Twitter',
          link: 'http://google.com',
          logo: 'github'
        },
        {
          name: 'LinkedIn',
          link: 'http://google.com',
          logo: 'github'
        }
      ]
    },
    methods: {
      
    },
    components: {
      'home': Home,
      'about': About,
      'tech': Tech,
      'work': Work,
      'contact': Contact,
      'links': Links
    },
    mounted: function () {

    }
  }
</script>

<style>
  body {
    font-family: Helvetica, sans-serif;
  }
</style>
