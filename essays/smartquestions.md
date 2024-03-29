---
layout: essay
type: essay
title: "The Art of Asking Smart Questions"
# All dates must be YYYY-MM-DD format!
date: 2024-01-24
published: true
labels:
  - StackOverflow
  - Python/JavaScript
---

# The Art of Asking Smart Questions

In the ever-changing and dynamic world of Software Engineering, one thing remains constant: 
Effective communication is crucial to successful collaboration within software engineering.
One way this manifests is in the art of asking smart questions. You may have heard of the term,
“There is no such thing as a dumb question,” which may be true, but there are ways to better express
questions using tools you already have at your advantage. Giving more information, being precise and
informative about your problem, checking other resources such as Google, and describing your problem's symptoms and 
not your own, are all some techniques mentioned by Eric Raymond in his guideline article about asking questions in a “smart” way.

To set the record straight, the term “smart” isn’t meant in a literal way; you don’t need to be a 
rocket scientist with multiple PhD’s to be qualified to ask a smart question. Asking a smart question 
comes from the techniques and information you are supplying within your question, how you are presenting 
your question, and if your question is applicable and solvable with the information you’ve given. 
They are not merely a formality but a pathway to efficient problem-solving, knowledge-sharing, and contributing 
to a positive community atmosphere. Software developers face complex challenges, and the ability to articulate 
questions thoughtfully can significantly impact the quality of assistance they receive.

To highlight the difference between a smart question and a question that may lack “smart” techniques, 
I’ve delved into every developer’s thought-provoking playground, StackOverflow. In a question posed by one 
of its users, they asked, “How do I not show empty arrays?” followed up with a copy of their code, and then 
nothing else. Of course, the question has one downvote, 11 views, yet no replies. While a valid question, 
an immense amount of details are missing from their question. What are they trying to use the array for? 
What framework or IDE are they working with? What have they tried so far? Have they tried to google this, 
or look into similar or verbatim questions on StackOverflow or other forums? Even recomposing the question 
may have helped them to receive tips and help from other users. By simply adding more background information 
about their issue, they could easily get the answers they need, and it all stems from how they proposed their 
problem. It is important to note that while this kind of question and issue may be answered by AI, when you 
are asking other developers and programming enthusiasts, it would significantly help people to help you with
your issue if you add as many details necessary to solving the problem, instead of posing the question in the 
most simplest way possible, giving others your code as if they will fill in the missing information themselves, 
such as AI usually does. As noted by Raymond in his article, “How to ask questions the smart way,” some of 
his techniques to be precise and informative about your issue include, describing the symptoms of your problem
or bug carefully and clearly, describing the environment in which it occurs (machine, OS, application, whatever,
and describing the research you did to try and understand the problem before you asked the question, all of which 
the user did not mention or include in presenting his problem. Adding these simple, yet effective techniques into
your proposed question could easily change the outcome of your solution and allow others to feel more confident about
helping you, knowing that they now have an efficient amount of background information about your issue to help you. 

[StackOverflow - How do I not show empty arrays?](https://stackoverflow.com/questions/77876539/how-do-i-not-show-empty-arrays)

Now, let’s look at a smart question posed with some of Raymond’s proper techniques
and presented with ample information to be solved. The question discusses a common
issue in Python related to default mutable arguments. Within the question, the author
provides a clear and concise description of the issue. They present a Python function 
foo with a default mutable argument, and they highlight the unexpected behavior when 
calling the function multiple times without providing a parameter. He describes his environment
clearly as well, by stating that the issue is common amongst  developers who work in Python, which
suggests a wide applicability of the problem. The specific code snippet and its behavior are presented,
providing the necessary context for understanding the problem. Additionally, the author describes his
efforts in researching the issue and resolving it on his own: they share a dialogue with a manager who 
considered it a "dramatic design flaw," indicating an attempt to seek understanding which also allows 
potential responders to see a different perspective from someone who already shared the issue with someone 
within their workplace. The author explores a related example presented by another user, showcasing an effort
to elaborate and investigate the problem further, and also present his solution in an edit of the post to all 
the contributors who were interested in how to solve the issue. While the user could make more efforts to describe
his errors and give more information, they provided ample information to attract contributions and resolutions to his
problems. Had he not, he would’ve had a more difficult time trying to obtain help from others. 

[StackOverflow - Least Astonishment and the Mutable Default Argument](https://stackoverflow.com/questions/1132941/least-astonishment-and-the-mutable-default-argument)

While the first example of a question lacking in Raymond’s smart techniques does not have any responses,
I found that the responses in the second example were very helpful, clear, supportive, and actually answered 
the user’s questions in various ways. The response provides a thorough explanation of why default parameters 
in Python are bound at function declaration rather than function execution by using various examples, starting 
by addressing the user's assumption about default parameters, using the example of the fruits. Additionally, 
the responder goes beyond addressing the Python-specific case and broadens the discussion to mutable variables
in various programming languages. The inclusion of a Java example with a Map and StringBuffer illustrates that
this issue is not unique to Python, providing a broader perspective. By sharing insights into the challenges 
with mutable variables in other languages, the response helps the user understand that the issue is a common one in programming. 
The responder acknowledges the possibility of special-casing using an empty list but explains the potential downsides,
such as causing more astonishment and backward incompatibility. This consideration demonstrates a thoughtful analysis 
of potential solutions and their implications. 

While comparing and contrasting the two very different questions posed on StackOverflow,
seeing the vast differences in responses between the two allowed me to understand just how 
significant and important it is to provide your audience with sufficient and necessary information that could
lead to them helping you and providing clear answers to your questions, that actually help you to gain an understanding 
of how to fix your issue and understand where you went wrong. By following the smart techniques and elevating your question, 
you avoid people ignoring you or being hesitant to answer because they don’t want to keep following up with more questions
that they need to solve

