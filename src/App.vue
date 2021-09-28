<template>
  {{ Foo }}
  {{ Bar }}
  {{ Baz }}
</template>

<script lang="ts">
export enum Foo {
  FOO = "Foo"
}
enum Bar {
  BAR = "Bar"
}
</script>

<script setup lang="ts">
enum Baz {
  BAZ = "Baz"
}
</script>
