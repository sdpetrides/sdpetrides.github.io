---
layout: post
title:  "You, Me, and System Design"
date:   2017-11-06 13:20:00 -0500
categories: technology
---
# Computer science is one of the best majors for a technical student. 

Computer science teaches problem-solving and it is highly applicable to other disciplines. One of my favorite parts of computer science is system design. I love system design because I see it in everything. Here are some examples.

* If I am implementing a strategy for managing how employees can work together, I am creating a scheduling algorithm.
* If I am making a system for efficient storage access at a production facility, I am creating a memory management system.
* If I am part of a group that is deciding on a new restaurant to try, I am using a consensus algorithm.

![Lego Airport]({{ '/images/lego_airport.jpg' | absolute_url }})
[Image Source](https://flic.kr/p/dW915G)

In its purest form, system design is about identifying a problem, assessing various trade-offs, and choosing a design pattern to solve that problem. Each tweak to the algorithm results in new behavior. The designers must carefully consider each trade-off to devise the system that meets the requirements and expectations. It’s a practical form of art.

System design is central to the technology we rely on every day. Take, for example, the Raft consensus algorithm. While it is very simple to understand, it was a breakthrough in system design. This algorithm allows multiple nodes to come to an agreement over many key-value pairs. We can create many replicated state machines. In other words, this allows us to have many consistent copies of the same data on separate machines. My favorite part is how Raft uses timeouts for leader election. That is genius.

Learn how Raft works with this [interactive demo](http://thesecretlivesofdata.com/raft/) or read the [technical paper](https://raft.github.io/raft.pdf).

System design extends into arguably every technical discipline. While I have no experience with business management or industrial engineering, my problem-solving skills carry over everywhere. I use them every day for optimizing my morning routine and keeping my room organized with minimal time and effort. These are small things but they demonstrate how relevant these skills are.

I don't know what I will use my system design skills for in the future. I hope I can contribute to some interesting software projects. I hope I can make the world a better place. Most of all, I hope I can help inspire the next generation of designers to tear up my designs and redefine what is possible.


---

Links:

* [Raft Interactive Demo](http://thesecretlivesofdata.com/raft/)
* [Raft Technical Paper](https://raft.github.io/raft.pdf/)
