---
layout: post
title:  "You, Me, and System Design"
date:   2017-11-06 13:20:00 -0400
categories: systems computer-science
---
# Computer science is one of the best majors for a technical student. 

Computer science teaches problem solving and it is highly applicable to many other disciplines. One of my favorite parts of computer science is system design. I love system design because I see it in everything. Here are some examples.

* When I design a scheduling algorithm for threads on a multi-core machine, I am also implementing a strategy for managing how employees can work together. 
* If I create a memory management system to optimize for multiple clients, I am really making a system for efficient access at a storage facility. 
* My solution to finding consensus among distrusting nodes is applicable to how a group of friends decides on which new restaurant to trial.

![Lego Airport]({{ '/images/lego_airport.jpg' | absolute_url }})
[Image Source](https://flic.kr/p/dW915G)

In its purest form, system design is about identifying a problem, assessing various trade-offs, and choosing a design pattern to solve that problem. Each tweak to the algorithm results new behavior. The designers must carefully consider each trade-off to devise the system that meets the requirements and expectations. It is almost an art.

System design is central to the technology we rely on everyday. Take for example, the Raft consensus algorithm. While it is very simple to understand, it was a breakthrough in system design. This algorithm allows multiple nodes to come to agreement over many key-value pairs. We can create many replicated state machines. In other words, this allows us to have many consistent copies of the same data on separate machines. Learn how Raft works with this [interactive demo](http://thesecretlivesofdata.com/raft/) or read the [technical paper](https://raft.github.io/raft.pdf). My favorite part is how they use timeouts for leader election. That is genius.

Raft and algorithms just like it are built in the technology that supports cryptocurrencies like Bitcoin and Ethereum. Cloud storage places nearly unlimited content at our fingertips without the slightest hint that data is streaming from machines located all over the world. Multithreaded processes is one of the reasons why we have more computing power in our pockets than NASA's engineers did to put a man on the [Moon](http://www.computerweekly.com/feature/Apollo-11-The-computers-that-put-man-on-the-moon). System design is responsible these and countless other software advancements.

![File System]({{ '/images/file_system.jpg' | absolute_url }})
[Image Source](https://flic.kr/p/bUZ7ow)

Still, system design does not stop there. It extends into arguably every technical discipline. While I have no experience with business management or industrial engineering, my problem solving skills carry over everywhere. I use them everyday for optimizing my morning routine and keeping my room organized with minimal time and effort. These are small things but they demonstrate how relevant these skills are.

I don't know what I will use my system design skills for in the future. I hope I can contribute to some interesting software projects. I hope I can make the world a better place. Most of all, I hope I can help inspire the next-generation of designers to tear up my designs and redefine what is possible.

---

Links:

* [Raft Interactive Demo](http://thesecretlivesofdata.com/raft/)
* [Raft Technical Paper](https://raft.github.io/raft.pdf/)
* [Apollo 11: The computers that put man on the moon](http://www.computerweekly.com/feature/Apollo-11-The-computers-that-put-man-on-the-moon)
