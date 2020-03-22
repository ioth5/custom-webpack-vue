<template>
    <div>
        <h2>{{text}}</h2>
        <div class="text">这是第三个路由页面</div>
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
</style>
