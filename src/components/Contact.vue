<template>
<div id="pro">
  <a :href="url" target="_blank">
    <button :style="{ backgroundColor: bgColor, color: textColor }">Click to Recive Gmail</button>
  </a>
  </div>
</template>

<style>
#mycomponent {
  background-color: #f0f0f0; /* เปลี่ยนสีพื้นหลังเป็นสีเทาอ่อน */
}
</style>

<script>
export default {
   name: 'HelloWorld',

   data() {
    return {
      url: 'https://mail.google.com/mail/u/0/#inbox?compose=CllgCJZcRlHtwRwXXfdGkbCShZqHQvrCFCblxFlXlwCLvKRCMfCjBLbKGVmzDxCQdZVHBzMNbVV',
      bgColor: 'red',
      textColor: 'black'
    }
  },
}
</script>
