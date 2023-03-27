<template>
    <h1>Jobs</h1>
    <div v-for="job in jobs" :key="job.id">
        <h2>{{ job.title }}</h2>
    </div>
</template>

<script>
export default {
    data() {
        return {
            jobs: [
                {title: 'Web Developer', id: 1, details: 'lorem'},
                {title: 'UX Designer', id: 2, details: 'lorem'},
                {title: 'App Developer', id: 3, details: 'lorem'},
            ]
        }
    }

}
</script>

<style>

</style>