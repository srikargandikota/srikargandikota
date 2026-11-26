<picture>
  <source media="(prefers-color-scheme: dark)" srcset="header-dark.svg">
  <img alt="Srikar Gandikota, Computer Science with minors in Linguistics and French at Georgia Tech" src="header-light.svg" width="100%">
</picture>

Most of what is here started as a specific problem in my own routine that I decided to build my way out of, and each repo's README goes through the design decisions, so this page covers where the ideas came from and what I took away from them. I have ordered the projects by impact.

### [spendwise](https://github.com/srikargandikota/spendwise) · Java, Android, Firebase

SpendWise is a personal finance app for Android that I built with four teammates over a full semester, and it grew from a login screen and some placeholder pages into an app with an expense log, category budgets, group savings circles, spending charts, budget notifications, and an AI chatbot. My part of it was the expense log, the budgets page, and the calendar date selection that both of them run on, and later the profile page with its user statistics. I also wrote the unit tests that kept each piece from breaking whenever someone else merged. We ran everything through Jira and pull requests. By the end the repo had passed 160 of them, and a lot of my time went into reviewing teammates' work and making sure our pieces actually fit together; I learned that most of the work on a team product happens between the features rather than inside them.

### [playlister](https://github.com/srikargandikota/playlister) · React Native, Node/TypeScript, Postgres

Playlister is a full-stack Spotify companion app, and the idea came from watching my own playlists go stale, because I would build a "study vibes" playlist in September and abandon it by November once it stopped matching how I actually listened. I sort music in my head by tags like chill, hype, and late-night, and those do not expire the way a playlist does. So the app syncs your whole library, tags every track by key, mood, and energy on its own, and lets you add your own tags on top. From there, `play chill study` builds a fresh queue of tracks tagged both chill and study, `queue any hype workout` relaxes that to either one, and a plain-language request like "something mellow for a rainy Sunday" gets mapped onto tags you actually have. It also recommends songs and playlists from your own library, ordered so neighboring tracks sit in compatible keys. The part I enjoyed most was designing the small command grammar and figuring out how to compile it down to a single parameterized SQL query.

## Elsewhere

Outside of these repos, most of my work has landed on the part of a product that sits between the people using it and the engineers building it, and the through-line is figuring out what a group of people actually needs and then making sure it ships.

As an AI/ML technical program manager intern at Qualpa, I led a zero-to-one program to ship customer-support AI agents for retailers, and I coordinated engineering on the agent harness and its eval loops until the resolution rate reached 90%, and the agents ended up automating 70% of support tickets. I scoped client requirements across more than 15 iteration cycles to keep engineering and stakeholders aligned on what we were shipping. As lead student researcher on the BCG x Georgia Tech Entrepreneurial Capitalism Initiative, I managed 4 researchers who produced 13 industry briefs in 6 weeks on how corporates partner with startups, and I presented 2 readouts in biweekly reviews with BCG that expanded their 9-mode partnership framework.

At the GT MATRIX Lab, I design a makerspace dashboard in Figma, and I had to reconcile requirements from students, assistants, and admin before the 7 audience views came together. I also built its live equipment queue, which meant working with the developers of Georgia Tech's equipment system on a new API that could return a whole queue at once. Before that, I worked in two research labs. One mapped dialect variation and accent leveling across more than 300 speakers, where I applied normalization to speech-to-text pipelines to reduce bias against underrepresented accents, and the other studied corporate layoffs, where I set up an LLM pipeline to pull statistics out of more than 250 sources. I also help run international academic competitions, where I built a Python tool to arbitrate more than 600 results in real time, and as director of special events for Alpha Kappa Psi I owned a $3.7k budget for a 102-person formal.

I study computer science at Georgia Tech with minors in linguistics and French, and I graduate in May 2028.

**Tools I reach for** · Python, Java, TypeScript, SQL, React Native, Node, Firebase, PyTorch, scikit-learn, Figma, Jira

[LinkedIn](https://www.linkedin.com/in/srikar-gandikota/) · [Email](mailto:sgandikota9@gatech.edu)
