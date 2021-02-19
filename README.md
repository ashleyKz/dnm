# Analysis & Design of An Algorithm – Zigzag Conversion

In this article, we develop the optimum algorithm for the [Zigzag Conversion](https://leetcode.com/problems/zigzag-conversion/) problem and analyze its complexity. We use as little technical terminology as possible in doing so. We develop the algorithm in Java. 

The problem is described in full on [Leetcode](https://leetcode.com/problems/zigzag-conversion/). Just to refresh – a zigzag of letters is constructed by lining them up in vertical blocks towards South, and in diagonal blocks towards North-East, repeatedly until all the letters in the input String are used up. The North and South corners of the zigzag are all at the same horizontal levels each, and the height of zigzag, i.e. the number of rows between its North and South ends is part of the input to this problem. 

So the input is two parts – the number of rows as an __`integer`__ and a sequence of characters as a `<String>`. We’ll refer to these two parameters as numRows and str respectively. Both inputs are fixed for a specific problem instance, i.e. their values don’t any change throughout the solution process. In this text, we’ll use the following problem instance for example purposes:

**L**|**0**|**1**
-- | --| --
0 | A | 
1 | B |
2 | C |
3 | D | F
4 | E |


```{r, attr.source='.numberLines'}
if (TRUE) {
  x <- 1:10
  x + 1
}
```
