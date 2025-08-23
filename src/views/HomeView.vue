<script setup>
import Hero from '@/components/Hero.vue';
import HomeCards from '@/components/HomeCards.vue';
import JobListings from '@/components/JobListings.vue';

</script>

<template>
  <Hero 
      title="Find A Job" 
      subtitle="With our innovative and advanced webscrapping technology, 
      we're able to catch all the entire available jobs in most of well-known companies 
      and we help them apply direct to you" 
  />
  <HomeCards />
  <JobListings
    :limit="3"
    :showButton="true"
    />
</template>