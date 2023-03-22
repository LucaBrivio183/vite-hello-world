<script>
export default {
    data() {
        return {
            image: "src/assets/Jumbotron.jpg",
            credits: 'Riccardo Turella',
        }
    }
}
</script>
<template>
    <div class="container">
        <img :src="image" alt="" />
        <small>{{ credits }}</small>
    </div>
</template>
<style scoped>
.container {
    width: 80%;
    max-width: 1000px;
    align-items: center;
}

img {
    width: 100%;
    display: block;
    object-fit: center;
}

small::before {
    content: '\00a9: ';
}
</style>