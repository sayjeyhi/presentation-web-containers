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

# Web Containers and server in client concept


<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    <carbon:arrow-right class="inline"/>
  </span>
</div>

<div class="avtar mt-36 rounded-full flex w-full align-center justify-center ">
  <img class="w-18 h-18 rounded-full grayscale" src="https://avatars.githubusercontent.com/u/6254009?v=4" />

  <a class="text-left ml-4 mt-2" href="https://github.com/sayjeyhi">
    <strong class="text-xl">Jafar Rezaei</strong> <br/>
    <span class="text-gray-400">Oct 2026</span>
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

# About Me


<span class="text-base text-gray-300">

By day, I'm a Tech Lead at Lyreco, building an e-commerce platform for a big international company.

By night, I'm an open-source enthusiast, creating tools, games and libraries.

</span>

<br />
<br />
<br />

- Jafar Rezaei
- **GitHub**: [sayjeyhi](https://github.com/sayjeyhi)
- **Twitter**: [@sayjeyhi](https://twitter.com/sayjeyhi)
- **LinkedIn**: [Jafar Rezaei](https://www.linkedin.com/in/jafar-rezaei)
- **[sayjeyhi.com](https://sayjeyhi.com)**


---
layout: center
---

# Containers?

What do we have in mind when we say "Web Containers"?


<v-click>

<div class="rounded-full flex w-full mt-12 align-center justify-center ">
<img class="w-80" src="https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExNTRiY3E4YmR6MnV2bmN1ZmxmOWsxNWY2YWE2eDIwNnFrdWhobjI5eSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/pPhyAv5t9V8djyRFJH/giphy.gif" />
</div>

</v-click>


---
layout: center
---


# Web Containers?

Is it related to Container Query (CSS)?

<div class="rounded-full mt-10 flex w-full align-center justify-center ">
<img class="w-[60%]" src="./css-container.jpg" />
</div>


---
layout: center
---


# Web Containers?

Is it related to Docker containers?

<div class="rounded-full mt-10 flex w-full align-center justify-center ">
<img class="w-[60%]" src="./docker-container.png" />
</div>

---
layout: center
---

# Web Containers?


<br/>

❌ Container Query (CSS)?

❌ Docker Containers


✅ &nbsp;Web Containers

> Main focus for this presentation, powered by WebAssembly


---
layout: center
---

<pre>
   <span class="text-blue-400">"Web"</span>                   <span class="text-green-400">"Containers"</span>
     |                          |
     v                          v
because the            because they behave like
container runs         lightweight, isolated 
entirely in the        environments <span class="text-green-400">(similar </span>
<span class="text-blue-300">browser</span>,               <span class="text-green-400">to Docker containers)</span>, 
<span class="text-blue-300">client-side</span>.           with their <span class="text-green-400">own filesystem</span>, 
                       <span class="text-green-400">process model</span>, and 
                       <span class="text-green-400">package manager</span>.
</pre>


---
layout: center
---

# What are Web Containers?

<div class="text-xl text-gray-300 leading-relaxed">

a browser-based runtime for executing <span v-mark.box.orange>Node.js</span> applications and operating system commands, entirely inside your browser tab. 

</div>

<div class="text-xs text-gray-500 mt-24">[<a href="https://webcontainers.io/guides/introduction/">official webcontainer.io definition</a>]</div>

---

# Web Containers vs Cloud VM
What makes it different?


<br/>

| #             | WebContainers (client-side)                     | Cloud VMs (legacy)           |
|---------------|-------------------------------------------------|------------------------------|
| **UX**        | No latency, faster than localhost, offline      | Network latency, online only |
| **Cost**      | Free local compute                              | Pay per minute               |
| **Scale**     | Millions via CDN + client compute               | Limited by server scaling    |
| **Run model** | In-browser, no server needed                    | Remote VM in cloud           |
| **Security**  | No miners, malware, phishing                    | Risk of bad actors           |
| **Start**     | [Starter on StackBlitz](https://stackblitz.com) | VM setup + config required   |


---

# Local Demo!

http://localhost:5173/

<iframe src="http://localhost:5173/" width="100%" height="500px"></iframe>


---

# Requirements for Web Containers

WebContainer _requires_ [SharedArrayBuffer](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/SharedArrayBuffer) to function.
In turn, this requires your website to be [cross-origin isolated](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/SharedArrayBuffer#security_requirements). Among other things, the root document must be served with:


---


<div class="rounded-full mt-10 flex w-full align-center justify-center ">
<img class="w-full" src="./shared-buffer-array.png" />
</div>

---

# SharedArrayBuffer

<br/> 

```javascript
const myWorker = new Worker("worker.js");

const sab = new SharedArrayBuffer(1024);
myWorker.postMessage(sab);
```

---

# Why using SharedArrayBuffer?

WebAssembly shared memory
WebAssembly.Memory objects can be created with the shared constructor flag. When this flag is set to true, the constructed Memory object can be shared between workers via postMessage(), just like SharedArrayBuffer, and the backing buffer of the Memory object is a SharedArrayBuffer. Therefore, the requirements listed above for sharing a SharedArrayBuffer between workers also apply to sharing a WebAssembly.Memory.

---


# COEP and COOP

- Cross-Origin Embedder Policy (COEP)
- Cross-Origin Opener Policy (COOP)

---

# Serve over HTTPS

Deployed page must be served over HTTPS. This is not necessary when developing locally, as `localhost` is exempt from some browser restrictions, but there is no way around it once you deploy to production.

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

<div grid="~ cols-2 gap-4">
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

# Pricing Models

<div grid="~ cols-2 gap-4">
<div>



## Common Models
- Freemium
- Subscription
- Pay-as-you-go
- Enterprise licensing



</div>
<div>



## Factors
- Usage volume
- Features needed
- Team size
- Support level



</div>
</div>

---

# Container Comparison

|Feature|Media Containers|Docker Containers|Web Containers|
|-------|---------------|-----------------|--------------|
|Purpose|Content delivery|App deployment|Browser execution|
|Technology|Codecs|OS virtualization|WebAssembly|
|Benefit|Unified media|Portability|Instant dev env|
|Use Case|Media playback|App deployment|Web development|


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

# Future Trends

- Enhanced browser capabilities
- Improved WebAssembly performance
- Hybrid container solutions
- New use cases emerging
- Evolution of standards


---

# Getting Started



1. Identify your needs
2. Choose the right container type
3. Start with simple examples
4. Gradually add complexity
5. Learn from the community



---

# Resources & Learning



- Official documentation
- Community forums
- Online courses
- Books and tutorials
- Practice projects



---

# resources

https://hacks.mozilla.org/2017/06/a-cartoon-intro-to-arraybuffers-and-sharedarraybuffers/

---
layout: center
class: text-center
---

# Questions?

Thank you for your attention!

<br />
<br />

[GitHub](https://github.com/sayjeyhi) · [Contact](mailto:sayjeyhi@gmail.com)
