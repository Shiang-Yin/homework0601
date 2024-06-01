<script>
import { RouterLink, RouterView } from 'vue-router'
export default{
    components:{
        RouterLink
    }

}
</script>

<template>

<div class="headerArea">
    <RouterLink to="/">Home</RouterLink>
    <RouterLink to="/quiz">Quiz</RouterLink>
</div>

</template>


<style scoped lang="scss">
</style>