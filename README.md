# Software engineering

I reached out a few days ago to find people who need help with software engineering. I found an overwhelming interest in learning about how commercial software development works in real teams. While mentoring people through this process, there are a few things that are going to be common for all projects. This document describes these commonalities.

In this document the reader is going to work through a project they choose. While they develop this idea and go through the software development process, this document should guide them through the different common phases. Every phase will results in an artifact of some sort that can be reviewed. A review will give the opportunity to find mistakes, find oversights and correct the course of the project before too much time is invested in the next phase. Keep in mind that surprises happen all the time; we do not expect to think of everything, but we do try to think of what we can.

## Developing an idea

Before we start on a new project, let's think about the problem we are going to try to solve. This could be "I want to learn C++" or it could be "I want to build a website where users can do X". Whatever it might be, write it down. Create a document of 1 or 2 pages and describe the following:

* What is the goal of the project for you?
  - For this, do not pretend to work in a real company - explain what _you_ want to get out of this. Is it important for you to learn everything very deeply, or are you ok with taking short-cuts to get results faster? Is your main goal to learn something or is your main goal to produce something?
* Who is your customer / who is the user of your product?
* What problem are you trying to solve for your customers
* How are you going to solve this problem?
* What are going to be important features of your product?

This will serve multiple purposes. For you, it will make your idea more concrete; it leads you to think more about what problem you're actually solving instead of just saying "build a website". For the reader of your document, it should convince them that what you want to spend your time on is actually worth it. In a company, your time is precious and it should not be wasted on a project that is unnecessary. Here, you try to sell your idea and make sure you know what you want and what the goal is.

After a review, and depending on how big your project is, you might want to go into more detail. Sometimes you need to prove that your idea would actually solve the problem (e.g. is it actually feasible to solve this problem with the current technology?). A reviewer will work with you to find out if this is necessary.

## Choosing a minimal viable product

Based on the idea in your previous document, it's time to bite off a chunk that can be solved in a reasonable amount of time. Here we try to solve a part of the problem and get something useful out as early as possible. This has multiple goals:

* Your customer will get something they can work with earlier.
* You'll be forced to change your code later once you want to extend your product.

Especially the second part is the actual hard thing in software development. Writing code is easy; writing code that is maintainable, testable and changeable without driving you insane is very, very hard.

Write a document where you describe your MVP product in some detail. It should cover the following:

* How does your product look and feel for your customer?
  - Include a mock-up (sketch drawing) of your user-interface if applicable.
* What are the features you absolutely need to have a useful product (the fewer features, the better).

Based on this, the rest of the process will work towards implementing this small project in a sound way. It will include design, planning, coding, reviews, testing and deployment. After that's done, we'll go into a cycle of adding features, testing, deploying. This will cause your product to incrementally grow in features and complexity.

## Fleshing out a design

After your idea document is reviewed, it's time to think more detailed about how to solve the problem. Here, you create a new document that solves the problem you describe in your idea document. You choose technologies and try to argue why this technology choice is correct. Reasons could range from "It's what I know" or "It's what I want to learn" to "This is the best tool for the job because it has shown to have the lowest latency". This document includes:

TBD
