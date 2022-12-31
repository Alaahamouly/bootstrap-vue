<template>
  <div class="aspect">
    <h3>** b-aspect **</h3>

    <b-button @click="changeAspect('2:1')" class="m-1">2:1</b-button>
    <b-button @click="changeAspect('4:3')" class="m-1">4:3</b-button>
    <b-button @click="changeAspect('16:9')" class="m-1">16:9</b-button>
    <b-button @click="changeAspect('1:1')" class="m-1">1:1</b-button>

    <b-aspect :aspect="aspect" style="border: 1px solid #999"
      >My 2:1 aspect!</b-aspect
    >
    <b-row>
      <b-col>
        <b-aspect :aspect="aspect" style="border: 1px solid #999"
          >My 2:1 aspect!</b-aspect
        >
      </b-col>
      <b-col>
        <b-aspect :aspect="aspect" style="border: 1px solid #999"
          >My 2:1 aspect!</b-aspect
        >
      </b-col>
    </b-row>
  </div>
</template>

<script>
export default {
  name: "AspectComponent",
  data() {
    return {
      aspect: "2:1",
    };
  },
  methods: {
    changeAspect(aspect_value) {
        this.aspect = aspect_value
    }
  }
};
</script>
