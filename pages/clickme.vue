<template lang="html">
    <div>
    <Header/>
        <p class="px-12 pt-32 text-left text-2xl">Since you did fall for the (annoying) clickbait, here's your chance to do a noble deed.</p>
        <p class="px-12 text-left text-2xl">Below is the list of a few open source projects that are awesome and I endorse.</p>
        <p class="px-12 text-left text-2xl">If you also use any of these projects, please consider donating. If you are not in a position to donate, please check their GitHub and leave a &#11088;!</p>
        <div class="flex-col p-10">
            <div class="myBox card text-center" onclick="location.href='https://oisf.net/memberships'">
                <a href="#"></a>
                <div>
                    <h2 class="font-bold">Suricata</h2>
                </div>
            </div>
            </br>
            <div class="card text-center" onclick="location.href='https://www.rust-lang.org/sponsors';">
                <a href="#"></a>
                <div>
                    <h2 class="font-bold">Rust</h2>
                </div>
            </div>
            </br>
            <div class="card text-center" onclick="location.href='https://opencollective.com/nuxtjs#contribute'">
                <a href="#"></a>
                <div>
                    <h2 class="font-bold">Nuxt.js</h2>
                </div>
            </div>
<!--            </br>
            <div class="card text-center">
                <a href="#"></a>
                <div>
                    <h2>Blah</h2>
                </div>
            </div>
            </br>
            <div class="card text-center">
                <a href="#"></a>
                <div>
                    <h2>Blah</h2>
                </div>
            </div> -->       
        </div>
    <Footer/>
    </div>
</template>

<style scoped>
.card {
    background-color: #f9fafb;
    border-radius: 25px;
    box-shadow: 0 3px 10px 0 #aaa;
    cursor: pointer;
    height: 100px;
    position: relative;
    width: 100%;
    padding: 10px;
}
</style>