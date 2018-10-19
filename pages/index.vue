<template>
    <section class="splash">
      <div class="message">
        <h2>Invest</h2> 
        <h3>in the whole world</h3>
        <p>Open world lets you invest in the whole world from your phone.<br/> For free.</p>
        <a class="signup" href="https://amanmender1.typeform.com/to/KfjmuU">Sign up</a>
      </div>
      <img src="https://d2ue93q3u507c2.cloudfront.net/assets/marketing/images/home_redesign/iPhoneHome_still%402x.png" class="image" />
    </section>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style>
* {
  font-family: 'Oswald', sans-serif;
}
.splash {
  margin: auto;
}
.splash > .message {
  display: inline-block;
}

h2 {
    font-size: 3.4em;
    margin-bottom: 0;
    padding: 0;
    margin: 0;  
}

h3 {
    font-size: 1.8em;
    margin-top: 0;
    padding: 0;
    margin: 0;  
}

p {
  padding-top: 10px;  
}

img {
    /*width: 20%;
    display: inline-block;
    top: 175px;
    position: relative;*/
    width: 80%;
}

a {
  padding: 10px;
  background: #21ce99; /* #13b713;*/
  color: white;
    display: inline-block;
    margin: 20px 0;
    border-radius: 4px;
    text-decoration: none;
}

@media screen and (max-width: 760px) {
  .splash {
    text-align: center;
  }
  .splash > .message {
    padding: 20px;    
      /*text-align: left;*/
  }
  .message > p {
    padding: 10px 50px;    
  }
}

@media screen and (min-width: 760px) {
  .splash {
    text-align: center;    
  }
  .splash > .message {
    text-align: left;
  }
  img {
    width: 20%;
    display: inline-block;
    /*top: 175px;*/
    top: 75px;
    position: relative;    
  }
}

@media screen and (min-width: 960px) {
  img {
    width: 22%;
    display: inline-block;
    top: 105px;
    position: relative;    
  }
}
</style>
