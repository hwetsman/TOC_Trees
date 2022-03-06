```mermaid
flowchart TB

human_variability(In any given series of repeated tasks done by a human, there will be variability in the outcome or success of that task)
above_and_below(In any given series of repeated tasks done by a human there will be times when they perform better than the mean and times when they perform worse than the mean)
  human_variability--->above_and_below
human_perception(Humans perceive better variations in performance to stem from variations in effort, concentration, or some other variable managble by the person performing the act - effort)
  and1(and)
  above_and_below--->and1
  human_perception--->and1
  lesser_effort(Managers are taught that lesser effort is blame worthy and will tend to punish it)
  observer_perception(When a human completes a series of repeated tasks, observers will perceive variations in effort)
    and1--->observer_perception
  managers_belief(Managers believe greater effort is laudable and will tend to praise it)
    and2(and)
    and3(and)
    observer_perception--->and2
    observer_perception--->and3
      lesser_effort--->and2
      managers_belief--->and3
    worse_outcomes(When outcomes are worse than average managers tend to punish)
    reversion(Because of reversion to the mean, below average outcomes are likely to be followed by better outcomes and above average outcomes are likely to be followed by worse outcomes)
    better_outcomes(When outcomes are better than average managers tend to praise)
      and4(and)
      and5(and)
      managers_punish(Managers who punish worse than average outcomes will perceive reward for their behavior)
      managers_praise(Managers who praise above average outcomes will perceive punishment for their behavior)
        and6(and)
        managers_over_time(Managers, over time, will learn to manage by punishing bad behavior rather than by rewarding good behavior)

````
