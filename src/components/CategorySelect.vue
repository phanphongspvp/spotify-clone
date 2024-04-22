<script setup>
import { ref, toRefs } from 'vue'
import { RouterLink } from 'vue-router'
import uniqolor from 'uniqolor'
const randColor = ref('')

randColor.value = uniqolor.random()

const props = defineProps({ category: String, image: String })
</script>

<template>
    <div>

    </div>
</template>

<style lang="scss" scoped>

</style>