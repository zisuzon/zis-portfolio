<template>
  <div id="sidebar" :class="{ inactive: isNotActive }">
    <div class="inner">

      <!-- Search -->
        <!-- <section id="search" class="alt">
          <form method="post" action="#">
            <input type="text" name="query" id="query" placeholder="Search" />
          </form>
        </section> -->

      <!-- Menu -->
        <nav id="menu">
          <header class="major">
            <h2>Menu</h2>
          </header>
          <ul>
            <li><nuxt-link to="http://www.zisuzon.com/">Home</nuxt-link></li>
            <li><nuxt-link to="http://blog.zisuzon.com/">Blog</nuxt-link></li>
            <li><nuxt-link to="">CV</nuxt-link></li>
            <!-- <li>
              <span class="opener">Submenu</span>
              <ul>
                <li><a href="#">Lorem Dolor</a></li>
                <li><a href="#">Ipsum Adipiscing</a></li>
                <li><a href="#">Tempus Magna</a></li>
                <li><a href="#">Feugiat Veroeros</a></li>
              </ul>
            </li> -->
          </ul>
        </nav>

      <!-- Section -->
        <section>
          <header class="major">
            <h2>Moments</h2>
          </header>
          <div class="mini-posts">
            <article>
              <a href="#" class="image"><img src="~/assets/images/deligram.jpg" alt="" /></a>
              <p>I am currently working at <b>Deligram Technology Inc</b> as a front-end developer. I am really grateful that I got the chance
              working there. Things I've learned and experienced at deligram will help me through out my career.</p>
            </article>
            <article>
              <a href="#" class="image"><img src="~/assets/images/my-workspace.jpg" alt="Workspace" /></a>
              <p>I love to work on two monitor setup on a messy desk. My favourite operating system is linux. But when I work on my photography I boot to windows which is kind of annoying.</p>
            </article>
          </div>
          <!-- <ul class="actions">
            <li><a href="#" class="button">More</a></li>
          </ul> -->
        </section>

      <!-- Section -->
        <section>
          <header class="major">
            <h2>Get in touch</h2>
          </header>
          <ul class="contact">
            <li class="fa-envelope-o"><a href="#">suzon.zahid@gmail.com</a></li>
            <li class="fa-phone">(+88) 0168-1465614</li>
            <li class="fa-home">Rupnagar, Mirpur<br />
            Dhaka, Bangladesh</li>
          </ul>
        </section>

      <!-- Footer -->
        <footer id="footer">
          <p class="copyright">
            &copy; Zahidul Islam Suzon. All rights reserved. <br>Design: <a href="https://html5up.net">HTML5 UP</a>.
          </p>
        </footer>

    </div>
    <a class="toggle toggle-button" @click="toggleMenu">Toggle</a>
  </div>
</template>

<script>
export default {
  data() {
    return {
      isNotActive: true
    }
  },
  methods: {
    toggleMenu () {
      this.isNotActive = !this.isNotActive
    }
  }

}
</script>

<style scoped>
  .toggle-button {
    cursor: pointer;
  }
</style>
