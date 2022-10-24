# CK.Books

Software engineering stuff I've read that you might be interested in.

**Note:** I’m not affiliated with any of the authors/publishers/etc. in anyway, and the perspective I shared is my own, not necessarily my [employer's](https://www.linkedin.com/in/collinkruger/).

<hr/>

## Learning HTTP/2

https://www.oreilly.com/library/view/learning-http2/9781491962435/

![Learning HTTP/2 Book Cover](img/learning-http-2.png)

HTTP/2 is the now widely supported successor of HTTP/1.1. Built on top of the work done at Google for the SPDY protocol, HTTP/2 significantly alters the very simple request-response paradigm of HTTP/1.1, including adding server push, multiplexing over a single TCP connection, and alterations to how headers work including compression. 

Learning HTTP/2 can be defined as a book in three acts. How did we get here and what were the problems and solutions along the way? How does HTTP/2 address those problems, what are its pros and cons, and what tools and techniques are available for working with it and debugging? And where do we see the future going? 

At important points, the authors took a numbers driven approach to comparing HTTP/1.1 to HTTP/2, demonstrating that certain metrics like Time To First Byte don’t mean the same thing between the protocols, and that in certain scenarios HTTP/2 performs worse than HTTP/1.1. As an engineer and also just core to who I am, I really appreciate these honest observations. 

At just 156 pages, the authors largely adhered to the writing philosophy “never use two words when one will do”. Pairing their concise yet conversational style with a “building from the bottom up” structuring of knowledge makes the book effective at getting information into the reader’s brain. 

One critique would be that, for me, some of the chapters are a tad long. For a variety of reasons sitting down for an extended period to read and focus can be difficult. However, doing just that is important, as my brain prefers consuming a rounded out and complete concept in its entirety which it can later process in the background. Fortunately, only two chapters were on the longer side. 

I like this book a lot and would definitely recommend it to someone who is looking to become familiar and effective with HTTP/2, or really anyone who works in the web space. It offers knowledge, tools, and techniques that are useful for front-end, back-end, and network engineers. 

_October 24, 2022_

<hr/>

## Getting Started with V Programming

https://www.packtpub.com/product/getting-started-with-v-programming/9781839213434

![Getting Started With V Programming Book Cover](img/getting-started-with-v-programming.png)

[V is a language](https://vlang.io/) I’ve dabbled in on and off since I bumped into it in a [LogRocket blog post](https://blog.logrocket.com/what-is-vlang-an-introduction/). It has interesting characteristics similar to [Rust](https://www.rust-lang.org/) in that it is a low-level language that by default enables you to **ignore** memory management without a garbage collector. It has high level functional features like immutability by default, sum types, option and result types, and no null (allowed in unsafe code). And lastly, it is obscenely fast at [compilation](https://fast.vlang.io/) and [execution](https://www.techempower.com/benchmarks/#section=data-r21&test=plaintext).

In this book, the author covers getting up and running with local build tools, covers the basics of the language and some of its more interesting characteristics, then dives into practical applications such as making HTTP requests, building a web service, and interacting with a database.

Though I did largely enjoy this book, I would squarely classify this as a gentle introduction. In any given chapter a concept is stated, and later restated in a different way. For topics I am new to I do find this manner of educating to be useful, but given I had already worked with the language, the book wasn’t quite dense enough for me.

As a critique, the book could use another round of proofing and technical review. There were some statements that were objectively wrong or lacked supporting evidence/references.

All in all, I did enjoy this book and was able to use a screen reader to listen to it rather quickly. It was a very easy read/listen and would be valuable for someone wanting an easy introduction to the language. If, however, you have experience with an existing language similar to [Go](https://go.dev/) or [Rust](https://www.rust-lang.org/), and/or prefer higher signal to noise ratio learning, the official [V lang docs](https://github.com/vlang/v/blob/master/doc/docs.md) are what you want.

_September 9, 2022_