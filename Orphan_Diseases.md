# Orphan Diseases

```mermaid
flowchart LR
proposition(Is personalized medicine <br>leading us to an <br>increasingly baysian world <br>where we need hundreds <br>of thousands of <br>separate diagnoses and <br>treatments rather than <br>to a simple place where <br>each person has one problem?)

old_diagnosis(A diagnosis was <br>a category attached to a <br> clinical state intended to <br>direct treatment)
new_diagnosis(Diagnosis - <b>DX</b> - is <br>now a category combining <br>clinical states that <br>generally require similar <br>levels of resources)

orphan(An orphan disese, <b>OD</b>, <br>is defined in the US as <br>an illness affecting less <br>than 200,000 people <br> nation-wide)
disease(A disease is defined <br>as a disordered or <br>incorrectly functioning <br>organ, part, structure, <br>or system of the body)
and1((and))
    orphan--->and1
    disease--->and1
every_pt(Every patient has, regardless <br> of diagnosis, <br> a unique set of organ <br>system dysfunctions leading to <br>or impacting their <br> diagnosis)
    and2((and))
        every_pt--->and2
        disease--->and2
OD_def(An OD is a <br>disordered or incorrectly <br> functioning organ, part, <br>structure or system of the <br>body that occurs in less <br>than 200,000 Americans)
    and1--->OD_def
every_pt2(Every patient has a <br>unique illness <br>regardless of the <br> primary diagnosis they <br>are given)
    and2--->every_pt2
logic(1<200,000)
and3((and))
    OD_def--->and3
    every_pt2--->and3
    logic--->and3
every_pt3(Every patient <br>has an <br>orphan <br>disease)
    and3--->every_pt3
accurate(Accurate personal <br>diagnosis is required <br>in every patient not <brmatter how common <br>their primary <br>diagnosis is)
    every_pt3--->accurate

body(A body is made <br>up of and <br>functions as a <br>system of parts)
systems(A system can appear to be <br>functioning normally <br>if viewed from <br> outside, even if it is <br>not functioning well)
and4((and))
    body--->and4
    systems--->and4
persons(A person, as a biopsychosocial <br>system, can be buffered or <br> compensated os that the output <br> of the system with regard to any <br>individual diagnosis appears <br>normal, while there is still <br>dysfunction in the system)
    and4--->persons

system(A system is a <br>network of <br>functioning parts)
any_system(Any part of <br>a system can <br>malfunction <br> causing system <br>malfunction)
buffered(Systems can be robust <br>or buffered such that <br>malfunction in a part <br>may not create <br>apprent malfunction of <br>the system)
and5((and))
    system--->and5
    any_system--->and5
    buffered---and5
        dysfunction(The dysfunction of any part of a <br>network creates a dysfunction in <br>the network or system though <br> that dysfunction may not be <br>apparent because of robustness <br> of the system or buffering)
        and5--->dysfunction

age(All biological <br>systems degrade <br>with age)
limits(All human <br>beings are born <br>with inherent <br>biological <br>limitations)
and6((and))
    age--->and6
    limits--->and6
time(All human <br>beings' biological <br>systems get <br>worse with time)
    and6--->time
        and7((and))
        time--->and7
        dysfunction--->and7
            tardive(Illnesses stemming <br>from inherent <br>biological limitations <br>may become <br>apparent with time)
                and7--->tardive
                genetic(Illnesses with <br>genetic origin <br>may become <br>apparant later <br>in life)
                    tardive--->genetic

    


```
