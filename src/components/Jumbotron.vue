<template>
    <div class="container-fluid">
        <div class="banner">
            <!-- <img src="../assets/jumbotron.jpg" alt="">    -->
        </div>
        

    </div>
</template>


<script>
export default {
  name: "Jumbotron",
};
</script>


<style scoped lang="scss">
@import '../style/colors';

    .banner{
        background-image: url("../assets/jumbotron.jpg");
        background-size: cover;
        height: 400px;
    }

</style>

