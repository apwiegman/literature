# literature


## Kubernetes
- https://www.confluent.io/en-gb/blog/microservices-apache-kafka-domain-driven-design/
- https://www.youtube.com/watch?v=X48VuDVv0do
- https://kubernetes.io/docs/reference/kubectl/cheatsheet/
- https://www.eksworkshop.com/
- https://helm.sh/docs/
- https://kubernetes.io/docs/reference/using-api/
- https://www.youtube.com/watch?v=5_J7RWLLVeQ

## Authentication
- https://oauth.net/2/
- https://developers.google.com/identity/protocols/oauth2
- https://medium.com/google-cloud/understanding-oauth2-and-building-a-basic-authorization-server-of-your-own-a-beginners-guide-cf7451a16f66
- https://protect-za.mimecast.com/s/fAfwC66yDnSrw6EtptN2Z?domain=toptal.com
- https://support.kraken.com/hc/en-us/articles/360000906023-What-is-a-nonce-
- https://medium.com/@skshukla.0336/mtls-everything-you-need-to-know-e03804b30804

## Rest API
- Restful API design https://www.youtube.com/watch?v=QpAhXa12xvU

## Code Structure:
- https://www.baeldung.com/cs/layered-architecture#:~:text=6.,apply%20them%20to%20larger%20projects.
- https://gitlab.com/james.smith4/hexagonal-poc
- https://vaadin.com/blog/ddd-part-3-domain-driven-design-and-the-hexagonal-architecture

## Database
- https://www.byteslounge.com/tutorials/spring-transaction-isolation-tutorial
- https://www.byteslounge.com/tutorials/spring-transaction-propagation-tutorial
- https://www.cloudways.com/blog/mysql-performance-tuning/
- (Streaming Database Changes) https://github.com/davidarchanjo/spring-boot-debezium-mysql
- https://dev.mysql.com/doc/refman/8.0/en/partitioning-types.html
- https://www.baeldung.com/jpa-composite-primary-keys
- when to use persistable
```
In JPA, the Persistable interface is not a standard JPA interface, but rather a Spring Data interface. It is used to indicate that an entity class is new and should be persisted.

If you are using Spring Data JPA, you can implement the Persistable interface in your entity classes to let Spring Data handle the logic of determining whether an entity should be persisted or merged. This is useful when you have an entity class with a composite primary key or a primary key that is generated by the database, as Spring Data can use the isNew() method of the Persistable interface to determine whether the entity should be persisted or merged.

You should implement Persistable in JPA when you have an entity with a composite primary key or a primary key that is generated by the database and you want to let Spring Data handle the logic of determining whether the entity should be persisted or merged. If you do not have such requirements, then there is no need to implement Persistable.
```

## Microservices
- https://microservices.io/
- https://12factor.net/

## Kafka
- https://www.kai-waehner.de/blog/2022/06/03/apache-kafka-request-response-vs-cqrs-event-sourcing/
- https://www.kai-waehner.de/blog/2022/05/30/error-handling-via-dead-letter-queue-in-apache-kafka/
- https://github.com/bstashchuk/apache-kafka-course/blob/master/basic-kafka-commands.txt

## Logging
- https://logback.qos.ch/manual/layouts.html
- https://clurgo.com/en/how-to-develop-software-more-flexibly-with-hexagonal-architecture/

## Books to Read
- Designing Data-Intensive Applications [Book] - O'Reilly Media
- https://www.zero2prod.com/index.html?country=the%20UK&discount_code=VAT20 

## CQRS
- https://medium.com/design-microservices-architecture-with-patterns/cqrs-design-pattern-in-microservices-architectures-5d41e359768c
- https://martinfowler.com/bliki/CQRS.html

## Load Testing
- https://github.com/gatling/gatling

## Testing
- https://www.vincenzoracca.com/en/blog/framework/spring/testcontainers-localstack/
- https://gist.github.com/rponte/8a46133aeca05f07ae49035879a18143

## Springcloud Streams
- https://docs.awspring.io/spring-cloud-aws/docs/3.0.0-SNAPSHOT/reference/html/index.html#sqs-integration
- https://refactorfirst.com/spring-cloud-stream-with-kafka-communication.html
- https://cloud.spring.io/spring-cloud-stream-binder-kafka/spring-cloud-stream-binder-kafka.html
- https://tanzu.vmware.com/developer/guides/spring-cloud-stream-kafka-p1/
- https://medium.com/@anupriyakumawat95/consume-messages-in-batch-using-spring-cloud-stream-kafka-binder-d82b0f4a9935

## Reactive/ Asynchronous/ Webflux
- https://reflectoring.io/getting-started-with-spring-webflux/
- https://www.baeldung.com/spring-mvc-async-vs-webflux
- https://www.baeldung.com/cs/async-vs-multi-threading

## Cache
- https://docs.spring.io/spring-boot/docs/current/actuator-api/htmlsingle/#caches.evict-all

## Distributed locks
- https://tanzu.vmware.com/developer/guides/spring-integration-lock/
- https://medium.com/@bb8s/design-distributed-lock-with-mysql-9bc28ac59629
- https://medium.com/@bb8s/design-distributed-lock-with-redis-e42f452cb60f

## AWS
- https://www.bluematador.com/learn/aws-cli-cheatsheet

## Teraform
- https://blog.gruntwork.io/an-introduction-to-terraform-f17df9c6d180

## Leadership
- https://www.youtube.com/watch?v=uU9Pz0w6fe4
  

  

