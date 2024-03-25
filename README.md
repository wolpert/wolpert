# Ned Wolpert

## How to Contact Me
- <a rel="me" href="https://hachyderm.io/@CodeHead">Mastodon</a>
- <a href="https://www.linkedin.com/in/wolpert">Linkedin</a>
- email: ned dot wolpert at gmail dot com

## Open Source Projects

The following is a list of open-source projects that are published on Github. I
have a bunch in the works but not ready to share. These are all Java projects unless
otherwise noted.

* [Svarm](https://github.com/wolpert/svarm)

Started my own dynamodb. Idea is folks could have an off-premise DDB clone to
save a buck, and be high-cardinality index friendly unlike Cassandra.
Built to be multi-tenant, secure, and (eventually) API compatible with the real thing.

Leaving Amazon, I miss DynamoDB. So I started my own. No, there is no other 
rational reason. That's it. And I'm having fun building it.

* [CodeHead Test](https://github.com/wolpert/codehead-test)

Provides test utilities I use. Generally around Jupiter, immutables and
jackson. Small, easy to consume.

* [Database Test](https://github.com/wolpert/database-test)

Test utilities I have around databases. Mostly around cassandra and unique
strings. Moved out of codehead-test because they are really specialized.

* [Metrics](https://github.com/wolpert/metrics)

Dropwizard/Micrometer integration with dagger support. Helper utilities
including help for unit tests with code that use metrics.

* [OOP Mock](https://github.com/wolpert/oop-mock)

Out of process mock facilities. Gives you the ability to mock downstream dependencies
in your functional tests. Useful if you want to separate out service level
tests from external integration frameworks. Ideal for those who have separate
tests for functional and integration. I built this because I as an ex-amazon
developer, I missed the internal project called Chameleon.

* [State Machine](https://github.com/wolpert/statemachine)

A state machine you can use internal to your java project. This was used
back when I had a consulting job, and I made an open-source version. It still
needs work, but useful to start with. If you like to help, contact me and I
can review what's missing.

* [Gamelib](https://github.com/wolpert/gamelib)

A libGDX library that I used extensively for game development. Big on dagger
for dependency injection. I also started adding in a netty client/server 
library but that has not been used in production.

* [Sample Game](https://github.com/wolpert/sample-game)

Sample code on how to get started with the gamelib stuff with various examples.

* [Terrapin](https://github.com/wolpert/terrapin)

An 'in-work' project that originally was intended to be a commercial project.
Not any where near close but work on it is open-sourced now. Provides for secure
3rd party data management where the control is in the hands of the data suppliers, 
not the 3rd party.

## Soon Projects

These are projects I'm working on but the code isn't ready for public
consumption. i.e., ideas but not enough there to share.

* [Violet Keys](https://github.com/VioletKeys/)

A rust project that securely encrypts data against a terrapin backend. Gives the
data owner control of data used by 3rd parties.

* [Star Field](https://github.com/wolpert/star_field/)

Learning the Bevy game engine which is written in rust. A minor project.
