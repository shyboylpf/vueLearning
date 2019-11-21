<template>
    <div>
        <p v-if=isMorning> 早上好 </p>
        <p v-if=isAfternoon> 早上好 </p>
    </div>
</template>

<script>
export default {
  name: 'test1',
  props: {
    isMorning: Boolean,
    isAfternoon:Boolean
  }
}
</script>