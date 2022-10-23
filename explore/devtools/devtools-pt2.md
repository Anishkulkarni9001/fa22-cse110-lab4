# Part 4 - Solutions

1. Here, the bug was an issue of data types - the inputs to the document were both string values, so when the code tried to add the two together, it wound up concatenating strings instead of adding numbers, giving a wrong output.

2. The fix I used is simple - call the 'parseInt()' method in the 'calculateSum' section to read the two inputs as integers rather than strings. Then, adding the two leads to regular numerical addition, and gives the desired output. 

![Image](explore/screenshots/fix.png)
