
# How to fix a relational noSQL Database

**The situation**

Let's say your application uses a NoSQL Database Service. Amazon DynamoDB was the one being used, but there are many cloud based options which are pretty much interchangable. Well done.

Now let's say you're using JavaScript functions funning somewhere like AWS Lambda. Even more well done.

Now let's say you've created your API's initial CRUD endpoints and... that's where we're at when we hit this issue

**The problem**

How to iterate and improve on a noSQL DB which is a bit too.... relational without breaking it and improving it in the process?


## FHIR

[Why FHIR?](https://www.hl7.org/fhir)

FHIR offers many improvements over existing standards

- A strong focus on implementation: fast and easy to implement (multiple developers have had simple interfaces working in a single day)
- Multiple implementation libraries, many examples available to kick-start development
- Specification is free for use with no restrictions
- Strong foundation in Web standards: XML, JSON, HTTP, OAuth, etc.
- Support for RESTful architectures, seamless exchange of information using messages or documents, and service-based architectures
- Concise and easily understood specifications
- A human-readable serialization format for ease of use by developers
Ontology-based analysis with formal mapping for correctness (under development)

## AWS Lambda

> **What does [AWS Lambda](https://aws.amazon.com/lambda) do?** You can cun code without thinking about servers or clusters