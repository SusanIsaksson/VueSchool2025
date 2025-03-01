<script setup lang="ts">
import ClassHeader from '@/components/ClassHeader.vue';
</script>

<template>
    <div>

        <ClassHeader/>
        <div class="githubProfile">
            <h1>This is about Github Profiles</h1>
        </div>
    </div>
    
</template>


<style>
@media (min-width: 1024px) {
  .githubProfile {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>