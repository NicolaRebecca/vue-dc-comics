<template>

    <div class="footer-container">


        <!-- div con due ul (menu del footer) -->
        <div class="menu-container">
            <ul>
                <li>DC COMICS</li>
                <li><a href="#">Characters</a></li>
                <li><a href="#">Comics</a></li>
                <li><a href="#">Movies</a></li>
                <li><a href="#">TV</a></li>
                <li><a href="#">Games</a></li>
                <li><a href="#">Videos</a></li>
                <li><a href="#">News</a></li>
            </ul>

            <ul>
                <li>SHOP</li>
                <li><a href="#">Shop DC</a></li>
                <li><a href="#">Shop DC collectibles</a></li>
            </ul>

            <ul>
                <li>DC</li>
                <li><a href="#">Terms of use</a></li>
                <li><a href="#">Privacy policy</a></li>
                <li><a href="#">Ad choises</a></li>
                <li><a href="#">Advertising</a></li>
                <li><a href="#">Jobs</a></li>
                <li><a href="#">Subscriptions</a></li>
                <li><a href="#">Talent workshops</a></li>
                <li><a href="#">CPSC Certificates</a></li>
                <li><a href="#">Ratings</a></li>
                <li><a href="#">Shop help</a></li>
                <li><a href="#">Contact us</a></li>
            </ul>

            <ul>
                <li>SITES</li>
                <li><a href="#">DC</a></li>
                <li><a href="#">MAD Magazine</a></li>
                <li><a href="#">DC Kids</a></li>
                <li><a href="#">DC universe</a></li>
                <li><a href="#">DC power visa</a></li>
            </ul>
        </div>

        <!-- div con logo -->
        <div class="logo-container">
            <img src="../assets/dc-logo-bg.png" />
        </div>
        
    </div>
</template>

<script>
export default {
    name: 'Footer'
}
</script>

<style lang="scss" scoped>

    .footer-container {
        background-image: url("../assets/footer-bg.jpg");
        display: flex;


        .logo-container {
            width: 30%;
            img{
                width: 70%;
            }
        }

        .menu-container {
            display: flex;
            flex-grow: 1;
            margin-left: 100px;

            ul {
                width: 50%;
                list-style: none;

                li {
                    font-size: 12px;
                    margin:5px 0;

                    &:first-child {
                        color: white;
                        font-size: 18px;
                        font-weight: bold;
                    }

                    a {
                        color: rgb(214, 210, 210);
                        text-decoration: none;

                        &:hover {
                            text-decoration: underline;
                        } 

                    }


                }


            }


        }

    }

</style>