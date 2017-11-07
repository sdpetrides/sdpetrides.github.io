---
layout: post
title:  "You, Me, and System Design"
date:   2017-11-06 13:20:00 -0400
categories: systems computer-science
---
# Computer science is one of the best majors for a technical student. 

Computer science teaches problem solving and it is extremely applicable to many other disciplines. One of my favorite parts of computer science is system design. I love system design because I see it in everything. Here are some examples.

* When I design a scheduling algorithm for threads on a multi-core machine, I am also implementing a strategy for managing when employees work. 
* When I create a memory management system to optimize for multiple clients, I am really making a system for efficient access at a storage facility. 
* My solution to finding consensus among distrusting nodes is applicable to how a group of friends decides on which restaurant to try.

![Lego Airport]({{ '/images/lego_airport.jpg' | absolute_url }})
[Image Source](https://flic.kr/p/dW915G)

In its purest form, system design is about identifying a problem, assessing various trade-offs, and choosing a design pattern to solve that problem. Each tweak to the algorithm results in a new behavior of the system. The designers must carefully consider each trade-off to devise the system that meets the requirements and expectations just right. It is almost an art.

System design is central to the technology we rely everyday. Take for example, the Raft consensus algorithm. While it is very simple to understand, it was a breakthrough in system design. This algorithm allows multiple nodes come to agreement over many key-value pairs. This allows for replicated state machines. In other words, this allows us to have many consistent copies of the same thing on separate machines. Learn how Raft works with this [interactive demo](http://thesecretlivesofdata.com/raft/) or read the [technical paper](https://raft.github.io/raft.pdf).

Raft and algorithms just like it are at work in the technology that supports cryptocurrencies like Bitcoin and Ethereum. System design places nearly unlimited content at our fingertips without the slightest hint that data is streaming from machines located all over the world. System design is the reason why he walk around with more computing power in our pockets than NASA's engineers did to put a man on the [Moon](http://www.computerweekly.com/feature/Apollo-11-The-computers-that-put-man-on-the-moon).

![File System]({{ '/images/file_system.jpg' | absolute_url }})
[Image Source](https://flic.kr/p/bUZ7ow)

But system design does not stop there. It extends into arguably every technical discipline. While I have no experience with business management or industrial engineering, my problem solving skills carry over. I use them everyday for optimizing my morning routine and keeping my room organized with minimal time and effort. These are small things but they demonstrate how germane these skills are.

My ability to identify and assess the trade-offs of a proposed solution will be useful to any design problem. There lies the value of learning system design and studying computer science.

---

Links:

* [Raft Interactive Demo](http://thesecretlivesofdata.com/raft/)
* [Raft Technical Paper](https://raft.github.io/raft.pdf/)
* [Apollo 11: The computers that put man on the moon](http://www.computerweekly.com/feature/Apollo-11-The-computers-that-put-man-on-the-moon)
