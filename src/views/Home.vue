<template>
  <div class="home">
    hello wolrd this is blog list
    <search />
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
import search from "@/components/Search.vue";
@Component({
  name: "home",
  components: {
    search,
  },
})
export default class extends Vue {
  private flag = "fkagou";
}
</script>
