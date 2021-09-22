<template lang="html">
    <div>
    <Header />
    <script>
        export default {
            async asyncData({ $content, params }) {
            const articles = await $content('blog') // instead of $content('articles', params.slug)
                .only(['title', 'slug'])
                .sortBy('createdAt', 'asc')
                .fetch()

            return {
                articles
                }
            }
        }
    </script>
    <Footer />
    </div>
</template>