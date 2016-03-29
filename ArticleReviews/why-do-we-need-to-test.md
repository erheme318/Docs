## Why do we need to test ?

## Impacts
 - humans executing a bunch of tests manually doesn't provide the same
   result each time


## We automate
Generaly, we automate to avoid repeated manual work, get faster feedback,
save time on running tests over and over again, and ensure we are always
executing tests consistently with the same preconditions and expectations.


## Important
 - Fast feedback is important for any successful continuous integration
   strategy, and critical as you move towards Continuous Delivery
 - It allows you to identify if there is any regression in the quality
   at the time the code is committed, allowing the team to fix problems
   as soon as they are introduced

 - The team will also rely on it in order to implement changes, or
   to re-factor the code.

 - Continuous integration requires automated tests, because for every
   small change, we are able to re-execute all regressions and make sure
   we aren't breaking anything.

## Too much is bad
 - A long running regression test suite quickly becomes a bottleneck
   when committing changes. As a consequence, developers will commit
   less frequently, with larger commits.

## Importance relevance

FeaturesBusiness RelevanceError RateTotal
Inbox235
New mail123
Login314
Settings1                           12
                            

# Reference
 - https://www.thoughtworks.com/insights/blog/functional-tests-how-decide-what-automate-or-not
