### akka
---
https://github.com/akka/akka

https://akka.io/

```java
// akka-cluster/src/test/java/cluster/ClusterJavaCompileTest.java

@SupressWarnings("ConstantConditions")
public class ClusterJavaCompileTest {
  
  final ActorSystem system = null;
  final Cluster cluster = null;
  
  public void compileJoinSeedNodesInJava() {
    final List<Address> addresses = Collections.singletonList(new Address("akka", "MySystem"));
    cluster.joinSeedNodes(addresses);
  }
}

```

```
```

