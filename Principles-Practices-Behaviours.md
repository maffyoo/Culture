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

Spike solutions are really good for checking feasibility, viability and scope of an idea or piece of work. Spikes should never be shipped and therefore should be kept away from master. Spikes should also be time-boxed: this avoids unbounded amounts of work being done away from Master where value is shipped from.

## Use architectural decision records ##

We use architectural decision records (ADRs) as a way of capturing and communicating key decisions about our software architecture. These should be lightweight enough that they arent a burden to read, but detailed enough that they capture the essential context of the decision made including options considered decision made and why, in relevant context, the choice was made. ADRs should be maintained, sustainable and accessible to everyone. 

## Mobbing ##

Where there are decisions about direction or areas that need broad awareness and exploration Mobbing is a valuable tool allowing a team to consider a problem or challenge as a whole group sharing their understanding and leveraging the skills and knowledge of the entire group. 

## Code Review ##

All code must be reviewed and this must include review by someone who is not the author of the code. This is not necessarily a Pull-request (PR) related review. Pairing provides one form of (p)review as does a classic PR based code review. Small batches are key to keeping this an efficient practice. Pairs should be verifying and committing regularly. 

# Principles #

## SOLID ##

We write object-oriented code that is sympathetic to the SOLID principles of object oriented design. These being

**S**ingle responsibility principle

**O**pen-closed principle

**L**iskow substitution principle

**I**nterface segregation principle

**D**ependency inversion principle

These principles produce code that is loosely coupled easy to reason about and simple to change.

## Lean ##

We believe in the principles of lean development.

The flow of work
fast feedback 
continuous learning and improvement

and many of the detailed applications that this implies, many of which are reflected in this document

## Done means Done ##

Code isnt "done" if it isn't running in production. For this reason only code that is shippable should be handed off from an engineer. 

## Automation ##

We should automate repetitive tasks to allow teams to focus on less structured and predictable activities. Test specialists should be able to focus on Exploratory testing and not be burdened with validating acceptance criteria 

## Clean Architecture Principles ##

Our Software architecture should reflect the principles of Clean Architecture. Clean architecture produces testable code, where details are only known known by the least amount of our code making them easy to replace or change. 

[Clean Architecture](https://blog.cleancoder.com/uncle-bob/2012/08/13/the-clean-architecture.html)

## Visualise work ##

Visualising work allows teams to share understanding about many aspects of their work, from plans, system processes and progress to team structures, inter-team or department relationships and dependencies. Removing ambuguity by visualising work enables productive discussion and transparency and shared understanding.

## Agile ##

Agile development allows us to work in a way that best delivers value effectively focussing on activities that improve outcomes rather than beaurocractic activities that produce artefacts for the sake of it. 

The agile manifesto captures the overriding 

- Individuals and interactions over processes and tools
- Working software over comprehensive documentation
- Customer collaboration over contract negotiation
- Responding to change over following a plan

## Be prepared to throw things away ##

> _The management question, therefore, is not whether to build a pilot system and throw it away. You will do that. The only question is whether to plan in advance to build a throwaway, or to promise to deliver the throwaway to customers_
 **Fred Brooks**

Write code to clarify and to start solving problems and dont be afraid to throw things away because you probably will anyway

## Measure key aspects of our code and architecture ##

Analytics provide an invaluable insight into the effectiveness of products and their features based on goals and objectives of the product. In a similar way we can use analytics, such as fitness functions, to measure architectural health and fitness of our code base, ensuring it exhibits desirable traits and ensuring that when we have a problem we know that we need to focus on maintaining our software architecture.

## Make it easiest to do the right thing ##

Wherever we have important processes or practices we should always make it easiest to do the right thing even if that involves actively blocking options that may make it easy for a team member to bypass or avoid a key task or step in a process. For example, if we have a policy of comments on all public API methods, we could automatically reject pull requests that dont have comments on public API ensuring that the easiest way to avoid getting a Pull Request rejected is to have comments on all Public API

## Technology decisions are owned by chapters ##

Any key decisions on platform specific technology and its use are decided by chapters. it should never be the case that new paradigms or approaches to creating or integrating features are adopted in isolation without ensuring the platform technology community is aware and approving of the approach.

## Quality is not negotiable ##

Quality concerns cover all that we do. Our quality standards are not negotiable. We never take shortcuts to get work delivered, we should always reduce scope in this scenario. if we have to play tactics purely to meet a deadline, this is not done without debt being planned in and agreed as part of the decision process

## Continuoue Improvement ##

We set clear and ambitious goals and use the proactive practice of continuous improvement as a means of meeting and exceeding these goals. If we react to events and observations rather than improving and fixing towards a goal we will never have a consistent goal for improvement

# Behaviours #

## Transparency ##

Transparency provides for a culture of trust and allows shared understanding. Information should be shared as soon as is feasible in way that does not push this information onto everyone causing overload. Visualisation is a great way of providing transparency.

## Inclusivity ##

Inclusion is critical to healthy gelled teams, everyone should feel included regardless of their physical location or any individual needs or special attributes that they have

## Fairness and equality ##

We operate in an environment of fair and equal treatment that takes everyone and their needs into consideration. in some cases this may mean we have to put reasonable measures in place such that the environment, our teams and how we work ensures equality and fairness for everyone

## Embrace Challenge ##

Because we believe in fairness, equality and inclusivity we encourage challenge where someone feels strongly about a decision, our direction or similar. We also expect that decisions are respected. Challenges repeatedly made in a way that undermines the team or any individual is not acceptable, though.

## Support team decisions ##

Team decisions should be respected and supported even if there is individual disagreement. Everyone has the right to disagree but the team are responsible for deciding what the team does and decisions have to be respected. Its also worth remembering that everyone is a member of multiple teams. This could be your reports, if you are a manager, your peers and your community team such as iOS or Android chapter. 

## Blame free post-mortems ##

We conduct blame free post-mortems and incident reviews that allow everyone to learn. 

## Continual learning and development ##

Providing an environment where engineers can grow and progress means paying particular attention to continual learning in pursuit of Mastery. Mastery is accepted as a key pillar of personal motivation and engagement it also ensures that we are continually improving our ability to create great products and services.

## Everyone is a teacher, everyone is a student ## 

Put simply we can all learn from each other. and should. whether its complex technical concerns or personal advice we should be prepared to act as a teacher or as a student

