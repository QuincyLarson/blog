---
title: "[Do not Publish] Google Summer of Code — 2018."
description: "freeCodeCamp.org is nonprofit that helps millions of people learn to code for free. We are applying for Google Summer of Code as a mentor…"
date: "2019-06-11T18:37:17.921Z"
categories: []
published: false
---

freeCodeCamp.org is nonprofit that helps millions of people learn to code for free. We are applying for [Google Summer of Code](https://summerofcode.withgoogle.com/) as a mentor organization in 2018.

If you are a student, then we have some challenging, widely-used projects for you to work on this summer.

#### What is Google Summer of Code (GSoC)?

Google Summer of Code is a global program focused on bringing more student developers into open source software development. 

Students work with an open source organization on a 3-month programming project during their break from school.

To learn more about the program and its eligibility requirements, [visit GSoC’s page here](https://summerofcode.withgoogle.com/how-it-works/).

#### freeCodeCamp’s participation in GSoC.

We will list projects you can participate here on this page. Students will be able to take part in any of those for the year 2018. It will evolve over the coming days, and will be overseen by [Mrugesh Mohapatra](https://medium.com/u/77e07c28e64f).

**As a student**, this will help you gain experience working on a real world platform that millions of people use each month as they work through our free open source web development curriculum and earn our standardized certifications.

**As a mentor**, you can help students build some substantial projects that will lead to make learning to code a more fun, interactive experience for millions of learners.

---

> **Note:** The mentoring organizations [will be announced by February 12, 2018](https://developers.google.com/open-source/gsoc/timeline). We will update this page as and when more information is available. 

> You can still join us [as a contributor](https://contribute.freecodecamp.org/), regardless of the of our participation in GSoC or your eligibility in the program.

---

### List of Project Ideas for 2018

One of our broader goals is expand freeCodeCamp’s platform functionality and interactive coding challenges. Toward this goal, we plan to building some of the projects below.

Here are some projects we would love to see your proposals on:

#### Project #1: Implementing OAuth 2.0 and universal user management

Our aim is to factor freeCodeCamp’s authentication and user management out of our the interactive learning platform and into a separate service.

This will help us manage our stack and resources much better. For instance, it will allow us to optimize our resource usage during peak loads by scaling them as demand requires.

We plan to:

-   make the authentication independent of our learning platform according to [OAuth 2.0](https://oauth.net/2/)
-   have a universal login that makes the authentication agnostic of sub-domains. This will unify all our resources — such as our forum and blog — into a seamless user experience.
-   allow for third party validation of our accounts, via OAuth 2.0, similar to that of other social platforms like Twitter, Facebook, and Google.

#### Project #2: GraphQL-based open API and management console

We plan to provide a robust API around our vast public datasets. This way we can keep this component separate from our core learning platform.

These datasets include technology topics that are discussed in our chat rooms and forums, statistics on coding challenge completion, and other data commonly used by developers and academics.

Using the APIs, third-party developers can build apps of their own around our curriculum. For example, they could validate the certifications held by our students on their own job platform.

The possibilities here are truly endless.

We plan to:

-   provide a [GraphQL](http://graphql.org/learn/)\-based open API
-   have a management console where we can authenticate and provide developer keys for the API (similar to AWS IAM).
-   add rate limiting to the usage. We plan to provide open data, while being able to afford that economically and securely.

#### Project #3: Real-time pair programming tool

Pair programming is a helpful method for learning programming. We plan to build tools around this, and to make learning to program even more fun.

We plan to:

-   have the ability to pair program with other users of the learning platform by being able to share the code editor collaboratively.
-   get this working on a single page application which is currently a React-based web app.
-   keep this very light-weight, sharing only the essential data among the users. Some inspiration can be taken from [TogetherJS](https://togetherjs.com/) on implementing this.

#### Project #4: Granular statistics dashboard that unifies our various platforms

We plan to build a granular statistics page that will be publicly available. Here we will showcase analytical and statistical data in real time.

We plan to show:

-   challenges which are the most popular over a period of time.
-   how long on average it’s taking people to solve these challenges, and how many attempts it takes them.
-   certifications that are being earned, and users who have earned them.
-   people joining our local study groups, and their demographics.
-   articles, videos, podcast episodes, and forum topics that are trending on our platform.

####   

### Additional projects, that we look forward to.

These are some of the many projects we have slated for 2018. We would be excited to hear any proposals you may have for functionality we can add to the freeCodeCamp platform, too.

Some ideas currently being floated by contributors:

1\. A tool for exporting all challenge solutions to a file directory, which can then be committed to Git.

2\. Interactive streaming with a publicly shared code editor, and audio on our learning platform.

**\[And more…\]**

> You can submit your own ideas, on our [GSoC resources repository](https://github.com/freeCodeCamp/gsoc).

---

> **Note:** This ideas list above is actively being updated as we receive more feedback from the team and community. You can connect with us via the resources listed later on this page.

---

### **Sub**mitting a proposal and getting started

We welcome your proposals for the projects discussed here. And we invite you to share your own project ideas as well.

> While submitting proposals, please follow the template that is available on our [GSoC resources repository](https://github.com/freeCodeCamp/gsoc).

This will help us evaluate your application.

We will do our best to respond to as many proposals as possible.

Once these projects start, we will have Kanban boards on the same repository, so that we can plan features, assign tasks, and track contributors’ progress.

---

You can reach out the mentors and ask questions, seek assistance, and leave feedback throughout the program via the resources listed here.

**Mentors / Organisation Admins for GSoC 2018:**

[Mrugesh Mohapatra](https://medium.com/u/77e07c28e64f)  
[Twitter](https://twitter.com/raisedadead) | [GitHub](https://github.com/raisedadead)  
Email: [gsoc+2018@raisedadead.com](mailto:%20gsoc+2018@raisedadead.com)

[Quincy Larson](https://medium.com/u/17756313f41a)  
[Twitter](https://twitter.com/ossia) | [GitHub](https://github.com/QuincyLarson)

**Links  
**GSoC Home page: [https://summerofcode.withgoogle.com/](https://summerofcode.withgoogle.com/)  
Guidelines and Resources: [https://github.com/freeCodeCamp/gsoc](https://github.com/freeCodeCamp/gsoc)  
Eligibility: [https://summerofcode.withgoogle.com/how-it-works/](https://summerofcode.withgoogle.com/how-it-works/)  
FAQ: [https://developers.google.com/open-source/gsoc/faq](https://developers.google.com/open-source/gsoc/faq)

> **Note:** We will update this section to reflect more changes to information, when applicable.

---

Thank you again for your interest in helping our freeCodeCamp.org with its mission to help people around the world to learn to code for free. If you have any friends who you also think would be interested in helping our nonprofit, we encourage you to share this with them through email or Facebook/Twitter. Thanks, and happy coding!
