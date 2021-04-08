<template>
  <div class="glob-container">
    <h2 class="glob-header">Party Planner</h2>
    <div class="glob-body">
      <PartySelect />
      <GuestListForParty />
    </div>
  </div>
</template>

<script>
import PartySelect from "../components/PartySelect.vue";
import GuestListForParty from "../components/GuestListForParty.vue";
export default {
  name: "Planner",
  components: {
    PartySelect,
    GuestListForParty,
  },
};
</script>
