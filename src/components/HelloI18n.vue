<template>
  <div>
    <p>{{ $t('hello') }}</p>
    <p>{{ $t('message') }}</p>
    <p>{{ $t('hello.world', { world: '世界' }) }}</p>
  </div>
</template>

<script>
export default {
  name: 'HelloI18n'
}
</script>

<i18n>
{
  "en": {
    "hello": "Hello i18n in SFC!"
  }
}
</i18n>
