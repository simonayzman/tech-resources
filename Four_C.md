## The 4 C's of Effective Technical Interviews

So, the interviewer has given you a technical programming problem. Right off the bat, it feels hard. You've never heard or seen the problem before. Your mind is racing. The empty whiteboard or page in front of you is begging to be filled. How do you proceed?

You pause. And you remember the four C's. A basic formula for answering these sorts of programming questions asked in technical interviews. In order, you remember that they are (1) **Clarify**, (2) **Construct**, (3) **Code**, and (4) **Confirm**.

#### Clarify
_Clear up any confusion and resolve any ambiguities in the problem given to you._ Pause and think. The question the interviewer actually wants you to address might be simpler than you originally supposed. However, even simple questions might have tricky cases or situations. An oversimplified understanding of the problem will bite you later. Either way, assumptions can seriously hurt you. Clear them up as early as possible. It's also good to mention if you've seen the problem before, even if you're not completely sure about the solution.

This step should take betweeen one and three minutes.

#### Construct
_Create a strong foundation for an algorithm that solves the problem._ Before even a single line of code gets written, achieving clarity (for the interviewer, and **especially** for you) about a solution is the key to success. Start off by providing the simplest, brute force solution to the interviewer (if it exists). Be sure to explain why it's probably not the best algorithm using Big-O complexity analysis. Often, the interviewer will agree with you and say that it's not good enough, and wants a better algorithm. However, in certain circumstances, the interviewer won't necessarily want you to implement a better solution, so they'll allow you to go forward with the brute force solution.

If not, the next step will be to discover the more optimal solution. This requires you to find a key insight or recognize a pattern from other problems you've previously solved. If you don't come up with one relatively quickly, a good approach is to create examples or formulate test cases for the problem. Bringing up tests early shows that you care about resilient code, not just working code. It helps you see things about your problem that might not normally be clear when you're thinking in your head. Diagramming is your best friend! Coming up with test cases also provides an additional benefit--if you're stuck, it provides excellent stalling time!

Once you have a solution, explain it thoroughly, using your examples if necessary. Perhaps even provide complexity analysis without prompting. Make sure you and the interviewer agree on (and understand!) the solution before proceeding to the next **C**. The most important thing about this entire step is communication. Talk out loud! It shows the interviewer your thought process. This is just as important as writing good code. There might be a lot going on in your head, but if you're stuck and quiet, that helps neither you nor the interviewer. If the interviewer really see that it's necessary, they may give a hint.

Ideally, this whole step should take betweeen three and eight minutes.

#### Code
_Translate the algorithm into (relatively) clean code._ The key to being comfortable here is to fully understand what your solution is. Moreover, doing a lot of practice problems where you actually code and don't just mentally answer the question is super helpful for not freezing up during a real interview.

Some DO's:

* If you forget an official library function name, simply make up a name for it and mention that you've forgotten it, but that you know it exists.
* If you want to use a helper function that "accomplishes" a certain step for you, ask if you can assume it exists and offer to implement it later if necessary.
* Leave yourself space between your lines of code, especially at the beginning of a function; you'll almost certainly realize that you forgot to include something midway through your implementation.

Some DO NOT's:

* Don't talk **too** much. We've gotten through the hard part already of creating and explaining an algorithm. At this stage it's ok to explain the part of the algorithm that some code line/block refers to, but re-hashing a complete version of your earlier explanation takes up valuable time. I tend to talk less than I would during the **Construct** phase, but I definitely don't stay completely silent. Some interviewers like it when you explain during this step; others do not. Either way, it depends on the interviewer, so gauge what you can from body language and their responses to you.
* Don't write in pseudocode, but provide code comments where necessary. We've already explained the solution verbally, so pseudcode here will only slow you down and take up time.

Ideally, this whole step should take between five and ten minutes.

#### Check
_Check and test your code for correctness._ Once you're done writing code, give it a quick look-over. This is just a rudimentary check for basic syntax errors and any blanks that you promised to fill in. Then, do a second check that's more in-depth. Trace through your code. Offer to run it against the test examples that you created earlier! This may not always be necessary, but it shows that you care about correctness. If you find bugs, don't panic and don't change the code willy nilly. Take some time to think about the issue and then fix it once you understand where it went wrong. Finally, when you feel confident that your implementation is solid, you can declare that you're done. Sometimes, you may still have missed something. The interviewer could bring this up in a variety of leading and non-leading ways. Either way, follow the same policy as before. Don't panic and don't change the code brazenly.

This step should take between three and eight minutes.

#### Afterthoughts

The interviewer might feel fully satisifed with the way you completed the problem. In fact, they might take it as an opportunity to challenge you even further and add new constraints to the problem that they didn't mention before. This is a good sign! They think you're capable enough to push you harder. They may not expect you to augment your previous code or add new code, but at least, they'll want to discuss it as a thought experiment. Sometimes, though, this can actually segue into a totally new, but related problem. Take it in stride and tackle it from the beginning of the four C's.

Understand that, at the end of the day, no matter what the interviewer asks you, they know a lot about their problem. A lot. They've asked it many times before. They know how candidates approach the question. They know how to simplify it and how to complicate it. They know where you'll likely get stuck and they know when to jump in with a hint. They know when to let you stew without any help because even with that deafening silence, they know when you can solve it without their guidance. Practice, learn from your experiences (especially the failures!), and do better next time! Good luck!
