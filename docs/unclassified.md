Everything That Does Not Fit Anything
=====================================

TODO: Classify it!

Observations
------------

- lack of documentation is social problem, not technical 
- introducing code base to a new employee takes time and costs
- [dist] code says what and how, docs tells why
- information is no longer a value; filtering information and giving us
  the right information and teaching us is now a value
- internet is many-to-many communication 
- lack of documentation is marketing problem
- people care more about documentation if they are accountable for it
  personally (bugs in documentation)
- documentation is not the same as communication
- documentation -- tactical thinking
- it's important to have right links in search engines
- docs were written for users who already signed up, now it needs to be
  marketed to potential users too; docs is marketing; it's like shop window
- people can get to your docs through different paths because web is
  just pages with hyperlinks
- documentation must be easily searchable (cannot lack an index)

what docs should be about?
--------------------------

- the docs should say what is the good default (i.e. what encryption
  should I use?)
- describe common use cases
- assume that user doesn't know what he doesn't know; don't provide
  defaults, provide recommendations;
- compare bad/good; too less/enough/too much; before/after;
  good/better/best;

other practical advices
-----------------------

- make spec
- if you do not have any editors, ask OReilly for help and releasing
  your documentation as a book
- show, don't tell
- think holistically about documentation
- "readme driven development" -- write readme before everything else

- use Empathy when writing API reference

    * Emphaty - ability to mutually experience the thoughts, emotions, and
      direct experience of others
    * Sympathy - feeling of care or concern for the state of another
    * use your own API
    * use other APIs and their docs
    * know your readers -- survey them
    * sample code and writing instructions are most important for reference
      users
    * tell true stories ==> give use cases
    * provide friendly UI
        + single page docs & click insanity
        + better typography
    * reference completeness is not enough
    * give most attention to your API's most common endpoints and methods;
      provide order for them
    * document edge cases!
    * provide meaningful error messages and HTTP response codes
    * role examples: [twillo](twilio.com)
    * provide "debugging errors" section

- how-tos
- underline all nontrivial words which has no definition

- don't follow big companies, follow the small ones
- small companies make better documentation

- every doc easily accessible -- there must be one page with links to
  all existing docs ==> structure?
- link to howtos from your marketing site and new user experience

- process
    * write bad first drafts as motivation to expert writers
    * draw documentation fast and deliver early 
    * get someone to test your documentation; don't allow them to use any other
      resource; if they have to use Google, it's a bug in documentation
    * give documention first (no implementation nor tests) and ask users what
      they would do next?

other (unclassified unclassified)
---------------------------------

- Minimum Viable Documentation ASAP; use template
- different types of documentation: tutorial vs guide vs reference
  http://jacobian.org/writing/what-to-write/