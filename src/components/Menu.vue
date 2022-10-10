<template>
    <div>
        <div v-show="isShow">
            <input type="text" v-model="name">
        </div>
        <button @click="isShow = !isShow">{{isShow ? "Show" :"Hide"}}</button>
       {{name}}
    </div>
</template>

<script>
export default {
    name:"Menu",
    data() {
        return {
            name: "Nguyen Van Nam",
            isShow: true
        }
    }
}
</script>

<style>
    
</style>