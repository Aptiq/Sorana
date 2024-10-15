<template>
    <div>
      <h1>Plan Comptable</h1>
      <UButton @click="importPlan">Importer Plan Comptable</UButton>
      <!-- Ici, nous ajouterons plus tard la logique pour afficher le plan comptable -->
    </div>
  </template>
  
  <script setup lang="ts">
  const importPlan = () => {
    // Logique d'importation à implémenter
    console.log('Importation du plan comptable')
  }
  </script>