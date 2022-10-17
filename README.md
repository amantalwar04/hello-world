# plantuml demos

## Example 1:

![Tree view 1](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.github.com/amantalwar04/hello-world/master/images/testother.iuml)

## Example 2:

![Tree view 1](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.github.com/amantalwar04/hello-world/master/images/esp8266.iuml)

## Example 3:

![Tree view 1](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.github.com/amantalwar04/hello-world/master/images/testtree.iuml)

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
    
    
