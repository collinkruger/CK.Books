# CK.Books

Software engineering stuff I've read that you might be interested in.

**Note:** I’m not affiliated with any of the authors/publishers/etc. in anyway, and the perspective I shared is my own, not necessarily my [employer's](https://www.linkedin.com/in/collinkruger/).

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