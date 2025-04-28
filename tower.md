# Tower
tower is a [stack based language](stacklanguage.md)

## Instruction Set

|Number|Instructons|Description|
|-|-|-|
|0|pop(address)||
|1|push(address)||
|2|jump(address)||
|3|>||
|4|<||
|5|=||
|6|=>||
|7|<=||
|8|!=||
|9|popr(address)||
|A|pushr(address)||
|B|set(constant)||
|C|add||
|D|sub)||
|E|jumpr(address)||
|F|label(LABEL)||

comment /comment\

## Examples
```
/pushr explanation\
set(5)   /stack top set to 5\
pop(0)   /stack top moved to R0 and then removed\
set(2)   /stack top set to 2\
pop(5)   /stack top moved to R5 and then removed\
/R0 = 5\
/R5 = 2\
pushr(0) /stack top set to contents of RR0\
/stack top is 2\
/hi\
```
