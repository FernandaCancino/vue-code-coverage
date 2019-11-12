<template>
    <div>
        <h3>Welcome</h3>

        <p>Button count is:{{count}}</p>
        <button @click="changeCount"> Click </button>

    </div>
</template>

<script>
export default {
  data () {
    return {
      count: 0
    }
  },
  methods: {
    changeCount () {
      this.count += 1
    }
  }
}
</script>
