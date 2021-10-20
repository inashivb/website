<template lang="html">
    <div>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
        <p class="pt-12">I am Shivani. I work as a programmer. I am found at some place in India for most of the year.</p>
        <p>I get paid to <s>write code</s> break code and then fix it. I sometimes architect solutions and develop features too.</p>
        <p>I am currently employed by <a class="text-blue-600" href="https://oisf.net/">OISF</a> to work on <a class="text-blue-600" href="https://suricata.io/">Suricata</a> and its <a class="text-blue-600" href="https://github.com/orgs/OISF/repositories">auxiliary tools</a>.</p>
        <p>My current favorite programming language is Rust.</p>
        <p>My text editor of choice is Vim.</p>
        <p class="text-3xl">Computer languages</p>
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
        <p class="text-3xl">Human Languages</p>
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
        <p class="text-3xl">Social links</p>
        <div class="pl-8 flex flex-row">
            <div><a href="https://www.linkedin.com/in/shivan1" class="icon fa fa-linkedin flex-grow"></a></div>
            <div><a href="https://twitter.com/tuxish" class="icon fa fa-twitter flex-grow"></a></div>
            <div><a href="https://stackoverflow.com/users/3715736/unixia" class="icon fa fa-stack-overflow flex-grow"></a></div>
            <div><a href="https://github.com/inashivb" class="icon fa fa-github flex-grow"></a></div> 
        </div>
    </div>
</template>

<style>
.comp-lang-fr-bar {
    background: #4b5563;
    display: flex-grow;
}

.comp-lang-bk-bar {
    background: #d1d5db;
    display: flex-grow;
}

.human-lang-fr-bar {
    background: #f87171;
    display: flex-grow;
}

.human-lang-bk-bar {
    background: #fee2e2;
    display: flex-grow;
}

.icon {
  padding: 20px;
  font-size: 30px;
  text-align: center;
  margin: 5px 5px;
  border-radius: 20%;
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