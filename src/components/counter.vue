<template>
   <q-card>
     <q-card-section>
        <div class="text-h6">Counter</div>
      </q-card-section>
      <q-separator dark />
      <q-card-section>
        {{ valeur }}
      </q-card-section>
      <q-separator dark />
       <q-card-actions>
        <q-btn flat>-</q-btn>
        <q-btn flat>+</q-btn>
      </q-card-actions>
    </q-card>
</template>
<script>
export default {
  name: 'Counter',
  data () {
    return {
      valeur: 0
    }
  }
}
</script>
