<template lang="html">
    <div>
    <script>
        export default {
            async asyncData({ $content, params }) {
            const articles = await $content('blog')
                .only(['title', 'slug'])
                .sortBy('createdAt', 'asc')
                .fetch()

            return {
                articles
                }
            }
        }
    </script>
    </div>
</template>