# Document 1

## this document is an example.

here is some inline images
{{< figure src="test.png" caption="My Test Image" >}}

here is another image
![alt text](test.png)

## try some math

here is some math
{{< katex display=true >}}
f(x) = \int_{-\infty}^\infty\hat f(\xi)\,e^{2 \pi i \xi x}\,d\xi
{{< /katex >}}

## My Math Post

Euler's identity is famous: $e^{i\pi} + 1 = 0$.

And Einstein's formula:

$$
E = mc^2
$$

This is another example
$$
f(x) = \int_{-\infty}^\infty\hat f(\xi)\,e^{2 \pi i \xi x}\,d\xi
$$


## test in UML
here is some UML

```plantuml
@startuml
Alice -> Bob: Hello
Bob --> Alice: Hi!
@enduml
```

```plantuml
@startuml
actor User
User -> System : Login
System -> Database : Check credentials
Database --> System : Return result
System --> User : Success or failure
@enduml
```