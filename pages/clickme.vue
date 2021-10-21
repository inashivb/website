<template lang="html">
    <div>
        <p class="pt-12">Since you fell for the (annoying) clickbait, here's your chance to do a noble deed.</p>
        <p>Below is the list of some awesome open source projects.</p>
        <p>If you also use any of these projects, please consider donating. If you are not in a position to donate, please give them a shout-out on Twitter, check their GitHub and leave a &#11088;!</p>
        <div class="flex-col p-10">
            <div class="card" onclick="location.href='https://oisf.net/memberships'">
                <a href="#"></a>
                <div>
                    <h2 class="font-bold">Suricata</h2>
                </div>
            </div>
            </br>
            <div class="card" onclick="location.href='https://www.rust-lang.org/sponsors';">
                <a href="#"></a>
                <div>
                    <h2 class="font-bold">Rust</h2>
                </div>
            </div>
            </br>
            <div class="card" onclick="location.href='https://opencollective.com/nuxtjs#contribute'">
               <a href="#"></a>
                <div>
                    <h2 class="font-bold">Nuxt.js</h2>
                </div>
            </div>
        </br>
            <div class="card" onclick="location.href='https://github.com/darktable-org/darktable'">
               <a href="#"></a>
                <div>
                    <h2 class="font-bold">Darktable</h2>
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
    text-align: center;
}
</style>