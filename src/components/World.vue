<template>
	<div class="world">
		<h3>{{msg}}</h3>
	</div>
</template>

<script type="text/javascript">
export default {
  name: 'world',
  data () {
    return {
      msg: 'this is a page of world!'
    }
  }
}
</script>

<style type="text/css" scoped>
	.world h3{
		color: skyblue;
	}
</style>