<template>
  <div clas="column">
    <div>
      <h6 class="q-ma-none "> Account</h6>
    </div>
    <q-form class="q-my-md">
      <q-input dense label="Account Name" outlined />

    </q-form>
    <q-separator class="q-my-md"></q-separator>
    <div class="row q-my-md q-gutter-sm">
      <div>
        <q-btn label="Submit" color="green" unelevated></q-btn>
      </div>
      <div>
        <q-btn label="Cancel" color="red" unelevated></q-btn>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  data () {
    return {

    }
  }
}
</script>
