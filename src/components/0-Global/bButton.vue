<template>
<div class="portfolio-experiment">
   <a id="b__btn" :href="externalLink">
     <span class="text"><v-icon>{{btnIcon}}</v-icon>{{btnText}}</span>
     <span class="line -right"></span>
     <span class="line -top"></span>
     <span class="line -left"></span>
     <span class="line -bottom"></span>
   </a>
</div>
</template>
<script>
export default {
  name: 'bbutton',
  props: ['externalLink', 'btnIcon', 'btnText']
}
</script>
<style>
</style>
