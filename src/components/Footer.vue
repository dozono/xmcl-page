<template>
    <div class="w-full bottom-0 flex items-center justify-center">
        <div class="flex flex-col items-center pb-2">
            <router-link to="/privacy">{{ t('privacy') }}</router-link>
            <div>Copyright © 2020-2022 CI010</div>
        </div>
    </div>
</template>
<script setup lang="ts">
const { t } = useI18n()
</script>