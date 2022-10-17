# plantuml demos
For more information, see the [PlantUML documentation](https://crashedmind.github.io/PlantUMLHitchhikersGuide).
## Example 1:

![Tree view 1](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.github.com/amantalwar04/hello-world/master/images/testother.iuml)


## Example 2:

```plantuml
@startsalt

{
    {T
* ws_of
** aman
*** allocators
**** gstsdxallocator.c
**** gstsdxallocator.h
*** apps
**** optical_flow
***** main.c
*** base
**** gstsdxbase.c
**** gstsdxbase.h
*** plugins
**** optical_flow
***** gstsdxopticalflow.cpp
***** gstsdxopticalflow.h
** opticalflow
*** src
**** optical_flow_sds.cpp
**** optical_flow_sds.h    
     }
}

@endsalt

```
## Example 3

```plantuml
@startuml
actor Bob [[http://plantuml.com/sequence]]
actor "This is [[http://plantuml.com/sequence Alice]] actor" as Alice
Bob -> Alice [[http://plantuml.com/start]] : hello
note left [[http://plantuml.com/start]]
  a note with a link
end note
Alice -> Bob : hello with [[http://plantuml.com/start{Tooltip for message} some link]]
note right [[http://plantuml.com/start]] : another note
note left of Bob
You can use [[http://plantuml.com/start links in notes]] also.
end note
@enduml
```

# Mermaid
For more information, see the [Mermaid documentation](https://mermaid-js.github.io/mermaid/#/).

To create a Mermaid diagram, add Mermaid syntax inside a fenced code block with the `mermaid` language identifier.

## Example 1:

Here is a simple flow chart:

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

## Example 2


```mermaid
sequenceDiagram
    Alice ->> Bob: Hello Bob, how are you?
    Bob-->>John: How about you John?
    Bob--x Alice: I am good thanks!
    Bob-x John: I am good thanks!
    Note right of John: Bob thinks a long<br/>long time, so long<br/>that the text does<br/>not fit on a row.

    Bob-->Alice: Checking with John...
    Alice->John: Yes... John, how are you?
```    
    
    
