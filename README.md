# Leetcode-1220-Hard-DP
Leetcode 1220, a hard DP problem. To me, it is not hard, the patterns behind is quite easy to find if you draw a table. Also, the given hint helped a lot. A bug I encountered is how to initialize the 2D dp table. When using [0,0,0] * n, the sublists are not independent and change in one of them will affect the whole table, so using a for loop is recommended.

In the end, I learned from a solution, not the dp part but the set up part. That is coding, where problems can come from everywhere, the essential part or seemingly easy part.
