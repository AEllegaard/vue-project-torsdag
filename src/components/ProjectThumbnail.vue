<script>

    export default {
    props: {
        title: String,
        image: String,
        url: String,
    },
}
</script>

<template>
    <div class="bg-gray-100 p-4 rounded-lg shadow-inner">
        <img :src="image" alt="Project Thumbnail" class="w-full h-48 object-cover rounded-lg">
        <h2 class="text-xl font-semibold mt-2">{{ title }}</h2>
        <RouterLink :to="url">Visit Project</RouterLink>
    </div>
</template>