[Link to my repository](https://github.com/nbilog/markdown-parser)

[Link to repository I reviewed](https://github.com/NLChung9/markdown-parser)

Output of snippet 1: ['google.com, google.com, ucsd.edu]

Output of snippet 2: [a.com, a.com(()), example.com]

Output of snippet 3: [https://www.twitter.com, https://sites.google.com/eng.ucsd.edu/cse-15l-spring-2022/schedule, https://cse.ucsd.edu/]

Code in MarkdownParseTest.java: ![junit](junittestss.JPG)

For my implementation:
* snippet 1: Test did not pass, ![mytest1](mytest1.JPG)
* snippet 2: Test did not pass, ![mytest2](mytest2.JPG)
* snippet 3: Test did not pass, ![mytest3](mytest3.JPG)

For reviewed code implementation:
* snippet 1: Test did not pass, ![review1](review1.JPG)
* snippet 2: Test did not pass, ![review2](review2.JPG)
* snippet 3: Test did not pass, ![review3](review3.JPG)

Question 1: I think there is a small code change that would make my program work for snippet 1. The code change would be to make it so that if there is an apostrophe before a bracket, do not count the indexes of the brackets until there is another apostrophe to end the string. After those apostrohpes and there is a bracket after, then count that bracket and get the links.

Question 2: I think there is a small code change that would make my program work for snippet 2. The code change would be to make it so that if there is another left parethesis in the link, it would have to count that as being part of the link name. The code would have to then reach until the last parenthesis in which it would not count that last one, but the other parenthesis before that.

Question 3: I think there isn't a small code change that would make my program work for snippet 3 as it would need to be a more involved change. The reason is that my code would need to make it so that the link names do not count the extra spaces between the link name and a parenthesis. It would also need to make it so that if there is no closing parenthesis, then the code shouldn't run through that link and skip to the next lines where there is a starting bracket or parenthesis. Since there was no closing parenthesis, my code kept running until there was an end parenthesis, making the link name be the extra text in the file.

