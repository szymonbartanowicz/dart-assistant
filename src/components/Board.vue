<template>
  <v-container class="fill-height">
    <v-responsive class="d-flex align-center text-center fill-height">
      <div>
        <ScoreButton :value="1"/>
        <ScoreButton :value="2"/>
        <ScoreButton :value="3"/>
        <ScoreButton :value="4"/>
        <ScoreButton :value="5"/>
      </div>
      <div>
        <ScoreButton :value="6"/>
        <ScoreButton :value="7"/>
        <ScoreButton :value="8"/>
        <ScoreButton :value="9"/>
        <ScoreButton :value="10"/>
      </div>
      <div>
        <ScoreButton :value="11"/>
        <ScoreButton :value="12"/>
        <ScoreButton :value="13"/>
        <ScoreButton :value="14"/>
        <ScoreButton :value="15"/>
      </div>
      <div>
        <ScoreButton :value="16"/>
        <ScoreButton :value="17"/>
        <ScoreButton :value="18"/>
        <ScoreButton :value="19"/>
        <ScoreButton :value="20"/>
      </div>
      <ActionButtons />
    </v-responsive>
  </v-container>
</template>

<script setup>
import ScoreButton from './ScoreButton.vue';
import ActionButtons from "../components/ActionButtons.vue";
</script>

<script>
export default {
  components: {
    ScoreButton,
    ActionButtons,
  },
  name: "Board",
};
</script>

<style scoped>
</style>
