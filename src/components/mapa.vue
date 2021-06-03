<template>
  <section>
    <div class="mapa">
      <iframe
        src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d7678.565200778723!2d-47.909469!3d-15.789046!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x1594c3ebdc2e4a0c!2sTIT%20Consultoria%20e%20Servi%C3%A7os!5e0!3m2!1spt-PT!2sbr!4v1622754586376!5m2!1spt-PT!2sbr"
        width="600"
        height="450"
        style="border: 0"
        allowfullscreen=""
        loading="lazy"
      ></iframe>
    </div>
  </section>
</template>

<script>
export default {
  name: "mapa",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    .mapa iframe{
        width: 100%;
    }
</style>
