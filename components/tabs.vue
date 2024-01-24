<template>
    <div id="tabs">
        <b-container>
            <b-tabs content-class="mt-3" fill>
                <b-tab title="Digital Drawing" active>
                    <Arts />
                </b-tab>
                <b-tab title="Skills">
                    <b-card-text>Tab contents 2</b-card-text>
                </b-tab>
                <b-tab title="About Me">
                    <b-card-text>Tab contents 2</b-card-text>
                </b-tab>
            </b-tabs>
        </b-container>
    </div>
</template>

<script>
import Arts from './Arts.vue'

export default {
  name: 'Tabs',
  components: {
    Arts
  }
}
</script>

<style scoped>
#tabs {
    margin-top: 30px;
}
</style>