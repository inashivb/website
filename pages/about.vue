<template lang="html">
    <div>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <Header />
        <p class="p-3 text-left text-xl">I am Shivani. I work as a programmer. I am found someplace in India for most of the year.</p>
        <p class="p-3 text-left text-xl">I get paid to <s>write code</s> break code and the fix it. I sometimes architect solutions and develop features too.</p>
        <p class="p-3 text-left text-xl">I am currently employed by <a class="text-blue-600" href="https://oisf.net/">OISF</a> to work on <a class="text-blue-600" href="https://suricata.io/">Suricata</a> and its <a class="text-blue-600" href="https://github.com/orgs/OISF/repositories">auxiliary tools</a>.</p>
        <p class="p-3 text-left text-xl">My current favorite programming language is Rust.</p>
        <p class="p-3 text-left text-xl">My text editor of choice is Vim.</p>
        <p class="p-3 text-left text-xl font-bold">Computer languages</p>
        <div class="flex flex-row">
            <div class="text-center w-40">Rust</div>
            <div class="bg-yellow-600 flex-grow w-1/2"></div>
            <div class="bg-yellow-200 flex-grow w-1/2">50%</div>
        </div><br>
        <div class="flex flex-row">
            <div class="text-center w-40">C</div>
            <div class="bg-yellow-600 flex-grow w-3/5"></div>
            <div class="bg-yellow-200 flex-grow w-2/5">60%</div>
        </div><br>
        <div class="flex flex-row">
            <div class="text-center w-40">Python</div>
            <div class="bg-yellow-600 flex-grow w-4/5"></div>
            <div class="bg-yellow-200 flex-grow w-1/5">80%</div>
        </div><br> 
        <p class="p-3 text-left text-xl font-bold">Human Languages</p>
        <div class="flex flex-row">
            <div class="text-center w-40">हिंदी</div>
            <div class="bg-pink-800 flex-grow w-11/12"></div>
            <div class="bg-red-200 flex-grow w-1/12">90%</div>
        </div><br>
        <div class="flex flex-row">
            <div class="text-center w-40">English</div>
            <div class="bg-pink-800 flex-grow w-11/12"></div>
            <div class="bg-red-200 flex-grow w-1/12">90%</div>
        </div><br>
        <div class="flex flex-row">
            <div class="text-center w-40">Español</div>
            <div class="bg-pink-800 flex-grow w-3/5"></div>
            <div class="bg-red-200 flex-grow w-2/5">60%</div>
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
.icon {
  padding: 20px;
  font-size: 30px;
  width: 50px;
  text-align: center;
  text-decoration: none;
  margin: 5px 2px;
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