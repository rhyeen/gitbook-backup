---
description: >-
  Coordinating & tracking Software Development effort is a solved elegant
  methodology, but the practical application is anything but.  Let's address
  that.
---

# Practical Agile Development

Agile Software Development is synonymous with Software Development. I was introduced to the methodology way back in school and have used it in every job since then. Every software engineer in the industry is familiar with the agile methodology, and although there are many competing methodologies ([Waterfall, Lean, etc.](https://en.wikipedia.org/wiki/List\_of\_software\_development\_philosophies)), most businesses run processes derived from "Agile", whether that's scrum, iterations (sprints), story points, velocity, burn down, and so on.

Despite how universally familiar this industry is with agile development, and despite how many high-level resources we have on the topic (just Google, "Agile Software Development"), I have yet to find a succinct resource that distills an effective solution for applying the agile methodology into planning and operations. In this article, I intend to resolve that by providing a comprehensive guide on how I have successfully applied agile development with my software teams.

{% hint style="info" %}
### What agile development solves and what it doesn't.

Since the agile methodology has fully saturated the tech industry, it has been construed to fit business expectations by marketing and over promising.  The [original principles](https://agilemanifesto.org/principles.html) of the [agile manifesto](https://agilemanifesto.org) have largely been lost in the flood of technical jargon and overpromises fabricated by business opportunists looking to turn a profit ([just listen to Uncle Bob](https://www.youtube.com/watch?v=a-BOSpxYJ9M), one of the father's of the agile principles, soapbox on the topic).

What this caused is a snake-oil belief that agile development is the solution to increase the productivity of software engineers through monitored measurements.  The hope being that if you can effectively keep engineers focused on measurable top-down tasks and track that progress, you can create more feature output and therefore increase your business value.

Although it can be argued that this particular application of agile development (known as Agile, with a capital "A") does indeed increase the output of features, I would strongly argue ([with other voices](https://www.youtube.com/watch?v=2JNXx8VdbAE)) against such practices as they directly distract from increasing meaningful business outcomes.  More output ≠ more profit.

Instead, consider agile development to be a set of guiding principles that will help your engineering teams better coordinate, better pivot, and better articulate how their work is contributing to the greater business goals.  In essence, agile development is about:

* knowing where you and where your team is working,
* defining steps to reaching your collective goals,
* learning through qualitative and quantitative data,
* and pivoting with agility when needed.

#### Benefits for remote work

This is especially important for modern tech business operations, in which the workforce is either fully or partially remote, or in which team members are scattered across different offices.  Many of the benefits of working physically adjacent to your fellow coworkers are no longer applicable.  Communication suffers over distances, no matter how many Zoom calls or Slack conversations you have.  Business need to compensate with effective cooperative practices, such as (you guessed it) agile development.&#x20;
{% endhint %}

## What we will cover

Agile development is a huge topic.  I'm going to cover what I believe is essential for your engineering team to be able to plan and work together on business-level tasks.  In technical terms, we'll be covering iteration planning and meetings, story points and milestones, velocity, kanban boards, and other sprinkled topics in between it all.

{% hint style="info" %}
### What we will NOT cover

This article is specifically focused on the aspects of agile development regarding business planning rather than software engineering practices.  Topics such as Test Driven Development (TDD), the SOLID Principles, Continuous Integration and Deployment (CI/CD), Pair Programming, Code Review, Acceptance Tests, etc. are topics worthy of their own research, but way beyond the scope of a single article.  For an excellent grasp regarding "why" these topics are important, I'd highly recommend picking up [Clean Agile](https://www.amazon.com/Clean-Agile-Basics-Robert-Martin/dp/0135781868).

There's also certain parts of agile development that I think are either not worth talking about or just outside of the scope of this article.  I have aggregated a lot of those in my [closing thoughts](readme/closing-thoughts.md#topics-i-ignored).  Most are specific to Scrum, which I personally believe has bastardized agile development and also suffers from circular self-entitled definitions (e.g. Scrum Meeting vs Stand up, Scrum Board vs Kanban board, etc.).
{% endhint %}

So let's dive into our first topic: scoping and utilizing an iteration/sprint.
