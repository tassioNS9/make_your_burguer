<template>
  <div class="main-container">
    <h1>Gerenciar Pedidos</h1>
    <Dashboard/>
  </div>
</template>


<script>
import Dashboard from '@/components/Dashboard.vue';
// @ is an alias to /src


export default {
  name: 'Requests',
  components:{
    Dashboard
  }
}
</script>