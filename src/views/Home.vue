<template>
  <div class="home">
    <img alt="Vue logo" src="@/assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js + TypeScript App - with a minor modification to test npm package"/>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import HelloWorld from '@/components/HelloWorld.vue'; // @ is an alias to /src
// import test from 'te-npm-package-test';

@Component({
  components: {
    HelloWorld,
  },
  mounted() {
    // console.log(test('mensaginha a ser transformada em caps'));
  },
})
export default class Home extends Vue {}
</script>
