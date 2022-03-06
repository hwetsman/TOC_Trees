```mermaid
flowchart LR

human_variability(In any given series of repeated <br>tasks done by a human, there <br>will be variability in the outcome <br>or success of that task)
above_and_below(In any given series of <br>repeated tasks done by a <br>human there will be times <br>when they perform better <br>than the mean and times when <br>they perform worse <br>than the mean)
  human_variability--->above_and_below
human_perception(Humans perceive better variations <br>in performance to stem from <br>variations in effort, <br>concentration, or some <br>other variable managble by <br>the person performing the <br>act - effort)
  and1(and)
  above_and_below--->and1
  human_perception--->and1
  lesser_effort(Managers are taught <br>that lesser effort is <br>blame worthy and will <br>tend to punish it)
  observer_perception(When a human completes <br>a series of repeated <br>tasks, observers will <br>perceive variations in <br>effort)
    and1--->observer_perception
  managers_belief(Managers believe greater <br>effort is laudable <br>and will tend to <br>praise it)
    and2(and)
    and3(and)
    observer_perception--->and2
    observer_perception--->and3
      lesser_effort--->and2
      managers_belief--->and3
    worse_outcomes(When outcomes are <br>worse than average managers <br>tend to punish)
      and2--->worse_outcomes
    reversion(Because of reversion <br>to the mean, below <br>average outcomes are likely <br>to be followed by better <br>outcomes and above average <br>outcomes are likely to <br>be followed by worse outcomes)
    better_outcomes(When outcomes are <br>better than average <br>managers tend to praise)
      and3--->better_outcomes
      and4(and)
      and5(and)
        worse_outcomes--->and4
        reversion--->and4
        reversion--->and5
        better_outcomes--->and5
      managers_punish(Managers who punish <br>worse than average outcomes <br>will perceive reward <br>for their behavior)
        and4--->managers_punish
      managers_praise(Managers who praise <br>above average outcomes will <br>perceive punishment <br>for their behavior)
        and5--->managers_praise
        and6(and)
          managers_punish--->and6
          managers_praise--->and6
        managers_over_time(Managers, over time, <br>will learn to manage <br>by punishing bad behavior <br>rather than by rewarding <br>good behavior)
          and6--->managers_over_time
````
