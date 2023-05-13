<script setup>

</script>

<template>
  <div>
    <main>
      <article id="article1" style="padding: 20px;">
        <div class="inline-block" style="max-width:65%;">
          <p>
            With over <span class="exception">2000</span> tutors,
          </p>
          <h1 style="font-size: 50px;font-weight: bold;">
            TUTORMATCH
          </h1>
          <p>
            will help you find a <span class="exception">
              local
            </span> or<span class="exception">online
            </span> tutor that matches your needs and price point. Choose from peer tutors, professional tutors, or
            certified teachers in a wide variety of subject areas.
          </p>
          <br>
          <button>
            Book Your Free Trial Session
          </button>
        </div>
        <div class="inline-block" style="width: 35%;height: 500px;float: right;">
          daDAd
        </div>
      </article>
      <article id="article2">

      </article>
      <article id="article3" style="text-align: center; clear: both;">
        <div>
          <div style="text-align: center;">
            <img src="https://staging.tutormatch.me/static/media/why-tutor-1.db2c6d271b96c7381db0c0400fe22acb.svg"
              alt="logo">
          </div>
          <p>
            One-on-one tutoring for a learning experience catered just for you from the comfort of your own home
          </p>
        </div>

        <div>
          <div style="text-align: center;">
            <img src="https://staging.tutormatch.me/static/media/why-tutor-1.db2c6d271b96c7381db0c0400fe22acb.svg"
              alt="logo">
          </div>
          <p>
            Customize your lessons to match your learning pace and personal schedule
          </p>
        </div>

        <div>
          <div style="text-align: center;">
            <img src="https://staging.tutormatch.me/static/media/why-tutor-1.db2c6d271b96c7381db0c0400fe22acb.svg"
              alt="logo">
          </div>
          <p>
            Pick from a wide variety of subjects and tutors to effectively enhance your learning
          </p>
        </div>
        <br>
      </article>

      <article id="article4">
        <div>
          <p>
            Choose from over <span class="exception">600 qualified <span style="color:blue;">PEER</span>, PROFESSIONAL,
              and <span style="color:red;">CERTIFIED</span></span> tutors with certified credentials!
          </p>
          <p>Click <span class="exception">MATCH</span> now to book your free 15-minute trial session!
          </p>
        </div>
        <div style="text-align: center;">
          <select id="education" class="options">
            <option value="">sodddws</option>
            <option value="">sodddws</option>
            <option value="">sodddws</option>
            <option value="">sodddws</option>
          </select>

          <select id="education" class="options">
            <option value="">sodddws</option>
            <option value="">sodddws</option>
            <option value="">sodddws</option>
            <option value="">sodddws</option>
          </select>
          <span id="filter" style="margin-right: 10px;">
            <img src="https://staging.tutormatch.me/static/media/filter.368bb3036a5d65cbcd1db97f24793d2a.svg"
              alt="filter">

          </span>
          <div class="inline-block"
            style="height:37px; border: 3px solid #3d5a80;border-radius: 10px;padding: 5px; width: 400px;text-align: start;">
            <div class="inline-block"
              style="border-right: 3px solid #3d5a80; margin-right: 10px;height: 30px;padding: 4px;"><img
                style="margin-top: 2px;"
                src="https://staging.tutormatch.me/static/media/search-icon.d2cf5365706b954d70d1c9943848bce0.svg" alt="">
            </div>
            <input type="text" style="height:37px; border: none;" placeholder="search">
          </div>
          <button class="button" style="height:50px; margin-left: 20px;">
            Search
          </button>
        </div>
      </article>
      <article id="article5"></article>
      <article id="article6">
        <h1 class="exception" style="padding:20px;"><span style="font-weight: 100;font-size: 30px;">Graduate with</span>
          CONFIDENCE</h1>
        <div class="inline-block card">
          <div class="inline-block">
            <img class="img-test" src="https://staging.tutormatch.me/api/uploads/testimonial/test.jpg" alt="test">
          </div>
          <div class="inline-block card-message">
            “Cras iaculis a dolor ut tempus. Etiam eget accumsan justo, dignissim pharetra justo.“
            <div>
              <span>
                <img src="https://staging.tutormatch.me/static/media/stars.52586ff9aa6a1647df930251c169dbc5.svg" alt="">
              </span>
            </div>
          </div>
        </div>
      </article>

    </main>
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

button {
  border: none;
  padding: 10px;
  border-radius: 5px;
  background-color: #3d5a80;
  color: white;
  font-weight: bold;
  cursor: pointer;
}

button:hover {
  background-color: #3d5a80d3;
}

main {
  font-family: Montserrat, sans-serif !important;
}

.exception {
  font-size: 30px;
  font-weight: bold;
}

#article3 {
  font-size: 15px;
  background-color: #1e2b37ed;
  color: white;
}

#article3 div img {
  width: 200px;

}

#article3 p {
  display: inline-block;
  width: 400px;
  font-size: 16px;
}

#article4 p {
  padding: 20px;
  text-align: center;
}

.options {
  background-color: #3d5a80;
  color: white;
  width: 300px;
  height: 50px;
  text-align: center;
  border: none;
  border-radius: 10px;
  margin-right: 20px;
  font-style: italic;
}
.card-message{
  font-size: 15px;
  color:#3d5a80d3;
}

.img-test {
  height: 200px;
  border-radius: 50%;
  margin: 20px;
}
#article6 .card{
  background-color: red;width:90% ;height: 200px;
}

.inline-block {
  display: inline-block;
}

@media screen and (max-width:1090px) {
  #filter {
    display: none;
  }

  .options {
    width: 40%;
    margin-bottom: 10px;
  }
}</style>
