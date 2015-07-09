#CloudCredo Training Template

##Who are [CloudCredo](http://www.cloudcredo.com/)

We're a consultancy focused on [Cloud Foundry](http://www.cloudfoundry.org) and [BOSH](http://bosh.io/). We help our clients participate in the Cloud Foundry ecosystem.

##What is this repository

When we on-board new engineers we use this backlog, in [Pivotal Tracker](https://www.pivotaltracker.com/n/projects/1151108), as a basis for their training. We pair our new engineers with experienced engineers on this work so they can gain domain expertise as quickly as possible.

##Creating the backlog

If necessary, create an account in [Pivotal Tracker](https://www.pivotaltracker.com/). Create an appropriately named training project. In the project settings, select 'Import CSV'. Choose the CSV file from this repository and import it. You should have a lovely backlog populated with fresh training stories.

####What if I can't use Pivotal Tracker?

Tracker's great. Use it.

If you really can't use it, maybe try [Fulcrum](https://github.com/fulcrum-agile/fulcrum). We haven't tried it with these stories but it should work.

##A Way of Working

This is more than just a training backlog; you're learning an agile way to deliver value. We kick-off this backlog with an 'Inception', have daily standups, and regular iteration planning meetings and retrospectives. Change the backlog as you're learning and your goals evolve.

It is important to pair with experienced engineers on the training backlog to reduce blocking issues and provide context. It's also important to have a psuedo 'Product Owner' to prioritise the backlog against the training objectives.

[Get in contact](http://www.cloudcredo.com/contact-us/) if you'd like to pair with experienced engineers from [CloudCredo](http://www.cloudcredo.com/).

Further information about this way of working is available on [our site](http://www.cloudcredo.com/the-cloudcredo-way/).

##FAQ

####Why are there no answers?

'The joy is in the journey' - the learning you derive from delivering the features is the value.

####What are the labels?

We've added some basic labels to show the themes our training usually follows. They should be fairly self explanatory, with the possible exception of 'p1' - this is for [Pivotal's cloud platform](http://pivotal.io/).

####How do I get help when I'm stuck?

[Contact CloudCredo.](http://www.cloudcredo.com/contact-us/)

####How do I contribute?

Please fork the repo and issue a pull request. The CSV isn't the easiest format to work with; we're considering moving to [Prolific](https://github.com/onsi/prolific) in the near future. I used this regex to filter the important elements from a Tracker-exported CSV;
```
[0-9]+,(.*),".*",,,[A-Za-z ]+,,.*,\n
```