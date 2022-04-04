# Communication Strategies

```mermaid
flowchart TB

every_idea(Every idea has a <br>non-zero chance of <br>being off-putting to <br>a listener)
communication(A communication is <br>made of one or <br>more statements conveying <br>one idea)
and1((and))
  every_idea---->and1
  communication---->and1
nonzero(Every statement of <br>a communication has <br>a non-zero chance of <br>putting off a listener)
  and1---->nonzero

individuals(Individuals have different <br>reactions to ideas and <br>different levels of tolerance <br>for hearing communications <br>from people expousing <br>off-putting ideas)
reaction(A reaction function, <br>in this tree, <br>is an individual's reaction <br>to any specific idea)
threshold(A threshold function, <br>T, is the number of <br>off-putting ideas an <br>individual will tolerate <br>before turning off the <br>communication. A person's <br>T can be affected by <br>internal and external factors)
and2((and))
  individuals---->and2
  reaction---->and2
  threshold---->and2
  group(A group is made <br>up of individuals <br>that have different <br>reaction and threshold <br>functions)
    and2---->group
