<template>
    <div class="searchOut">
        <el-button type="success" @click="cablickFn" plain>返回</el-button>
        
        <img src="../assets/searchOut.jpg"  style="height:100%;width:100%" alt="">
    </div>
</template>

<script>
export default {
    props: {

    },
    data() {
        return {

        };
    },
    methods:{
        cablickFn(){
            history.back()
        }
    }
};
</script>

<style scoped lang="scss">

</style>
