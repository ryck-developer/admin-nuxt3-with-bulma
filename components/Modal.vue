<template>
  <div class="modal" :class="{ 'is-active': show }">
    <div class="modal-background"></div>
    <div class="modal-card">
      <header class="modal-card-head">
        <p class="modal-card-title">Modal title</p>
        <button
          class="modal-close is-large"
          aria-label="close"
          @click="close"
        ></button>
      </header>
      <section class="modal-card-body">
        Testeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee
      </section>
      <footer class="modal-card-foot">
        <button class="button is-success">Save changes</button>
        <button class="button">Cancel</button>
      </footer>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Modal',
  data() {
    return {
      show: false,
    };
  },
};
</script>
