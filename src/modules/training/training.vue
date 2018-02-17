<template>
  <f7-page>
    <f7-navbar title="Тренировки" back-link="Back"></f7-navbar>
    <f7-block-title>Тренировки</f7-block-title>
    <f7-block strong>
      <p>Тут будут тренировки!</p>
    </f7-block>
  </f7-page>
</template>
<script>
export default {
  name: 'training',
  data: function() {
    return {
      items: []
    }
  },
  created() {
    console.log('on created')
  }
}
</script>

