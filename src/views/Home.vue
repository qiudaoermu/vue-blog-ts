<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <p>{{ flag }}</p>
    <HelloWorld msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script lang="ts">
import HelloWorld from "@/components/HelloWorld.vue";
import { Component, Vue } from "vue-property-decorator";
@Component({
  name: "home",
  components: {
    HelloWorld,
  },
})
export default class extends Vue {
  private flag = "fkag";
}
</script>
