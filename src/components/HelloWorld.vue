<template>
  <p>{{msg}}</p>
</template>

<script lang="ts">
import Vue from 'vue'
import Component from 'vue-class-component'

@Component({})
export default class Hello extends Vue {
 msg: String = 'Hello world'
}
</script>
