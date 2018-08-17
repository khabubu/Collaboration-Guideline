# Code Collaboration Guideline #

# Code Review Guidance #

## For Reviewers ##
1. Be kind. Yes, a person is not their code, but writing code is a creative act. Creators are by nature intimately involved with their creation. You're going to be critiquing another person's creation, at a minimum, be kind when you do it. Better yet, find positive as well as negative things to say. We want both the code and the coder to be better once you're done; don't make it easy to reject your constructive observations by being a jerk about it.

1. Ask questions, learn. Regardless of whether you're an experienced developer reviewing someone's code for an annual review or a beginning developer doing a peer review of your lead developer's pull request, you should approach a code review as a way to learn. This is especially true if you're doing a review for someone's annual technical evaluation. Those code reviews are more about the conversation than the code itself.  If you're not asking questions, you're probably doing it wrong.

1. Focus first on correctness, then on readability and understanding. Does the code solve the right problem? Is there a way to solve the problem without writing code? Is this code solving the problem correctly in the given context. Once you're satisfied that the code is correct, ask yourself if it's expressed in a way that is readable and understandable. Is there a simpler, more obvious way to communicate what the code is doing and why?

1. Remember context is more than just the particular technical requirements - consider all the constraints under which the code was developed - time, deadlines, team capability, future work. Unless it's clearly an error, your best course of action when you find something that seems "wrong" is to ask questions. What led you to this implementation? Why choose it over <insert "right" alternative>?

1. Encourage the use of tools. Ideally you shouldn't be commenting on anything that can be enforced by a code analysis tool. If you find yourself making a lot of these observations, your conversation should be about using the tooling, not about the code. Solve the root problem.
