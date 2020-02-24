# Principles: 

## API-First

 * Indentify what the actors expect frm apis
 * Kin Lane "Before you build your website (...) you need to develop an API First"
 
### Benefits for the Business

 * Reduce de time/cost of getting something done
 * Increase the ease

What's the purpose? What's yours?

INPORTANT: Why you do this? API First? Microservice-model, etc

### People-Centric 

 * Know your customer
 * Regards
  - Deadlines 
  - SLA
  - TParty
 
You need to sove the customer problem, don't make him your own laboratory.

The API need to talk the business language.

### Why to use HTTP?

 * Message
 * Methodos
   * Express communication intent
   * IT DOES NOT FUNCTION
 * Safety & Indempotence
 * Message carry state (through the headers)
   * No state about the representation

#### Safety and Indepotence

 * GET vs DELETE
 * Idempotence: PUT doesn't change the state of representational protocol. It's like I've the object T and if I udpate the T to T_1 and I received T_1_R response, then my result needs to be T_1_R for any request T_1.

## The WEB

 * Isn't a standard specification: it's a set of common practices
 * "Linked information system
 * REST is a STYLE! DON'T FORGET IT.

### REST 
 
 * See [RFC 2616](https://tools.ietf.org/html/rfc2616) and the R> Fielding [dissertation](https://www.ics.uci.edu/~fielding/pubs/dissertation/top.htm)

### Interaction 
 
 * Donald Norman
 * "Norman Doors", father of HCI (Human Computer Interaction)
 * Push/pull pattern
 * Action Lifecycle
 * RPW Loop - Request/Response
 * Modeling with sequence diagrams

# The Tutorial 

## Document the Story

 * Remember: the Api become from a customer purpose and needs, then we always need the story to describe them.

### Steps

 * Purpose: What's the purpose of this API?
 * Data: What's the data that needs to be modeled?
 * Actions: Describe the processes

### Documenting
 
 * Interview the stakeholders 
 * Check it into the project repo
 * Use a plain language 
 * PURPOSE: Put the responsability on a shared area
  
#### Diagraming

#### Describe the API 

 * Definition
   * WSDL
   * WADL
   * OpenAPI
   * AsyncAPI
   * protobuf
 * The api must be agnostic form the definition

#### ALPS
```yml
alps: 
  version: '1.8'
  description: 'A simple test'

descriptors:
  . . .
```

#### Sketching

 - Ideas for buildings (Frank Gehry)
 - Prottotypes and models
 - Rough drawings 
 - this is only a general idea of something
 - BLUEPRINT