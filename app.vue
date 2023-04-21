<template>
    <div>
        <OnDevelopment></OnDevelopment>
    </div>
</template>
<script setup lang="ts">
import OnDevelopment from '~/components/OnDevelopment.vue';

useHead({
	title: 'Адреналин. Охота, Туризм, Рыбалка',
	meta: [
      {
          name: 'description',
          content: 'Сеть магазинов «Адреналин». Товары для охоты, туризма и рыбалки'
      },
      {
          name: 'keywords',
          content: 'адреналин, адреналин75, охота, туризм, рыбалка, чита, забайкальский край, забайкалье, бурятия'
      }
  ],
	htmlAttrs: {
		lang: 'ru'
	}
});
</script>