<template>
    <div class="main-container">
        <div class="main-page">
            <h1>Content goes here</h1>
        </div>
        <div class="pre-footer">
            <ul>
                <li>DIGITAL COMICS</li>
                <li>DC MERCHANDISE</li>
                <li>SUBSCRIPTION</li>
                <li>COMIC SHOP LOCATOR</li>
                <li>DC POWER VISA</li>
            </ul>
        </div>
    </div>


    
</template>

<script>
export default {
    name: 'Main'
}
</script>


<style lang="scss" scoped>

    .main-container {
        background-color: darkgray;
        height: 100px;

        .pre-footer{
            text-align: center;
            width: 100%;
            height: 100px;
            background-color: royalblue;
            li{
                color: white;
                display: inline-block;
                margin-left:50px;
                margin-top:20px;
            }
        }



    }

</style>