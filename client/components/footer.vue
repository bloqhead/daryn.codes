<template>
  <footer class="page-footer">
    <div class="page-footer__content">

      <ul class="page-footer__social">
        <li>
          <a href="https://codepen.io/bloqhead">
            <fa :icon="[ 'fab', 'codepen' ]" /> <span>Codepen</span>
          </a>
        </li>
        <li>
          <a href="https://github.com/bloqhead">
            <fa :icon="[ 'fab', 'github' ]" /> <span>Github</span>
          </a>
        </li>
        <li>
          <a href="https://twitter.com/bloqhead">
            <fa :icon="[ 'fab', 'twitter' ]" /> <span>Twitter</span>
          </a>
        </li>
        <li>
          <a href="https://instagram.com/karmapizza">
            <fa :icon="[ 'fab', 'instagram' ]" /> <span>Instagram</span>
          </a>
        </li>
      </ul>

      <div class="page-footer__copyright">
        <p>&copy; {{ new Date().getFullYear() }} Daryn St. Pierre</p>
        <p>Built with <a href="https://nuxtjs.org/">Nuxt</a>. Hosted by <a href="https://zeit.co/">Zeit</a>.</p>
        <p><nuxt-link to="/uses/">What I use</nuxt-link>.</p>
      </div>

    </div>
  </footer> <!-- .page-footer -->
</template>
