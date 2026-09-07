---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

I have worked on so many projects over the years. This page lists some recent active
projects.


[Datalevin](https://github.com/datalevin/datalevin)
---

[![Clojars Downloads](https://img.shields.io/clojars/dt/datalevin)](https://clojars.org/datalevin)

This is an open-source database that I have been working on since 2020. It is a
new generation of general purpose database that is much more ergonomic than
traditional SQL RDBMS, while still has the benefits of relational databases.
Datalevin also comes with strong capabilities in graph, document and logical
database paradigms.

My goal is not just to compete with existing databases, but also to lay the
foundation for advanced artificial intelligence of the future: Just like memory
is the center of human cognition, databases ought to serve the same purpose in
artificial intelligence.

I have written some materials about Datalevin.

* Book [**Datalevin: the Definite Guide to Logical and Intelligent Databases**](https://www.amazon.com/dp/B0H8X1QF2Q/)
* Post [Datalevin 1.1.0: State-of-the-Art Performance Across Data Models](https://yyhh.org/blog/2026/09/datalevin-1-1-0-performance/)
* Post [Achieving High Throughput and Low Latency through Adaptive Asynchronous
  Transaction](https://yyhh.org/blog/2025/02/achieving-high-throughput-and-low-latency-through-adaptive-asynchronous-transaction/)
* Post [Competing for the JOB with a
  Triplestore](https://yyhh.org/blog/2024/09/competing-for-the-job-with-a-triplestore/)
* Post [T-Wand: Beat Lucene in Less Than 600 Lines of
  Code](https://yyhh.org/blog/2021/11/t-wand-beat-lucene-in-less-than-600-lines-of-code/)

The work on Datalevin is ongoing. [github](https://github.com/juji-io/datalevin)

[Xia](https://github.com/huahaiy/xia)
---

Xia is a secure Portable Persistent AI Assistant (P2A2) for online work. It runs
as a single local application, remembers context across sessions, works with any
LLM models, and helps with web research, browser automation, authenticated APIs,
and recurring online tasks. Xia does not have ambient access to the host machine
and runs task in sandbox.

One of the main innovation of Xia is its human-like memory architecture that
separate episodic from semantic memories, and a hippocampus for consolidation of
knowledge. Xia's internal state representation separates persistent goals from
transient states, and is robust in handling long horizon tasks. The vision of
Xia is to become an OS of intelligence. The work on Xia is ongoing.

[Editscript](https://github.com/juji-io/editscript)
---

[![Clojars Downloads](https://img.shields.io/clojars/dt/juji%2Feditscript)](https://clojars.org/juji/editscript)

This is an open-source Clojure library I wrote to diff/patch data structures. It
is widely in the Clojure community. I have given a talk on its use: [Data Diffing Based Software
Architecture Patterns](https://youtu.be/n-avEZHEHg8?si=_okX3Qexb5JtlYOf)

The work on the library is ongoing.
[github](https://github.com/juji-io/editscript)

[Juji Platform](https://juji.io)
---

I drove R&D of Juji Platform, an AI conversational agent platform that is the
basis of Juji Studio, Juji IDE and Juji API products of [Juji
Inc.](https://juji.io). Accenture acquired IP of Juji in 2026.

Juji is the leading conversational agent platform that allows customers to
retain total control while using generative AI, a unique yet critical capability
that enables successful enterprise use of generative AI.

I have given talks and written about Juji platform.

* [How can AI like ChatGPT be turned into gold in
  enterprises?](https://juji.io/blog/how-can-you-turn-ai-like-chatgt-into-gold-in-enterprise/)
  in 2023
* [Generative AI: Past, Present, and Future – A Practitioner's Perspective](https://www.slideshare.net/slideshow/genaipdf/260536464) in 2023
* [Three Big Ideas Behind the Surprising Power and Ease of Use of Juji Platform](https://juji.io/blog/three-big-ideas-behind-the-surprising-power-and-ease-of-use-of-juji-platform/)
  in 2020
* [A Clojure Fusion of Symbolic and Data Driven
  AI.](https://www.youtube.com/watch?v=phA4bMjKvCY&t=5s) in 2018

More details can be found on [Juji Documentation site](https://juji.io/docs).
