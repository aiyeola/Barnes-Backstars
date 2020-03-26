# Checkpoint Submission Process

Version 2.0

#### Git _Workflow_

This is the recommended Git _workflow_ to enable easy review:

- First create the checkpoint repository on your Github account.
- Clone the repository on your local machine.
- At this point, your will only be having one branch (master), create a new branch (develop) off master branch.
- All your work should done on the **develop** branch.
- On Github, create a Pull Request:
  - Subject: **Checkpoint <number> Review**
  - Description: **write a summary of what you’ve done and your approach.**
- This will make it easy for the reviewer to comment through your code at one glance as opposed to moving in between your commits. See sample below:

![Github](https://raw.githubusercontent.com/andela-mkwamboka/code-review-guidelines/master/appendix/gitworkflow.png)

#### Integrations

The following 3 integrations **must** be on your repository:

- Tests, we recommend any of the following:
  - [TravisCI](https://travis-ci.org/)
  - [CircleCI](http://circleci.com/)
- Test Coverage, we recommend:
  - [Coveralls](https://coveralls.io/)
- Code Quality, we recommend any of the following:
   - [StyleCI](https://styleci.io/) (PHP)
  - [HoundCI](https://houndci.com/) (JavaScript)
- Then include the badges for your integration on the README, e.g.

![Integrations](https://raw.githubusercontent.com/andela-mkwamboka/code-review-guidelines/master/appendix/integrations.png)

