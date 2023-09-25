<script setup>
import Navbar from "../components/Navbar";
import Footer from "../components/Footer";

</script>

<template>
  <div>
    <Navbar />
    <VApp>
      <VMain>
        <slot />
      </VMain>
      <Footer />
    </VApp>
  </div>
</template>
