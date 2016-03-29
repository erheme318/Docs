* Improve your operation with machine data
  by Logmatic.io

  Intelligent log management

* Spring meetup introduction

  - autour de sprig framework, technology
  - Rabbit MQ,
  - Reddis
  - Dagger
  - Functional programming



* Spring HATEOAS
  by Yoann Buch & Yiquan Zhou

  findtheflow.io

  REST HATEOAS -> web hypermedia

  * Maturity level
   source: martinfowler: richardson maturity model

        - Level 0: HTML only

  - Level 1: Resources
    ex: `POST /orders`

  - Level 2: HTTP verbs
    ex: `POST|POST|GET|DELETE /ordes`, 201 CREATED (status code)

  - Levele 3: Hypermedia As The Engine Of Application State (HATEOAS)
        - Define transtion state in the resource representations (in the response of
          the request)
        - Content-Type:

        - Hypermedia formats:
          'application/atom+xml', 'application/hal+json'

          Introduce resource concept and resource link


  * Demo:
        - use verbs in controller actions
        - chrome extension view source

  * Concept
   Resource, Link
   Links of resource indicate possible operations of the resource

   Server guides the client what operations can be possible after the
   operation that client just made depending on the state of the system.

   Easy to explore the resources

        * Client

    Enough to know the entry point (root resource) only

  - Root controller - Starting point
    Resource support - linkTo(Controller)
    resource.add(link1, link2,..., linkN);

  - Traverson, traverson-hal, 

  * Summary

   With HATEOAS, API explorable and auto-descriptive
   Client side simplification: 
        - No hard-coded URI
        - Client follows the protocol

      Book: REST in Practice: Hypermedia and Systems Architecture
      Spring Restbucks project
      Good examples: FoxyCart, Paypal
      Spring Data REST


* Spring REST Docs: Living API documentation made easy
  by fbiville (Criteo)

  Documentation is hard to maintain
  Documentation is out of sync
  code = the source of truth

  doc is automatically derived from the code (better)
  doc is automatically derived from the tests (still better)
  
  Swagger
   - Specification


  *.adoc, ascii doctor - format
  Book: Living documentation - Cyrille Martraire

