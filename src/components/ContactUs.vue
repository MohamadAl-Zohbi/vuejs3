<script setup>

</script>

<template>
    <div class="center">
        <h1 style="margin-bottom: 5px;font-weight: bold; font-size: 23px;">Contact Us</h1>
        <p style="font-size: 18px;">By getting in touch with our team</p>
        <br>

        <div>
            <input class="input" type="text" placeholder="Name*">

        </div>

        <div>
            <input class="input" type="text" placeholder="E-Mail Address">

        </div>

        <div>
            <input class="input" type="text" placeholder="Purpose of Message">
        </div>

        <div>
            <!-- <input class="input" style="height: 140px; text-align: sta;" type="text" placeholder="Message*"> -->
            <textarea style="width:290px;height: 130px; padding: 10px; border: 3px solid #3D5A80; border-radius: 10px;" placeholder="Message*" ></textarea>
        </div>

        <div>
            <button
                style="width:315px; background-color: #3D5A80; color: white; margin-top: 10px; height: 45px; border: none; border-radius: 10px;">
                Send
            </button>
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

.input {
    border: 3px solid #3d5a80d3;
    border-radius: 10px;
    height: 35px;
    margin-bottom: 10px;
    width: 300px;
    padding: 5px;
}

#password {
    border: none;
    height: 20px;
    margin-bottom: 10px;
    width: 200px;
    padding: 5px;
    position: absolute;
    left: 10px;
    top: 5px;
    background: none;
}


</style>
