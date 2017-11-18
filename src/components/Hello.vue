<template>
	<div>
		<h1>{{msg}}</h1>
		<div class="marquee-wrap" style="width: 100px;">
			<vue-marquee content="33333" class="two" :showtwo="false"></vue-marquee>
		</div>
		<div class="marquee-wrap" style="width: 100px;">
			<vue-marquee content="22222" class="two" :showtwo="false"></vue-marquee>
		</div>
		<div class="marquee-wrap" style="width: 100px;">
			<vue-marquee content="1" class="two" :showtwo="false"></vue-marquee>
		</div>
	</div>

</template>

<script>
	import VueMarquee from 'vue-marquee-ho';
	import Css from 'vue-marquee-ho/dist/vue-marquee.min.css'
	export default {
		name: 'Hello',
		data() {
			return {
				msg: 'Hello world！！！'
			}
		},
		components: {
			VueMarquee
		}
	}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
	h1,
	h2 {
		font-weight: normal;
	}
	
	ul {
		list-style-type: none;
		padding: 0;
	}
	
	li {
		display: inline-block;
		margin: 0 10px;
	}
	
	a {
		color: #42b983;
	}
</style>