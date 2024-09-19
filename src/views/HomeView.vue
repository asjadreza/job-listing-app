<script setup>
import Hero from "@/components/Hero.vue";
import Homecards from "@/components/Homecards.vue";
import JobListings from "@/components/JobListings.vue";
</script>

<template>
  <Hero
    title="Become a Vue Dev"
    subTitle="Find the Vue job that fits your skills and needs"
  />
  <Homecards />
  <JobListings :limit="3" :showButton="true" />
</template>
