<script setup>
import { ref } from 'vue'

const props =
defineProps
({item: Object});
</script>

<template>
<ul>
    <li v-for="item in items" :key="item.id">{{  }}
    {{ list.items.item-name }}
    </li>
</ul>
</template>