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

    statement_to_group(Every statement of <br>a communication to a <br>group has a non-zero <br>chance of putting off <br>someone in the group)
    and3((and))
      group---->and3
      nonzero---->and3
      and3---->statement_to_group
  
  seeking(People seeking to <br>communicate want to <br>impart their ideas)
  turn_off(When a listener turns <br>off, ideas can no <br>longer be communicated)
  and4((and))
  seeking---->and4
  turn_off---->and4
    communicators(Communicators want <br>to avoid turning off <br>the listener)
    and4---->communicators
    
    effectiveness(A communicator's <br>effectiveness is measured <br>by their getting their <br>ideas across)
    and5((and))
      statement_to_group---->and5
      effectiveness---->and5
      communicators---->and5
      
        choose(Communicators choose <br>various methods of <br>minimizing putting <br>off listeners)
          and5---->choose
          probability(Probability of individual <br>acceptance of ideas can <br>often be precalculated <br>based on other factors)
          and6((and))
            choose---->and6
            probability---->and6
            predisposed(Some communicators seek <br>to communicate to <br>individuals that are <br>predisposed to not <br>being putt off by <br>the ideas presented)
              and6---->predisposed
        and7((and))
          individuals---->and7
          choose---->and7
          rapport(Some communicators <br>seek to gain rapport <br>with the individual <br>they are speaking <br>to and individualize <br>the order and content <br>of the communication <br>in order to lessen T)
            and7---->rapport
            
            ideas(Ideas that are <br>acceptable to one <br>person may be <br>off-putting <br>to another)
            and8((and))
              group---->and8
              ideas---->and8
  
