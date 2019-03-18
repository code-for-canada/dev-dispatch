---
layout: post
title: Sprint Planning for Developers
author: "Caley Brock"
---

Code for Canada fellowships are broken up into 4 phases: Onboarding, Discovery, Build, and Transition. Our team at the Public Service Commission (PSC) transitioned from Discovery to Build about a month ago, and in doing so, have redefined our product goals, and the process we use to achieve those goals.

![alt text](https://raw.githubusercontent.com/code-for-canada/dev-dispatch/master/images/psc/timeline.png "Code for Canada fellowship timeline")

IT Discovery primarily involved researching existing systems at the PSC and setting up the tools we’d need to start building in February. We introduced a lot of new things: a technology stack for web development, an ambitious architecture plan for a new application, goals for automated deployment, accessibility standards, and automated testing - all big changes for the department and the development team we work with.

![alt text](https://raw.githubusercontent.com/code-for-canada/dev-dispatch/master/images/psc/psc-it-discovery.png "IT Discovery. We spent time understanding existing systems (products, architecture, tech stack) and processes (deployment, testing, security), so we could understand the biggest opportunities for improvement and make goals for a new system.")

During Build, the goal of a product team is to actually *build* a product, so we want get as much feature work done as possible. When we started building features based on user stories, it was easy to forget that all the process and technology changes needed support too.

We realized our developer work items during the early stages of “Build” fall into three categories.
* Automated deployment pipeline
* Developer process and training
* Feature work

Investing in a deployment pipeline, developer processes, and training all speed up feature work in the long run. Here’s how we’re finding a balance and agreeing on priorities as a team.

![alt text](https://raw.githubusercontent.com/code-for-canada/dev-dispatch/master/images/psc/sprint-work-items.png "Feature work takes up 80% of the sprint, development 10%, and dev processes and training another 10%")

When we plan our sprint, we purposefully break up our work into these three categories. Most of our tasks should be feature work related to the user stories for that sprint. (If you’re interested if how we plan our feature work, check out our [project blog](https://code-for-canada.github.io/psc-updates/).)  Based on the retros from the previous sprint, we pick the *most painful* part of our current development processes, and work on improving it. We also take a step closer to automated server deployment. 

Since we agree on these work items and discuss their value as a team, there’s less guilt for taking time away from direct feature work, and more excitement about the long term sustainability of development.

Here’s some of my favourite changes that came out of this process
* [Prettier](https://prettier.io/) - At first we had setup ESLint, which was helpful but annoying. I saw [this tweet](https://twitter.com/dan_abramov/status/1086215004808978434?lang=en) from Dan Abramov, we installed Prettier, and writing code feels so much smoother.
* Accessibility Co-Training - Each sprint, everyone on the team does a single topic [Web Accessibility Tutorial](https://www.w3.org/WAI/tutorials/) and then has 15 minutes to teach the content to the rest of the team. We’re striving to create experts in different areas of accessible web development and working to hold each other accountable in code and design reviews.
* [PR Templates](https://help.github.com/en/articles/creating-a-pull-request-template-for-your-repository) - One sprint we introduced them, and then we felt like the process was too heavy, so we adjusted once again. Now [our template](https://github.com/code-for-canada/project-thundercat/blob/master/docs/PULL_REQUEST_TEMPLATE.md) makes the team more productive and better at documenting.

Our process will never be perfect, but it’s been nice to see to have it always be better than last sprint.
