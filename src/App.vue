<template>
  <div id="home">
    
    <b-navbar type="is-dark" style="background-color:black;" v-if="!isMobile()"  :mobile-burger="false">
        <template slot="brand">
            <b-navbar-item tag="router-link" :to="{ path: '/' }">
                <img src="../public/logo.png"
                />
                <h1 style="font-weight:bolder;font-size:25px;font-family:'Lato';margin-left:10px;">theCodingGuy</h1>
            </b-navbar-item>
        </template>
        
    </b-navbar>
    <video ref="videoRef" autoplay loop playsinline muted style="height:60vh;width:100vw;">
      <source src="../public/Video.mp4" type="video/mp4">
    </video>

    <section class="section" style="background-color:#181818;text-align:left;">
    <div class="container">
      <div class="row">
        <div class="columns">

          <div class="column is-quarter">
                <video style="outline :none;width:100%;" ref="videoRef" autoplay playsinline loop muted>
       
              <source src="../public/logo.mp4" type="video/mp4">
            </video>

          </div>


          <div class="column is-three-quarter">
            <h1 class="title" style="color:white;font-weight:bolder;font-size:30px;text-align:left;text-decoration:underline;">About Me</h1>
            <h2 style="font-weight:bold;color:white;font-size:18px;">My Name Is Rony Marine Quail & I Develop The Most Basic To Complex Functional & Scalable Websites or Web, Mobile & Server Applications.<br/><br/>I Am Dedicated To My Work & I Give 100% To Any Project I Undertake.<br/><br/>Frameworks That I Use For All My Projects Include;<br/>- VueJS For Web Development.<br/>- NativescriptVue For Mobile Development.<br/>- NodeJS For Server Development.<br/>- MySQL & MongoDB Databases.<br/>- Firebase Hosting & Functions For Deploying Web Applications and Server Functions.</h2>
          </div>
        </div>

    </div>
    </div>
  </section>

   <section v-if="!isMobile()" class="section" style="background-color:#181818;text-align:left;">
    <div class="container">
      <div class="row">
        <div class="columns">


          <div class="column is-three-quarter">
            <h1 class="title" style="color:white;font-weight:bolder;font-size:30px;text-align:left;text-decoration:underline;">BlockChain Technology</h1>
            <h2 style="font-weight:bold;color:white;font-size:18px;">The goal of blockchain is to allow digital information to be recorded and distributed, but not edited.The simplest way to think of blockchain is as a large distributed ledger of sorts that stores records of transactions.Blockchain is the underlying technology behind cryptocurrencies like Bitcoin and has earned a significant attraction for entrepreneurs, businesses and researchers nowadays.<br/><br/>I Know How To Create BlockChain Applications Using Solidity or NodeJS and I Am Currently Working On A BlockChain Concept That Can Be Implemented In Kenya and Eventually Africa.</h2>
          </div>

          <div class="column is-quarter">
                  <img src="https://i2.wp.com/hr-gazette.com/wp-content/uploads/2018/03/bigstock-Blockchain-technology-wording-228825697.jpg?fit=1600%2C900&ssl=1"
                />
                
          </div>


        </div>

    </div>
    </div>
  </section>

  <section v-if="isMobile()" class="section" style="background-color:#181818;text-align:left;">
    <div class="container">
      <div class="row">
        <div class="columns">

          <div class="column is-quarter">
                  <img src="https://i2.wp.com/hr-gazette.com/wp-content/uploads/2018/03/bigstock-Blockchain-technology-wording-228825697.jpg?fit=1600%2C900&ssl=1"
                />
                
          </div>

          <div class="column is-three-quarter">
            <h1 class="title" style="color:white;font-weight:bolder;font-size:30px;text-align:left;text-decoration:underline;">BlockChain Technology</h1>
            <h2 style="font-weight:bold;color:white;font-size:18px;">The goal of blockchain is to allow digital information to be recorded and distributed, but not edited.The simplest way to think of blockchain is as a large distributed ledger of sorts that stores records of transactions.Blockchain is the underlying technology behind cryptocurrencies like Bitcoin and has earned a significant attraction for entrepreneurs, businesses and researchers nowadays.<br/><br/>I Know How To Create BlockChain Applications Using Solidity or NodeJS and I Am Currently Working On A BlockChain Concept That Can Be Implemented In Kenya and Eventually Africa.</h2>
          </div>


        </div>

    </div>
    </div>
  </section>

  <section class="section" style="background-color:#181818;text-align:left;">
    <div class="container">
      <div class="row">
        <div class="columns">

          <div class="column is-quarter">
                  <img src="https://cdnp1.stackassets.com/339f7e3cd0226586bbbff46207c14bdf808f3149/store/dc16664408d9a12615f01a74117f0e7a973e7967b8f4f7ac98a8fc844aa2/sale_10872_primary_image_wide.jpg"
                />
                
          </div>


          <div class="column is-three-quarter">
            <h1 class="title" style="color:white;font-weight:bolder;font-size:30px;text-align:left;text-decoration:underline;">Network Administration</h1>
            <h2 style="font-weight:bold;color:white;font-size:18px;">Network Administrators Work To Install & Maintain A Network On Which A Company's Information & Communications Are Stored And Transmitted.<br/><br/>I Have The Following Certification From Cisco Who Develop, Manufacture, Sell Networking Hardware & Software;<br/><br/>- CCNA 1 - INTRODUCTION TO NETWORKS<br/>- CCNA 2 - ROUTING & SWITCHING<br/>- CCNA 3 - SCALING NETWORKS<br/></h2>
          </div>


        </div>

    </div>
    </div>
  </section>

  <section class="section" style="background-color:#181818;text-align:right;">
    <div class="container">
      <div class="row">
        <div class="columns">

          <div class="column is-three-quarter">
            <h1 class="title" style="color:white;font-weight:bolder;font-size:30px;text-align:right;text-decoration:underline;">Cyber Security & Ethical Hacking</h1>
            <h2 style="font-weight:bold;color:white;font-size:18px;">"The More Connected We Are, The Less Secure.."<br><br>As An Ethical Hacker, Also Referred To As A White Hat Hacker, I Can Systematically Attempt to Penetrate Computer Systems, Networks, Applications Or Other Computing Resources On Behalf Of Its Owners -- And With Their Explicit Permission -- To Find Security Vulnerabilities That Malicious Hackers Could Exploit.</h2>
          </div>

          <div class="column is-quarter">
                  <img  src="../public/ethical.jpg"
                />
                
          </div>


        </div>

    </div>
    </div>
  </section>

  <section v-if="isMobile()" class="section" style="background-color:#181818;text-align:right;">
    <div class="container">
      <div class="row">
        <div class="columns">

          <div class="column is-quarter">
                  <img  src="../public/ethical.jpg"
                />
                
          </div>

          <div class="column is-three-quarter">
            <h1 class="title" style="color:white;font-weight:bolder;font-size:30px;text-align:right;text-decoration:underline;">Cyber Security & Ethical Hacking</h1>
            <h2 style="font-weight:bold;color:white;font-size:18px;">"The More Connected We Are, The Less Secure.."<br><br>As An Ethical Hacker, Also Referred To As A White Hat Hacker, I Can Systematically Attempt to Penetrate Computer Systems, Networks, Applications Or Other Computing Resources On Behalf Of Its Owners -- And With Their Explicit Permission -- To Find Security Vulnerabilities That Malicious Hackers Could Exploit.</h2>
          </div>



        </div>

    </div>
    </div>
  </section>

  <section class="section" style="background-color:#181818;text-align:left;">
    <div class="container">
      <div class="row">
        <div class="columns">

          <div class="column is-quarter">
                  <img  src="../public/crypto.jpg"
                />
                
          </div>

          <div class="column is-three-quarter">
            <h1 class="title" style="color:white;font-weight:bolder;font-size:30px;text-align:left;text-decoration:underline;">Crypto For Business</h1>
            <h2 style="font-weight:bold;color:white;font-size:18px;">Crypto Is Here To Stay & Businesses Are Quickly Starting To Adopt Ways In Which They Can Accept Crypto At Their Businesses. Using The Binance Platform, I Have Helped Three Establishments Accept Crypto Payments.</h2>
          </div>


        </div>

    </div>
    </div>
  </section>

  

  <section class="section" style="background-color:#282828;text-align:center;">
    <h1 class="title" style="text-align:center;color:white;font-weight:bolder;font-size:40px;">Clients</h1>
    <div class="columns">
  <div class="column">
    <img style="height:230px;width:350px;" src="../public/td.jpeg"/>
    <p style="font-weight:bold;color:white;">ThunderDome BBQ</p>
    <a href="https://thunderdomebbq.co.ke"><p style="font-weight:bold;color:white;">https://thunderdomebbq.co.ke</p></a>
  </div>
  <div class="column">
    <img style="height:230px;width:350px;" src="../public/fck.jpeg"/>
    <p style="font-weight:bold;color:white;">Fruit Cake Kafé</p>
    <a href="https://fruitcakeskafe.co.ke"><p style="font-weight:bold;color:white;">https://fruitcakeskafe.co.ke</p></a>
  </div>
  <div class="column">
    <img style="height:230px;width:350px;" src="../public/pc.jpg"/>
    <p style="font-weight:bold;color:white;">Pet Connect</p>
    <a href="https://petconnect-ke.com"><p style="font-weight:bold;color:white;">https://petconnect-ke.com</p></a>
  </div>
</div>
  </section>

<section class="section" style="background-color:black;text-align:center;">
    <h1 class="title" style="text-align:center;color:white;font-weight:bolder;font-size:40px;">Get In Touch</h1>
    <h2 style="font-weight:bold;color:white;font-size:18px;">email: rony@thecodingguy.co.ke</h2>
    <h2 style="font-weight:bold;color:white;font-size:18px;">mobile: (+254) 0705009784</h2>
  </section>


</div>
</template>

<script>

export default {
  name: 'App',
  methods: {
    isMobile() {
   if(/Android|webOS|iPhone|iPad|iPod|BlackBerry|IEMobile|Opera Mini/i.test(navigator.userAgent)) {
     return true
   } else {
     return false
   }
  }
  }

}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

#home {
  background-color: black;
}
</style>
