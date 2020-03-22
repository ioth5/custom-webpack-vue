<template>
    <div>
        <h2>{{text}}</h2>
        <div class="text">第二个</div>
        <img class="imgs" src="../static/img/next.png"/>
        <Router-link to="/3">跳转第三个路由页面</Router-link>
    </div>
</template>

<script>
import {a} from "../static/lib/dict.js"
export default {
    data(){
        return{
            text:a
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
