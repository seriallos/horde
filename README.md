horde
=====

NodeJS HTTP Stress Testing Tool

Goals
=====

* Open source
* Self-hosted / run internally against private servers
* Simulate complex user behavior using code
* Horizontally scalable
* Easy to integrate with CI
* Easy to collaborate with a team
* Decently high throughput without sacrificing ease of scripting
* Reporting via live charts and machine readable output
* First class *NIX citizen (CLI support, pipeable, modular, etc)
* HTTPS support

Implemented
===========

Nothing yet!

Install
=======

TODO

Use
===

TODO

Reasoning
=========

There are a lot of website load testing tools out there, from the venerable, if
creaky, JMeter to insanely expensive Enterprise Buzzword Compliant hosted solutions.
The options that are out there rarely solve all of the goals listed at the top
of this document.

Here are some of the other projects I've run across and why they don't quite for
me:

**nodeload**

* No longer maintained
* Difficult to perform complex sequences
* Patchy HTTPS support

**JMeter**

* Want to write code, not XML
* Not very *NIX-y

**LoadUI/SoapUI**

* Expensive
* Concurrency problems with complex scenarios
* Hard to collaborate with a team

**Gomez**

* Expensive
* "Enterprise"

**blitz**

* Hosted

**ab/siege/httperf**

* Too simplistic
