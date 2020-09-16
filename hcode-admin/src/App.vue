<template>
  <v-app>
    <v-main>
      <AdminForm />
    </v-main>
  </v-app>
</template>

<script>
import AdminForm from './components/AdminForm';

export default {
  name: 'App',
  components: {
    AdminForm,
  },
};
</script>
