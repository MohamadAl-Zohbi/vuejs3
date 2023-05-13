<script setup>

</script>

<template>
    <div class="center">
        <div style="margin: 100px 0px 100px 0px;">
            <h1 style="margin-bottom: 5px;font-weight: bold; font-size: 23px;">Our Mission</h1>
            <p style="font-size: 15px; display: inline-block; max-width: 500px; line-height: 19px; color: #3d5a80;">Lorem
                ipsum
                dolor sit amet, consectetur adipiscing elit. Arcu fermentum viverra sem ac rhoncus egestas suscipit
                dignissim
                habitant. Eget volutpat lectus diam ultricies. Donec gravida est aliquam nulla justo ultrices duis. At at
                sed ac
                eget aliquam nunc.
            </p>
        </div>

        <div style="text-align: start; padding: 20px;">

            <div style="display:inline-block; float: left; padding-top: 30%;">
                <h1 style="margin-bottom: 5px;font-weight: bold; font-size: 23px;">The Brains Behind Tutormatch</h1>
                <p style="font-size: 15px; display: inline-block;max-width: 500px; line-height: 19px; color: #3d5a80;">Lorem
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Arcu fermentum viverra sem ac rhoncus egestas
                    suscipit dignissim habitant. Eget volutpat lectus diam ultricies. Donec gravida est aliquam nulla justo
                    ultrices duis. At at sed ac eget aliquam nunc.

                </p>
            </div>
                <img id="avatar" src="https://staging.tutormatch.me/static/media/about-us-img.889fd467e5b665b01242b7d5a5d41639.svg" width="calc(100% -500px)">

        </div>
    </div>
</template>

<script>
export default {
    data() {
        return {
            menu: false,
        }
    },


    methods: {
        // openMenu(){
        //   alert("jcdj")
        // }
    },

    // `mounted` is a lifecycle hook which we will explain later
    mounted() {

        // this.openMenu()

    }
}
</script>

<style scoped>
* {
    padding: 0px;
    margin: 0px;
    font-size: 20px;
}

.center {
    text-align: center;
    font-family: Montserrat, sans-serif !important;
    font-weight: 100;

}
#avatar{
    width: calc(100% - 500px);
    float: right;
}
@media screen and(max-width:900px) {
    #avatar{
        width: 100%;
        display: none;
    }
}
</style>
