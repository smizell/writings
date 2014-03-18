# Thoughts on Hyperdescribe, Hypermedia Components, and More

First, I want to ask this question, what is the ultimate goal here? What are we trying to accomplish? Below are just some questions to think through.

* Are we trying to make hypermedia easier to design?
* Are we trying to make hypermedia easier to implement?
* Are we trying to teach clients and servers about more hypermedia types?
* Are we trying to make make server code and client code hypermedia agnostic?
* Are we trying to promote a new way of thinking about client design? "Don't code the message, code the hypermedia components."
* Are we trying to help hypermedia adoption?

It could be none or all of these, or somewhere in the middle.

Second, how should we refer to this initiative? What's a simple name and concept that encapsilates this entire idea.

## Aspects of this endeavor

* Describing hypermedia messages (e.g. Hyperdescribe)
  - What hypermedia components does the message use?
  - How would you map to these components?
  - Starting with these components, how would you map to this media type?
* Generalized Client (e.g. Backrest)
  - Working toward a client that can work with any supported media type
* Media type implemenation guide (e.g. Hyperdescribe)
  - For helping in the design of media types (forces you to describe media type)
  - Provides a way for creating hypermedia describers and builders (for use with Halpert or other library)

## Projects

* Server-side library to convert from one type to another. 
  - Javascript - Halpert
* Client-side library for generically dealing with components of hypermedia types
  - Javascript - Backrest (only started to work out concepts)