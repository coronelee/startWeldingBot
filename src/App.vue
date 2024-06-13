<template>
  <div id="app"></div>
</template>

<script setup>
import { TelegramWebAppContainer } from '@telegram-web-app/core';

const telegram = new TelegramWebAppContainer();

telegram.WebApp.ready();
telegram.WebApp.expand();
telegram.WebApp.openTelegramLink('https://t.me/welding_seams_bot/WeldingSeamsApp');

</script>