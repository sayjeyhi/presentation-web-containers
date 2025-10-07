---
theme: seriph
background: https://images.unsplash.com/photo-1613690399151-65ea69478674?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=2072&q=80
class: text-center
highlighter: shiki
lineNumbers: false
info: |
  ## Web Containers and server in client concept
drawings:
  persist: false
css: unocss
---

# Web Containers
and server in client concept


<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    <carbon:arrow-right class="inline"/>
  </span>
</div>

<div class="avtar mt-36 rounded-full flex w-full align-center justify-center ">

  <a class="text-left ml-4 mt-2" href="https://github.com/sayjeyhi">
    <span class="text-gray-400">Oct 2025</span>
  </a>
</div>

<style>
h1 {
  font-weight: 900;
  background: #BECF24;
background: linear-gradient(to right, #BECF24 0%, #95E6FF 50%, #CF8377 100%);
-webkit-background-clip: text;
-webkit-text-fill-color: transparent;
}
</style>

---

# I'm
# Jafar Rezaei



<br />

<div class="grid grid-cols-2 gap-4 text-left text-sm text-gray-400">

<div>
<div class="text-base text-gray-300">

<span class="text-base text-green-400">By day</span>, I'm Squad Lead at Lyreco, e-commerce platform for launching in 25+ countries.

<br/> 

<span class="text-base text-green-400">By night</span>, I'm OSS lover, book writer, 3D enthusiast, game developer.

<svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 12 12"><!-- Icon from Dinkie Icons by atelierAnchor - https://github.com/atelier-anchor/dinkie-icons/blob/main/LICENSE --><path fill="currentColor" d="M3 2H2v1h1Zm0 0h6V1H3Zm-3 8h1V8H0Zm1 1h3v-1H1Zm3 1h6v-1H4ZM1 8h1V3H1Zm3 0h1V7H4ZM3 7h1V5H3Zm2 2h2V8H5Zm5 2h1v-1h-1Zm-1-1h1V8H9ZM5 5h1V4H5Zm2 2h1V6H7ZM6 4h1V3H6Zm2 2h1V5H8Zm2 2h1V3h-1ZM9 3h1V2H9Zm0 0"/></svg>

</div>

<br/>


</div>
<div>
  <img class="absolute top-10 right-20 w-24 h-24 rounded-full grayscale" src="/openart-video_cf97c9b8_1759827505833.gif" />
  <img src="https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExcjdhYWZ2eDM4ZHdzeG5jYXllNGh3ZnMzeWF1d2kwNXo3M3dzMTE0YyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/JTTAjM197sku8MgrRa/giphy.gif" />
</div>
</div>


---
layout: center
align: center
---


<svg xmlns="http://www.w3.org/2000/svg" width="54" height="54" viewBox="0 0 12 12"><!-- Icon from Dinkie Icons by atelierAnchor - https://github.com/atelier-anchor/dinkie-icons/blob/main/LICENSE --><path fill="currentColor" d="M4 12h4v-2h2V9h1V6h-1v2H9V6H8V5H7V2H6V1H1v1H0v2h3v1H0v2h3v1H2v1h2V8h1v2h1v1H4Zm0-9V2h1v1Zm0 0"/></svg>

<br/>


# WEB CONTAINERS

<v-click>
<span class="text-gray-400">
server in client
</span>
</v-click>

<!--
Today we will know about web containers

if you are already familiar with the concept  
or you ask someone who knows web container they might say it is server in client.
-->

---

<div class="flex text-center gap-40 flex-row-reverse w-full align-center justify-center h-80 py-3 text-gray-400">
<div class="w-32">
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><!-- Icon from Tabler Icons by Paweł Kuna - https://github.com/tabler/tabler-icons/blob/master/LICENSE --><path fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 7a3 3 0 0 1 3-3h12a3 3 0 0 1 3 3v2a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3zm9 13H6a3 3 0 0 1-3-3v-2a3 3 0 0 1 3-3h10.5m-.5 6a2 2 0 1 0 4 0a2 2 0 1 0-4 0m2-3.5V16m0 4v1.5m3.032-5.25l-1.299.75m-3.463 2l-1.3.75m0-3.5l1.3.75m3.463 2l1.3.75M7 8v.01M7 16v.01"/></svg>
<h2 class="mt-8">Servers</h2>
</div>
<div class="w-32">
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 256 256"><!-- Icon from Phosphor by Phosphor Icons - https://github.com/phosphor-icons/core/blob/main/LICENSE --><g fill="currentColor"><path d="M240 86v84a8 8 0 0 1-5.8 7.69L128 208V48l106.2 30.34A8 8 0 0 1 240 86" opacity=".2"/><path d="M236.4 70.65L130.2 40.31a8 8 0 0 0-3.33-.23L21.74 55.1A16.08 16.08 0 0 0 8 70.94v114.12a16.08 16.08 0 0 0 13.74 15.84l105.13 15a8.5 8.5 0 0 0 1.13.1a8 8 0 0 0 2.2-.31l106.2-30.34A16.07 16.07 0 0 0 248 170V86a16.07 16.07 0 0 0-11.6-15.35M96 120H80V62.94l40-5.72v141.56l-40-5.72V136h16a8 8 0 0 0 0-16M24 70.94l40-5.72V120H48a8 8 0 0 0 0 16h16v54.78l-40-5.72Zm112 126.45V58.61L232 86v84Z"/></g></svg>
<h2 class="mt-8">Containers</h2>
</div>
</div>


<div class="flex items-center justify-center mt-8 text-blue-400 text-base relative right-[-5px]">
?
</div>

<!--
We should know about containers and servers.
-->

---

<div class="flex flex-col text-center gap-8 w-full align-center justify-center h-80 py-3 text-gray-400">
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 256 256"><!-- Icon from Phosphor by Phosphor Icons - https://github.com/phosphor-icons/core/blob/main/LICENSE --><g fill="currentColor"><path d="M240 86v84a8 8 0 0 1-5.8 7.69L128 208V48l106.2 30.34A8 8 0 0 1 240 86" opacity=".2"/><path d="M236.4 70.65L130.2 40.31a8 8 0 0 0-3.33-.23L21.74 55.1A16.08 16.08 0 0 0 8 70.94v114.12a16.08 16.08 0 0 0 13.74 15.84l105.13 15a8.5 8.5 0 0 0 1.13.1a8 8 0 0 0 2.2-.31l106.2-30.34A16.07 16.07 0 0 0 248 170V86a16.07 16.07 0 0 0-11.6-15.35M96 120H80V62.94l40-5.72v141.56l-40-5.72V136h16a8 8 0 0 0 0-16M24 70.94l40-5.72V120H48a8 8 0 0 0 0 16h16v54.78l-40-5.72Zm112 126.45V58.61L232 86v84Z"/></g></svg>
<h2>Container <div class="text-sm mt-2">1950</div></h2>

</div>

<div></div>

<br/>

<v-click>

> Redefined how things moved around the world

</v-click>

<!--
When shipping containers were introduced in the 1950s, no one thought they were exciting.

They looked like simple metal boxes, but there was more to the story. 
- Many people saw them as a bad idea
- worried about their jobs
- owners hesitated due to the expense 

everyone's attention was on the wrong aspects
rather than the boxes themselves.



It wasn’t about making shipping more efficient. It was about redefining how things moved.
-->

---
layout: center
---

# Containers in tech?

What do we mean when we say "Container" OR "Web Containers"?


<v-click>

<div class="rounded-full flex w-full mt-12 align-center justify-center ">
<img class="w-80" src="https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExNTRiY3E4YmR6MnV2bmN1ZmxmOWsxNWY2YWE2eDIwNnFrdWhobjI5eSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/pPhyAv5t9V8djyRFJH/giphy.gif" />
</div>

<div class="text-center mt-2">
Containers I used but web container? 
</div>

</v-click>

<!--
They play a critical role in technology as well.
and you might be familiar with some of Containers.

but What is web container?
-->

---
layout: center
---


# Web Containers?

Is it related to Container Query (CSS)?

<div class="rounded-full mt-10 flex w-full align-center justify-center ">
<img class="w-[60%]" src="/css-container.jpg" />
</div>


---
layout: center
---

# Web Containers?

Maybe Media Container?

<div class="rounded-full mt-10 flex w-full align-center justify-center ">
<img class="w-[60%]" src="/media-container.jpg" />
</div>


---
layout: center
---


# Web Containers?

Is it related to Docker containers?

<div class="rounded-full mt-10 flex w-full align-center justify-center ">
<img class="w-[60%]" src="/docker-container.png" />
</div>

---
layout: center
---

<v-clicks>
<pre>
   <span class="text-blue-400">"Web"</span>                +              <span class="text-green-400">"Containers"</span>
</pre>


<pre>
     |                                       |
     v                                       v
</pre>

<pre>
because the container            they behave like lightweight, isolated 
runs entirely in the             environments <span class="text-green-400">(similar to Docker containers)</span>, 
<span class="text-blue-300">browser tab</span> and fully         
<span class="text-blue-300">client-side</span>.                     <span class="text-green-400">- own boundaries</span>
                                 <span class="text-green-400">- own filesystem</span>
                                 <span class="text-green-400">- own process model</span> 
                              
</pre>


<div>
<br />
<br />

<div class="text-xl text-gray-300 leading-relaxed">

a browser-based runtime for executing <span v-mark.box.orange>Node.js</span> applications and operating system commands, entirely inside your browser tab.

</div>

<div class="text-xs text-gray-500 mt-4">[<a href="https://webcontainers.io/guides/introduction/">official webcontainer.io definition</a>]</div>

</div>

</v-clicks>



---

# WC vs Cloud VM
What makes it different?

<div class="grid grid-cols-2 mt-12 h-70 gap-4 text-left text-sm text-gray-400 bg-white/10 p-6 rounded-lg">

<div>
  <img class="rounded-none" src="https://webcontainers.io/img/theme/webcontainer_api-logo-dark-blackwhite.svg"/>


  <div class="flex flex-col gap-8 items-center text-center mt-16 text-gray-300">
    <svg class="text-green-500" xmlns="http://www.w3.org/2000/svg" width="60" height="60" viewBox="0 0 12 12"><!-- Icon from Dinkie Icons by atelierAnchor - https://github.com/atelier-anchor/dinkie-icons/blob/main/LICENSE --><path fill="currentColor" d="M5 12h5v-1H8v-1h2v1h1V5H8v1h2v1H8V6H7v5H5Zm-5 0h3v-1h2v-1H3V7h1V6H2v5H1V6h1V5H0Zm4-6h1V5H4Zm4 3V8h2v1ZM5 5h1V2h1V1H5Zm2 0h1V2H7Zm0 0"/></svg>

    No latency, faster than localhost, offline 
  </div>
</div>


<div class="border-l-2 border-dashed border-white/20 pl-8">
  <div class="flex gap-4 items-center justify-start">
    <svg xmlns="http://www.w3.org/2000/svg" width="35" height="35" viewBox="0 0 24 24"><!-- Icon from Cyber free icons by Streamline - https://creativecommons.org/licenses/by/4.0/ --><g fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-miterlimit="10"><path d="M22.5 5.5H.5v6h22zm-4-4h-14l-4 4h22zm1 6v2m-2-2v2m-2-2v2"/><path d="M4.75 7.25L3.5 8.5l1.25 1.25L6 8.5zM22.5 11.5H.5v6h22zm-3 2v2m-2-2v2m-2-2v2"/><path d="M4.75 13.25L3.5 14.5l1.25 1.25L6 14.5zM22.5 17.5H.5v6h22zm-3 2v2m-2-2v2m-2-2v2"/><path d="M4.75 19.25L3.5 20.5l1.25 1.25L6 20.5z"/></g></svg>
    <strong class="text-xl text-white!">VMs, Servers</strong>
  </div>


  <div class="flex flex-col gap-8 items-center text-center mt-16 text-gray-300">
    <svg class="scale-y-[-1] text-red-500" xmlns="http://www.w3.org/2000/svg" width="60" height="60" viewBox="0 0 12 12"><!-- Icon from Dinkie Icons by atelierAnchor - https://github.com/atelier-anchor/dinkie-icons/blob/main/LICENSE --><path fill="currentColor" d="M5 12h5v-1H8v-1h2v1h1V5H8v1h2v1H8V6H7v5H5Zm-5 0h3v-1h2v-1H3V7h1V6H2v5H1V6h1V5H0Zm4-6h1V5H4Zm4 3V8h2v1ZM5 5h1V2h1V1H5Zm2 0h1V2H7Zm0 0"/></svg>

    Network latency, online only
  </div>
</div>
</div>

<div class="flex items-center justify-center mt-8 text-blue-400 text-base relative right-[-5px]">
[User Experience]
</div>


---



# WC vs Cloud VM
What makes it different?

<div class="grid grid-cols-2 mt-12 h-70 gap-4 text-left text-sm text-gray-400 bg-white/10 p-6 rounded-lg">

<div>
  <img class="rounded-none" src="https://webcontainers.io/img/theme/webcontainer_api-logo-dark-blackwhite.svg"/>


  <div class="flex flex-col gap-8 items-center text-center mt-16 text-gray-300">
    <svg class="text-green-500" xmlns="http://www.w3.org/2000/svg" width="60" height="60" viewBox="0 0 12 12"><!-- Icon from Dinkie Icons by atelierAnchor - https://github.com/atelier-anchor/dinkie-icons/blob/main/LICENSE --><path fill="currentColor" d="M5 12h5v-1H8v-1h2v1h1V5H8v1h2v1H8V6H7v5H5Zm-5 0h3v-1h2v-1H3V7h1V6H2v5H1V6h1V5H0Zm4-6h1V5H4Zm4 3V8h2v1ZM5 5h1V2h1V1H5Zm2 0h1V2H7Zm0 0"/></svg>

     Millions via CDN + client compute
  </div>
</div>


<div class="border-l-2 border-dashed border-white/20 pl-8">
  <div class="flex gap-4 items-center justify-start">
    <svg xmlns="http://www.w3.org/2000/svg" width="35" height="35" viewBox="0 0 24 24"><!-- Icon from Cyber free icons by Streamline - https://creativecommons.org/licenses/by/4.0/ --><g fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-miterlimit="10"><path d="M22.5 5.5H.5v6h22zm-4-4h-14l-4 4h22zm1 6v2m-2-2v2m-2-2v2"/><path d="M4.75 7.25L3.5 8.5l1.25 1.25L6 8.5zM22.5 11.5H.5v6h22zm-3 2v2m-2-2v2m-2-2v2"/><path d="M4.75 13.25L3.5 14.5l1.25 1.25L6 14.5zM22.5 17.5H.5v6h22zm-3 2v2m-2-2v2m-2-2v2"/><path d="M4.75 19.25L3.5 20.5l1.25 1.25L6 20.5z"/></g></svg>
    <strong class="text-xl text-white!">VMs, Servers</strong>
  </div>


  <div class="flex flex-col gap-8 items-center text-center mt-16 text-gray-300">
    <svg class="scale-y-[-1] text-red-500" xmlns="http://www.w3.org/2000/svg" width="60" height="60" viewBox="0 0 12 12"><!-- Icon from Dinkie Icons by atelierAnchor - https://github.com/atelier-anchor/dinkie-icons/blob/main/LICENSE --><path fill="currentColor" d="M5 12h5v-1H8v-1h2v1h1V5H8v1h2v1H8V6H7v5H5Zm-5 0h3v-1h2v-1H3V7h1V6H2v5H1V6h1V5H0Zm4-6h1V5H4Zm4 3V8h2v1ZM5 5h1V2h1V1H5Zm2 0h1V2H7Zm0 0"/></svg>

    Limited by server scaling
  </div>
</div>
</div>

<div class="flex items-center justify-center mt-8 text-blue-400 text-base relative right-[-5px]">
[Scale]
</div>

---

# WC vs Cloud VM
What makes it different?

<div class="grid grid-cols-2 mt-12 h-70 gap-4 text-left text-sm text-gray-400 bg-white/10 p-6 rounded-lg">

<div>
  <img class="rounded-none" src="https://webcontainers.io/img/theme/webcontainer_api-logo-dark-blackwhite.svg"/>


  <div class="flex flex-col gap-8 items-center text-center mt-16 text-gray-300">
    <svg class="text-green-500" xmlns="http://www.w3.org/2000/svg" width="60" height="60" viewBox="0 0 12 12"><!-- Icon from Dinkie Icons by atelierAnchor - https://github.com/atelier-anchor/dinkie-icons/blob/main/LICENSE --><path fill="currentColor" d="M5 12h5v-1H8v-1h2v1h1V5H8v1h2v1H8V6H7v5H5Zm-5 0h3v-1h2v-1H3V7h1V6H2v5H1V6h1V5H0Zm4-6h1V5H4Zm4 3V8h2v1ZM5 5h1V2h1V1H5Zm2 0h1V2H7Zm0 0"/></svg>

     No miners, malware, phishing
  </div>
</div>


<div class="border-l-2 border-dashed border-white/20 pl-8">
  <div class="flex gap-4 items-center justify-start">
    <svg xmlns="http://www.w3.org/2000/svg" width="35" height="35" viewBox="0 0 24 24"><!-- Icon from Cyber free icons by Streamline - https://creativecommons.org/licenses/by/4.0/ --><g fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-miterlimit="10"><path d="M22.5 5.5H.5v6h22zm-4-4h-14l-4 4h22zm1 6v2m-2-2v2m-2-2v2"/><path d="M4.75 7.25L3.5 8.5l1.25 1.25L6 8.5zM22.5 11.5H.5v6h22zm-3 2v2m-2-2v2m-2-2v2"/><path d="M4.75 13.25L3.5 14.5l1.25 1.25L6 14.5zM22.5 17.5H.5v6h22zm-3 2v2m-2-2v2m-2-2v2"/><path d="M4.75 19.25L3.5 20.5l1.25 1.25L6 20.5z"/></g></svg>
    <strong class="text-xl text-white!">VMs, Servers</strong>
  </div>


  <div class="flex flex-col gap-8 items-center text-center mt-16 text-gray-300">
    <svg class="scale-y-[-1] text-red-500" xmlns="http://www.w3.org/2000/svg" width="60" height="60" viewBox="0 0 12 12"><!-- Icon from Dinkie Icons by atelierAnchor - https://github.com/atelier-anchor/dinkie-icons/blob/main/LICENSE --><path fill="currentColor" d="M5 12h5v-1H8v-1h2v1h1V5H8v1h2v1H8V6H7v5H5Zm-5 0h3v-1h2v-1H3V7h1V6H2v5H1V6h1V5H0Zm4-6h1V5H4Zm4 3V8h2v1ZM5 5h1V2h1V1H5Zm2 0h1V2H7Zm0 0"/></svg>

    Risk of bad actors
  </div>
</div>
</div>

<div class="flex items-center justify-center mt-8 text-blue-400 text-base relative right-[-5px]">
[Security]
</div>

---

# WC vs Cloud VM
What makes it different?

<div class="grid grid-cols-2 mt-12 h-70 gap-4 text-left text-sm text-gray-400 bg-white/10 p-6 rounded-lg">

<div>
  <img class="rounded-none" src="https://webcontainers.io/img/theme/webcontainer_api-logo-dark-blackwhite.svg"/>


  <div class="flex flex-col gap-8 items-center text-center mt-16 text-gray-300">
    <svg class="scale-y-[-1] text-red-500" xmlns="http://www.w3.org/2000/svg" width="60" height="60" viewBox="0 0 12 12"><!-- Icon from Dinkie Icons by atelierAnchor - https://github.com/atelier-anchor/dinkie-icons/blob/main/LICENSE --><path fill="currentColor" d="M5 12h5v-1H8v-1h2v1h1V5H8v1h2v1H8V6H7v5H5Zm-5 0h3v-1h2v-1H3V7h1V6H2v5H1V6h1V5H0Zm4-6h1V5H4Zm4 3V8h2v1ZM5 5h1V2h1V1H5Zm2 0h1V2H7Zm0 0"/></svg>

     Owned by stackblitz, and a bit blackbox
  </div>
</div>


<div class="border-l-2 border-dashed border-white/20 pl-8">
  <div class="flex gap-4 items-center justify-start">
    <svg xmlns="http://www.w3.org/2000/svg" width="35" height="35" viewBox="0 0 24 24"><!-- Icon from Cyber free icons by Streamline - https://creativecommons.org/licenses/by/4.0/ --><g fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-miterlimit="10"><path d="M22.5 5.5H.5v6h22zm-4-4h-14l-4 4h22zm1 6v2m-2-2v2m-2-2v2"/><path d="M4.75 7.25L3.5 8.5l1.25 1.25L6 8.5zM22.5 11.5H.5v6h22zm-3 2v2m-2-2v2m-2-2v2"/><path d="M4.75 13.25L3.5 14.5l1.25 1.25L6 14.5zM22.5 17.5H.5v6h22zm-3 2v2m-2-2v2m-2-2v2"/><path d="M4.75 19.25L3.5 20.5l1.25 1.25L6 20.5z"/></g></svg>
    <strong class="text-xl text-white!">VMs, Servers</strong>
  </div>


  <div class="flex flex-col gap-8 items-center text-center mt-16 text-gray-300">
    <svg class="text-green-500" xmlns="http://www.w3.org/2000/svg" width="60" height="60" viewBox="0 0 12 12"><!-- Icon from Dinkie Icons by atelierAnchor - https://github.com/atelier-anchor/dinkie-icons/blob/main/LICENSE --><path fill="currentColor" d="M5 12h5v-1H8v-1h2v1h1V5H8v1h2v1H8V6H7v5H5Zm-5 0h3v-1h2v-1H3V7h1V6H2v5H1V6h1V5H0Zm4-6h1V5H4Zm4 3V8h2v1ZM5 5h1V2h1V1H5Zm2 0h1V2H7Zm0 0"/></svg>

    Open source, auditable, long term
  </div>
</div>
</div>

<div class="flex items-center justify-center mt-8 text-blue-400 text-base relative right-[-5px]">
[Limitations]
</div>

---



# WC vs Cloud VM
What makes it different?

<div class="grid grid-cols-2 mt-12 h-70 gap-4 text-left text-sm text-gray-400 bg-white/10 p-6 rounded-lg">

<div>
  <img class="rounded-none" src="https://webcontainers.io/img/theme/webcontainer_api-logo-dark-blackwhite.svg"/>


  <div class="flex flex-col gap-8 items-center text-center mt-16 text-gray-300">
    <svg class="text-green-500" xmlns="http://www.w3.org/2000/svg" width="60" height="60" viewBox="0 0 12 12"><!-- Icon from Dinkie Icons by atelierAnchor - https://github.com/atelier-anchor/dinkie-icons/blob/main/LICENSE --><path fill="currentColor" d="M5 12h5v-1H8v-1h2v1h1V5H8v1h2v1H8V6H7v5H5Zm-5 0h3v-1h2v-1H3V7h1V6H2v5H1V6h1V5H0Zm4-6h1V5H4Zm4 3V8h2v1ZM5 5h1V2h1V1H5Zm2 0h1V2H7Zm0 0"/></svg>

    Free local compute (paid for commercial use)
  </div>
</div>


<div class="border-l-2 border-dashed border-white/20 pl-8">
  <div class="flex gap-4 items-center justify-start">
    <svg xmlns="http://www.w3.org/2000/svg" width="35" height="35" viewBox="0 0 24 24"><!-- Icon from Cyber free icons by Streamline - https://creativecommons.org/licenses/by/4.0/ --><g fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-miterlimit="10"><path d="M22.5 5.5H.5v6h22zm-4-4h-14l-4 4h22zm1 6v2m-2-2v2m-2-2v2"/><path d="M4.75 7.25L3.5 8.5l1.25 1.25L6 8.5zM22.5 11.5H.5v6h22zm-3 2v2m-2-2v2m-2-2v2"/><path d="M4.75 13.25L3.5 14.5l1.25 1.25L6 14.5zM22.5 17.5H.5v6h22zm-3 2v2m-2-2v2m-2-2v2"/><path d="M4.75 19.25L3.5 20.5l1.25 1.25L6 20.5z"/></g></svg>
    <strong class="text-xl text-white!">VMs, Servers</strong>
  </div>


  <div class="flex flex-col gap-8 items-center text-center mt-16 text-gray-300">
    <svg class="scale-y-[-1] text-red-500" xmlns="http://www.w3.org/2000/svg" width="60" height="60" viewBox="0 0 12 12"><!-- Icon from Dinkie Icons by atelierAnchor - https://github.com/atelier-anchor/dinkie-icons/blob/main/LICENSE --><path fill="currentColor" d="M5 12h5v-1H8v-1h2v1h1V5H8v1h2v1H8V6H7v5H5Zm-5 0h3v-1h2v-1H3V7h1V6H2v5H1V6h1V5H0Zm4-6h1V5H4Zm4 3V8h2v1ZM5 5h1V2h1V1H5Zm2 0h1V2H7Zm0 0"/></svg>

    Pay per minute
  </div>
</div>
</div>

<div class="flex items-center justify-center mt-8 text-blue-400 text-base relative right-[-5px]">
[Cost Efficiency]
</div>

---

# Local Demo!

http://localhost:5173/

<iframe src="http://localhost:5173/" width="100%" height="500px"></iframe>


---

# WebContainer _requires_:
2 simple rules to work

<br/>
<br/>

<v-click>


- Deployed page must be served over <span v-mark.box.orange>HTTPS</span>. Not necessary for `localhost` (exempt from some browser restrictions), but required to deploy to production.

<br/>
<br/>


- <span v-mark.box.orange><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/SharedArrayBuffer" target="_blank" >SharedArrayBuffer</a></span>. Root document must be served with:



```typescript
Cross-Origin-Embedder-Policy: require-corp
Cross-Origin-Opener-Policy: same-origin
```


</v-click>


---
layout: center
---

<div class="flex w-full align-center justify-start ml-10 mb-4 h-40 py-3 text-gray-400">
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><!-- Icon from Material Design Icons by Pictogrammers - https://github.com/Templarian/MaterialDesign/blob/master/LICENSE --><path fill="currentColor" d="M19 8h1v1h-1zm1-3h-1v2h1V6h.5c.28 0 .5-.22.5-.5v-2c0-.28-.22-.5-.5-.5H18v1h2zm-3-2h-1v4h1zm-3.5 12.5a2 2 0 1 0 4 0c0-1.11-.89-2-2-2s-2 .9-2 2M17 8h-1v1h1zm5 6h-1c0-1.5-.47-2.87-1.26-4h-2.77c1.22.91 2.03 2.36 2.03 4v2h2v1h-2v3H5v-3H3v-1h2v-2c0-2.76 2.24-5 5-5h4c.34 0 .68.04 1 .1V7.08c-.33-.05-.66-.08-1-.08h-1V5.73A2 2 0 1 0 10 4c0 .74.4 1.39 1 1.73V7h-1c-3.87 0-7 3.13-7 7H2c-.55 0-1 .45-1 1v3c0 .55.45 1 1 1h1v1a2 2 0 0 0 2 2h14c1.11 0 2-.89 2-2v-1h1c.55 0 1-.45 1-1v-3c0-.55-.45-1-1-1m-13.5-.5c-1.1 0-2 .9-2 2s.9 2 2 2s2-.89 2-2s-.89-2-2-2"/></svg>
</div>


# SharedArrayBuffer?
We had also other array-like objects in JavaScript?

<br/>
<br/>

- There was a regular ArrayBuffer?
- I heard about Int8Array/Int16Array/Int32Array but shared?
- We also have UInt8Array/UInt16Array/UInt32Array...




---

# ArrayBuffer
ArrayBuffer is just a block of memory

<div class="grid grid-cols-2 gap-4 mt-12">
<div>

- Created by: `new ArrayBuffer(size)`
- Accessed via: Int8Array, Uint8Array, etc.
- Used in: WebGL, File APIs, binary protocols, etc.
- Only one thread can use it.

</div>
<div>

<div class="flex w-full align-center justify-center h-40 py-3 text-gray-400">
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><!-- Icon from Sargam Icons by Abhimanyu Rana - https://github.com/planetabhi/sargam-icons/blob/main/LICENSE.txt --><g fill="none"><path fill="currentColor" fill-opacity=".16" fill-rule="evenodd" d="M7.4 5h9.2A2.4 2.4 0 0 1 19 7.4v9.2a2.4 2.4 0 0 1-2.4 2.4H7.4A2.4 2.4 0 0 1 5 16.6V7.4A2.4 2.4 0 0 1 7.4 5m3.2 4h2.8a1.6 1.6 0 0 1 1.6 1.6v2.8a1.6 1.6 0 0 1-1.6 1.6h-2.8A1.6 1.6 0 0 1 9 13.4v-2.8A1.6 1.6 0 0 1 10.6 9" clip-rule="evenodd"/><path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-miterlimit="10" stroke-width="1.5" d="M14 5V3m-4 2V3m4 18v-2m-4 2v-2m11-5h-2m2-4h-2M5 14H3m2-4H3m4.4-5h9.2A2.4 2.4 0 0 1 19 7.4v9.2a2.4 2.4 0 0 1-2.4 2.4H7.4A2.4 2.4 0 0 1 5 16.6V7.4A2.4 2.4 0 0 1 7.4 5m3.2 4h2.8a1.6 1.6 0 0 1 1.6 1.6v2.8a1.6 1.6 0 0 1-1.6 1.6h-2.8A1.6 1.6 0 0 1 9 13.4v-2.8A1.6 1.6 0 0 1 10.6 9"/></g></svg>
</div>
</div>
</div>

<br/>
<br/>
<br/>

👉 A box of memory that only you can touch.

---

# Typed Arrays (Int8Array, Uint8Array, etc.)
holes to view/edit inside the box

<div class="grid grid-cols-2 gap-4 mt-12">
<div>

```typescript
         +----------------------------------+
         |                                  |
         |          ArrayBuffer             |
         |        0101000100111010          |
         |     [ raw bytes of memory ]      |
         |                                  |
         +----------------------------------+
               ↑                    ↑
           Int8Array          Float32Array
         (small lens)       (different lens)
```

</div>

<div class="flex w-full align-center justify-center h-40 py-3 text-gray-400">
<svg xmlns="http://www.w3.org/2000/svg"  viewBox="0 0 512 512"><!-- Icon from Game Icons by GameIcons - https://github.com/game-icons/icons/blob/master/license.txt --><path fill="currentColor" d="M88.125 31.344c-13.054.25-26.12 5.152-32.906 13.843L87.28 221.78c-19.708 13.59-35.83 29.68-47.25 47.657c-12.288 19.35-18.983 40.904-18.968 62.688v.03c-.015 21.785 6.68 43.308 18.97 62.658c12.296 19.36 30.06 36.565 51.874 50.78s47.62 25.404 75.656 32.97s58.217 11.5 88.438 11.5c30.22 0 60.402-3.934 88.438-11.5c28.035-7.566 53.873-18.754 75.687-32.97s39.547-31.42 51.844-50.78c12.288-19.35 18.983-40.873 18.967-62.657v-.03c.016-21.758-6.676-43.263-18.937-62.595l-.03-.092c-11.426-17.99-27.557-34.094-47.283-47.688L456.72 45.187c-10.86-13.906-37.754-18.04-55.033-9.062l-10.25 66.656H120.5l-10.22-66.686c-6.478-3.367-14.323-4.9-22.155-4.75zm39.844 120.094h256l-6.94 45.125a294 294 0 0 0-32.592-10.875c-28.036-7.566-58.217-11.47-88.438-11.47c-30.22 0-60.402 3.904-88.438 11.47a294 294 0 0 0-32.656 10.906zM256 196.78c28.71 0 57.438 3.75 83.844 10.876c11.757 3.173 23.078 7.005 33.75 11.438l-7.906 51.406H146.25l-7.875-51.375c10.684-4.44 22.01-8.292 33.78-11.47c26.407-7.125 55.135-10.874 83.845-10.874zm164.406 48.595c15.023 11.292 27.036 24.022 35.438 37.25c10.226 16.1 15.236 32.92 15.22 49.5l-.002.03c.018 16.58-4.992 33.37-15.218 49.47c-10.227 16.1-25.784 31.476-45.625 44.406c-19.843 12.93-43.97 23.438-70.376 30.564C313.438 463.72 284.71 467.47 256 467.47s-57.438-3.75-83.844-10.876s-50.502-17.633-70.344-30.563c-19.84-12.93-35.43-28.304-45.656-44.405c-10.226-16.1-15.236-32.89-15.218-49.47v-.03c-.018-16.58 4.992-33.4 15.218-49.5c8.395-13.218 20.4-25.934 35.407-37.22l30.812 169.69c13.39 10.178 31.056 16.062 49.344 21.342l-4.407-28.78h177.312l-4.406 28.78c18.287-5.28 35.984-11.164 49.374-21.343l30.812-169.72zM151.437 304.28H360.5l-12.188 79.533H163.656l-12.22-79.532z"/></svg>
</div>
</div>

<br/>
<br/>


👉 They let you look into the box and interpret what’s inside

---

# SharedArrayBuffer
a shared box of bytes

<div class="grid grid-cols-2 gap-4 mt-12">
<div>

- Created by: `new SharedArrayBuffer(size)`
- Access with TypedArrays (`Int16Array`, etc.)
- Used for: parallel or worker communication
- Multiple threads can read/write simultaneously

</div>
<div class="flex w-full align-center justify-center h-40 py-3 text-gray-400">
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><!-- Icon from Solar by 480 Design - https://creativecommons.org/licenses/by/4.0/ --><path fill="currentColor" d="M7.205 7.562a.75.75 0 0 0-.993-1.124A8.73 8.73 0 0 0 3.25 13a.75.75 0 0 0 1.5 0a7.23 7.23 0 0 1 2.455-5.438m10.583-1.124a.75.75 0 0 0-.993 1.124A7.23 7.23 0 0 1 19.25 13a.75.75 0 0 0 1.5 0a8.73 8.73 0 0 0-2.962-6.562m-7.601 13.584a.75.75 0 1 0-.374 1.452a8.8 8.8 0 0 0 4.374 0a.75.75 0 1 0-.374-1.452A7.3 7.3 0 0 1 12 20.25a7.3 7.3 0 0 1-1.813-.228" opacity=".5"/><path fill="currentColor" d="M9 6a3 3 0 1 0 6 0a3 3 0 0 0-6 0M2.5 18a3 3 0 1 0 6 0a3 3 0 0 0-6 0m16 3a3 3 0 1 1 0-6a3 3 0 0 1 0 6"/></svg>
</div>
</div>

<br/>

```javascript
Main Thread                                                       Worker Thread
   |                      +---------------------+                        |
   |                      |  SharedArrayBuffer  |                        |
   +----------------------|    001110110101     |------------------------+
                          |  [ shared memory ]  |
                          +---------------------+

```

---

# SharedArrayBuffer

<div class="grid grid-cols-2 gap-4 text-left text-sm text-gray-400">


<img src="/img.png" class="w-full mx-auto my-8"/>

<div>
<br/>


The syntax to create and pass a SharedArrayBuffer to a Web Worker is similar to that of a regular ArrayBuffer:

<br/>

```javascript
const myWorker = new Worker("worker.js");

const sab = new SharedArrayBuffer(1024);
myWorker.postMessage(sab);
```

</div></div>

<!--
There is a guy standing between our app and memory called JS Engine.

He is a bit transparent and don't notice him managing the memory for us, because he is kind to us (current thread)
-->

---

```javascript

Main Thread                                                      Worker Thread
     |                                                                 |
     |                       (creation / transfer)                     |
     |<----------------------- request SAB access -------------------->|
     |                                                                 |
     |                       +-----------------------+                 |
     |                       |     JS Engine         |                 |
     |                       |-----------------------|                 |
     |                       | Checks:               |                 |
     |                       |  - COOP: same-origin  |                 |
     |                       |  - COEP: require-corp |                 |
     |                       |  => crossOriginIsolated ?               |
     |                       +-----------------------+                 |
     |                             /          \                        |
     |                   allowed (true)      blocked (false)           |
     |                          /                                      |
     |                         v                                       |
     |               +---------------------+                           |
     |               |  SharedArrayBuffer  |                           |
     +---------------|    001110110101     |-------postMessage(...)----+
                     |  [ shared memory ]  |
                     +---------------------+

```

---

# Spectre attack

<img src="/spectre-attack.gif" class="w-3/4 mx-auto my-8"/>

---

# High-precision timers
sub-millisecond accuracy [far finer than Date.now()]

<br />
<br />
<br />

<div class="grid grid-cols-2 gap-4 text-left text-sm text-gray-400">
<div>

- **SharedArrayBuffer** + **Atomics.wait**() (if available)
- **performance.now**() + **requestAnimationFrame**() 
- **AudioContext** (Web Audio API)
- **WebGL** rendering times
- more

</div>
<div class="flex w-full align-center justify-center h-32 text-gray-400">

<svg xmlns="http://www.w3.org/2000/svg" class="w-40" viewBox="0 0 12 12"><!-- Icon from Dinkie Icons by atelierAnchor - https://github.com/atelier-anchor/dinkie-icons/blob/main/LICENSE --><path fill="currentColor" d="M3 11H2v1h1Zm0 0h5v-1h1V9h1V4H9V3H8V2H6V1H5v1H3v1H2v1H1v5h1v1h1Zm5 1h1v-1H8ZM0 4h1V3h1V2H0Zm5 3V3h1v3h2v1Zm5-3h1V2H9v1h1Zm0 0"/></svg>


</div>
</div>

---

# How they attack?

<br/>

- **Cache timing (Spectre/Meltdown)**  
  Use precise timing to detect how CPU cache behaves and guess secret data.

- **Cross-site leaks (XS-Leaks)**  
  Measure how long other websites take to respond to learn things like:
  - If a user is logged in
  - What content they can access

- **Fingerprinting & tracking**  
  Use stable timers (like from audio or GPU) to find unique hardware patterns and track devices.

- **Keystroke or touch inference**  
  Use very accurate timers to detect timing between key presses or touches and infer user behavior.


--- 

# What browsers do to mitigate

<br/>

- **Reduce precision** & add jitter to timers when not isolated:
  performance.now() is often limited (~1 ms or worse) and randomized; background tabs get even coarser (setTimeout ≥ 1–4 ms+).

- Gate the strongest primitives behind cross-origin isolation (COOP+COEP) so sites must opt in knowingly to regain SharedArrayBuffer.

- Site Isolation / Spectre mitigations in engines, partitioned caches, and policy headers to reduce cross-origin information flow.

---


# COEP and COOP

- Cross-Origin Embedder Policy (COEP)
- Cross-Origin Opener Policy (COOP)

---

# Why using SharedArrayBuffer?

WebAssembly shared memory
WebAssembly.Memory objects can be created with the shared constructor flag. When this flag is set to true, the constructed Memory object can be shared between workers via postMessage(), just like SharedArrayBuffer, and the backing buffer of the Memory object is a SharedArrayBuffer. Therefore, the requirements listed above for sharing a SharedArrayBuffer between workers also apply to sharing a WebAssembly.Memory.

---

# Quick look at WebAssembly
Let's see a simple example of WebAssembly in action.

```bash
source ~/emsdk/emsdk_env.sh
```

```bash
emcc -v
```

```bash
emcc hello.c -o hello.html
```

```bash
bunx serve
```



---


# Web Container in web container!


https://stackblitz.com/edit/webcontainer-fst-demo?file=main.js


---

# Web Containers
## The New Frontier



- Run development environments in the browser
- Powered by WebAssembly
- Zero local setup required
- Revolutionary approach to web development



---

# How Web Containers Work

<div class="grid ~ cols-2 gap-4">
<div>



## Core Technologies
- WebAssembly (Wasm)
- Browser APIs
- Virtualization
- File System Simulation



</div>
<div>



## Key Features
- In-browser Execution
- Native-like Performance
- Secure Sandboxing
- Cross-platform Support



</div>
</div>

---

# WebAssembly's Role



- Enables near-native performance
- Supports multiple programming languages
- Provides secure execution environment
- Bridges native and web applications
- Powers complex in-browser applications



---

# Real-World Examples



- **bolt.new**: Full-stack development environment
- **Figma**: Collaborative design tool
- **Autodesk Fusion 360**: 3D modeling
- **Canva**: Browser-based design platform



---

# Use Cases for Web Containers

<div grid="~ cols-2 gap-4">
<div>



## Development
- Interactive coding
- Rapid prototyping
- Code sharing
- Live collaboration


</div>
<div>



## Education

- Programming tutorials
- Interactive learning
- Instant setup
- Real-time feedback



</div>
</div>

---

# Advantages of Web Containers

- No local setup required
- Instant access from any device
- Consistent environment
- Easy collaboration
- Resource efficiency



---

# Limitations of Web Containers

- Browser dependency
- Performance constraints
- Limited access to local resources
- Internet connectivity required
- Complex architecture



---
layout: center
class: text-center
---

# Demo time!

#### Let's see a Web Container in action...

---

# Feature environment

Preview review and create PR in the browser

https://github.com/sayjeyhi/ui.pr.new

---

# Web Containers Deep Dive

- **Architecture**
  - Browser runtime
  - Virtual file system
  - Network simulation
  - Process management

- **Integration**
  - IDE features
  - Git support
  - Package management

---

# WASM Beyond the Browser
How the future might look like?

“Cool, but we’re not doing any browser-based rendering.”

Or worse:
“We’re not a gaming company.”

---

# WASM Beyond the Browser

---

# DockerCon 2023

<div>
<img class="w-[70%]" src="/docker-web-assembly.59.21.png" />
</div>

3rd generation of containers: WebAssembly

---

Change is hard at first, messy in the middle and gorgeous at the end.
with web assembly, web containers and shared array buffer, the web is getting gorgeous!

---

<div>
<img class="w-[70%]" src="/docker-wasi-wasm.51.08.png" />
</div>

Sometimes someone builds something and people say "It can do that as well" and "It can do the other thing as well"

---

<img src="https://github.com/container2wasm/container2wasm/raw/main/docs/images/ubuntu-wasi-on-browser.png">

https://github.com/container2wasm/container2wasm

---

# WebAssembly 3.0 Spec
Released September 2025

<div>
<img class="w-[70%]" src="/wasm3_0.png" />
</div>

---

# WASM Runtimes

- **[WasmEdge](https://wasmedge.org/)**: A lightweight, high-performance WebAssembly runtime optimized for edge computing.
  - 100x faster startup compared to Linux containers.
  - 1/100th application size, with WASM modules often under 20 MB.
  - 20% faster runtime performance than traditional containerized inference.
- **[Wassette](https://github.com/microsoft/wassette)**: Microsoft announced WebAssembly 3.0 support in Azure Functions
- **[Wasmtime](https://github.com/bytecodealliance/wasmtime)**: A standalone runtime for WebAssembly and WASI, built by the Bytecode Alliance.
- **[Wasmer](https://wasmer.io/)**: A universal WebAssembly runtime that can run WASM modules anywhere.
- **Mozilla Wasm Agents**: Each Wasm Agent compiles into a WASM binary, and executed directly in the browser’s WASM runtime.

---

# resources

- https://webcontainers.io/
- Lin Clark from Mozilla has a great cartoon intro to ArrayBuffers and SharedArrayBuffers:
https://hacks.mozilla.org/2017/06/a-cartoon-intro-to-arraybuffers-and-sharedarraybuffers/

- https://webassembly.org/news/2025-09-17-wasm-3.0/
- [The Universal Microservices Architecture (UMA) | White Paper](https://docs.google.com/document/d/1MHj8ruFsGsZTNfMayP9Xck2qAMnXu-qfjTs0zWjP8OE/edit?source=collection_home_page----a64ecaa04f0c----------------------------------------&tab=t.0#heading=h.lldls594wja3)
- [Why Device independent Matters More Than Ever](https://medium.com/the-rise-of-device-independent-architecture/why-device-independence-matters-more-than-ever-27afe78a0a61)
- https://github.com/bytecodealliance/wasmtime
- https://www.youtube.com/watch?v=7553XZ0T6pM
- https://medium.com/wasm-radar/i-beg-you-please-stop-thinking-webassembly-is-only-for-the-web-a24f502cde78
- https://www.youtube.com/watch?v=KHy3XIlGIJ8
- https://hacks.mozilla.org/2019/08/webassembly-interface-types/
- [COEP COOP CORP CORS CORB - CRAP that's a lot of new stuff!](https://scotthelme.co.uk/coop-and-coep/)
- [Cloudflare workers Performance and timers](https://developers.cloudflare.com/workers/runtime-apis/performance/)

---
layout: center
class: text-center
---

# Questions?

Thank you for your attention!

<br />
<br />

[GitHub](https://github.com/sayjeyhi) · [Contact](mailto:sayjeyhi@gmail.com)
