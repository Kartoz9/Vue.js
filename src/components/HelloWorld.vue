<template>
  <div class="hello">
    <p>Спеціальність: {{ speciality }}</p>
    <p>Курс: {{ course }}</p>
    <p>Група: {{ groupName }}</p>
    <p>ПІБ: {{ fullName }}</p>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data() {
    return {
      speciality: 'Інженерія програмного забезпечення',
      course: 1,
      groupName: '1ПРс',
      fullName: 'Глуховський І.В.'
    }
  }
}
</script>

