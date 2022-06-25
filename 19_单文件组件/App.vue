<template>
<!--    模板里面必须有一个根元素-->
    <div>
        <School></School>
        <Student></Student>
    </div>
</template>

<script>
    // 引入组件
    import School from "./School";
    import Student from "./Student";

    export default {
        name:"App",
        components:{
            School,
            Student,
        }
    }
</script>