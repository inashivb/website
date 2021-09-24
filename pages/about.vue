<template lang="html">
    <div class="relative">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <Header />
        <p class="px-8 text-left text-2xl pt-32">I am Shivani. I work as a programmer. I am found someplace in India for most of the year.</p>
        <p class="px-8 py-3 text-left text-2xl">I get paid to <s>write code</s> break code and the fix it. I sometimes architect solutions and develop features too.</p>
        <p class="px-8 py-3 text-left text-2xl">I am currently employed by <a class="text-blue-600" href="https://oisf.net/">OISF</a> to work on <a class="text-blue-600" href="https://suricata.io/">Suricata</a> and its <a class="text-blue-600" href="https://github.com/orgs/OISF/repositories">auxiliary tools</a>.</p>
        <p class="px-8 py-3 text-left text-2xl">My current favorite programming language is Rust.</p>
        <p class="px-8 py-3 text-left text-2xl">My text editor of choice is Vim.</p>
        <p class="px-8 pt-3 pb-8 text-left text-2xl font-bold">Computer languages</p>
        <div class="flex flex-row pr-10">
            <div class="text-center w-40">Rust</div>
            <div class="comp-lang-fr-bar w-1/2"></div>
            <div class="comp-lang-bk-bar w-1/2">50%</div>
        </div><br>
        <div class="flex flex-row pr-10">
            <div class="text-center w-40">C</div>
            <div class="comp-lang-fr-bar w-3/5"></div>
            <div class="comp-lang-bk-bar w-2/5">60%</div>
        </div><br>
        <div class="flex flex-row pr-10">
            <div class="text-center w-40">Python</div>
            <div class="comp-lang-fr-bar w-4/5"></div>
            <div class="comp-lang-bk-bar w-1/5">80%</div>
        </div><br> 
        <p class="px-8 pt-3 pb-8 text-left text-2xl font-bold">Human Languages</p>
        <div class="flex flex-row pr-10">
            <div class="text-center w-40">हिंदी</div>
            <div class="human-lang-fr-bar w-11/12"></div>
            <div class="human-lang-bk-bar w-1/12">90%</div>
        </div><br>
        <div class="flex flex-row pr-10">
            <div class="text-center w-40">English</div>
            <div class="human-lang-fr-bar w-11/12"></div>
            <div class="human-lang-bk-bar w-1/12">90%</div>
        </div><br>
        <div class="flex flex-row pr-10">
            <div class="text-center w-40">Español</div>
            <div class="human-lang-fr-bar w-3/5"></div>
            <div class="human-lang-bk-bar w-2/5">60%</div>
        </div><br>
        <p class="p-3 text-left text-xl font-bold">Social links</p>
        <div class="pl-3 flex flex-row">
            <div><a href="https://www.linkedin.com/in/shivan1" class="icon fa fa-linkedin flex-grow"></a></div>
            <div><a href="https://twitter.com/tuxish" class="icon fa fa-twitter flex-grow"></a></div>
            <div><a href="https://stackoverflow.com/users/3715736/unixia" class="icon fa fa-stack-overflow flex-grow"></a></div>
            <div><a href="https://github.com/inashivb" class="icon fa fa-github flex-grow"></a></div> 
        </div>
    <Footer />
    </div>
</template>

<style>
.comp-lang-fr-bar {
    background: #fcd34d;
    display: flex-grow;
}

.comp-lang-bk-bar {
    background: #fef3c7;
    display: flex-grow;
}

.human-lang-fr-bar {
    background: #f472b6;
    display: flex-grow;
}

.human-lang-bk-bar {
    background: #fbcfe8;
    display: flex-grow;
}

.icon {
  padding: 20px;
  font-size: 30px;
  text-align: center;
  margin: 5px 5px;
  border-radius: 50%;
}

.fa:hover {
    opacity: 0.7;
}

.fa-twitter {
  background: #55ACEE;
  color: white;
}

.fa-linkedin {
  background: #007bb5;
  color: white;
}

.fa-stack-overflow {
    background:#ef8236;
    color: white;
}

.fa-github {
    background: #333;
    color: white;
}
</style>