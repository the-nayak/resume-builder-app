<template>
  <div id="app" class="mx-5">
    <div class="flex items-center justify-between mt-5">
      <h1 class="text-green-brand font-serif text-3xl">Creative <span class="text-blue-brand">Resume</span></h1>
      <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-help-circle text-blue-brand"><circle cx="12" cy="12" r="10"></circle><path d="M9.09 9a3 3 0 0 1 5.83 1c0 2-3 3-3 3"></path><line x1="12" y1="17" x2="12.01" y2="17"></line></svg>
    </div>
    <div class="mt-20 md:flex items-center justify-around">
      <h1 class="text-blue-brand font-bold text-4xl font-serif leading-11">Get Your <br><span class="text-green-brand">Resume</span> Ready <br>in just <span class="text-green-brand">5 minutes</span> </h1>
      <div class="mx-auto ">
        <img class="transform rotate-10 object-contain mt-10" :src="heroImg" alt="">
      </div>
    </div><br>
    <div>
      <h1 class="font-bold text-2xl font-serif text-blue-brand">Simple Steps:</h1>
      <ul class="text-blue-brand list-none font-serif text-lg">
        <li class="my-2">-- Choose a template,</li>
        <li class="my-2">-- Fill your details,</li>
        <li class="my-2">-- Preview your resume,</li>
        <li class="my-2">-- Download as PDF</li>
      </ul>
    </div>
    <div class="bg-green-brand font-serif w-50 h-11 rounded-xl mx-auto py-1 mt-16">
    <a class="text-2xl text-white text-center mx-10" href="#">Get Started</a>
    </div>
    <p class="text-base text-blue-brand text-center">&copy; 2020 <br> Designed &amp; Developed by Pradeep Nayak</p>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
  },
  data(){
    return{
      heroImg: require('./assets/img/mores.png')
    }
  }
}
</script>

<style>
</style>
