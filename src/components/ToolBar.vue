<template>
    <div class="tool-bar p-3">
        <b-button-group class="mx-1" v-for="tool in tools" :key="tool.name">
            <b-button variant="light">{{ tool.name }}</b-button>
        </b-button-group>
    </div>
</template>

<script>
export default {
  name: 'ToolBar',
  data() {
    return{
        tools: [
            { name: 'Summary' },
            { name: 'Site' },
            { name: 'Site Survey' },
            { name: 'Downhole Survey' },
            { name: 'Lithology' },
            { name: 'Alteration' },
            { name: 'Mineralisation' },
            { name: 'Geotech Defect' },
            { name: 'Geotech zone' },
            { name: 'Recovery Core' }
        ]
    }
  }
}
</script>
<style scoped>
.tool-bar {
    background-color: #2d2d2d;
}
</style>