<script setup lang="ts"></script>
<template>
  <PartsLayoutHeader />
  <div class="bg-gray-400">
    <UContainer>
      <slot />
    </UContainer>
  </div>
  <PartsLayoutFooter />
</template>
