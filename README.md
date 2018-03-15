# Reciate

## Our workflow

It is important to us that the specification of this application is forged by consensus among its contributors, and that its implementation follows clearly from the specification. For that reason, everyone who contributes will try, as far as possible, to be rigorous in following this workflow.

If you wish to make a contribution to this repository, we request that you follow these steps:

  1. If the contribution includes a new feature, or changes how a feature will be consumed publicly, please design a specification for the feature or change:

  The process of designing a specification includes

  - Experimenting in code

  Feel free to make changes to the code in a new branch. It is of course difficult to design without the feedback offered by playing with code. Just understand, it is impossible that any changes to the code can be merge into master unless it is in full conformity with the design in the specification, or you can offer a valid justification explaining why it is not (for example, your implementation cuts a corner that would otherwise be very technically challenging, but is still usable; of course, these kinds of divergences from the specification would have to be approved reviewers).

  - Conversations with other contributors

  - Creating a PR to the README of the master branch of this repository with a description of the specification

  - Thoughtfully considering all of the comments made to the PR

  - Applying the suggested changes to the PR until at least two fellow contributors, including an author of the repository, have accepted the PR, and none are rejecting it. 

  At the end of this design process, the specification of the feature or change you wish you implement should be merged into the README of the master branch. The README serves as a single source of truth for all design decisions. That means, once your specification is merged to master, it is now a part of the agreed 'truth' of this application. All further design decisions will refer to your specification as accepted cannon, unless it is changed in a future accepted PR.

  If your contribution does not effect the public consumption of the application (for example, code refactors), feel free to skip this step. But when in doubt, propose a specification.

  2. Open a PR with the proposed changes, in full conformity with the specification, unless you have good reason to diverge from the specification

  - Like in step 1, this PR cannot be merged until it has been approved by two or more reviewers, including an author of the repository, and is not being blocked by any reviewers.

  - Step 2 doesn't necessarily have to take place after step 1, but it certainly cannot take place before step 1. The code changes can be in the same PR as the specification, in which case you cannot merge the PR unless both the specification and the changes have been approved.
