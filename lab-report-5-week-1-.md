How I found tests with different results is that I manually found these differences. I ran random test files in the markdownparse repository from lab 9. 
Once I found a test file that didn't give an empty output, I copied that file to my own markdownparse implementation to see if there is a difference in outputs. Some tests weren't able to be cloned into my ieng6, so instead, I used vim editor to create a new file to put in the test that wasn't cloned.

[Link to test first file with different results](https://github.com/nidhidhamnani/markdown-parser/blob/main/test-files/194.html.test)

## Test 1
My implmentation is correct because it gave an empty list of links since this test file has no links in it.

Output for my implementation:
![myoutput1](myoutput1.JPG)

Output for LAB9 implementation:
![output1](output1.JPG)

Expected output should be [].

[Link to second test file with different results](https://github.com/nidhidhamnani/markdown-parser/blob/main/test-files/487.html.test)

## Test 2
LAB9 implementation is correct because it gave a an empty list which it should result in since a space in a link makes it not a link.

Output for my implementation:
![myoutput2](myoutput2.JPG)

Output for LAB9 implementation:
![output2](output2.JPG)

Expected output should be [].
