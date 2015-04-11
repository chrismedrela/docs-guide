Documentation Structure
=======================

This page is about how to split huge documentation base into pages and how to
structure pages.

General observations
--------------------

1. Most documentation grow organically, that is there is no structure. Somebody
   must enforce a structure at the beginning.

2. If writers do not know where to put their work, the structure is bad.

3. People won't read entire documentation from cover to cover. Therefore, there
   is no sense in structuring documentation to minimize duplication between
   pages.

4. People don't like *click insanity*. This should be the objective even if
   that results in duplicated information in a lot of pages.

How to find good structure?
---------------------------

All documentation can be split by the target audience. People know what role
they are, that is if they are Designers, Organizers or Editors. That way, they
can easily narrow the scope of pages they are interested in. Look at this
Guide. If we just put all the pages on one list, you would have to check 15
pages. But we decided to split it by audience. Since you are documentation
Organizer, you have to check only six pages (and that is the worst case!).

If there is too much material for one audience for one page, you should split it, possibly via topic, as in this Guide.

**Practical advice**: put all topics on post-it stickers and then try to
organize them.

Single page documentation
-------------------------

We recommend single page documentation for non-introductonary documentation. A
role model is [CoffeeScript main page](http://coffeescript.org/).

Don't misunderstand it. It's not about mixing tutorials, guides and API
references on one page. It's about i.e. putting entire reference on one page.

There are a few arguments behind single page documentation:

<font color="green">

1. *Click insanity* -- people don't like lot's of clicking to find out
   interesting piece of information.

2. Searching single-page documentation is easier and faster than googling. Yes,
   browsers have search tool and it's free.

3. Scrolling is natural (really).

</font>

There are some downsides:

<font color="red">

1. Google will probably land you in wrong section. 

2. It's bad from marketing point. People will find your single page tutorial
   and say "shit, it's too long". Therefore, don't use it for introductory
   materials like tutorials.

3. It's hard to link to sections of such documentation. Although good anchors
   solve the problem.

</font>

When using single-page, you should provide **persistent navigation**, otherwise
you risk *scroll insanity*. You can also provide *dynamic orientation*, so
navigation shows where on the page you are.

Page structure
--------------

Inside one page, you also need some structure. Below, we listed the most common structures:

- **tell a story** -- follow a linear timeline. Walkthrough.

- **paint a picture** -- describe everything on the screen. Use when
  introducing a feature or tool

- **reference** -- introduce one at a time and describe.

- **theme + situations** -- idea and use cases. Use in introduction to a
  concept.

- **drill down** -- general to specific.

- **level up** -- start simple (information hiding) and reveal it as you go
  along. Use in Getting Started.
