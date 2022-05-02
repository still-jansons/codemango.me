<template>
    <div class="overflow-hidden" :style="bg_fluid">
        <div class="w-screen h-screen flex items-center justify-center" :style="bg_glass">
            <img class="max-w-[90%]" src="/codemango.svg" alt="CODE MANGO">
        </div>
    </div>
</template>

<script>
export default {
    name: 'IndexPage',
    data() {
        return {
            bg_fluid: {
                backgroundColor: 'white',
                backgroundImage: "url(/fluid.svg)"
            },
            bg_glass: {
                background: 'rgba( 255, 255, 255, 0 )',
                backdropFilter: 'blur( 8px )',
                '-webkit-backdrop-filter': 'blur( 8px )',
                filter: 'saturate(120%)'
            }
        }
    }
}
</script>
