# archive / documentation
Project documentation should 

* State the roles, responsibilities. 
* Give some information about participants. 
* Show point of contact.

Here is an example content:

| Project Name  | Lorem Ipsum |
|---------------|-------------|
| Project Owner | Team or PO  |
| Analyst       | @yyy @ttt   |
| Developers    | @zzz @aaa   |
| QA            | @bbb @ccc   |


![Project Documentation Structure](https://github.com/Poseid10ur/archive/blob/main/resources/images/documentation-structure-20220319.png?raw=true)


Project documentation can be mainly categorized as 
* Service Documentation
* Process Documentation

## Service Documentation
Service documentation clearly describes the service that is being developed. It should state some information related to the underlying technology and give brief instructions to client.

### Underlying Technology
* Service Requirement: This is where we state the business rules, the purpose of its functionalities, and behaviors.
* Environment Information: This is where we give brief information related to environments. (i.e resources)
* Design & Architecture: This is where we should state the underlying domain model, user interaction diagrams, tech stack.  
* Testing Documents: This is where we give brief information about ci pipelines, automation tests, components, how-tos.
* Manuals & FAQs: This is where we state service dependencies (external services, resources with versions). This section should state the steps to run the service locally as well.

### Client Documentation
* Consumer documentation: This is where we state the service endpoints and behaviors. It should be as simple as the client can understand.
* System admin documentation: This is where we state our environment-specific resources (i.e staging and production works on live DB). Besides, scheduled tasks should be stated at this section.

## Process Documentation
Process documentation should contain information about the evolution of the service. For instance, the new feature user stories should be under this section.

* Functional Analysis: This is where we state the use cases.
* Scheduled Test Reports: This is where we state the important metrics of the scheduled tests. (Like load-tests)
