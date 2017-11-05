<template>
  	<div class="home_container">
        <itemcontainer father-component="home"></itemcontainer>
    </div>
</template>

<script>
import itemcontainer from '../../components/itemcontainer'

export default {
	name: 'home',
  	components: {
  		itemcontainer
  	},
    created(){
        console.log(1111)
    }
}
</script>

<style lang="less" scoped>
    .home_container{

    }
</style>
