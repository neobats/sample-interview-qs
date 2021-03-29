# SBI Technical Interview Questions
## General
Some questions you’ve probably already thought of, but ones that I would consider asking anyways:
* nothing here (yet?)

## Front-end
1. Of the things you’ve built with JavaScript frameworks/libraries, which is your favorite? Tell me about that project and what made it so memorable.
	1. Here you’re looking for words like “React”, “Angular”, “Vue”, or “Svelte”. If you hear something about jQuery as the favorite, that’s probably a red flag. Definitely a yellow flag.
	2. I’d be watching for _how_ they describe their work, as much as _what_ they built.  As is probably already known: you need someone who can break down technical jargon.
	3. The size of the app matters. The favorite app might be small, so if it is, make sure to ask this next question.
2. What are your favorite and least favorite parts of implementing a designer’s ideas?
	1. This is definitely a soft skills question, so I’m not going to suggest much. But it’s a good question to ask anyone expected to do front-end development.
	2. If the person likes CSS (the language used for styling the web), and they can demonstrate examples of complex CSS work, that’s a big plus… but only if they’re proficient elsewhere too. The dev who loves CSS and backend is a 🦄.
3. How do you feel about TypeScript (TS)? 
	1. Good answers will provide some of the following as positives: code & type safety, abstract data types (and/or object-oriented design & inheritance), certainty in coding, type-driven development.
	2. Great answers will include negatives, and could mention any of the following: hurdles to speed of development, overkill in small projects (maybe, deserves some explanation), painpoints when working with native APIs (if they say something about the DOM, that’s a common frustration).
	3. Unfamiliarity with TypeScript is a red flag. We lean really heavily into it with this project.
4. This article is worth reviewing: [10 Interview Questions Every JavaScript Developer Should Know | by Eric Elliott | JavaScript Scene | Medium](https://medium.com/javascript-scene/10-interview-questions-every-javascript-developer-should-know-6fa6bdf5ad95)


## Architecture
1. What is the most complex project you’ve seen or worked on? What made it complex? How would you reduce that complexity?
	1. This is obviously a loaded question. The last part assumes that the candidate will know how to simplify a complex problem.
	2. Watch for typical bad candidate things: passing blame on others, etc. If the candidate can’t identify something concrete in the project that was complex, this is a **big** red flag. You don’t have to understand what made it complex, necessarily—but it needs to be concrete.
	3. Some good solutions to complexity may include: 
		1. finding or leveraging known solutions (this could be a third-party tool, a documented algorithm, or something like that).
		2. Separating concerns.
		3. Words/phrases that might be good indicators of strong problem solving: Backtracking, Divide-and-Conquer, Breadth-first, Depth-first, Greedy, Branch & Bound, Dynamic Programming. These are all different “families” or “paradigms” of algorithms.
2. What’s your dream tech stack? (<- This isn’t a great question, but it could give you good insights. Lowest priority in questioning)
	1. “It depends” is probably a really good answer here. Another non-answer that could be really good is “I don’t think it matters that much.” Or “What’s the problem we’re solving?”
	2. Anything that sounds old isn’t an automatic out. But the ideal candidate would enjoy what we’re using. See the next point.
	3. Stuff we’re using that would be a plus: React, TypeScript, Node, serverless functions, Postgres, SQL.
	4. Some indications of a robust approach to architecture would include:
		1. Test-Driven Development, CI/CD (Continuous Integration, Continuous Deployment), Containers (Docker)
3. It’s your first day on the job, and you’re able to get into the codebase. What’s the first thing you want to do?
	1. Some possible good answers: Run it, Look at the tests, Refactor (a critical response to old code is a red flag. But refactoring is a good thing taken with the right attitude), Get a walkthrough with Crema, Make contributions, Set up the “Pipeline” (CI/CD), Break it.
4. (Based off the last question) At the end of the day, what will you know about the codebase?
	1. Again, a loaded question. This assumes the candidate has lived in unfamiliar codebases before, and knows what to expect.
	2. Any answer that shows some sort of contribution is a good one. “Nothing” isn’t automatically a wrong answer, but should be probed.
	3. “The tech stack” or [insert some programming language] is a poor answer.
