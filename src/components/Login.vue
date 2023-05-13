<script setup>

</script>

<template>
    <div class="center">
        <h1 style="margin-bottom: 5px;font-weight: bold; font-size: 23px;">Welcome Back!</h1>
        <p style="font-size: 18px;">Ready to resume your journey?</p>
        <br>

        <div>
            <input type="text" placeholder="E-Mail">

        </div>

        <div>
            <div style="text-align: center;">
                <div class="inline-block"
                    style="margin: auto; width: 315px; border: 3px solid #3d5a80d3; position: relative; height: 30px;border-radius: 10px; padding: 0px 0px 10px 0px ;">

                    <input id="password" type="password" placeholder="Password">
                    <svg style="width: 30px;position: absolute; margin-top: 5px; right: 10px;" aria-hidden="true"
                        viewBox="0 0 24 24" data-testid="VisibilityIcon">
                        <path
                            d="M12 4.5C7 4.5 2.73 7.61 1 12c1.73 4.39 6 7.5 11 7.5s9.27-3.11 11-7.5c-1.73-4.39-6-7.5-11-7.5zM12 17c-2.76 0-5-2.24-5-5s2.24-5 5-5 5 2.24 5 5-2.24 5-5 5zm0-8c-1.66 0-3 1.34-3 3s1.34 3 3 3 3-1.34 3-3-1.34-3-3-3z">
                        </path>
                    </svg>
                </div>

            </div>
        </div>
        <div>
            <button
                style="width:315px; background-color: #3D5A80; color: white; margin-top: 10px; height: 45px; border: none; border-radius: 10px;">
                LOGIN
            </button>
        </div>
        <p class="center">
            -or-
            <br>
            Log in through
        </p>
        <div>
            <img src="https://staging.tutormatch.me/static/media/login-google.d97b0a8315f74b11e6273a6e66b15995.svg"
                style="width: 40px; margin:20px 10px 0px 0px;" alt="">
            <img src="https://staging.tutormatch.me/static/media/login-facebook.44a6df4e04273e7eb59c283d5f973e3e.svg"
                style="width: 40px;" alt="">
        </div>
        <div>
            <div class="center">Don’t have an account?</div>
            <a href="#" style="font-weight: bold; color: black; font-size: 17px;">Sign Up!</a>
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

input {
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
}</style>
