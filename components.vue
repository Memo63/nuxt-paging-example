
<template>
  <div>
    <!-- <div class=" bg-indigo-700 md:flex md:flex-shrink-0 w-1/12 h">
      <div class="flex flex-col w-64">
        <div class="mt-5 flex-1 flex flex-col">
          <div
            v-for="(category, index) in categories"
            :key="index"
            class="text-white text-2xl my-4"
            @click="setIndex(index)"
          >
            {{ category }}
          </div>
        </div>
      </div>
    </div>
    <nuxt-child />
  </div> -->
  </div>
</template>

<script>

export default {

  // data () {
  //   return {
  //     categories: []
  //   }
  // },

  // computed: {
  //   components () {
  //     return this.$store.compStore.state.components
  //   }
  // },

  // mounted () {
  //   console.log(this.$store)
  //   this.getCategories(this.categories)
  //   this.removeDuplicates()
  // },

  // methods: {
  //   getCategories (array) {
  //     for (let i = 0; i < this.$store.state.components.length; i++) {
  //       array.push(this.$store.state.components[i].category)
  //     }
  //     return array
  //   },
  //   removeDuplicates () {
  //     this.categories = [...new Set(this.categories)]
  //   },
  //   setIndex (ind) {
  //     // this.$store.dispatch('activeCategory', this.$store.state.components[ind].category)
  //     this.$store.commit('setActiveCategory', this.$store.state.components[ind].category)
  //   }
  // }

}
</script>

<style lang="postcss" scoped>

</style>
