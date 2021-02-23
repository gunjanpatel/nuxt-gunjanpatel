<template>
  <div>
    <Navbar/>
    <!-- Header -->
    <header>
      <div class="container">
        <div class="row">
          <div class="col-lg-offset-2 col-lg-10 intro-block">
            <div class="inner text-left"><span>Full Stack Web Developer</span>
              <h1 class="heading-title"> Hello, I’m <span>Gunjan</span> and these are my experiments. </h1></div>
          </div>
        </div>
      </div>
    </header>
    <div id="about">
      <div class="about-wrapper">
        <div class="container">
          <div class="row">
            <div class="col-lg-offset-2 col-lg-10 intro-block">
              <div class="intro-text">
                <span class="name">कर्मण्येवाधिकारस्ते मा फलेषु कदाचन। <br> मा कर्मफलहेतुर्भूर्मा ते सङ्गोऽस्त्वकर्मणि॥ २-४७</span>
              </div>
            </div>
          </div>
        </div>

      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
header {
  background-color: #101010;
  background-image: url('~assets/images/background.jpg');
  /*background-position: 50%;*/
  background-repeat: no-repeat;
  background-size: cover;
  padding: 150px 0;
  transform: scaleX(-1);
  filter: FlipH;
}

header .container {
  transform: scaleX(-1);
  filter: FlipH;
}

header img {
  display: block;
  margin: 0 auto 20px;
}


header .intro-text .skills {
  font-size: 1.25em;
  font-weight: 300;
}

#about {
  padding: 120px 0;
  text-align: center;
  background: #191919;
}

.intro-text .name {
  display: block;
  text-transform: uppercase;
  font-family: Montserrat, "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-size: 2em;
  font-weight: 700;
}

.inner h1.heading-title {
  font-size: 75px;
  font-weight: 900;
  font-family: Montserrat,sans-serif;
  line-height: 90px;
  text-transform: inherit;
  width: 70%;
}

@media only screen and (min-width: 992px) and (max-width: 1263px) {
  .inner h1.heading-title {
    font-size: 70px;
  }
}

@media only screen and (min-width: 992px) and (max-width: 1263px) {
  .inner h1.heading-title{
    font-size: 58px;
    line-height: 75px;
  }
}

.inner h1.heading-title span {
  color: #f9004d;
}

</style>
