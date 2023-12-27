<script setup>
import { onMounted, ref } from 'vue';


const props = defineProps({
    cols: {
        type: String,
        default: 12,
    }
});

const gridClass = ref('col-span-' + props.cols);

</script>
<template>
    <div :class="[gridClass, 'relative bg-white dark:bg-slate-800 dark:text-slate-200 rounded shadow']">
        <div class="flex flex-col"><slot /></div>
    </div>
</template>