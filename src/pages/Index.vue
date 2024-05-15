<template>
  <q-page>
    <div>
      <q-icon
        name="icon-mat-search"
        size="xl"
        class="q-ma-lg"
      />
      <q-icon
        name="icon-fa-500px-brands"
        size="xl"
        class="q-ma-lg"
      />
      <q-icon
        name="icon-ion-md-add-circle-outline"
        size="xl"
        class="q-ma-lg"
      />
      <q-icon
        name="icon-eva-activity-outline"
        size="xl"
        class="q-ma-lg"
      />
      <q-icon
        name="icon-ti-arrow-up"
        size="xl"
        class="q-ma-lg"
      />
      <q-icon
        name="icon-la-accessible-icon"
        size="xl"
        class="q-ma-lg"
      />
      <q-icon
        name="icon-mat-settings"
        size="xl"
        class="q-ma-lg"
      />
      <q-icon
        name="icon-if-phone"
        size="xl"
        class="q-ma-lg"
      />
      <q-icon
        name="icon-custom-member"
        size="xl"
        class="q-ma-lg"
      />
    </div>

    <q-select
      v-model="model"
      :options="options"
      dropdown-icon="icon-mat-arrow_drop_down"
      label="Filled"
      style="width: 200px;"
      class="q-ma-xl"
      filled
    />

  </q-page>
</template>

<script>
import { ref } from 'vue'

export default {
  setup () {
    return {
      model: ref(null),
      options: [
        'Google', 'Facebook', 'Twitter', 'Apple', 'Oracle'
      ]
    }
  }
}
</script>