
<template>
    <div class="flex">
        <SideBar/>
        <div class="flex flex-col w-[calc(100%-240px)]">
            <Header :page-title="pageTitle"/>
            
            <slot/>
        </div>
    </div>
</template>

<script  setup>
    import SideBar from '../components/SideBar.vue'
    import Header from '../components/Header.vue'
    const props = defineProps(['pageTitle'])
    const { pageTitle } = toRefs(props)
</script>
