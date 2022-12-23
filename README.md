##Flowchart for fibonacci numbers

This is my design of flowchart for solving problem of finding specific fibonacci number 

```mermaid
flowchart TD;
    A([Start]) --> Ini[r0=0, r1=1, i=0] --> I[/Read n/] --> W{i < n}
    W -- true --> P[r2=r0+r1 <br> r0=r1 <br> r1=r2] --> W{i < n}
    W -- false --> O[Display r2] --> Z([Stop])
    
    
    
```
