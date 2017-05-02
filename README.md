
___
# The gist
**When**: May 2017

**How it works**: _Create GitHub issues, fork, refactor, open/merge Pull Requests_

* Maintainers of open source repositories create GitHub issues with the ["SpringCleaning"](https://github.com/search?q=label%3ASpringCleaning&type=Issues&utf8=%E2%9C%93) label, using the refactoring candidates from the [Better Code Hub](https://bettercodehub.com) analysis results. 
* Contributors fork the repo, refactor some code based on the issue's description and then create a [Pull Request](https://help.github.com/articles/creating-a-pull-request-from-a-fork/).
* Maintainers can use the Better Code Hub webhook integration to validate the contribution and accept the merge.

**Need a Playground?**
* Like to see a sample Better Code Hub report with the proposed refactoring candidates?
* Fancy doing some practice refactoring first? 
* Here's a repo just for that: [Playground](https://github.com/OpenSourceSpringCleaning/Playground) 

___

[![Gitter chat](https://badges.gitter.im/gitterHQ/gitter.png)](https://gitter.im/OpenSourceSpringCleaning/Lobby)

# Why do Open Source Spring Cleaning?

Starting out contributing to open source projects can be daunting. Some say that open source can be downright intimidating. No wonder, since opening up the issues belonging to popular open source projects typically means unfolding a set of very technical tasks for which deep codebase knowledge is crucial. Here's [one](https://github.com/ReactiveX/RxJava/issues) example. Where would you start...? 

We (the [Better Code Hub](https://bettercodehub.com) team at [SIG](https://www.sig.eu)) see untapped potential here. There's latent development effort that can be leveraged to bring open source projects forward, if a more "gentle" starting point would exist. We hold the belief that code quality improvements would fit the bill nicely. Maintainers can create "bite sized" refactoring candidates and make them available for the community. The community can pick these up and do them, sparking a positive and welcoming exchange between the maintainers and new contributors. "The ice is broken" now, new faces get the hang of it, and become motivated to provide more and increasingly difficult but rewarding contributions. 

# What's in it for you? 

If you participate in this initiative you get rewarded with: 

* If you're a contributor, we will send you a free hard copy of O'Reilly's book [“Building Maintainable Software”](http://shop.oreilly.com/product/0636920049159.do) if you are one of the first 100 contributors that get a Spring Cleaning Pull Request accepted.

* If you're a maintainer, you get a cleaner code base and new contributors to extend your repository. 😊 

# How does it work?

* Maintainers use [Better Code Hub](https://bettercodehub.com) to receive a set of proposed prioritized refactoring candidates. They then create GitHub issues labelled 'SpringCleaning' based on them. [Editing and creating GitHub labels](https://help.github.com/articles/creating-and-editing-labels-for-issues-and-pull-requests/)

* Contributors search for [these issues](https://github.com/search?q=label%3ASpringCleaning&type=Issues&utf8=%E2%9C%93), pick them up and follow the regular [GitHub flow](https://guides.github.com/introduction/flow/) that they are used to. They create a Pull Request against the base of the Parent repository when they are ready. 

* Maintainers can integrate the Better Code Hub webhook to check the contribution and only merge it if they're happy with it. 

# Getting started 

**As a maintainer**

Send us a Pull Request with your Better Code Hub Badge [here](https://github.com/OpenSourceSpringCleaning/OpenSourceSpringCleaning.github.io/blob/master/SpringCleaningScoreBoard.md). This is our Open Source Spring Cleaning Score Board. You can also send us an e-mail if you prefer, and we'll put it up there. The code for the Badge can be found by clicking on the  ⚙ icon in Better Code Hub.

Then proceed to creating 'SpringCleaning' issues using [Better Code Hub](https://bettercodehub.com). 

**As a contributor**

Search on Github for [issues with the "SpringCleaning" label](https://github.com/issues?utf8=✓&q=is%3Aopen+label%3Aspringcleaning). 

Fork, refactor and create a Pull Request from your Head to the Base of the Parent repository.

# How do I know my contribution will be accepted?

You can't know for sure of course, it's up to the maintainer. But you can use Better Code Hub on your proposed contribution and check the guidelines before contacting the maintainer. 

# Using [Better Code Hub](https://bettercodehub.com)

... is easy. Head over to [bettercodehub.com](https://bettercodehub.com) and login with your GitHub account. You'll then see your repos, and you can start an analysis clicking the ▶️ button. It will analyze the default branch. 

To enable Better Code Hub to run on your own fork for every Push and Pull Request, click the ⚙ icon and toggle the "Push & Pull request analysis" switch.

![githubflow](https://cdn-images-1.medium.com/max/720/1*N4wz389i80UbXKnjSp_QoA.png "Activate GitHub flow")


## Feedback 

Don't hesitate to send us feedback about our platform at bettercodehub@sig.eu. We're always happy to hear improvement suggestions from you.  

*Let's do some thorough spring cleaning here, one Pull Request at a time!*

[Rob](https://github.com/robvanderleek), [Mircea](https://github.com/mcadariu) and [Michiel](https://github.com/michielcuijpers)

![Broom](https://raw.githubusercontent.com/OpenSourceSpringCleaning/OpenSourceSpringCleaning.github.io/master/27282130.png "Broom")
