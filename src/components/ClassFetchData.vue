<template>
    <button @click="getPosts">show posts</button>
</template>

<script>
export default {
    getPosts() {
        fetch('https://api.github.com/users')
    }
}
console.log(getPosts)
</script>
