_Fill in each this file with your responses, placing each response after its
corresponding question._

---

**Question**

Pick three quotes from the readings about language design. Good candidates
are:

- Something you agreed with / resonates with your own experience
- Something you disagree with
- Something that is interesting, a new idea or perspective you'd like to remember
- Something you didn't understand

For each quote, describe what it was about the quote that led you pick it.

**Response**

In the Pavlus article, they include a quote from Andreas Stefik: "I think that whenever you make a product design simpler there’s a potential danger of removing features that experts need" [Pavlus, 2012]. This quote stood out to me because while I do beleive that it is a valid design concern, it could be read as in conversation with broader discussions about computing access and how knowing, or not knowing, specific languages are used as ways to gatekeep technical fields and communities. This is discussed a lot more in the Yang and Rabkin article about language stereotypes [Yang and Rabkin, 2015]. I wonder if when Stefik says a danger of "removing features that experts need" that it is also a future way for people to judge those who know Quorum as an "inferior" language as a veiled way to judge the programers themselves.

"In stead of designing a thing, you need to design a way of doing. And this way of doing must make some choices now but leave other choices to a later time." [Steele, 1998] This is definitely a perspective I want to remember. In theory, I agree that users should have control and voice during the design process - they are after all, the ones who are going to use it at the end. In practice, that feels really hard to do, but remembering this idea might help. It doesn't sound easier, but perhaps will ultimately be more useful and live longer than I do.

"Obey the principle of least astonishment." [Bloch, 2006] I picked this quote because it's so simple. Name, define, and design things so that users aren't surprised. Make it predictable, or at least as predicable as possible so that there are less bugs, users are less confused, and so that users are less frustrated.

**Question**

How would you know a well-designed language? What are the symptoms? How would
you know a poorly designed language? What are the symptoms?

**Response**

This is a bit of a tough question because what makes a language well or poorly designed sometimes depends on the metrics that we use. One can argue R is a well-designed language, but Tim Smith found it difficult to learn, and so disliked it even though he now regrets the tone he took in intitial criticisms. [Smith, 2016] Perl is very difficult to learn as well, and yet is still relevant today as a programming language. [Stefik _et al._, 2011] Therefore, metrics like ease-of-use for a novice programmer can be subjective and are one symptom of a language. That being said, I think there are some things I use when I try to figure out whether a language is well-designed or not. I definitely will judge it based on whether the rules feel consistent. Python, C++, and R all have different means and rules for assignments, but once you know the rules you can always assign something. Similarly, if it's consistent than I also feel like it's a little predictable - little syntax things I might have to look up, but I can follow what's happening in a program. A poorly designed language, I cannot.


**Question**

How might the themes of _Growing a Language_ relate to ideas from the Fowler reading?

**Response**

More obviously, the idea of limited expressiveness that Fowler discusses is very related to _Growing a Language_ and the ways that Steele uses limited expressiveness to make his points. Of using only one syllable words, unless defined first, he says "in truth, the words of one syllable form quite a rich vocabulary, with which you can say many things." [Steele, 1995] He is able to use a small language and express many things quite fluently, or at least the bare minimum things that he needs - note that Steele doesn't define anything he doesn't use. Similarly, Fowler characterizes DSls with limited expressiveness, and that it doesn't have extraneous features, just what it needs to support its domain. [Fowler, 2010] 
 
 NOT DONE

**Question**

In what way is an API a language?

**Response**

An API a language because it is a set of rules for how programs can talk to each other. If a programming language is a set of rules for communicating with a computer to solve a problem, then using an API is the same, it's just a subset of rules presented in a different way. This is why the article on designing a good API is important, because it needs to be fluent and have overlapping principles with designing a general purpose language, like good names and documentation. [Bloch, 2006]

**Question**

What does the post on grayscale tell us about the process of API design?

**Response**

It tells us that there are lots of ways to to name functions that do the same thing with the same result, and so user input is important in that process to make sure that most people find it intuitive. That being said, because there are so many "correct" ways to do things, and everyone has different ways of thinking about problems and different ideas (like how to quantify the color gray) that not everyone is going to be happy. I feel like it is following Bloch's ideas for good API design, because it's giving attention to the importance of names, getting input, and trying to be as least surprising as possible. [Bloch, 2006] Essentially, the API design process as modelled here is purposeful and public so that it is as intuitive and effectively designed as possible.

**Question**

The Pavlus article mentions the researchers' comments that people preferred
"natural-language replacements for some of the more abstruse syntax". In other
words, people found it easier to work with code that looks more like a human language (e.g.,
English). Consider the following quote by William R. Cook, one of the creators
of AppleScript:

> The experiment in designing a language that resembled natural languages (English
> and Japanese) was not successful. It was assumed that scripts should be
> presented in “natural language” so that average people could read and write
> them. … In the end the syntactic variations and flexibility did more to confuse
> programmers than to help them out. It is not clear whether it is easier for
> novice users to work with a scripting language that resembles natural language,
> with all its special cases and idiosyncrasies. The main problem is that
> AppleScript only appears to be a natural language: in fact, it is an artificial
> language, like any other programming language. … even small changes to the
> script may introduce subtle syntactic errors that baffle users. It is easy to
> read AppleScript, but quite hard to write it.
> [[Cook 2007, page 1-20]](https://dl.acm.org/citation.cfm?doid=1238844.1238845)

Are these two experiences of natural languages at odds with one another? Would
you choose to include natural language in the design of a DSL? If so, how might
you do so? If not, why not?

**Response**

I think these two experiences are a bit at odds, but that doesn't erase the validity of either one. It is true that a more natural looking language is easier to read and initially parse, but as Cook says, it is still an artificial language. Part of my follow-up questions might be more related to what part of the process do we wish to streamline more - is the initial understanding like in the Pavlus article, or is it in the debugging stage later like what Cook found. 

NOT DONE
