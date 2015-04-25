Writing Documentation
=====================

General advices
---------------

1. Compare bad/good; too less/enough/too much; before/after; good/better/best.

2. While the code says "how?", the documentation should explain "why?" (the
   reason for some decisions)

3. Assume that a reader doesn't know what he doesn't know. I.e., the reader may
   not know that the private key should be kept secret in order to cryptography
   remain secure.  It's the writer responsibility to include that information.
   You need to be mistake-proof. By the way, see
   [mistakeproofing.com](http://mistakeproofing.com) for some ideas outside our
   industry.

4. Provide good defaults.

5. On the other hand, don't skip explaining that the reader has choice. Your
   defaults should be recommendations, not true defaults. Your reader must know
   when they have choice.

6. Describe common use cases. If the use cases are long enough, you can turn
   them into [howtos](doctypes.md#how-tos).

7. If you can see some product failure, ask the developer to fix it instead of
   documenting around them.

Too long sentences
------------------

A common problem is to write too long sentences. Long sentences are bad because:

- They are hard to understand.
- Every piece of doc will be translated by google translator, which cannot
  handle complicated structures.

Solutions:

- Make cats arrive when you're writing.
- Write via dictation. We have "eye" and "ear" brains; when you listen to, you
  can't remember too much information (as opposed to when you can see the
  text). Ear brain can remember 3 out of 5 bullet points.

Use typewriter instead of computer -- you must not make mistakes.

Use Empathy
-----------

Empathy is an ability to mutually experience the thoughts, emotions and direct experience of others. It should not be confused with sympathy, which is the feeling of care or concern for the state of another.

Here are tips to write empathicaly:

- use your own API
- use other APIs and their docs so you can suffer from others lack of empathy
- sample code and writing instructions are most important for reference
  users
- tell true stories ==> give use cases
- reference completeness is not enough
- give most attention to your API's most common endpoints and methods;
  provide order for them
- document edge cases!
- provide meaningful error messages and HTTP response codes
- role example: [twillo](twilio.com)
- provide "debugging errors" section

What to do next?
----------------

The next thing to do after writing is editing your documentation. See "For Editors" section.