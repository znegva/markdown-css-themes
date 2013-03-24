
* * *
# A First Level Header

## A Second Level Header

### A Third Level Header

#### A Fourth Level Header

##### A Fifth Level Header

###### A Sixed Level Header

Now is the time for all good men to come to
the aid of their country. This is just a
regular paragraph.

The quick brown fox jumped over the lazy
dog's back.

* * *

### Header 3

> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
> consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
> Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.
> 
> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
> id sem consectetuer libero luctus adipiscing.
> 
> ## This is an H2 in a blockquote
> 
> This is the first level of quoting.
> 
> > This is nested blockquote.
> 
> Back to the first level.

Some of these words _are emphasized_.
Some of these words _are emphasized also_.

Use two asterisks for **strong emphasis**.
Or, if you prefer, **use two underscores instead**.

*   Candy.
*   Gum.
*   Booze.
*   Red
*   Green
*   Blue

*   A list item.

With multiple paragraphs.

*   Another item in the list.

*   This is a list item with two paragraphs. Lorem ipsum dolor
sit amet, consectetuer adipiscing elit. Aliquam hendrerit
mi posuere lectus.

Vestibulum enim wisi, viverra nec, fringilla in, laoreet
vitae, risus. Donec sit amet nisl. Aliquam semper ipsum
sit amet velit.*   Suspendisse id sem consectetuer libero luctus adipiscing.

*   This is a list item with two paragraphs.

This is the second paragraph in the list item. You're
only required to indent the first line. Lorem ipsum dolor
sit amet, consectetuer adipiscing elit.

*   Another item in the same list.

*   A list item with a blockquote:

> This is a blockquote
> inside a list item.
*   A list item with a code block:

    code goes here

Here is an example of 

    tell application "Foo"
        beep
    end tell

This is an [example link](http://example.com/).

I get 10 times more traffic from [Google](http://google.com/ "Google") than from
[Yahoo](http://search.yahoo.com/ "Yahoo Search") or [MSN](http://search.msn.com/ "MSN Search").

I start my morning with a cup of coffee and
[The New York Times](http://www.nytimes.com/).

![alt text](image.jpg "Title")

![alt text](image2.jpg "Title")

I wish SmartyPants used named entities like `&mdash;`
instead of decimal-encoded entites like `&#8212;`.

If you want your page to validate under XHTML 1.0 Strict,
you've got to put paragraph tags in your blockquotes:

```
<blockquote>
  <p>For example.</p>
</blockquote>
```
# August 31, 2011

Homework: Problems 2.10-2.19; complete registration system

* * *

## Chapter 2

### Phases of Software Development

1.  Analysis
2.  Design
3.  Implementation

#### Analysis phase

_Requirements_ -- what the customer wants or needs.  Understanding on needs expressed by:

*   Use cases can (can use UML)
*   User manual style of analysis document

#### Design phase

Goals of OO design:

1.  Identify classes -- things in the system
2.  Identify responsibilities of the classes
3.  Identify relationships between classes

Classes consist of:

1.  Behavior: Methods represent the class behavior
2.  State: Fields represent the state of the class instance (object)
3.  Identity:  each unique object should have its own address in memory
which contains its state

Types of classes that are common:

1.  Tangible things
2.  Agents
3.  Events and transactions
4.  Users and roles
5.  Systems
6.  System interfaces and devices
7.  Foundational classes

Types of class relationships:

1.  Dependency (_uses a_)
2.  Aggregation (_has a_)

    *   Aggregation -- 1:many
    *   Association -- 1:1
    *   Composition -- "_if I'm composed of other things, then I am considered
responsible for the lifetime for those things_"
3.  Inheritance (_is a_)

Classes and relationships are the basis for a UML class diagram.
