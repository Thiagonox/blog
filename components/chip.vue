<template>
    <div class="snap-center px-4 mx-2 border border-white/50 rounded-full flex items-center bg-[#45483F]">
        <p class="text-text text-lg font-principal">{{ chip }}</p>
    </div>
</template>
<script>
export default {
  props: {
    chip: String,
  }
}
</script>