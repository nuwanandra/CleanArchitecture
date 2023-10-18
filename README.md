# CleanArchitecture-
Clean Architecture With .NET 6 And CQRS - Project Setup


Domain: entities, Business Logics,  If you Use DDD( Aggrgates, Value Objects, Domain Events ), Repository interfacess, factory interfacess, domain servicess, custome exceptions <br>
Application: Use Cases, CQRS, <br>
Precentation: Entry Points for Outer Users. (REST API, GRPC) <br>
Infrastructure:  external Systems/Services ( DB access, Message Queues[Rabit MQ,Kafka],  Email,nortification, storage servicess  ) <br>
Core Folder (Domain, Application) <br>
External Folder (Infrastructure, Presentation) <br>
