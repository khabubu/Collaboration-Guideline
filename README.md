# Code Collaboration Guideline #

# Code Review Guidance #

## For Reviewers ##
1. Be kind. Yes, a person is not their code, but writing code is a creative act. Creators are by nature intimately involved with their creation. You're going to be critiquing another person's creation, at a minimum, be kind when you do it. Better yet, find positive as well as negative things to say. We want both the code and the coder to be better once you're done; don't make it easy to reject your constructive observations by being a jerk about it.

1. Ask questions, learn. Regardless of whether you're an experienced developer reviewing someone's code for an annual review or a beginning developer doing a peer review of your lead developer's pull request, you should approach a code review as a way to learn. This is especially true if you're doing a review for someone's annual technical evaluation. Those code reviews are more about the conversation than the code itself.  If you're not asking questions, you're probably doing it wrong.

1. Focus first on correctness, then on readability and understanding. Does the code solve the right problem? Is there a way to solve the problem without writing code? Is this code solving the problem correctly in the given context. Once you're satisfied that the code is correct, ask yourself if it's expressed in a way that is readable and understandable. Is there a simpler, more obvious way to communicate what the code is doing and why?

1. Remember context is more than just the particular technical requirements - consider all the constraints under which the code was developed - time, deadlines, team capability, future work. Unless it's clearly an error, your best course of action when you find something that seems "wrong" is to ask questions. What led you to this implementation? Why choose it over <insert "right" alternative>?

1. Encourage the use of tools. Ideally you shouldn't be commenting on anything that can be enforced by a code analysis tool. If you find yourself making a lot of these observations, your conversation should be about using the tooling, not about the code. Solve the root problem.

1. Use a checklist. Don't make it up every time you look at code. Have a mental if not a written checklist of things you need to look at.

1. Provide actionable feedback. Do not just criticize but provide a way forward.

1. The way you would do things is not the standard. In a code review you're not checking to see if the code was done the way you would do it, but whether it's correct and fit for the purpose along with all the "ilities" - readability, maintainability, etc. There are lots of ways to solve a problem. It's helpful to talk about how you might do it differently, but it's not necessarily "wrong" just because the submitter did it a different way. Again, learn from each other — use a different implementation to help refine your own thinking as well as the submitter.

1. It's ok to not find anything to correct. Be thorough, but don't be picky. Your code review can consist of purely positive comments if there's really nothing to fix.

1. What happens in the code review, stays in the code review. Treat a code review like you would a personnel matter. Generally what you discover is private between you and the submitter. Occasionally, you might share it with others on a need-to-know basis — to complete a performance review or provide advice to a project lead on who should take on a particular task, for example. Reviews shouldn't become the subject of office gossip.

## For Submitters ##

1. Provide context. Help the reviewer by giving them an idea of how your code fits into the overall program. Explain any decisions that might go counter to the way you would normally do things. Help the reviewer understand the constraints under which the code was developed. If your code was in reference to a ticket, provide a link to the ticket along with the code.

1. Use good commit messages. This provides a good source of information on intent and context for future readers, including code reviewers (and future you, when you revisit the code). Good commit messages are both clear and concise. If you must, error on the side of clarity, not brevity but don't write a novel or even a short story. If you feel like you'll need more information later, that's a good sign that the information belongs in your README.

1. Keep the amount of code you're submitting for a review relatively small. This is true when using Pull Requests for reviews as well. Features should be small and targeted so that all the code can be reviewed. Long-lived feature branches with dozens or hundreds of changes have their own problems for code quality and integration. Guidelines: ~5 files, 300-600 lines of code, a day's worth of work, 20-60 minutes of code review time. If you have more than this, consider splitting it up.

1. Your code should be complete, self-tested, and self-reviewed. If your code doesn't build or doesn't pass the tests, if any, don't submit it for review.

1. Don't take it personally. Having your code reviewed is a good thing. It will help you get better and will help us deliver a better outcome for the client. If future you reviewed your code from today, I would hope that you would find areas that you could improve. That a more experienced developer might find things that you could do better will help you to grow faster by leveraging their experience in addition to your own.

1. Keep it positive. This isn't the time to get defensive. Assume that the person reviewing your code is trying to be helpful. You don't have to agree with all the feedback you get. You might have to do things differently if the review is by your project lead, but that doesn't necessarily mean you were wrong. Even the best of us occasionally mistake personal preference for correctness. Do your best to set aside your own ego and understand the perspective of the reviewer, especially if that person is more experienced. Sometimes the naive, obvious way holds pitfalls that only someone who has a lot of experience knows to avoid.
