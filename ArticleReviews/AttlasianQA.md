# Atlasian Quality assistance

Traditional testers help to ship safely by doing the testing, but this
can have the side-effect of slowing the team down. When bugs are found
in a testing stage:
 - fixing them requires rework of existing code
 - taking extra time

 The team is then put in a position where they have to decide between
 shipping **quickly or safely**.


 At Atlassian, they optimised the process by **empowering and educating
 developers** to test their own features to **production quality standards**.

  - Keeping the ratio of testers/developers low
    Not because of resource constraints, but to force the “whole team”
    mentality when it comes to **quality**


As developers learn to build quality into their features from the start:
 - rework is reduced
 - the team can achieve both **quick and safe delivery**.


### Quality

Development teams should be delivering software that works under all
conditions. They should not expect other teams, users of dogfooding
instances, or customers to find their bugs. 

**Experimentation** is the key.

### Speed

Development teams should be able to ship their features to production
in as short a time as possible. They should not write code that does not
get shipped, and should minimize the need for rework. 

### Independence

Development teams should be able to: 
 - write features
 - test those features
 - and deliver them to production themselves.

They should not rely on QA, or other teams, which may act as
bottlenecks.


### QA kickoffs:
>
pairing to brainstorm on testing notes before the coding starts

Pairing with developers encourages them to think of all the risks and
edge cases upfront, before they start implementing the story.
Implementation choices may be influenced by these requirements, and
problems may be prevented earlier on. You can brainstorm together to
come up with testing notes, and sort out any ambiguities from the start.

#### Testing notes:
Testing notes cover the **risks** that need to be tested. They are not
an explanation of how to test.

>
Testing notes should be updated as more is learned about the
implementation of the story.




### QA Demo:
to confirm that the testing was done (not to repeat the testing).


### DoT
>
A different developer tests the story, using both the testing notes
and their own exploratory testing skills.

Assigning a "Developer on Test" is a good way to introduce developers
to the idea of testing, improve their skills, and make it explicit that
quality is everybody's responsibility.

However, long-term reliance on DoTing is a sign that a team isn't
confident in the testing done by the developer who implements the
story. Effectively, somebody is double-checking the testing tasks
that should have been done by the original developer, which is
inefficient.

# Reference
 - Moving from quality assurance to quality assistance
   https://fr.atlassian.com/inside-atlassian/quality-assurance-vs-quality-assistance
