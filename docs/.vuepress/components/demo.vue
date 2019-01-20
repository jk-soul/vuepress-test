<template>
    <div>组件-data-name：{{name}}</div>
</template>
<script>
export default {
    data:()=>({
        name:'first component'
    }),
    mounted(){
        console.log('组件 mounted')
    }
}
</script>
<style scoped>

</style>

