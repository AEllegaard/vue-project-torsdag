<script>
import ProjectThumbnail from '@/components/ProjectThumbnail.vue';
 export default {
    components: {
        ProjectThumbnail,
    },
 }
</script>

<template>
    <h1>Projects</h1>
    <div class="grid grid-cols-3 p-4 gap-4">
        <ProjectThumbnail
        title="First Project"
        image="https://picsum.photos/200"
        url="/projects/1">
    </ProjectThumbnail> 

    <ProjectThumbnail
        title="First Project"
        image="https://picsum.photos/200"
        url="/projects/1">
    </ProjectThumbnail> 

    <ProjectThumbnail
        title="First Project"
        image="https://picsum.photos/200"
        url="/projects/1">
    </ProjectThumbnail> 
    </div>
</template>
