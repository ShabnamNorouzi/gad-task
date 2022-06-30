<template>
    <div class="side-panel">
        <div v-for="item in items" :key="item.name">
            <b-button squared :style="{width:'100%', textAlign:'left'}">
                <i class="bi bi-grid-fill"></i> {{ item.name }}
            </b-button>
        </div>
    </div>
</template>

<script>
export default {
  name: 'LeftSidepanell',
  data() {
    return{
        items: [
            { name: 'Dashboards' },
            { name: 'Site Area Management' },
            { name: 'Site Data' },
            { name: 'Drillholes' },
            { name: 'Points' },
            { name: 'Trenches' },
            { name: 'Daily Drill Reporting' },
            { name: 'Import & validation' },
            { name: 'Exports' },
            { name: 'Assay Management' },
            { name: 'Photo Management' },
            { name: 'Reports' },
            { name: 'Config' }
        ]
    }
  }
}
</script>
<style scoped>
.side-panel {
    background-color: #6d757c;
    flex-direction: column;
    text-align: left;
    padding-top: 1.5rem;
    padding-bottom: 18rem;
}
</style>
