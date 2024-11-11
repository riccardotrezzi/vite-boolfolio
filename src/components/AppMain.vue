<script>

import axios from 'axios';

export default {
  data(){
    return {

    };
  },
  methods: {
    getProjects() {
      axios
          .get()
          .then((res)=> {
            console.log(res.data);
          });
    }
  }

}
</script>

<template>

  <main>
    
    <div class="container">
      MAIN
    </div>

  </main>

</template>

<style scoped>

</style>