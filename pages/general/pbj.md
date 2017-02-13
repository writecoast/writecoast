---
layout: page
title: The PBJ test
permalink: /pbj/
categories: []
tags: []
status: publish
type: page
published: true
---
## My answer

When hiring technical writers, one of the tests employers like to give is the PBJ test: "Write a procedure for making a peanut butter and jelly sandwich." This is not so much a writing test as a personality test. How will you react to the lack of context given, like the audience or business purpose? How much of a literalist are you? What assumptions will you make about prior knowledge? How deep will you dive into the cultural knowledge required for the task? Do you use parallel construction? And will you make any tpyos?

My take on this test is that the simplest answer is best.


**How to make a peanut butter and jelly sandwich**

1. Spread peanut butter evenly on one side of a slice of bread.
2. On another slice of bread, spread jelly evenly on one side.
3. Stack the slices (peanut butter side against jelly side) to form the sandwich.

## Rationale
Writing this procedure only took a few minutes, but behind that was a lifetime of experience.

Let's start with some context. In this case, I was responding to a pre-employment screening test from a Silicon Valley IT company. So I wrote a completely different procedure than I would write if I were (for example) writing for a children's cookbook, or for school cafeteria workers, or for a non-US market (<a target="_blank" href="http://www.huffingtonpost.com/2014/04/09/peanut-butter_n_5105203.html">reportedly</a>, peanut butter is not a familiar food outside the US).

### Re-use
Especially in Silicon Valley, open source code is used frequently and highly valued. So my first thought was to copy the procedure from the best available source on the Internet. <a target="_blank" href="http://www.wikihow.com/Make-a-Peanut-Butter-and-Jelly-Sandwich">More complete PBJ procedures</a> have already been written. In a real-world production situation though, I would probably be discouraged from reinventing the wheel for a well-known and obvious procedure. But the requirement was for me to write it myself, so that's what I did. I was tempted to adopt an open-source solution, but I didn't think it was wise to commit plagiarism on a job application.

### Requirements

The verbatim requirement was this:  
<blockquote>
<ol>
<li>Complete a short writing exercise. </li>
<ol type="a">
<li>Please create a procedural document that explains how to make a peanut butter and jelly sandwich.</li> 
<li>The purpose of this exercise is to get a standard writing sample.  Please do not spend more than an hour or so writing this document. </li>
</ol>
</ol>
</blockquote>

There is a tremedous amount of ambiguity and missing information in this requirement. But that's OK, because I have plenty of experience resolving ambiguity and finding missing information. And isn't that the point of the test?

### User story
The requirement suggests a <a target="_blank" href="https://www.agilealliance.org/glossary/user-stories/">user story</a>, but leaves out some important information. In Agile, user stories are often in the form:

As a *\<type of user>*, I want *\<some goal>* so that *\<some reason>*.

But from the requirement, all we know is the goal. We don't know the user's role, or why they want to make a sandwich. Since clarification is not an option, some assumptions are in order.

The real user story is:

As an IT employer, I want a writing sample, so that I can screen an employment candidate.

I know that as a candidate, I have to respond to the stated requirement, while keeping the real user story in mind. Which is a very common real-world scenario.

### Cultural assumptions

I assumed the reader is familiar with sandwiches, sliced bread, and how to spread a viscous substance. The procedure does NOT specify a tool to use for spreading the peanut butter or jelly, or what kind of jelly to use, or whether to cut the sandwich, or options for enhancements like additional fillings. Nor does it specify to wash your hands before beginning. The reader is assumed to have this knowledge. 

### Scope

I wanted to be responsive to the requirement, so I had to consider what was meant by "procedural document" and whether it was different in scope from a "procedure." The requirement created some ambiguity - does a "procedural document" contain more information than a "procedure?" In a production situation, I would research to clarify what the customer expected. But for this test, clarification was not an option. So I made the assumption that a "procedural document" was a simple procedure. The one-hour time limit for the test suggested that more information was not expected. 

## Testing

My procedure passed QA, and the sandwich was delicious.


## Deployment

My first thought was to deliver the response as a Word document attached to an email. But then I considered the context and the audience, and I realized I'd rather post it on my GitHub site using <a target="_blank" href="https://github.com/jekyll/jekyll">Jekyll</a> (the native GitHub documentation platform).

## Conclusion

I'd like to thank the employers who thought well enough of me to give me this test, and I am looking forward to hearing from you soon! 