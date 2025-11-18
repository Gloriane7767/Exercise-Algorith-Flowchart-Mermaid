# Exercise: Algorithm and flowchart

## Exercise 1

===

Find the Largest of Two Numbers

**Problem**
Write a program that:

- Takes two numbers **A** and **B** as input
- Compare the two numbers
- Display which number is larger
- if they are equal, display: **Both numbers are equal**

## Pseudocode

 
BEGIN
    INPUT A
    INPUT B

    IF A > B THEN
        DISPLAY "B is larger"
    ELSE IF A == B
        DISPLAY "Both numbers are equal"
    ELSE
        DISPLAY "B is larger"
END

## Flowchart

```mermaid
flowchart TD
    A([Start]) --> B[/Input A/]
    B --> C[/Input B/]
    C --> D{A > B?}
    
    D -->|Yes| E[Display "A is larger"]
    D -->|No| F{B > A?}
    
    F -->|Yes| G[Display "B is larger"]
    F -->|No| H[Display "Both numbers are equal"]
    
    E --> I([End])
    G --> I([End])
    H --> I([End])
```