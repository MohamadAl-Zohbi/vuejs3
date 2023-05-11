<script setup>
// import HelloWorld from './components/HelloWorld.vue';
</script>

<template>
  <header>
    <div id="container">
      <div id="logo-header">
        <img style="max-width: 100%;"
          src="https://staging.tutormatch.me/static/media/logo.e8fb406fec6d3046ddec12c64c859127.svg" alt="logo">
      </div>
      <div id="header-nav">
        <div id="tutor">Tutor With Us</div>
        <div id="about">About Us</div>
        <div id="contact">Contact</div>
        <div id="login">Log In</div>
        <button tabindex="0" type="button">Get Started</button>
      </div>
    </div>
  </header>
  <!-- ####### -->


  <!-- ####### -->
  <footer>
    <div id="sub-footer">
      <div id="sub-sub-footer">
        <div class="connect">
          <div>
            <a href="/about-us">Help &amp; Support</a><a href="/about-us">Our Team</a><a
              href="/about-us">Career/Volunteer</a><a href="/signup">Become A Tutor</a>
          </div>
        </div>
        <div class="connect">
          <a href="/about-us">Terms &amp; Policy</a><a href="/about-us">Cookie
            Settings</a><a href="/about-us">Site Map</a>
          <a href="/about-us">Contact Me</a>
        </div>
      </div>
      <!-- ############ -->
      <div id="sub-footer-contact">
        <div>
          <div>
            <div>
              <div class="foot"><img
                  src="https://staging.tutormatch.me/static/media/footer-logo.a8cbb5b8a7a29a8fcce4b53a6c5af114.svg"
                  alt="footer-logo"></div>
              <div class="foot">hello@tutormatch.me</div>
              <div class="foot">(xxx)xxx-xxxx</div>
              <div class="foot"><img
                  src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADIAAAAyCAYAAAAeP4ixAAAACXBIWXMAAAsTAAALEwEAmpwYAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAKbSURBVHgB3ZqPdZswEMY//DoAI6gT2NkAT9B0A3eDdII4E/h1AtIN2glgAycToA2cTnC9Q5BH/ACBEFjk9975n4Skj5NOQnIETxCR4reEbcsmn3dscWU1urIXtle2PIoijVvDjY/ZHtkKcudclaGwNFxpwpaRf9JFBJHxwInmJ51NEBd8z3ah5SjYDvAJLeOFLh4xFTJdKaXbk7LFfW2N+kTwWwYTRkNAQvaew/VbW+Km58ITwhEhSFtOXYlf2n4k0y8PmAddWY14XuHjxNnFgdum2StP1pyc8UD+Kdge+vo5mfG4o2GTa2IToWjaLN3GA0YwsH7JE/cVkpJfDhgJDb+Rp64CFPnlCAdoXI9QbQWk5I8CjowUkl5f7Nsbo8bFBCFCOVbq8JvAL/mQTNwImRuu56ohYbiJ3LRjXeCZPGKrmUwPyMgPWbNQn1jHB/mPjvEGt1mGKPjlXoQkWB4Fv+xEyBbrR4mQsVEiRLYiRGH9xJ/FI/EG7jxH7Xy1XSh52i7kpD0cmSJkDpynAhGiEQ4KbmgR8oZwcJ0KSiGvCAcFN/6JkBcEAJnluIIbuQjJEQZT1nx5uUHHd+MCf/OJtoXgaoWs4LG+Ovz+xnrJ5aUW8gfr5Ze8lELYNTnCGStjkKO7Mlg1Z3b7NmR4vA+JdyEr9Ip447n+cr3W+on18KP55YOQqr+toYs9DTrWpmlbNUN2UQpy59xWZtcyXtymER6a7XtbQquQym17hCVGwxy96bbEzgerwMRo9IgQep8QAxFTH4LqvkzWR92qgDtUS4GFkTr3ke8/3pA5Xyxo/qgl6Qnmhis59jRmipBLVfZyW1RkTmHFQ2cPQjKynPraiOABMgc2Cds3tpj79J0lv0xqsunxF40V7BT+A6WUkCbmWAtBAAAAAElFTkSuQmCC"
                  alt="facebook" style="width: 32px;"><img
                  src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADIAAAAyCAYAAAAeP4ixAAAACXBIWXMAAAsTAAALEwEAmpwYAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAJ5SURBVHgB7ZmBbdswEEW/iw6QDaJO0G5QbdBsUHeCOhNEmSDuBPIGdSdwOkG9gdQJkg2ux5ICVJWSjmQonYE8gJCRiJS+j/y8o4GFIKKGprlBAm+ghyskoEnIBySgScgnJKBJSMHrpEQkmoQYPkM7AtfqiFor2iJiqFlMsINpFGIi8gCtBEytjhO3AtqIEEKuzxaaoDghfUEPFGkEmoT0eSI77Xb98TUu9jmMo5UYZAKXKMTLqxBtaBJy4HbLrUUEb5EI2U2ra8+unTebzTMC4T57Hu/IHyvkTiD5QVfcbrh9d1boo/L0a6ZdlerB/Sat3zqr9XHq3x8UEe58xxfj30llqQSOTgs73Q5kk8gSNg+7ho3+uX+/SAjZHbVGYjkai5umR9e8zC52FmHmqgnj+unBBJNCWMRX2PBmn0qpjAohWz/vcSF4hThLrXFBjEXEuFOBeFoszH+u5aKxRRjGVVp3XcUUfPZ7BzmP3O7ZHh/7f6SIw4NUfEKkh8m3JqXw/SMmPUnlnzXinErybd6PiZgga5SGi73EPCYhrBDOokLez3fBNyhkKETyrR2hkODCao2FLGEo5DfWI+nZwRFhZ7sO7NJtsnMkRXoo5Czo8wXhlIJ7JM+WYQoomucpdOcWlLmEl4bG6/A+4syY7JntHC/vhDxoRTLM4UMxMY45pKiFY0nTolE2vhfgSwPZntLCVpA/3GfTp+D2EfJDipYt/R1ywGJ2tBzJ0ZgTc6L85C+lyR6QNZSPX1iKjGIaWvr3wQxiTrRCBdmJMVa6pzTM/rSDBshG5xD2/n8FVLmjsEEEZOd3Cfs7XuFa96ItbAL4E7Z2OS+R+v8BQtia7lIyjTYAAAAASUVORK5CYII="
                  alt="tiktok" style="width: 32px;"><img
                  src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADIAAAAyCAYAAAAeP4ixAAAACXBIWXMAAAsTAAALEwEAmpwYAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAALDSURBVHgB7ZrvddsgFMWvcvK93aB4gqQTWJ6g7QR1J4g3sDxBnAmqTlBngiobJBOUTNBuoL5XQQ5RQBJ/HOMT/87hIAOyuDbwLtjAibwobIVt276n7DMlgbyQlJqiKORoSxJxRelPmzfrMRHr9nhYmX0vDBGCst84Hv5SmtEw4xxnRkWJ40LP4/+cGxUCh4c/3R8qNxGUvlraC31xjrz46FqRaOh/wMCoOUNGjCyrdwN1eQmJ4SQkN7IS0nbWKIjcvhGr9SCBJezL7xO5Lb+rvvWYyr6EcEDbUXpQ15wEpTmMaJySfQi5oVRpD9RjqzxdhZGh4ktKIdzxLySgGWqkgt6SBN1Tfo1EpJzsoyJMqO2Wsm9IRCohGx8RGrqnRmcSo0klpEY4FRIwNkcaPDdrPEFFr83tpD20A76X5kuDl86W59Ct8XqOAfc7JuSOHlTpF/RAfjPRa9MgHl6my17ZY+/ZFRLaeGEpk4jn3lL2Dh6kmCPB/iglvkJsQS6FEIFIfIU8WMo+IZ75xGc58RViG8uXMfZbWZbSUtXAA18htaWMRawRjuveBh54CVFGsLFUsf32NoF0zxVlS0tV7TCdTkJWrY2jvPbZSygRW89nOPEWojzVzlF9TR38rsa9FarjOfUTbhE3IU4h1Maza72EfdlcorPpDTp7I1X5hbqnhBtJIl5vh8jjlzq6oMtfcMeAEn7nyZLSAoEER3b19S+QzqIsYsxnlEUxxMTsKXhrHCWCifZa3AFKS7qcYbogfTjBh9Yr36XWRrI9u7EXr9DNDZ7YF0YT7uwjumG0S9F5k+SnKEpQjVfmzZz9pnC20ShTGnVkylGYfyCVOCw83wYdtilEOtoI5PfHAY3UF+bP06yYP/0stq4Tmen48zRH1HLo7ToPyGYwiHIcaPOG/17ywli6/lQj0AU1gbyQ2EMwPbEP/gFmwsCCbFGZ4QAAAABJRU5ErkJggg=="
                  alt="instagram" style="width: 32px;"></div>
            </div>
          </div>
          <div>
            <div>
              <div class="foot">Sign up to our newsletter</div>
              <div class="foot">We offer exciting promotions all year round to provide more reason to learn and keep on
                growing!</div>
              <div id="subscribe-text-field">
                <div>
                  <div class="foot">
                    <input aria-invalid="false" type="text" value="">
                    <fieldset aria-hidden="true" >
                      <legend><span class="notranslate">​</span></legend>
                    </fieldset>
                  </div>
                </div>
              </div><button>
                Sign up</button>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div id="copyright">© 2023 Tutormatch | © 2023 Growth Empowerment INC. All Rights Reserved.</div>
  </footer>
  <HelloWorld />
</template>

<style scoped>
* {
  margin: 0%;
  padding: 0px;
}

header {
  background-color: #fff;
  box-shadow: 0 0 8px 0 grey;
  display: flex;
  font-weight: 700;
  height: 80px;
  position: fixed;
  width: 100%;
  z-index: 999;
  top: 0px;
  left: 0%;
}

#container {
  margin-left: auto;
  margin-right: auto;
  max-width: 90%;
  width: 1600px !important;
  justify-content: space-between;
  display: flex;

}

#logo-header {
  max-width: 100%;
  width: 254px;
  word-break: break-word;
  padding: 12px;
}

#header-nav {
  align-items: center;
  display: flex;
  gap: 60px;
  flex: none;
}

#header-nav div {
  cursor: pointer;
  color: #3d5a80;
  font-size: 19px;
  word-break: break-word;
  font-family: Montserrat, sans-serif !important;

}

#header-nav button {
  background-color: rgb(61, 90, 128);
  outline: 0px;
  border: 0px;
  cursor: pointer;
  font-weight: bold;
  user-select: none;
  font-size: 20px;
  line-height: 1.75;
  letter-spacing: 0.02857em;
  text-transform: uppercase;
  min-width: 64px;
  padding: 6px 8px;
  border-radius: 4px;
  color: white;
}

#header-nav button:active {
  background-color: rgba(61, 90, 128, 0.605);
}

#sub-footer {
  background-color: #3d5a80;
  width: 100%;
  justify-content: space-around;
  display: flex;

}

footer {
  position: absolute;
  bottom: 0px;
  width: 100%;

}

footer #sub-sub-footer {
  width: 50%;
  display: flex;
  padding-top: 10px;
  justify-content: space-around;
}

footer .connect {
  display: inline-block;
  height: 107px;
  /* justify-content: space-around; */
}

footer .connect a {
  display: block;
  margin-bottom: 20px;
  color: #fff !important;
  font-size: 16px;
  width: -webkit-fit-content;
  width: -moz-fit-content;
  font-family: Montserrat, sans-serif !important;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  font-size: 17px;
  width: fit-content;
}

footer #copyright {
  display: block;
  width: 100%;
}

footer #sub-footer-contact {
  max-width: 50%;
  display: flex inline-block;
  justify-content: space-between;
}

footer #sub-footer-contact .foot {
  display: inline-block;
  width: 50%;
}</style>
