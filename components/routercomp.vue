<template>
    <div>
        <h2>{{text}}</h2>
        <div class="text">store:{{this.$store.state.text}}</div>
        <img class="imgs" src="../static/img/next.png"/>
        <Router-link to="/2">跳转第二个路由页面</Router-link>
    </div>
</template>

<script>
import {a} from "../static/lib/dict.js"
export default {
    data(){
        return{
            text:'初步用webpack打包'
        }
    }
}
</script>

<style lang="less">
    .text{
        color: red;
    }
    .imgs {
        width: 10px;
        height: 10px;
    }
</style>


