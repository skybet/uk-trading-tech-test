# UK Trading Tribe Tech Test

Welcome to the UK Trading Tribe Tech Test!

We hope that you find this exercise fun. There are no trick questions; we want to see your solution to a simple problem with well thought-out and well structured code.

## The Brief

Create an application to model a very basic family tree (feel free to use a framework if you wish). The application must fulfil the following core requirements:

* Initialise the family tree with 2 members, 1 male, 1 female
* Add a child, each child must have 1 father and 1 mother. Parents must be a current family member
* List both parents for any given family member
* List children for any given family member
* List all descendants for any given family member
* List all ancestors for any given family member
* These operations should be exposed through a REST API

Please keep it simple. If you require any additional information, please ask. We would rather you asked obvious questions and got it right rather than not ask questions and get it wrong. (Asking good questions is seen as a positive!)

## Review Criteria

All tech test submissions (for any of our tech tests) are anonymised and reviewed using a standard template.

At a high level we will be looking for:
* Readability: clear naming conventions, clear documentation where necessary
* Good understanding of the programming language and its features
* Automated tests
* Simplicity
* Clear instructions on how to build, test & run the application using the build framework of your choice
* Logging
* Error handling
* Clearly described regular commits visible through VCS

## Languages

We use a mixture of coding languages but for data consumption we mainly use Kotlin and a bit of Node. For this tech test we recommend you use Java or Kotlin, but if you can show off your skills better in another language then please do so and include your justification in the README.

## Timescale

Please time-box this exercise at about 3 hours. If you've spent more than that and you're still not finished, just submit what you have - we're more interested in what you have done, not what you haven't, nor do we want this to take up a huge amount of your time. It is more important to model a subset of functionality to a higher level of quality than to model all the functionality but to a lower level of quality.

## The Deliverable

In the root of your application create a README.md including:

  1. A covering note explaining the technology choices you have made.
  2. Any instructions required to run your solution and tests in a Linux/Mac environment.

Email a link to your repo (make sure it's public!), or as an attachment the git bundled repository showing your commit history with all your commits on the master branch:

        git bundle create <anything>.bundle --all
