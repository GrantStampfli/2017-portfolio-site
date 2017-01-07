<template>
  <h4>Link Section</h4>
</template>

<script>
export default {
  data: function () {
    return {

    }
  },
  props: {
  	linkList: {
  		type Array,
  		required: true,
  		default: [
			{
				name: 'Github',
				link: 'http://github.com',
				logo: 'github'	
  			}
  		]
  	}
  	['name', 'link', 'logo']
  },
  methods: {
    
  }
}
</script>

<style>

</style>

<!-- 
{
  name: 'Google +',
  link: 'http://google.com',
  logo: 'github'
}, -->