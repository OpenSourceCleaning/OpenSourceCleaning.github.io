
___
# The Gist
**When**: _May 2017_

**How it works**: _Create SpringCleaning GitHub issues, fork, refactor, open/merge Pull Requests_

* Maintainers of open source repositories on GitHub create ["SpringCleaning"](https://github.com/search?q=label%3ASpringCleaning&type=Issues&utf8=%E2%9C%93) issues based on the proposed prioritized refactoring candidates from the [Better Code Hub](https://bettercodehub.com) analysis results. 
* Contributors fork the repo, refactor some code based on the issue's description and then create a [Pull Request](https://help.github.com/articles/creating-a-pull-request-from-a-fork/) proposing the improvement to the maintainers.
* Maintainers can use the Better Code Hub webhook integration to validate the contribution and merge the Pull Request.

[![Gitter chat](https://badges.gitter.im/gitterHQ/gitter.png)](https://gitter.im/OpenSourceSpringCleaning/Lobby)

___

# What's the idea?

Starting out contributing to open source projects can be daunting. Some say that open source can be downright intimidating. No wonder, since opening up the issues belonging to popular open source projects typically means unfolding a set of very technical tasks for which deep codebase knowledge is crucial. Here is [one example](https://github.com/ReactiveX/RxJava/issues). This project is very successful, but where would a newcomer start...? 

We see untapped potential here. There is latent development capacity that can be leveraged to bring open source projects forward, if a more "gentle" starting point would exist. We hold the belief that code quality improvements would be a nice fit for this. Maintainers can create bite-sized improvement items (refactoring candidates) and then propose them to be refactored by the community. The community can pick these up and do them, sparking a positive and welcoming exchange between the maintainers and new contributors. "The ice is broken" now, new faces get the hang of it, and become motivated to provide more contributions. 

_Every Pull Request matters. With enough of these contributions, the open source code on GitHub gets cleaner, easier to work with, reuse and extend. Small improvements, added up, will make a difference._

# What's the reward for participation?  

If you participate in this initiative you get rewarded with: 

* The first 100 contributors that get a SpringCleaning Pull Request accepted will get a hard copy of [“Building Maintainable Software”](http://shop.oreilly.com/product/0636920049159.do) (O'Reilly).
* If you're a maintainer, you get a cleaner code base and new contributors to extend your repository. 😊 

# Getting started 

**As a maintainer**

* (If not already done) Enable issues in the repository's settings page.
* Create a 'SpringCleaning'-label [Here's how.](https://help.github.com/articles/creating-and-editing-labels-for-issues-and-pull-requests/)
* Create issues based on the proposed prioritized refactoring candidates from [Better Code Hub](https://bettercodehub.com) and attach the 'SpringCleaning' label to them.
* To enable Better Code Hub to run on every Push and Pull Request, click the ⚙ icon and toggle the "Push & Pull request analysis" switch. This will activate the webhook.

**As a contributor**

* Search on Github for [issues with the "SpringCleaning" label](https://github.com/search?q=label%3ASpringCleaning&type=Issues&utf8=%E2%9C%93). 
* Fork, refactor and create a [Pull Request](https://help.github.com/articles/creating-a-pull-request-from-a-fork/).

**Want to see a sample Better Code Hub report?**

* Head over to [bettercodehub.com](https://bettercodehub.com) and login with your GitHub account. You'll then see your repos, and you can start an analysis clicking the ▶️ button. It will analyze the default branch. 

**Need a Spring Cleaning Playground?**

* Fancy doing some practice refactoring first? 
* Here's a repo just for that: [Playground](https://github.com/OpenSourceSpringCleaning/Playground)
* Fork it and run Better Code Hub to see refactoring candidates.

# Keep in mind

Better Code Hub supports 16 programming languages up to 100,000 lines of code per repository:

* C#
* C++
* Go
* Groovy
* Java
* JavaScript
* Objective C
* Perl
* PHP
* Python
* Ruby
* Scala
* Shell Script
* Solidity
* Swift
* TypeScript

# Feedback 

Don't hesitate to send us feedback about Better Code Hub at <a href="mailto:bettercodehub@sig.eu">bettercodehub@sig.eu</a>. 

*Let's do some thorough Spring Cleaning here, one Pull Request at a time!*

[Rob](https://github.com/robvanderleek), [Mircea](https://github.com/mcadariu) and [Michiel](https://github.com/michielcuijpers)
