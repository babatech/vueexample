<template>
  <div>
    <app-header></app-header>
    <personal-data></personal-data>
    <ews></ews>
    <skills></skills>
    <languages></languages>
    <reference></reference>
    <past-work></past-work>
    <br>
    <br>
    <br>
    <br>
    <app-footer></app-footer>
  </div>
</template>

<script>
import 'bootstrap'
import $ from 'jquery'
import PersonalData from './personalData'
import Skills from './skills'
import Languages from './languages'
import PastWork from './pastWork'
import AppFooter from './appFooter'
import AppHeader from './appHeader'
import Ews from './ews'
import Reference from './reference';
export default {
  name: 'HelloWorld',
  components: {Reference, Ews, AppHeader, AppFooter, PastWork, Languages, Skills, PersonalData},
  mounted: function () {
    $(document).on('click', 'a[href^="#"]', function (event) {
      event.preventDefault()
      $('html, body').animate({
        scrollTop: ($($.attr(this, 'href')).offset().top - 110) }, 500)
    })
  },
  created: function () {

  },
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
