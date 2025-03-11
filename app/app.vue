<script setup lang="ts"></script>

<template>
  <div>
    <NuxtLoadingIndicator />

    <header>
      <div class="py-[20px] px-[50px]">
        <div class="flex flex-wrap gap-x-4">
          <NuxtLink to="/">Home</NuxtLink>
          <NuxtLink to="/accordion">Accordion</NuxtLink>
          <NuxtLink to="/carousel">Carousel</NuxtLink>
          <NuxtLink to="/collapse">Collapse</NuxtLink>
          <NuxtLink to="/dropdown">Dropdown</NuxtLink>
          <NuxtLink to="/input-number">Input Number</NuxtLink>
          <NuxtLink to="/overlay">Overlay</NuxtLink>
          <NuxtLink to="/pin-input">Pin Input</NuxtLink>
          <NuxtLink to="/remove-element">Remove Element</NuxtLink>
          <NuxtLink to="/scrollspy">Scrollspy</NuxtLink>
          <NuxtLink to="/select">Select</NuxtLink>
          <NuxtLink to="/stepper">Stepper</NuxtLink>
          <NuxtLink to="/strong-password">Strong Password</NuxtLink>
          <NuxtLink to="/tabs">Tabs</NuxtLink>
          <NuxtLink to="/toggle-count">Toggle Count</NuxtLink>
          <NuxtLink to="/toggle-password">Toggle Password</NuxtLink>
          <NuxtLink to="/tooltip">Tooltip</NuxtLink>
        </div>
      </div>
    </header>

    <div class="pb-[20px] px-[50px]">
      <NuxtPage />
    </div>
  </div>
</template>
