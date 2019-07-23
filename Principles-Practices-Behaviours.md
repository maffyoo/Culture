# Practices #

## Test Driven Development ##

Test-driven development produces testable code by default and writing tests first avoids the challenge of whether you will write them afterward.Test-driven development also encourages client-oriented design; choices are made from the perspective of a consumer which can promote better API design.

[TDD Kata](http://www.butunclebob.com/ArticleS.UncleBob.TheBowlingGameKata)

## Pairing and Pair Programming ##

Pair Programming allows upfront discussion of specifications and design decisions rather than relying on a review of already written code. Pair programming is generally done at the right time for the right reasons - not all day, every day. Its useful to agree a pairing style and the scope of the work to be done before beginning a pairing session 

## Work is done in small batches ##

Small batches of work are easily verifiable, reduce risk and support our goals of continuous integration and delivery
Local Changes should be kept to less than 1 day old

## Feedback early and often ##

Clarifying Specifications and validating solution outlines continuously and early avoids relying on a single check that is a review once code is already written. Pair Programming is great for continuous review and TDD for continuous feedback

## Continuous delivery ##

Continuous Delivery produces measurable outcomes quickly. working in small batches mean issues can be detected and fixed cheaply and this supports our principle of feeding back early and often

## Trunk Based Development ##

We should ensure code is always shippable from master because we value small changes and fast fedback this also means we should be able to support longer term batches of work by using Feature Flags and Branch by Abstraction techniques

## Remote first ##

Remote workers are first class participants in any activity they are part of. A modern workforce should be enabled to work in a flexible way that supports their location and allows them an equal presence with other participants

## Spikes ##

Spike solutions are really good for checking feasibility, viability and scope of an idea or piece of work. Spikes should never be shipped and spike should be kept away from master. Spikes should also be time-boxed this avoids unbounded amounts of work being done away from Master which is where value is shipped from.

## Use Architectural decision records (ADRs) ##

We use architectural decision records as a way of capturing and communicating key decisions about our software architecture. These should be lightweight enough that they arent a burden to read, but detailed enough that they capture the essential context of the decision made. They should be maintained, sustainable and accessible to everyone. 

## Mobbing ##

Where there are decisions about direction or areas that need broad awareness and exploration Mobbing is a valuable tool allowing a team to consider a problem or challenge as a whole group sharing their understanding and leveraging the skills and knowledge of the group

## Code Review ##

All code must be reviewed and this must include review by someone who is not the author of the code. This is not necessarily a PR related review. Pairing provides one form of (p)review as does a classic code review. Small batches are key to keeping this an efficient practice. Where an engineer works alone pairs should be commiting regularly. 

# Principles #

## SOLID ##

We write object-oriented code that is sympathetic to the SOLID principles of object oriented software. These being

**S**ingle responsibility principle

**O**pen-closed principle

**L**iskow substitution principle

**I**nterface segregation principle

**D**ependency inversion principle

## Done means Done ##

Code isnt done if it isn't runngin in production. Only code that is shippable is handed off from an engineer

## Clean Architecture Principles ##

Software architecture should reflect the principles of Clean Architecture

[Clean Architecture](https://blog.cleancoder.com/uncle-bob/2012/08/13/the-clean-architecture.html)

## Visualise work ##

Visualise work to share understanding


## Agile ##

Agile development allows us to work in a way that best delivers value effectively

- Individuals and interactions over processes and tools
- Working software over comprehensive documentation
- Customer collaboration over contract negotiation
- Responding to change over following a plan

## Be prepared to throw things away ##

Write code to clarify and solve problems dont be afraid to throw it away

## Measure key aspects of our code and architecture ##

Use Architectural analytics, such as fitness functions, to measure architectural health and fitness

## Make it easiest to do the right thing ##

Wherever we have important processes or practices we always make it easiest to do the right thing even if that involves actively blocking options

## Technology decisions are owned by chapters ##

Any key decisions on platform specific technology and its use are decided by chapters. it should never be the case that new paradigms, approaches of features are adopted in isolation without ensuring the platform technology community is aware and approving of the change

## Total Quality ##

Quality concerns cover all that we do
Our quality standards are not negotiable. never take shortcuts to get work delivered, we should always reduce scope. if we have to play tactics, this is not done without debt being planned in and agreed as part of the decision process

## Continuoue Improvement ##

We Set clear and ambitious goals and use the proactive practices of continuous improvement as a means of meeting and exceeding them

# Behaviours #

## Transparency ##

Transparency provides for a culture of trust and allows shared understanding

## Inclusivity ##

Inclusion is important in a healthy gelled team

## Fairness and equality ##

Fair and equal treatment that takes everyone and their needs into consideration.

## Support team decisions ##

Team decisions should be respected and supported even if there are individual disagreement

## Continual learning and development ##

Self development and mastery is critical to our personal and mutual success

## We believe everyone is a coach ## 

> **_We help each other be our best through honest dialogue, advice and support _**

