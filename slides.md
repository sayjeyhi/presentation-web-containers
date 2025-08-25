---
theme: seriph
background: https://images.unsplash.com/photo-1451187580459-43490279c0fa?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=2072&q=80
class: text-center
highlighter: shiki
lineNumbers: false
info: |
  ## Web Containers, Docker Containers, Media Containers
  How to use different types of containers in modern technology
drawings:
  persist: false
css: unocss
---

# Containers are Everywhere!

CSS Media Containers, Docker Containers, Web Containers?!

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    <carbon:arrow-right class="inline"/>
  </span>
</div>

<div class="avtar mt-36 rounded-full flex w-full align-center justify-center ">
  <img class="w-18 h-18 rounded-full grayscale" src="https://avatars.githubusercontent.com/u/6254009?v=4" />

  <a class="text-left ml-4 mt-2" href="https://github.com/sayjeyhi">
    <strong class="text-xl">Jafar Rezaei</strong> <br/>
    <span class="text-gray-400">Feb 2024</span>
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

# Overview

Understanding different types of containers in modern technology

- 📦 Media Containers
- 🐳 Docker Containers

## 🌐 Web Containers
Main focus for this presentation, powered by WebAssembly

---

# Why Talk About Containers?


- Containers are fundamental to modern technology
- They solve different problems in unique ways
- Understanding containers helps make better technical decisions
- Each type serves a specific purpose in the tech ecosystem


---

# Media Containers
## The Basics



- File formats that bundle multimedia content
- Package multiple streams into a single file
- Common examples: MP4, MKV, AVI
- Essential for digital media distribution



---

# Media Container Structure

<div grid="~ cols-2 gap-4">
<div>



- Video Stream
- Audio Stream(s)
- Subtitles
- Chapters
- Metadata
- Timestamps



</div>
<div>

```mermaid {scale: 0.7}
graph TD
    A[Media Container] --> B[Video Stream]
    A --> C[Audio Streams]
    A --> D[Subtitles]
    A --> E[Metadata]
    C --> F[Audio 1]
    C --> G[Audio 2]
```

</div>
</div>

---

# Media Container Benefits



- **Synchronization**: Keep audio and video in perfect sync
- **Organization**: Multiple streams in one file
- **Flexibility**: Support various codecs
- **Portability**: Easy to move and share
- **Metadata**: Store additional information



---

# Docker Containers
## Introduction



- Lightweight, standalone packages
- Contains everything needed to run an application
- Revolutionary approach to software deployment
- Industry standard for containerization



---

# Docker Container Architecture

```mermaid {scale: 0.8}
graph TD
    A[Application] --> B[Dependencies]
    B --> C[Container Runtime]
    C --> D[Host OS]
    D --> E[Infrastructure]
```

---

# Docker Container Benefits

<div grid="~ cols-2 gap-4">
<div>



- Isolation
- Portability
- Consistency
- Efficiency
- Scalability



</div>
<div>



- Version Control
- Quick Deployment
- Resource Management
- Easy Updates
- Security



</div>
</div>

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

# Media Containers Deep Dive



- **Popular Formats**
  - MP4: Universal compatibility
  - MKV: Flexibility and features
  - AVI: Legacy support
- **Use Cases**
  - Streaming services
  - Digital distribution
  - Media archiving



---

# Docker Containers Deep Dive



- **Key Components**
  - Dockerfile
  - Images
  - Containers
  - Registry
- **Ecosystem**
  - Docker Hub
  - Kubernetes
  - Docker Compose



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

# Security Considerations

<div grid="~ cols-2 gap-4">
<div>



## Media Containers
- DRM support
- Content protection
- Format validation



</div>
<div>



## Docker & Web Containers
- Isolation
- Vulnerability scanning
- Access control
- Resource limits



</div>
</div>

---

# Performance Comparison



- **Media Containers**: Optimized for streaming
- **Docker Containers**: Near-native performance
- **Web Containers**: Browser-dependent performance
- Trade-offs and considerations
- Use case-specific requirements



---

# Future Trends



- Enhanced browser capabilities
- Improved WebAssembly performance
- Hybrid container solutions
- New use cases emerging
- Evolution of standards



---

# Best Practices

<div grid="~ cols-2 gap-4">
<div>



## Selection
- Understand requirements
- Consider limitations
- Evaluate alternatives
- Plan for scaling



</div>
<div>



## Implementation
- Follow standards
- Monitor performance
- Regular updates
- Security first



</div>
</div>

---

# Integration Strategies



- Combining container types
- Hybrid approaches
- Migration paths
- Compatibility considerations
- Performance optimization



---

# Tools and Resources

<div grid="~ cols-2 gap-4">
<div>



## Development
- IDEs
- CLI tools
- SDKs
- Documentation



</div>
<div>



## Monitoring
- Performance tools
- Analytics
- Debugging
- Logging



</div>
</div>

---

# Case Studies



- Successful implementations
- Lessons learned
- Common pitfalls
- Best practices
- Real-world impact



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
layout: center
class: text-center
---

# Questions?

Thank you for your attention!

<br />
<br />

[GitHub](https://github.com/sayjeyhi) · [Contact](mailto:sayjeyhi@gmail.com)
