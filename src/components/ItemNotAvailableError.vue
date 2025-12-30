
<template>
  <!-- usually not visible but if page is called with wrong id or the page was not closed after an item is deleted -->
  <div class="window-height window-width row justify-center items-center flex flex-center">
    <q-card class="q-pa-md no-shadow" bordered>
      <q-card-section>
        <div class="text-h5 text-weight-bold">{{ $t('TITLE_ITEM_NOT_FOUND') }}</div>
      </q-card-section>
      <q-card-section>
        <p>{{ $t('MSG_ITEM_NOT_FOUND_DETAIL') }}</p>
      </q-card-section>
      <q-card-section>
        <q-btn rounded color="accent" :label="$t('BTN_LABEL_GO_HOME')" class="full-width" to="/"></q-btn>
      </q-card-section>
      <q-card-section>
        <p>{{ $t('MSG_REPORT_BUG') }}</p>
      </q-card-section>
    </q-card>
  </div>
</template>

<script setup lang="ts"></script>
