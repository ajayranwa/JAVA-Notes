## Array implementation in Java

### Declaration

```java
boolean[] visited = new boolean[length];
```

### Array sort
```java
java.util.Arrays.sort(A);
```

### Array sort (2d array, sorting by 1st element)
```java
java.util.Arrays.sort(A, Comparator.comparingInt(a -> a[0]));
```