<template>
  <svg
    viewBox="0 0 24 24"
  >
    <path d="M4 12C4 12 6.90909 6.5 12 6.5C17.0909 6.5 20 12 20 12C20 12 17.0909 17.5 12 17.5C6.90909 17.5 4 12 4 12Z"
      :stroke="color"
      :stroke-width="strokeWidth"
      stroke-linecap="round"
      stroke-linejoin="round"/>
    <path d="M12 15C13.6569 15 15 13.6569 15 12C15 10.3431 13.6569 9 12 9C10.3431 9 9 10.3431 9 12C9 13.6569 10.3431 15 12 15Z"
      :stroke="color"
      :stroke-width="strokeWidth"
      stroke-linecap="round"
      stroke-linejoin="round"/>
  </svg>
</template>

<script>
export default {
  name: 'EyeIcon',
  props: {
    color: {
      type: String
    },
    strokeWidth: {
      type: [Number, String]
    }
  }
}
</script>
