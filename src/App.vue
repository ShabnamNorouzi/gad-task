<template>
    <b-container fluid class="text-light mx-auto">
        <b-row>
            <TopNav />
        </b-row>
        <b-row>
            <b-col md="2">
                <LeftSidepanel />
            </b-col>
            <b-col md="10">
                <b-row>
                    <FilterBar />
                </b-row>
                <b-row>
                    <ToolBar />
                </b-row>
                <b-row>
                    <EmptyContainer />
                </b-row>
            </b-col>
        </b-row>
    </b-container>
    <FooterBar />
</template>

<script>
import TopNav from './components/TopNav.vue'
import LeftSidepanel from './components/LeftSidepanel.vue'
import ToolBar from './components/ToolBar.vue'
import FilterBar from './components/FilterBar.vue'
import EmptyContainer from './components/EmptyContainer.vue'
import FooterBar from './components/FooterBar.vue'

 
export default {
 name: 'App',
 components: {
   TopNav,
   LeftSidepanel,
   FilterBar,
   ToolBar,
   EmptyContainer,
   FooterBar
 }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  background-color: #6d757c;
}
</style>
