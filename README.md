# Ruby Programming Idioms and Patterns

This is a (potential) book about idioms and patterns in Ruby.


## Inspirations

I've given several talks about patterns and idioms, especially in Ruby.
That has inspired me to collect more of them in a book form.

In a way, this is a clean-room reimplementation of Kent Beck's _Smalltalk Best Practice Patterns_.
That's definitely the biggest inspiration.
But I'd also like to incorporate patterns introduced several other books:

* _Practical Object-Oriented Design in Ruby_ by Sandi Metz
* _99 Bottles of OOP_ by Sandi Metz and Katrina Owen
* _Confident Ruby_ by Avdi Grimm
* _Exceptional Ruby_ by Avdi Grimm


## Patterns versus Idioms

Unfortunately, there's no clear distinction between an idiom and a pattern.
While we tend to think of patterns as larger architectural features,
there are also "patterns in the small";
Smalltalk Best Practice Patterns contains many examples.

An idiom is defined as a "recurring construct" or a "characteristic mode of expression".
A pattern is defined as a "general, reusable solution".
Given those definitions, it seems like an idiom is more of an expressive choice,
and you might have particular idioms that you prefer to use over others.
A pattern is something that is less of a stylistic choice;
anyone would likely always choose the same one in a given situation.

Perhaps we can make a distinction between patterns that we have to think about,
and idioms that have just become second nature.
One canonical example of this is that in assembly langauge, a subrouting call is a pattern.
But in higher-level languages, we no longer thing of that as a pattern; it's just a part of the language.


## Format

For each pattern and idiom:

* Name
* When to use (contexts)
* How to use
* Examples
* Contra-indications
* Caveats
