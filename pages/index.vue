<template>
  <!-- Main -->
  <div id="main">
    <div class="inner">

      <!-- Header -->
        <header id="header">
          <a href="index.html" class="logo"><strong>Portfolio</strong> of ZIS</a>
          <ul class="icons">
            <li><a href="https://github.com/zisuzon" class="icon fa-github"><span class="label">Github</span></a></li>
            <li><a href="https://codepen.io/suzon007/" class="icon fa-codepen"><span class="label">Codepen</span></a></li>
            <li><a href="https://twitter.com/zisuzon" class="icon fa-twitter"><span class="label">Twitter</span></a></li>
            <li><a href="https://www.facebook.com/zisuzon" class="icon fa-facebook"><span class="label">Facebook</span></a></li>
            <li><a href="https://www.instagram.com/zisuzon/" class="icon fa-instagram"><span class="label">Instagram</span></a></li>
            <li><a href="https://medium.com/@zisuzon" class="icon fa-medium"><span class="label">Medium</span></a></li>
          </ul>
        </header>

      <!-- Banner -->
        <section id="banner">
          <div class="content">
            <header>
              <h1>Hi, I’m <br />ZI Suzon</h1>
              <p>A web developer currently daing with Vue JS</p>
            </header>
            <p>
              A passionate web developer with 1 year experience in this domain, focused on building great websites, web appiclation, SPA and so on.
              For every single project I've done, my focus has been on createing the best CODE and UX possible. It is always exciting to 
              learn new technology and concept related to web development. Creating web applications by writing lines of code give me immense pleasure. 
              <br><br>
              Photography is one of my other hobbies and I love to read books. I use to play guitar and travel quite often.  
            </p>
            <ul class="actions">
              <li><nuxt-link to="http://blog.zisuzon.com/" class="button big">Learn More</nuxt-link></li>
            </ul>
          </div>
          <span class="image object">
            <img src="~/assets/images/zis2.jpeg" alt="" />
          </span>
        </section>

      <!-- Section -->
        <section>
          <header class="major">
            <h2>Skills</h2>
          </header>
          <div class="features">
            <article>
              <span class="icon fa-html5"></span>
              <div class="content">
                <h3>HTML 5</h3>
                <p>HTML is not just a markup language. If you know how to write semantic markup, your applications will be in other level. I have good knowledge in sematic markup like where to put what tag.</p>
              </div>
            </article>
            <article>
              <span class="icon fa-css3"></span>
              <div class="content">
                <h3>CSS3</h3>
                <p>I've worked on <strong>Bootstrap</strong> framwork. CSS always seems messy to me but the more I am experiencing the more I am loving it.</p>
              </div>
            </article>
            <article>
              <span class="icon"><b class="js">JS</b></span>
              <div class="content">
                <h3>JavaScript</h3>
                <p>My expertise now mainly on JavaScript. Currently I am working with <strong>NUXT JS</strong>, which is a SSR supported framework on  <strong>VUE JS </strong> including <strong>VUEX</strong> and <strong>VUE ROUTER </strong>.</p>
              </div>
            </article>
            <article>
              <span class="icon fab"><b class="js">PHP</b></span>
              <div class="content">
                <h3>PHP</h3>
                <p>PHP is my first web programming language before I fall in love with Javascript. After learning <strong>Raw PHP</strong> and <strong>OOP PHP</strong>, I did my first project in <strong>CODEIGNITER</strong> framework. Then I've worked on some small scale application using <strong>LARAVEL</strong> framework.</p>
              </div>
            </article>
          </div>
        </section>

      <!-- Section -->
        <section>
          <header class="major">
            <h2>Projects</h2>
          </header>
          <div class="posts">
            <article>
              <a href="#" class="image"><img src="~/assets/images//projects/truck-pathao.png" alt="Truck Pathao" /></a>
              <h3>Truck Pathao</h3>
              <p>Truck pathao is a single page web application for goods transport service.</p>
              <ul class="actions">
                <li><a href="http://truckpathao.com/" class="button">Visit</a></li>
              </ul>
            </article>
            <article>
              <a href="#" class="image"><img src="~/assets/images//projects/iub-env.png" alt="Iub env" /></a>
              <h3>SESM Dept, Independent University</h3>
              <p>A website for SESM department of Independent University Bangladesh.</p>
              <ul class="actions">
                <li><a href="http://www.sesm.iub.edu.bd/" class="button">Visit</a></li>
              </ul>
            </article>
            <article>
              <a href="#" class="image"><img src="~/assets/images//projects/omega-point.png" alt="" /></a>
              <h3>Omega Point Coaching Center</h3>
              <p>Student management system for a local coaching center.</p>
              <ul class="actions">
                <li><a href="http://coaching.zisuzon.com/" class="button">Visit</a></li>
              </ul>
            </article>
            <article>
              <a href="#" class="image"><img src="~/assets/images//projects/zis-portfolio.png" alt="" /></a>
              <h3>Old Portfolio Template</h3>
              <p>Made this template with traditional Html, Css and jQuery.</p>
              <ul class="actions">
                <li><a href="https://zisuzon.github.io/personal/" class="button">Visit</a></li>
              </ul>
            </article>
            <article>
              <a href="#" class="image"><img src="~/assets/images//projects/car.png" alt="" /></a>
              <h3>Fun Project</h3>
              <p>When I was bored.</p>
              <ul class="actions">
                <li><a href="http://zisuzon.com/projects/car3/" class="button">Visit</a></li>
              </ul>
            </article>
            <article>
              <a href="#" class="image"><img src="~/assets/images//projects/number-quote.png" alt="" /></a>
              <h3>Number Quote</h3>
              <p>Vue JS fun app project based on <a href="http://numbersapi.com/">Numbers API.</a> </p>
              <ul class="actions">
                <li><a href="https://github.com/zisuzon/numberQuote" class="button">Visit</a></li>
              </ul>
            </article>
          </div>
        </section>

    </div>
  </div>
</template>

<script>

export default {
}
</script>

<style scoped>
.js {
  color: #f56a6a;
  font-size: 26px;
}
</style>
