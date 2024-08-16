<template>
  <div>
    <NuxtRouteAnnouncer />
    <NuxtWelcome />
  </div>
</template>

<script setup lang="ts">
const languageNames = new Intl.DisplayNames("en", { type: "language" });
const regionNames = new Intl.DisplayNames("en", { type: "region" });
const currencyNames = new Intl.DisplayNames("en", { type: "currency" });

console.log(languageNames.of("fr"));
console.log(regionNames.of("fr"));
console.log(currencyNames.of("eur"));
</script>
