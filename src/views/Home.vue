<template>
  <div class="home">
   <Navbar />
  </div>
</template>
<script>


import Navbar from "@/components/Navbar";

export default {
  name: 'Home',
  components: {
    Navbar
  },
  metaInfo() {
    return {
      title: 'Página principal',
    }
  },
}
</script>
