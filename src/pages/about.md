---
layout: ../layouts/AboutLayout.astro
title: "About Me"
---

Welcome to my corner of the Internet! [Stay awhile, and read on](https://www.youtube.com/watch?v=tAVVy_x3Erg).
I am Szymon Duchniewicz, a software engineer passionate about Open Source, [wind and wave chaser](/assets/windsurf_is_up.jpeg). I am a principal contributor of the [Carbon Aware SDK project](https://github.com/Green-Software-Foundation/carbon-aware-sdk) and work part-time as an Open Technology Engineer at [Avanade](https://www.avanade.com/en-gb). I graduated UCL with first class honours Master of Engineering degree in Computer Science. My thesis focused on analysing and improving the memory management system of CantripOS -- an experimental seL4-based operating system (PDF and abstract can be found below).


<div>
  <img src="/assets/me_cropped.jpg" class="sm:w-1/2 mx-auto" alt="Headshot of yours truly!">
</div>

## Tech Stack

I dabble in many areas of computer science, but with a stronger focus on Embedded Systems, Natural Language Processing and Computer Vision. I also occasionally take part in game jams, even [winning some of them](https://hist0r.itch.io/the-deluge).

My programming languages of choice are C, Python 🐍 and Rust 🦀, but you will find me using .NET, GoLang and others from time to time.

## Interests

Apart from the (I am told) obvious passion for Computer Science, there are a few other things I hold close to heart - windsurfing and surfing. Ask me over a beer/coffee and I will be happy to talk about any of them!

# Academia
## MEng Thesis: ``Improving the Space Efficiency of Dynamic Memory Allocation in an Experimental Capability-Based Operating System''

[PDF version available here](/assets/MEng_thesis.pdf).

Supervisor: [Prof. Brad Karp](http://www0.cs.ucl.ac.uk/staff/b.karp/)

**Abstract**: Efficient management and tracking of memory resources pose a significant challenge for computer systems due to diverse program memory requirements and system constraints. This thesis aims to improve the memory management system of CantripOS, a new experimental operating system designed for cost-constrained, memory-limited edge compute nodes, built atop the secure, formally verified seL4 microkernel. We investigate the space efficiency and performance of CantripOS’s memory management system, hypothesising significant memory fragmentation due to the system’s global rather than per-region memory tracking. The primary goals of this work are to improve memory bookkeeping in CantripOS, decrease failed allocation system calls, and reduce memory fragmentation. We evaluate two different memory allocators: next-fit and best-fit, and show that our improvements eliminate failed allocation system calls and substantially decrease memory fragmentation for various synthetic and representative workloads.

<!---
TODO: Add skills, socials and tl;dr on the blogs content and recent achievments
---!>
