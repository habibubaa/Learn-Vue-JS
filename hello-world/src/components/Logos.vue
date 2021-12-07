<template>
    <div class="header-wrapper">
        <h2>Hello Habib!</h2>
    </div>
    
    <div class="logos-wrapper">
        <div class="item-logos">
            <img class="logos-gojek" alt="Gojek Logo" src="../assets/logo-gojek.png">
        </div>

        <div class="item-logos">
            <img class="logos-traveloka" alt="Traveloka Logo" src="../assets/logo-traveloka.png">
        </div>
        
        <div class="item-logos">
            <img class="logos-tokopedia" alt="Tokopedia Logo" src="../assets/logo-tokopedia.png">
        </div>
        
        <div class="item-logos">
            <img class="logos-gojek" alt="Gojek Logo" src="../assets/logo-gojek.png">
        </div>

        <div class="item-logos">
            <img class="logos-traveloka" alt="Traveloka Logo" src="../assets/logo-traveloka.png">
        </div>
        
        <div class="item-logos">
            <img class="logos-tokopedia" alt="Tokopedia Logo" src="../assets/logo-tokopedia.png">
        </div>
    </div>
    
</template>

<script>
    export default {
        name: 'Logos'
    }
</script>

<style scoped>
    .header-wrapper{
        width: 70%;
        overflow: hidden;
        margin: auto;
        background: skyblue;
    }

    .logos-wrapper{
        width: 62%;
        overflow: hidden;
        margin: auto;
        /* background: red; */
    }

    .item-logos{
        width: 200px;
        height: 200px;
        /* background: springgreen; */
        margin-left: 35px;
        margin-right: 35px;
        margin-top: 20px;
        margin-bottom: 20px;
        float: left;
    }

    .item-logos .logos-gojek{
        width: 150px;
        height: 130px;
    }

    .item-logos .logos-traveloka{
        width: 200px;
        height: 100px;
    }

    .item-logos .logos-tokopedia{
        width: 200px;
        height: 130px;
    }

</style>