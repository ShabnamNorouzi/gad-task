<template>
    <div class="filters" variant="outline-light">
        <b-dropdown text="Projets" variant="outline-light" size="sm">
            <b-dropdown-item>Item 1</b-dropdown-item>
            <b-dropdown-item>Item 2</b-dropdown-item>
        </b-dropdown>
        <b-dropdown text="Filter" variant="outline-light" size="sm">
            <b-dropdown-item>Item 1</b-dropdown-item>
            <b-dropdown-item>Item 2</b-dropdown-item>
        </b-dropdown>
        <b-dropdown text="Data View" variant="outline-light" size="sm">
            <b-dropdown-item>Item 1</b-dropdown-item>
            <b-dropdown-item>Item 2</b-dropdown-item>
        </b-dropdown>
    </div>
</template>

<script>
export default {
  name: 'FilterBar',
}
</script>

<style scoped>
.filters {
    background-color: #222529;
    border-top: 1px solid #6e757b;
    text-align: right;
    padding: 1rem;
}
.btn-group {
    margin-left: 2rem;
}
</style>