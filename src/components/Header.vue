<template>
    <div class="header-full">
        <div class="logo-container">
            <img src="../assets/dc-logo.png" />
        </div>
        <nav>
            <ul>
                <li>CHARACTERS</li>
                <li>COMICS</li>
                <li>MOVIES</li>
                <li>TV</li>
                <li>GAMES</li>
                <li>COLLECTIBLES</li>
                <li>VIDEOS</li>
                <li>FANS</li>
                <li>NEWS</li>
                <li>SHOP</li>
            </ul>
        </nav>
    </div>
</template>

<script>
export default {
    name: 'Header'
}
</script>

<style lang="scss" scoped>

    @import "../style/colors.scss";

    .header-full {
        display: flex;
        justify-content: space-around;
        margin-top:10px;
        margin-bottom:10px;

        .logo-container{
            img{
                width: 60%;
            }
        }

        nav {

            ul {
                display: flex;
                list-style: none;
                font-size: 14px;
                font-weight: bold;

                li {
                    height: 50px;
                    line-height: 60px;
                    padding: 0 10px;

                    &:hover {
                        background: $bg-color;
                    }

                }

            }

        }


    }



</style>
