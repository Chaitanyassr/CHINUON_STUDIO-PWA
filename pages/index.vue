<template>
  <v-layout
    column
    justify-center
    align-center
  >
    <v-flex
      xs12
      sm8
      md6
    >
      <div class="text-center">
        <logo />
        <vuetify-logo />
      </div>
      <v-card>
        <v-card-title class="headline">
          Welcome to Chinuon Studio
        </v-card-title>
        <v-card-text>
          <p>Chinuon-studio is a gameing studio that builds cool game.</p>
          <p>
            To downlaod the game, check out the <a
              href="https://sites.google.com/view/braveknightgame/home"
              target="_blank"
            >
              link
            </a>.
          </p>
          <p>
            If you have questions, please contact the founder of the Chinuon studio. the link of his site is given below. <a
              href="https://chaitanyassr.netlify.com/"
              target="_blank"
              title="chat"
            >
              Chaitanyassr
            </a>.
          </p>
          <p>
            Chaitanyassr's github account<a
              href="https://github.com/Chaitanyassr"
              target="_blank"
              title="contribute"
            >
              GitHub
            </a>.
          </p>
          <p>This app is build with Vuetify and Nuxt.js</p>
          <div class="text-xs-right">
            <em><small>&mdash; Kumar Chaitanya</small></em>
          </div>
          <hr class="my-3">
          <a
            href="https://nuxtjs.org/"
            target="_blank"
          >
            Nuxt Documentation
          </a>
          <br>
          <a
            href="https://github.com/nuxt/nuxt.js"
            target="_blank"
          >
            Nuxt GitHub
          </a>
        </v-card-text>
        <v-card-actions>
          <v-spacer />
          <v-btn
            color="primary"
            nuxt
            to="/inspire"
          >
            Continue
          </v-btn>
        </v-card-actions>
      </v-card>
    </v-flex>
  </v-layout>
</template>

<script>
import Logo from '~/components/Logo.vue'
import VuetifyLogo from '~/components/VuetifyLogo.vue'

export default {
  components: {
    Logo,
    VuetifyLogo
  }
}
</script>
