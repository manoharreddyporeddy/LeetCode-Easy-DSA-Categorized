# LeetCode-Easy-DSA-Categorized

# All LeetCode Easy Problems Categorized by DSA Pattern

---

Categorization is one of the most effective ways to learn DSA.

Learn a pattern, then solve multiple problems that use it. This reinforces understanding and develops pattern recognition.

When learning a new pattern, Easy problems are usually the best starting point. Once the pattern becomes familiar, it's much easier to tackle Medium and Hard problems. That's the purpose of this post.

---

This post categorizes all 630 LeetCode Easy problems as of June 2, 2026 into a hierarchy, **most specific → most general**:

1. **Specific data structures / techniques** — `LinkedList`, `Tree`, `BST`, `N-ary Tree`, `Stack`, `Queue`, `Heap`, `Matrix`, `Simulation / Implementation`, `Design`, `Sorting`, `Binary Search`, `Two Pointers`, `Sliding Window`, `Prefix Sum`, `Math`, `Bit Manipulation`, `Recursion`, `Greedy`, `DP`.
2. **`Set` / `Map`** (hash-based) — used when no specific data structure or technique applies, but the optimal solution needs a hash set or hash map.
3. **`Array`** — fallback for general array problems.
4. **`String`** — final fallback for general string problems.

The primary technique is the one that _defines_ the solution; secondary uses (e.g. an array used inside a hash map problem) are ignored.

---

## LinkedList (8)

1. [Middle of the Linked List](https://leetcode.com/problems/middle-of-the-linked-list) - LC 876
2. [Reverse Linked List](https://leetcode.com/problems/reverse-linked-list) - LC 206
3. [Merge Two Sorted Lists](https://leetcode.com/problems/merge-two-sorted-lists) - LC 21
4. [Palindrome Linked List](https://leetcode.com/problems/palindrome-linked-list) - LC 234
5. [Intersection of Two Linked Lists](https://leetcode.com/problems/intersection-of-two-linked-lists) - LC 160
6. [Remove Duplicates from Sorted List](https://leetcode.com/problems/remove-duplicates-from-sorted-list) - LC 83
7. [Remove Linked List Elements](https://leetcode.com/problems/remove-linked-list-elements) - LC 203
8. [Linked List Cycle](https://leetcode.com/problems/linked-list-cycle) - LC 141

## Tree (24)

9. [Find a Corresponding Node of a Binary Tree in a Clone of That Tree](https://leetcode.com/problems/find-a-corresponding-node-of-a-binary-tree-in-a-clone-of-that-tree) - LC 1379
10. [Root Equals Sum of Children](https://leetcode.com/problems/root-equals-sum-of-children) - LC 2236
11. [Binary Tree Inorder Traversal](https://leetcode.com/problems/binary-tree-inorder-traversal) - LC 94
12. [Invert Binary Tree](https://leetcode.com/problems/invert-binary-tree) - LC 226
13. [Maximum Depth of Binary Tree](https://leetcode.com/problems/maximum-depth-of-binary-tree) - LC 104
14. [Binary Tree Postorder Traversal](https://leetcode.com/problems/binary-tree-postorder-traversal) - LC 145
15. [Binary Tree Preorder Traversal](https://leetcode.com/problems/binary-tree-preorder-traversal) - LC 144
16. [Univalued Binary Tree](https://leetcode.com/problems/univalued-binary-tree) - LC 965
17. [Count Complete Tree Nodes](https://leetcode.com/problems/count-complete-tree-nodes) - LC 222
18. [Leaf-Similar Trees](https://leetcode.com/problems/leaf-similar-trees) - LC 872
19. [Average of Levels in Binary Tree](https://leetcode.com/problems/average-of-levels-in-binary-tree) - LC 637
20. [Binary Tree Tilt](https://leetcode.com/problems/binary-tree-tilt) - LC 563
21. [Diameter of Binary Tree](https://leetcode.com/problems/diameter-of-binary-tree) - LC 543
22. [Sum of Left Leaves](https://leetcode.com/problems/sum-of-left-leaves) - LC 404
23. [Sum of Root to Leaf Binary Numbers](https://leetcode.com/problems/sum-of-root-to-leaf-binary-numbers) - LC 1022
24. [Same Tree](https://leetcode.com/problems/same-tree) - LC 100
25. [Subtree of Another Tree](https://leetcode.com/problems/subtree-of-another-tree) - LC 572
26. [Balanced Binary Tree](https://leetcode.com/problems/balanced-binary-tree) - LC 110
27. [Symmetric Tree](https://leetcode.com/problems/symmetric-tree) - LC 101
28. [Second Minimum Node in a Binary Tree](https://leetcode.com/problems/second-minimum-node-in-a-binary-tree) - LC 671
29. [Minimum Depth of Binary Tree](https://leetcode.com/problems/minimum-depth-of-binary-tree) - LC 111
30. [Cousins in Binary Tree](https://leetcode.com/problems/cousins-in-binary-tree) - LC 993
31. [Path Sum](https://leetcode.com/problems/path-sum) - LC 112
32. [Binary Tree Paths](https://leetcode.com/problems/binary-tree-paths) - LC 257

## BST (8)

33. [Range Sum of BST](https://leetcode.com/problems/range-sum-of-bst) - LC 938
34. [Search in a Binary Search Tree](https://leetcode.com/problems/search-in-a-binary-search-tree) - LC 700
35. [Increasing Order Search Tree](https://leetcode.com/problems/increasing-order-search-tree) - LC 897
36. [Convert Sorted Array to Binary Search Tree](https://leetcode.com/problems/convert-sorted-array-to-binary-search-tree) - LC 108
37. [Two Sum IV - Input is a BST](https://leetcode.com/problems/two-sum-iv-input-is-a-bst) - LC 653
38. [Minimum Distance Between BST Nodes](https://leetcode.com/problems/minimum-distance-between-bst-nodes) - LC 783
39. [Minimum Absolute Difference in BST](https://leetcode.com/problems/minimum-absolute-difference-in-bst) - LC 530
40. [Find Mode in Binary Search Tree](https://leetcode.com/problems/find-mode-in-binary-search-tree) - LC 501

## N-ary Tree (3)

41. [N-ary Tree Postorder Traversal](https://leetcode.com/problems/n-ary-tree-postorder-traversal) - LC 590
42. [N-ary Tree Preorder Traversal](https://leetcode.com/problems/n-ary-tree-preorder-traversal) - LC 589
43. [Maximum Depth of N-ary Tree](https://leetcode.com/problems/maximum-depth-of-n-ary-tree) - LC 559

## Stack (13)

44. [Remove Outermost Parentheses](https://leetcode.com/problems/remove-outermost-parentheses) - LC 1021
45. [Maximum Nesting Depth of the Parentheses](https://leetcode.com/problems/maximum-nesting-depth-of-the-parentheses) - LC 1614
46. [Final Prices With a Special Discount in a Shop](https://leetcode.com/problems/final-prices-with-a-special-discount-in-a-shop) - LC 1475
47. [Baseball Game](https://leetcode.com/problems/baseball-game) - LC 682
48. [Next Greater Element I](https://leetcode.com/problems/next-greater-element-i) - LC 496
49. [Minimum String Length After Removing Substrings](https://leetcode.com/problems/minimum-string-length-after-removing-substrings) - LC 2696
50. [Remove All Adjacent Duplicates in String](https://leetcode.com/problems/remove-all-adjacent-duplicates-in-string) - LC 1047
51. [Make The String Great](https://leetcode.com/problems/make-the-string-great) - LC 1544
52. [Crawler Log Folder](https://leetcode.com/problems/crawler-log-folder) - LC 1598
53. [Implement Stack using Queues](https://leetcode.com/problems/implement-stack-using-queues) - LC 225
54. [Backspace String Compare](https://leetcode.com/problems/backspace-string-compare) - LC 844
55. [Valid Parentheses](https://leetcode.com/problems/valid-parentheses) - LC 20
56. [Make Array Elements Equal to Zero](https://leetcode.com/problems/make-array-elements-equal-to-zero) - LC 3354 (loop with stack-like zero-counting)

> Note: `valid-parentheses` is the canonical Stack problem.

## Queue (4)

57. [Number of Students Unable to Eat Lunch](https://leetcode.com/problems/number-of-students-unable-to-eat-lunch) - LC 1700
58. [Number of Recent Calls](https://leetcode.com/problems/number-of-recent-calls) - LC 933
59. [Time Needed to Buy Tickets](https://leetcode.com/problems/time-needed-to-buy-tickets) - LC 2073
60. [Implement Queue using Stacks](https://leetcode.com/problems/implement-queue-using-stacks) - LC 232

## Heap (3)

61. [Take Gifts From the Richest Pile](https://leetcode.com/problems/take-gifts-from-the-richest-pile) - LC 2558
62. [Last Stone Weight](https://leetcode.com/problems/last-stone-weight) - LC 1046
63. [Kth Largest Element in a Stream](https://leetcode.com/problems/kth-largest-element-in-a-stream) - LC 703

## Matrix (23)

64. [Largest Local Values in a Matrix](https://leetcode.com/problems/largest-local-values-in-a-matrix) - LC 2373
65. [Matrix Diagonal Sum](https://leetcode.com/problems/matrix-diagonal-sum) - LC 1572
66. [Flipping an Image](https://leetcode.com/problems/flipping-an-image) - LC 832
67. [Lucky Numbers in a Matrix](https://leetcode.com/problems/lucky-numbers-in-a-matrix) - LC 1380
68. [Flip Square Submatrix Vertically](https://leetcode.com/problems/flip-square-submatrix-vertically) - LC 3643
69. [Transpose Matrix](https://leetcode.com/problems/transpose-matrix) - LC 867
70. [Projection Area of 3D Shapes](https://leetcode.com/problems/projection-area-of-3d-shapes) - LC 883
71. [Matrix Similarity After Cyclic Shifts](https://leetcode.com/problems/matrix-similarity-after-cyclic-shifts) - LC 2946
72. [Row With Maximum Ones](https://leetcode.com/problems/row-with-maximum-ones) - LC 2643
73. [Island Perimeter](https://leetcode.com/problems/island-perimeter) - LC 463
74. [Special Positions in a Binary Matrix](https://leetcode.com/problems/special-positions-in-a-binary-matrix) - LC 1582
75. [Surface Area of 3D Shapes](https://leetcode.com/problems/surface-area-of-3d-shapes) - LC 892
76. [Find the Width of Columns of a Grid](https://leetcode.com/problems/find-the-width-of-columns-of-a-grid) - LC 2639
77. [Toeplitz Matrix](https://leetcode.com/problems/toeplitz-matrix) - LC 766
78. [Image Smoother](https://leetcode.com/problems/image-smoother) - LC 661
79. [Modify the Matrix](https://leetcode.com/problems/modify-the-matrix) - LC 3033
80. [Flood Fill](https://leetcode.com/problems/flood-fill) - LC 733
81. [Determine Whether Matrix Can Be Obtained By Rotation](https://leetcode.com/problems/determine-whether-matrix-can-be-obtained-by-rotation) - LC 1886
82. [Shift 2D Grid](https://leetcode.com/problems/shift-2d-grid) - LC 1260
83. [Available Captures for Rook](https://leetcode.com/problems/available-captures-for-rook) - LC 999
84. [Reshape the Matrix](https://leetcode.com/problems/reshape-the-matrix) - LC 566
85. [Zigzag Grid Traversal With Skip](https://leetcode.com/problems/zigzag-grid-traversal-with-skip) - LC 3417
86. [Check if Grid Satisfies Conditions](https://leetcode.com/problems/check-if-grid-satisfies-conditions) - LC 3142

## Simulation / Implementation (16)

87. [Final Array State After K Multiplication Operations I](https://leetcode.com/problems/final-array-state-after-k-multiplication-operations-i) - LC 3264
88. [Snake in Matrix](https://leetcode.com/problems/snake-in-matrix) - LC 3248
89. [Minimum Number Game](https://leetcode.com/problems/minimum-number-game) - LC 2974
90. [Minimum Number of Chairs in a Waiting Room](https://leetcode.com/problems/minimum-number-of-chairs-in-a-waiting-room) - LC 3168
91. [Count Tested Devices After Test Operations](https://leetcode.com/problems/count-tested-devices-after-test-operations) - LC 2960
92. [Fizz Buzz](https://leetcode.com/problems/fizz-buzz) - LC 412
93. [Ant on the Boundary](https://leetcode.com/problems/ant-on-the-boundary) - LC 3028
94. [Apply Operations to an Array](https://leetcode.com/problems/apply-operations-to-an-array) - LC 2460
95. [Distribute Elements Into Two Arrays I](https://leetcode.com/problems/distribute-elements-into-two-arrays-i) - LC 3069
96. [Fruits Into Baskets II](https://leetcode.com/problems/fruits-into-baskets-ii) - LC 3477
97. [Minimum Pair Removal to Sort Array I](https://leetcode.com/problems/minimum-pair-removal-to-sort-array-i) - LC 3507
98. [Lemonade Change](https://leetcode.com/problems/lemonade-change) - LC 860
99. [Maximum Number of Operations With the Same Score I](https://leetcode.com/problems/maximum-number-of-operations-with-the-same-score-i) - LC 3038
100.    [Find the Losers of the Circular Game](https://leetcode.com/problems/find-the-losers-of-the-circular-game) - LC 2682
101.    [Convert 1D Array Into 2D Array](https://leetcode.com/problems/convert-1d-array-into-2d-array) - LC 2022
102.    [Minimum Operations to Make the Array Increasing](https://leetcode.com/problems/minimum-operations-to-make-the-array-increasing) - LC 1827

## Design (6)

103. [Design Parking System](https://leetcode.com/problems/design-parking-system) - LC 1603
104. [Design an Ordered Stream](https://leetcode.com/problems/design-an-ordered-stream) - LC 1656
105. [Design HashSet](https://leetcode.com/problems/design-hashset) - LC 705
106. [Design HashMap](https://leetcode.com/problems/design-hashmap) - LC 706
107. [Design Neighbor Sum Service](https://leetcode.com/problems/design-neighbor-sum-service) - LC 3242
108. [Range Sum Query - Immutable](https://leetcode.com/problems/range-sum-query-immutable) - LC 303 (Design + PrefixSum; Design wins)

## Sorting (39)

109. [Transform Array by Parity](https://leetcode.com/problems/transform-array-by-parity) - LC 3467
110. [Minimum Number of Moves to Seat Everyone](https://leetcode.com/problems/minimum-number-of-moves-to-seat-everyone) - LC 2037
111. [Widest Vertical Area Between Two Points Containing No Points](https://leetcode.com/problems/widest-vertical-area-between-two-points-containing-no-points) - LC 1637
112. [Sort Integers by The Number of 1 Bits](https://leetcode.com/problems/sort-integers-by-the-number-of-1-bits) - LC 1356
113. [Sort Array by Increasing Frequency](https://leetcode.com/problems/sort-array-by-increasing-frequency) - LC 1636
114. [Height Checker](https://leetcode.com/problems/height-checker) - LC 1051
115. [Array Partition](https://leetcode.com/problems/array-partition) - LC 561
116. [Sort Array by Parity](https://leetcode.com/problems/sort-array-by-parity) - LC 905
117. [Delete Columns to Make Sorted](https://leetcode.com/problems/delete-columns-to-make-sorted) - LC 944
118. [Find Target Indices After Sorting Array](https://leetcode.com/problems/find-target-indices-after-sorting-array) - LC 2089
119. [Delete Greatest Value in Each Row](https://leetcode.com/problems/delete-greatest-value-in-each-row) - LC 2500
120. [Sort Array by Parity II](https://leetcode.com/problems/sort-array-by-parity-ii) - LC 922
121. [Apple Redistribution Into Boxes](https://leetcode.com/problems/apple-redistribution-into-boxes) - LC 3074
122. [Divide an Array Into Subarrays With Minimum Cost I](https://leetcode.com/problems/divide-an-array-into-subarrays-with-minimum-cost-i) - LC 3010
123. [The K Weakest Rows in a Matrix](https://leetcode.com/problems/the-k-weakest-rows-in-a-matrix) - LC 1337
124. [Matrix Cells in Distance Order](https://leetcode.com/problems/matrix-cells-in-distance-order) - LC 1030
125. [Minimum Average of Smallest and Largest Elements](https://leetcode.com/problems/minimum-average-of-smallest-and-largest-elements) - LC 3194
126. [Relative Sort Array](https://leetcode.com/problems/relative-sort-array) - LC 1122
127. [Minimum Subsequence in Non-Increasing Order](https://leetcode.com/problems/minimum-subsequence-in-non-increasing-order) - LC 1403
128. [Find Resultant Array After Removing Anagrams](https://leetcode.com/problems/find-resultant-array-after-removing-anagrams) - LC 2273
129. [Relative Ranks](https://leetcode.com/problems/relative-ranks) - LC 506
130. [Sort Even and Odd Indices Independently](https://leetcode.com/problems/sort-even-and-odd-indices-independently) - LC 2164
131. [Special Array With X Elements Greater Than or Equal X](https://leetcode.com/problems/special-array-with-x-elements-greater-than-or-equal-x) - LC 1608
132. [Mean of Array After Removing Some Elements](https://leetcode.com/problems/mean-of-array-after-removing-some-elements) - LC 1619
133. [The Employee That Worked on the Longest Task](https://leetcode.com/problems/the-employee-that-worked-on-the-longest-task) - LC 2432
134. [Button With Longest Push Time](https://leetcode.com/problems/button-with-longest-push-time) - LC 3386
135. [Maximum Units on a Truck](https://leetcode.com/problems/maximum-units-on-a-truck) - LC 1710
136. [Find Subsequence of Length K With the Largest Sum](https://leetcode.com/problems/find-subsequence-of-length-k-with-the-largest-sum) - LC 2099
137. [Minimum Difference Between Highest and Lowest of K Scores](https://leetcode.com/problems/minimum-difference-between-highest-and-lowest-of-k-scores) - LC 1984
138. [Absolute Difference Between Maximum and Minimum K Elements](https://leetcode.com/problems/absolute-difference-between-maximum-and-minimum-k-elements) - LC 3774
139. [Can Make Arithmetic Progression From Sequence](https://leetcode.com/problems/can-make-arithmetic-progression-from-sequence) - LC 1502
140. [Largest Perimeter Triangle](https://leetcode.com/problems/largest-perimeter-triangle) - LC 976
141. [Maximize Sum of At Most K Distinct Elements](https://leetcode.com/problems/maximize-sum-of-at-most-k-distinct-elements) - LC 3684
142. [Minimum Absolute Difference](https://leetcode.com/problems/minimum-absolute-difference) - LC 1200
143. [Longest Subsequence With Limited Sum](https://leetcode.com/problems/longest-subsequence-with-limited-sum) - LC 2389
144. [Minimum Cost of Buying Candies With Discount](https://leetcode.com/problems/minimum-cost-of-buying-candies-with-discount) - LC 2144
145. [Coupon Code Validator](https://leetcode.com/problems/coupon-code-validator) - LC 3606
146. [Assign Cookies](https://leetcode.com/problems/assign-cookies) - LC 455
147. [Maximize Sum Of Array After K Negations](https://leetcode.com/problems/maximize-sum-of-array-after-k-negations) - LC 1005

## Binary Search (11)

148. [Maximum Count of Positive Integer and Negative Integer](https://leetcode.com/problems/maximum-count-of-positive-integer-and-negative-integer) - LC 2529
149. [Find the Distance Value Between Two Arrays](https://leetcode.com/problems/find-the-distance-value-between-two-arrays) - LC 1385
150. [Kth Missing Positive Number](https://leetcode.com/problems/kth-missing-positive-number) - LC 1539
151. [Find Smallest Letter Greater Than Target](https://leetcode.com/problems/find-smallest-letter-greater-than-target) - LC 744
152. [Binary Search](https://leetcode.com/problems/binary-search) - LC 704
153. [Search Insert Position](https://leetcode.com/problems/search-insert-position) - LC 35
154. [First Bad Version](https://leetcode.com/problems/first-bad-version) - LC 278
155. [Guess Number Higher or Lower](https://leetcode.com/problems/guess-number-higher-or-lower) - LC 374
156. [Sqrt(x)](https://leetcode.com/problems/sqrtx) - LC 69
157. [Valid Perfect Square](https://leetcode.com/problems/valid-perfect-square) - LC 367
158. [Arranging Coins](https://leetcode.com/problems/arranging-coins) - LC 441

## Two Pointers (18)

159. [Count Pairs Whose Sum is Less than Target](https://leetcode.com/problems/count-pairs-whose-sum-is-less-than-target) - LC 2824
160. [Merge Strings Alternately](https://leetcode.com/problems/merge-strings-alternately) - LC 1768
161. [DI String Match](https://leetcode.com/problems/di-string-match) - LC 942
162. [Two Furthest Houses With Different Colors](https://leetcode.com/problems/two-furthest-houses-with-different-colors) - LC 2078
163. [Squares of a Sorted Array](https://leetcode.com/problems/squares-of-a-sorted-array) - LC 977
164. [Lexicographically Smallest Palindrome](https://leetcode.com/problems/lexicographically-smallest-palindrome) - LC 2697
165. [Move Zeroes](https://leetcode.com/problems/move-zeroes) - LC 283
166. [Remove Duplicates from Sorted Array](https://leetcode.com/problems/remove-duplicates-from-sorted-array) - LC 26
167. [Remove Element](https://leetcode.com/problems/remove-element) - LC 27
168. [Reverse Vowels of a String](https://leetcode.com/problems/reverse-vowels-of-a-string) - LC 345
169. [Minimum Common Value](https://leetcode.com/problems/minimum-common-value) - LC 2540
170. [Merge Sorted Array](https://leetcode.com/problems/merge-sorted-array) - LC 88
171. [Find the Index of the First Occurrence in a String](https://leetcode.com/problems/find-the-index-of-the-first-occurrence-in-a-string) - LC 28
172. [Maximum Enemy Forts That Can Be Captured](https://leetcode.com/problems/maximum-enemy-forts-that-can-be-captured) - LC 2511
173. [Long Pressed Name](https://leetcode.com/problems/long-pressed-name) - LC 925
174. [Reverse Only Letters](https://leetcode.com/problems/reverse-only-letters) - LC 917
175. [Reverse String](https://leetcode.com/problems/reverse-string) - LC 344
176. [Find the Array Concatenation Value](https://leetcode.com/problems/find-the-array-concatenation-value) - LC 2562

## Sliding Window (6)

177. [Alternating Groups I](https://leetcode.com/problems/alternating-groups-i) - LC 3206
178. [Minimum Recolors to Get K Consecutive Black Blocks](https://leetcode.com/problems/minimum-recolors-to-get-k-consecutive-black-blocks) - LC 2379
179. [Maximum Average Subarray I](https://leetcode.com/problems/maximum-average-subarray-i) - LC 643
180. [Find X-Sum of All K-Long Subarrays I](https://leetcode.com/problems/find-x-sum-of-all-k-long-subarrays-i) - LC 3318
181. [Maximum Length Substring With Two Occurrences](https://leetcode.com/problems/maximum-length-substring-with-two-occurrences) - LC 3090
182. [Shortest Subarray With OR at Least K I](https://leetcode.com/problems/shortest-subarray-with-or-at-least-k-i) - LC 3095

## Prefix Sum (11)

183. [Running Sum of 1d Array](https://leetcode.com/problems/running-sum-of-1d-array) - LC 1480
184. [Sum of Variable Length Subarrays](https://leetcode.com/problems/sum-of-variable-length-subarrays) - LC 3427
185. [Left and Right Sum Differences](https://leetcode.com/problems/left-and-right-sum-differences) - LC 2574
186. [Find the Highest Altitude](https://leetcode.com/problems/find-the-highest-altitude) - LC 1732
187. [Find Pivot Index](https://leetcode.com/problems/find-pivot-index) - LC 724
188. [Find the Middle Index in Array](https://leetcode.com/problems/find-the-middle-index-in-array) - LC 1991
189. [Minimum Value to Get Positive Step by Step Sum](https://leetcode.com/problems/minimum-value-to-get-positive-step-by-step-sum) - LC 1413
190. [Count Partitions With Even Sum Difference](https://leetcode.com/problems/count-partitions-with-even-sum-difference) - LC 3432
191. [Maximum Score After Splitting a String](https://leetcode.com/problems/maximum-score-after-splitting-a-string) - LC 1422
192. [Minimum Positive Sum Subarray](https://leetcode.com/problems/minimum-positive-sum-subarray) - LC 3364
193. [Find the Pivot Integer](https://leetcode.com/problems/find-the-pivot-integer) - LC 2485 (Math; PS variant)

## Math (115)

194. [Minimum Operations to Make Array Sum Divisible by K](https://leetcode.com/problems/minimum-operations-to-make-array-sum-divisible-by-k) - LC 3512
195. [Digit Frequency Score](https://leetcode.com/problems/digit-frequency-score) - LC 3945
196. [Find the Maximum Achievable Number](https://leetcode.com/problems/find-the-maximum-achievable-number) - LC 2769
197. [Divisible and Non-divisible Sums Difference](https://leetcode.com/problems/divisible-and-non-divisible-sums-difference) - LC 2894
198. [Find Minimum Operations to Make All Elements Divisible by Three](https://leetcode.com/problems/find-minimum-operations-to-make-all-elements-divisible-by-three) - LC 3190
199. [Convert the Temperature](https://leetcode.com/problems/convert-the-temperature) - LC 2469
200. [Compute Alternating Sum](https://leetcode.com/problems/compute-alternating-sum) - LC 3701
201. [The Two Sneaky Numbers of Digitville](https://leetcode.com/problems/the-two-sneaky-numbers-of-digitville) - LC 3289
202. [Minimum Element After Replacement With Digit Sum](https://leetcode.com/problems/minimum-element-after-replacement-with-digit-sum) - LC 3300
203. [Find Closest Person](https://leetcode.com/problems/find-closest-person) - LC 3516
204. [Smallest Even Multiple](https://leetcode.com/problems/smallest-even-multiple) - LC 2413
205. [Sum Multiples](https://leetcode.com/problems/sum-multiples) - LC 2652
206. [Count the Digits That Divide a Number](https://leetcode.com/problems/count-the-digits-that-divide-a-number) - LC 2520
207. [Difference Between Element Sum and Digit Sum of an Array](https://leetcode.com/problems/difference-between-element-sum-and-digit-sum-of-an-array) - LC 2535
208. [GCD of Odd and Even Sums](https://leetcode.com/problems/gcd-of-odd-and-even-sums) - LC 3658
209. [Earliest Time to Finish One Task](https://leetcode.com/problems/earliest-time-to-finish-one-task) - LC 3683
210. [Harshad Number](https://leetcode.com/problems/harshad-number) - LC 3099
211. [Find Missing and Repeated Values](https://leetcode.com/problems/find-missing-and-repeated-values) - LC 2965
212. [Maximum Product Difference Between Two Pairs](https://leetcode.com/problems/maximum-product-difference-between-two-pairs) - LC 1913
213. [Count Symmetric Integers](https://leetcode.com/problems/count-symmetric-integers) - LC 2843
214. [Find the Integer Added to Array I](https://leetcode.com/problems/find-the-integer-added-to-array-i) - LC 3131
215. [Calculate Money in Leetcode Bank](https://leetcode.com/problems/calculate-money-in-leetcode-bank) - LC 1716
216. [A Number After a Double Reversal](https://leetcode.com/problems/a-number-after-a-double-reversal) - LC 2119
217. [Smallest Index With Digit Sum Equal to Index](https://leetcode.com/problems/smallest-index-with-digit-sum-equal-to-index) - LC 3550
218. [Number of Common Factors](https://leetcode.com/problems/number-of-common-factors) - LC 2427
219. [N-Repeated Element in Size 2N Array](https://leetcode.com/problems/n-repeated-element-in-size-2n-array) - LC 961
220. [Count Operations to Obtain Zero](https://leetcode.com/problems/count-operations-to-obtain-zero) - LC 2169
221. [Number of Rectangles That Can Form The Largest Square](https://leetcode.com/problems/number-of-rectangles-that-can-form-the-largest-square) - LC 1725
222. [Minimum Cost to Reach Every Position](https://leetcode.com/problems/minimum-cost-to-reach-every-position) - LC 3502
223. [Maximum Sum With Exactly K Elements](https://leetcode.com/problems/maximum-sum-with-exactly-k-elements) - LC 2656
224. [Hexadecimal and Hexatrigesimal Conversion](https://leetcode.com/problems/hexadecimal-and-hexatrigesimal-conversion) - LC 3602
225. [Find If Digit Game Can Be Won](https://leetcode.com/problems/find-if-digit-game-can-be-won) - LC 3232
226. [Calculate Delayed Arrival Time](https://leetcode.com/problems/calculate-delayed-arrival-time) - LC 2651
227. [Maximum Containers on a Ship](https://leetcode.com/problems/maximum-containers-on-a-ship) - LC 3492
228. [Find the Sum of Encrypted Integers](https://leetcode.com/problems/find-the-sum-of-encrypted-integers) - LC 3079
229. [Find the Key of the Numbers](https://leetcode.com/problems/find-the-key-of-the-numbers) - LC 3270
230. [Distribute Candies Among Children I](https://leetcode.com/problems/distribute-candies-among-children-i) - LC 2928
231. [Remove Zeros in Decimal Representation](https://leetcode.com/problems/remove-zeros-in-decimal-representation) - LC 3726
232. [Construct Uniform Parity Array I](https://leetcode.com/problems/construct-uniform-parity-array-i) - LC 3875
233. [Maximum Difference by Remapping a Digit](https://leetcode.com/problems/maximum-difference-by-remapping-a-digit) - LC 2566
234. [Maximum Difference Between Adjacent Elements in a Circular Array](https://leetcode.com/problems/maximum-difference-between-adjacent-elements-in-a-circular-array) - LC 3423
235. [Make Array Zero by Subtracting Equal Amounts](https://leetcode.com/problems/make-array-zero-by-subtracting-equal-amounts) - LC 2357
236. [Count Square Sum Triples](https://leetcode.com/problems/count-square-sum-triples) - LC 1925
237. [Smallest Range I](https://leetcode.com/problems/smallest-range-i) - LC 908
238. [Split With Minimum Sum](https://leetcode.com/problems/split-with-minimum-sum) - LC 2578
239. [Find Champion I](https://leetcode.com/problems/find-champion-i) - LC 2923
240. [Minimum Cost to Move Chips to The Same Position](https://leetcode.com/problems/minimum-cost-to-move-chips-to-the-same-position) - LC 1217
241. [Check if Two Chessboard Squares Have the Same Color](https://leetcode.com/problems/check-if-two-chessboard-squares-have-the-same-color) - LC 3274
242. [Missing Number](https://leetcode.com/problems/missing-number) - LC 268
243. [Water Bottles](https://leetcode.com/problems/water-bottles) - LC 1518
244. [Check Divisibility by Digit Sum and Product](https://leetcode.com/problems/check-divisibility-by-digit-sum-and-product) - LC 3622
245. [Maximum Product of Two Digits](https://leetcode.com/problems/maximum-product-of-two-digits) - LC 3536
246. [Alternating Digit Sum](https://leetcode.com/problems/alternating-digit-sum) - LC 2544
247. [Add Digits](https://leetcode.com/problems/add-digits) - LC 258
248. [Count Integers With Even Digit Sum](https://leetcode.com/problems/count-integers-with-even-digit-sum) - LC 2180
249. [Minimum Time to Type Word Using Special Typewriter](https://leetcode.com/problems/minimum-time-to-type-word-using-special-typewriter) - LC 1974
250. [Maximum Difference Between Even and Odd Frequency I](https://leetcode.com/problems/maximum-difference-between-even-and-odd-frequency-i) - LC 3442 (could be Map)
251. [Distribute Candies to People](https://leetcode.com/problems/distribute-candies-to-people) - LC 1103
252. [Find the Child Who Has the Ball After K Seconds](https://leetcode.com/problems/find-the-child-who-has-the-ball-after-k-seconds) - LC 3178
253. [Largest Number After Digit Swaps by Parity](https://leetcode.com/problems/largest-number-after-digit-swaps-by-parity) - LC 2231
254. [Compute Decimal Representation](https://leetcode.com/problems/compute-decimal-representation) - LC 3697
255. [Sign of the Product of an Array](https://leetcode.com/problems/sign-of-the-product-of-an-array) - LC 1822
256. [Smallest Divisible Digit Product I](https://leetcode.com/problems/smallest-divisible-digit-product-i) - LC 3345
257. [Smallest Missing Multiple of K](https://leetcode.com/problems/smallest-missing-multiple-of-k) - LC 3718
258. [Average Value of Even Numbers That Are Divisible by Three](https://leetcode.com/problems/average-value-of-even-numbers-that-are-divisible-by-three) - LC 2455
259. [Minimum Number of Operations to Convert Time](https://leetcode.com/problems/minimum-number-of-operations-to-convert-time) - LC 2224
260. [K Items With the Maximum Sum](https://leetcode.com/problems/k-items-with-the-maximum-sum) - LC 2600
261. [Most Visited Sector in a Circular Track](https://leetcode.com/problems/most-visited-sector-in-a-circular-track) - LC 1560
262. [Nim Game](https://leetcode.com/problems/nim-game) - LC 292
263. [Day of the Week](https://leetcode.com/problems/day-of-the-week) - LC 1185
264. [Convert Integer to the Sum of Two No-Zero Integers](https://leetcode.com/problems/convert-integer-to-the-sum-of-two-no-zero-integers) - LC 1317
265. [Range Addition II](https://leetcode.com/problems/range-addition-ii) - LC 598
266. [Construct the Rectangle](https://leetcode.com/problems/construct-the-rectangle) - LC 492
267. [Base 7](https://leetcode.com/problems/base-7) - LC 504
268. [Count Odd Numbers in an Interval Range](https://leetcode.com/problems/count-odd-numbers-in-an-interval-range) - LC 1523
269. [Convert a Number to Hexadecimal](https://leetcode.com/problems/convert-a-number-to-hexadecimal) - LC 405
270. [Pass the Pillow](https://leetcode.com/problems/pass-the-pillow) - LC 2582
271. [Account Balance After Rounded Purchase](https://leetcode.com/problems/account-balance-after-rounded-purchase) - LC 2806
272. [Minimum Cuts to Divide a Circle](https://leetcode.com/problems/minimum-cuts-to-divide-a-circle) - LC 2481
273. [Number of Days Between Two Dates](https://leetcode.com/problems/number-of-days-between-two-dates) - LC 1360
274. [Day of the Year](https://leetcode.com/problems/day-of-the-year) - LC 1154
275. [Power of Three](https://leetcode.com/problems/power-of-three) - LC 326
276. [Check if the Number is Fascinating](https://leetcode.com/problems/check-if-the-number-is-fascinating) - LC 2729
277. [Check If N and Its Double Exist](https://leetcode.com/problems/check-if-n-and-its-double-exist) - LC 1346
278. [Count Days Spent Together](https://leetcode.com/problems/count-days-spent-together) - LC 2409
279. [Rectangle Overlap](https://leetcode.com/problems/rectangle-overlap) - LC 836
280. [Excel Sheet Column Title](https://leetcode.com/problems/excel-sheet-column-title) - LC 168
281. [Maximum Product of Three Numbers](https://leetcode.com/problems/maximum-product-of-three-numbers) - LC 628
282. [Maximum Area of Longest Diagonal Rectangle](https://leetcode.com/problems/maximum-area-of-longest-diagonal-rectangle) - LC 3000
283. [Maximum Height of a Triangle](https://leetcode.com/problems/maximum-height-of-a-triangle) - LC 3200
284. [Type of Triangle](https://leetcode.com/problems/type-of-triangle) - LC 3024
285. [Set Mismatch](https://leetcode.com/problems/set-mismatch) - LC 645
286. [Ugly Number](https://leetcode.com/problems/ugly-number) - LC 263
287. [Minimum Hours of Training to Win a Competition](https://leetcode.com/problems/minimum-hours-of-training-to-win-a-competition) - LC 2383
288. [Stone Removal Game](https://leetcode.com/problems/stone-removal-game) - LC 3360
289. [Find Minimum Log Transportation Cost](https://leetcode.com/problems/find-minimum-log-transportation-cost) - LC 3560
290. [Total Distance Traveled](https://leetcode.com/problems/total-distance-traveled) - LC 2739
291. [Check if It Is a Straight Line](https://leetcode.com/problems/check-if-it-is-a-straight-line) - LC 1232
292. [Valid Boomerang](https://leetcode.com/problems/valid-boomerang) - LC 1037
293. [Categorize Box According to Criteria](https://leetcode.com/problems/categorize-box-according-to-criteria) - LC 2525
294. [Prime in Diagonal](https://leetcode.com/problems/prime-in-diagonal) - LC 2614
295. [Perfect Number](https://leetcode.com/problems/perfect-number) - LC 507
296. [Add to Array-Form of Integer](https://leetcode.com/problems/add-to-array-form-of-integer) - LC 989 (Math; also Array)
297. [Add Binary](https://leetcode.com/problems/add-binary) - LC 67 (Math; also String)
298. [Add Strings](https://leetcode.com/problems/add-strings) - LC 415 (Math; also String)
299. [Find the Maximum Divisibility Score](https://leetcode.com/problems/find-the-maximum-divisibility-score) - LC 2644
300. [Power of Four](https://leetcode.com/problems/power-of-four) - LC 342 (Math; also Bit)
301. [Get Maximum in Generated Array](https://leetcode.com/problems/get-maximum-in-generated-array) - LC 1646 (DP; also Array)
302. [Maximum Subarray With Equal Products](https://leetcode.com/problems/maximum-subarray-with-equal-products) - LC 3411 (Math; also Array)
303. [Prime Arrangements](https://leetcode.com/problems/prime-arrangements) - LC 1175
304. [Minimum Operations to Equalize Array](https://leetcode.com/problems/minimum-operations-to-equalize-array) - LC 3674
305. [Earliest Finish Time for Land and Water Rides I](https://leetcode.com/problems/earliest-finish-time-for-land-and-water-rides-i) - LC 3633
306. [Number of Beautiful Pairs](https://leetcode.com/problems/number-of-beautiful-pairs) - LC 2748
307. [Make a Square With the Same Color](https://leetcode.com/problems/make-a-square-with-the-same-color) - LC 3127 (Math; also String)
308. [Maximize Expression of Three Elements](https://leetcode.com/problems/maximize-expression-of-three-elements) - LC 3745

## Bit Manipulation (21)

309. [Minimum Bit Flips to Convert Number](https://leetcode.com/problems/minimum-bit-flips-to-convert-number) - LC 2220
310. [Decode XORed Array](https://leetcode.com/problems/decode-xored-array) - LC 1720
311. [Sum of Values at Indices With K Set Bits](https://leetcode.com/problems/sum-of-values-at-indices-with-k-set-bits) - LC 2859
312. [Construct the Minimum Bitwise Array I](https://leetcode.com/problems/construct-the-minimum-bitwise-array-i) - LC 3314
313. [Bitwise OR of Even Numbers in an Array](https://leetcode.com/problems/bitwise-or-of-even-numbers-in-an-array) - LC 3688
314. [Counting Bits](https://leetcode.com/problems/counting-bits) - LC 338
315. [Smallest Number With All Set Bits](https://leetcode.com/problems/smallest-number-with-all-set-bits) - LC 3370
316. [Hamming Distance](https://leetcode.com/problems/hamming-distance) - LC 461
317. [Single Number](https://leetcode.com/problems/single-number) - LC 136
318. [Find the XOR of Numbers Which Appear Twice](https://leetcode.com/problems/find-the-xor-of-numbers-which-appear-twice) - LC 3158
319. [Maximum Strong Pair XOR I](https://leetcode.com/problems/maximum-strong-pair-xor-i) - LC 2932
320. [Number of Even and Odd Bits](https://leetcode.com/problems/number-of-even-and-odd-bits) - LC 2595
321. [Count Pairs of Similar Strings](https://leetcode.com/problems/count-pairs-of-similar-strings) - LC 2506
322. [Find the K-or of an Array](https://leetcode.com/problems/find-the-k-or-of-an-array) - LC 2917
323. [Check if Bitwise OR Has Trailing Zeros](https://leetcode.com/problems/check-if-bitwise-or-has-trailing-zeros) - LC 2980
324. [Binary Number With Alternating Bits](https://leetcode.com/problems/binary-number-with-alternating-bits) - LC 693
325. [Reverse Bits](https://leetcode.com/problems/reverse-bits) - LC 190
326. [Binary Watch](https://leetcode.com/problems/binary-watch) - LC 401
327. [Number Complement](https://leetcode.com/problems/number-complement) - LC 476
328. [Complement of Base 10 Integer](https://leetcode.com/problems/complement-of-base-10-integer) - LC 1009
329. [Binary Gap](https://leetcode.com/problems/binary-gap) - LC 868

## Recursion (0)

- _No problems are categorised here as "pure recursion"; recursive solutions appear as part of Tree, DP, etc._

## Greedy (1)

330. [Can Place Flowers](https://leetcode.com/problems/can-place-flowers) - LC 605

> Other problems here use greedy _technique_ but have a more specific primary category (e.g. Array, Sorting).

## DP (3)

331. [Min Cost Climbing Stairs](https://leetcode.com/problems/min-cost-climbing-stairs) - LC 746
332. [Best Time to Buy and Sell Stock](https://leetcode.com/problems/best-time-to-buy-and-sell-stock) - LC 121
333. [N-th Tribonacci Number](https://leetcode.com/problems/n-th-tribonacci-number) - LC 1137

---

## Set (37)

334. [Jewels and Stones](https://leetcode.com/problems/jewels-and-stones) - LC 771
335. [Count the Number of Consistent Strings](https://leetcode.com/problems/count-the-number-of-consistent-strings) - LC 1684
336. [Number of Arithmetic Triplets](https://leetcode.com/problems/number-of-arithmetic-triplets) - LC 2367
337. [Find Common Elements Between Two Arrays](https://leetcode.com/problems/find-common-elements-between-two-arrays) - LC 2956
338. [Unique Morse Code Words](https://leetcode.com/problems/unique-morse-code-words) - LC 804
339. [Find Missing Elements](https://leetcode.com/problems/find-missing-elements) - LC 3731
340. [Maximum Number of Words You Can Type](https://leetcode.com/problems/maximum-number-of-words-you-can-type) - LC 1935
341. [Find the Difference of Two Arrays](https://leetcode.com/problems/find-the-difference-of-two-arrays) - LC 2215
342. [Two Out of Three](https://leetcode.com/problems/two-out-of-three) - LC 2032
343. [Intersection of Two Arrays](https://leetcode.com/problems/intersection-of-two-arrays) - LC 349
344. [Minimize String Length](https://leetcode.com/problems/minimize-string-length) - LC 2716
345. [Subarrays Distinct Element Sum of Squares I](https://leetcode.com/problems/subarrays-distinct-element-sum-of-squares-i) - LC 2913
346. [Find the Distinct Difference Array](https://leetcode.com/problems/find-the-distinct-difference-array) - LC 2670
347. [Largest Positive Integer That Exists With Its Negative](https://leetcode.com/problems/largest-positive-integer-that-exists-with-its-negative) - LC 2441
348. [Keep Multiplying Found Values by Two](https://leetcode.com/problems/keep-multiplying-found-values-by-two) - LC 2154
349. [First Letter to Appear Twice](https://leetcode.com/problems/first-letter-to-appear-twice) - LC 2351
350. [Keyboard Row](https://leetcode.com/problems/keyboard-row) - LC 500
351. [Points That Intersect With Cars](https://leetcode.com/problems/points-that-intersect-with-cars) - LC 2848
352. [Intersection of Multiple Arrays](https://leetcode.com/problems/intersection-of-multiple-arrays) - LC 2248
353. [Minimum Number of Operations to Make Elements in Array Distinct](https://leetcode.com/problems/minimum-number-of-operations-to-make-elements-in-array-distinct) - LC 3396
354. [Path Crossing](https://leetcode.com/problems/path-crossing) - LC 1496
355. [Contains Duplicate](https://leetcode.com/problems/contains-duplicate) - LC 217
356. [Find All Numbers Disappeared in an Array](https://leetcode.com/problems/find-all-numbers-disappeared-in-an-array) - LC 448
357. [Find Subarrays With Equal Sum](https://leetcode.com/problems/find-subarrays-with-equal-sum) - LC 2395
358. [Count Distinct Numbers on Board](https://leetcode.com/problems/count-distinct-numbers-on-board) - LC 2549
359. [Split the Array](https://leetcode.com/problems/split-the-array) - LC 3046
360. [Happy Number](https://leetcode.com/problems/happy-number) - LC 202
361. [Unique Email Addresses](https://leetcode.com/problems/unique-email-addresses) - LC 929
362. [Fair Candy Swap](https://leetcode.com/problems/fair-candy-swap) - LC 888
363. [Form Smallest Number From Two Digit Arrays](https://leetcode.com/problems/form-smallest-number-from-two-digit-arrays) - LC 2605
364. [Number of Distinct Averages](https://leetcode.com/problems/number-of-distinct-averages) - LC 2465
365. [Check if Every Row and Column Contains All Numbers](https://leetcode.com/problems/check-if-every-row-and-column-contains-all-numbers) - LC 2133
366. [Check if All the Integers in a Range Are Covered](https://leetcode.com/problems/check-if-all-the-integers-in-a-range-are-covered) - LC 1893
367. [Maximum Unique Subarray Sum After Deletion](https://leetcode.com/problems/maximum-unique-subarray-sum-after-deletion) - LC 3487
368. [Minimum Operations to Collect Elements](https://leetcode.com/problems/minimum-operations-to-collect-elements) - LC 2869
369. [Smallest Absent Positive Greater Than Average](https://leetcode.com/problems/smallest-absent-positive-greater-than-average) - LC 3678
370. [Smallest Missing Integer Greater Than Sequential Prefix Sum](https://leetcode.com/problems/smallest-missing-integer-greater-than-sequential-prefix-sum) - LC 2996

## Map (69)

371. [Find Most Frequent Vowel and Consonant](https://leetcode.com/problems/find-most-frequent-vowel-and-consonant) - LC 3541
372. [Permutation Difference Between Two Strings](https://leetcode.com/problems/permutation-difference-between-two-strings) - LC 3146
373. [Find the Number of Good Pairs I](https://leetcode.com/problems/find-the-number-of-good-pairs-i) - LC 3162
374. [Count Number of Pairs With Absolute Difference K](https://leetcode.com/problems/count-number-of-pairs-with-absolute-difference-k) - LC 2006
375. [Kth Distinct String in an Array](https://leetcode.com/problems/kth-distinct-string-in-an-array) - LC 2053
376. [Find Maximum Number of String Pairs](https://leetcode.com/problems/find-maximum-number-of-string-pairs) - LC 2744
377. [Rings and Rods](https://leetcode.com/problems/rings-and-rods) - LC 2103
378. [Generate a String With Characters That Have Odd Counts](https://leetcode.com/problems/generate-a-string-with-characters-that-have-odd-counts) - LC 1374
379. [Count Pairs That Form a Complete Day I](https://leetcode.com/problems/count-pairs-that-form-a-complete-day-i) - LC 3184
380. [Robot Return to Origin](https://leetcode.com/problems/robot-return-to-origin) - LC 657
381. [Sum of Elements With Frequency Divisible by K](https://leetcode.com/problems/sum-of-elements-with-frequency-divisible-by-k) - LC 3712
382. [Unique Number of Occurrences](https://leetcode.com/problems/unique-number-of-occurrences) - LC 1207
383. [Finding 3-Digit Even Numbers](https://leetcode.com/problems/finding-3-digit-even-numbers) - LC 2094
384. [Merge Two 2D Arrays by Summing Values](https://leetcode.com/problems/merge-two-2d-arrays-by-summing-values) - LC 2570
385. [Make Two Arrays Equal by Reversing Subarrays](https://leetcode.com/problems/make-two-arrays-equal-by-reversing-subarrays) - LC 1460
386. [Uncommon Words From Two Sentences](https://leetcode.com/problems/uncommon-words-from-two-sentences) - LC 884
387. [Find Lucky Integer in an Array](https://leetcode.com/problems/find-lucky-integer-in-an-array) - LC 1394
388. [Maximum Number of Balls in a Box](https://leetcode.com/problems/maximum-number-of-balls-in-a-box) - LC 1742
389. [Count Common Words With One Occurrence](https://leetcode.com/problems/count-common-words-with-one-occurrence) - LC 2085
390. [Number of Unequal Triplets in Array](https://leetcode.com/problems/number-of-unequal-triplets-in-array) - LC 2475
391. [Check If All Characters Have Equal Number of Occurrences](https://leetcode.com/problems/check-if-all-characters-have-equal-number-of-occurrences) - LC 1941
392. [Destination City](https://leetcode.com/problems/destination-city) - LC 1436
393. [Sum of Unique Elements](https://leetcode.com/problems/sum-of-unique-elements) - LC 1748
394. [Count Elements With Maximum Frequency](https://leetcode.com/problems/count-elements-with-maximum-frequency) - LC 3005
395. [Find the Difference](https://leetcode.com/problems/find-the-difference) - LC 389 (Map; also String)
396. [Majority Frequency Characters](https://leetcode.com/problems/majority-frequency-characters) - LC 3692
397. [Redistribute Characters to Make All Strings Equal](https://leetcode.com/problems/redistribute-characters-to-make-all-strings-equal) - LC 1897
398. [Roman to Integer](https://leetcode.com/problems/roman-to-integer) - LC 13 (Map; also String)
399. [Check Distances Between Same Letters](https://leetcode.com/problems/check-distances-between-same-letters) - LC 2399
400. [Find Words That Can Be Formed by Characters](https://leetcode.com/problems/find-words-that-can-be-formed-by-characters) - LC 1160
401. [Unique 3-Digit Even Numbers](https://leetcode.com/problems/unique-3-digit-even-numbers) - LC 3483
402. [Find the Least Frequent Digit](https://leetcode.com/problems/find-the-least-frequent-digit) - LC 3663
403. [Minimum Operations to Make Array Values Equal to K](https://leetcode.com/problems/minimum-operations-to-make-array-values-equal-to-k) - LC 3375
404. [Minimum Deletions for At Most K Distinct Characters](https://leetcode.com/problems/minimum-deletions-for-at-most-k-distinct-characters) - LC 3545
405. [Find the Number of Winning Players](https://leetcode.com/problems/find-the-number-of-winning-players) - LC 3238
406. [Maximum Number of Balloons](https://leetcode.com/problems/maximum-number-of-balloons) - LC 1189
407. [Intersection of Two Arrays II](https://leetcode.com/problems/intersection-of-two-arrays-ii) - LC 350
408. [Minimum Index Sum of Two Lists](https://leetcode.com/problems/minimum-index-sum-of-two-lists) - LC 599
409. [Most Frequent Number Following Key in an Array](https://leetcode.com/problems/most-frequent-number-following-key-in-an-array) - LC 2190
410. [Rank Transform of an Array](https://leetcode.com/problems/rank-transform-of-an-array) - LC 1331
411. [Increasing Decreasing String](https://leetcode.com/problems/increasing-decreasing-string) - LC 1370
412. [Distribute Candies](https://leetcode.com/problems/distribute-candies) - LC 575
413. [First Unique Character in a String](https://leetcode.com/problems/first-unique-character-in-a-string) - LC 387
414. [Ransom Note](https://leetcode.com/problems/ransom-note) - LC 383
415. [Majority Element](https://leetcode.com/problems/majority-element) - LC 169
416. [Count Largest Group](https://leetcode.com/problems/count-largest-group) - LC 1399
417. [Number of Equivalent Domino Pairs](https://leetcode.com/problems/number-of-equivalent-domino-pairs) - LC 1128
418. [Check Whether Two Strings are Almost Equivalent](https://leetcode.com/problems/check-whether-two-strings-are-almost-equivalent) - LC 2068
419. [Count Special Quadruplets](https://leetcode.com/problems/count-special-quadruplets) - LC 1995
420. [Longest Harmonious Subsequence](https://leetcode.com/problems/longest-harmonious-subsequence) - LC 594
421. [Contains Duplicate II](https://leetcode.com/problems/contains-duplicate-ii) - LC 219
422. [Two Sum](https://leetcode.com/problems/two-sum) - LC 1
423. [Degree of an Array](https://leetcode.com/problems/degree-of-an-array) - LC 697
424. [Largest Substring Between Two Equal Characters](https://leetcode.com/problems/largest-substring-between-two-equal-characters) - LC 1624
425. [Most Common Word](https://leetcode.com/problems/most-common-word) - LC 819
426. [Word Pattern](https://leetcode.com/problems/word-pattern) - LC 290
427. [Verifying an Alien Dictionary](https://leetcode.com/problems/verifying-an-alien-dictionary) - LC 953
428. [Find Winner on a Tic Tac Toe Game](https://leetcode.com/problems/find-winner-on-a-tic-tac-toe-game) - LC 1275
429. [Isomorphic Strings](https://leetcode.com/problems/isomorphic-strings) - LC 205
430. [Find Common Characters](https://leetcode.com/problems/find-common-characters) - LC 1002
431. [X of a Kind in a Deck of Cards](https://leetcode.com/problems/x-of-a-kind-in-a-deck-of-cards) - LC 914
432. [Most Frequent Even Element](https://leetcode.com/problems/most-frequent-even-element) - LC 2404
433. [Shortest Completing Word](https://leetcode.com/problems/shortest-completing-word) - LC 748
434. [Longest Palindrome](https://leetcode.com/problems/longest-palindrome) - LC 409
435. [Check if Any Element Has Prime Frequency](https://leetcode.com/problems/check-if-any-element-has-prime-frequency) - LC 3591
436. [Max Pair Sum in an Array](https://leetcode.com/problems/max-pair-sum-in-an-array) - LC 2815 (could be Array)
437. [Buddy Strings](https://leetcode.com/problems/buddy-strings) - LC 859
438. [Remove Letter to Equalize Frequency](https://leetcode.com/problems/remove-letter-to-equalize-frequency) - LC 2423
439. [Find Valid Pair of Adjacent Digits in String](https://leetcode.com/problems/find-valid-pair-of-adjacent-digits-in-string) - LC 3438 (Map; also String)

## Array (77)

440. [Restore Finishing Order](https://leetcode.com/problems/restore-finishing-order) - LC 3668
441. [Build Array from Permutation](https://leetcode.com/problems/build-array-from-permutation) - LC 1920
442. [Concatenation of Array](https://leetcode.com/problems/concatenation-of-array) - LC 1929
443. [Shuffle the Array](https://leetcode.com/problems/shuffle-the-array) - LC 1470
444. [Richest Customer Wealth](https://leetcode.com/problems/richest-customer-wealth) - LC 1672
445. [Kids With the Greatest Number of Candies](https://leetcode.com/problems/kids-with-the-greatest-number-of-candies) - LC 1431
446. [Number of Employees Who Met the Target](https://leetcode.com/problems/number-of-employees-who-met-the-target) - LC 2798
447. [How Many Numbers Are Smaller Than the Current Number](https://leetcode.com/problems/how-many-numbers-are-smaller-than-the-current-number) - LC 1365
448. [Find Indices of Stable Mountains](https://leetcode.com/problems/find-indices-of-stable-mountains) - LC 3285
449. [Minimum Operations to Exceed Threshold Value I](https://leetcode.com/problems/minimum-operations-to-exceed-threshold-value-i) - LC 3065
450. [Create Target Array in the Given Order](https://leetcode.com/problems/create-target-array-in-the-given-order) - LC 1389
451. [Decompress Run-Length Encoded List](https://leetcode.com/problems/decompress-run-length-encoded-list) - LC 1313
452. [Separate the Digits in an Array](https://leetcode.com/problems/separate-the-digits-in-an-array) - LC 2553
453. [Count Good Triplets](https://leetcode.com/problems/count-good-triplets) - LC 1534
454. [Count Items Matching a Rule](https://leetcode.com/problems/count-items-matching-a-rule) - LC 1773
455. [Special Array I](https://leetcode.com/problems/special-array-i) - LC 3151
456. [Maximum Product of Two Elements in an Array](https://leetcode.com/problems/maximum-product-of-two-elements-in-an-array) - LC 1464
457. [Sum of Squares of Special Elements](https://leetcode.com/problems/sum-of-squares-of-special-elements) - LC 2778
458. [Defuse the Bomb](https://leetcode.com/problems/defuse-the-bomb) - LC 1652
459. [Find All K-Distant Indices in an Array](https://leetcode.com/problems/find-all-k-distant-indices-in-an-array) - LC 2200
460. [Neither Minimum nor Maximum](https://leetcode.com/problems/neither-minimum-nor-maximum) - LC 2733
461. [Number of Students Doing Homework at a Given Time](https://leetcode.com/problems/number-of-students-doing-homework-at-a-given-time) - LC 1450
462. [Find the Peaks](https://leetcode.com/problems/find-the-peaks) - LC 2951
463. [Transformed Array](https://leetcode.com/problems/transformed-array) - LC 3379
464. [Replace Elements With Greatest Element on Right Side](https://leetcode.com/problems/replace-elements-with-greatest-element-on-right-side) - LC 1299
465. [Three Consecutive Odds](https://leetcode.com/problems/three-consecutive-odds) - LC 1550
466. [Sum of Good Numbers](https://leetcode.com/problems/sum-of-good-numbers) - LC 3452
467. [Count Hills and Valleys in an Array](https://leetcode.com/problems/count-hills-and-valleys-in-an-array) - LC 2210
468. [Find the Nearest Point That Has the Same X or Y Coordinate](https://leetcode.com/problems/find-nearest-point-that-has-the-same-x-or-y-coordinate) - LC 1779
469. [Minimum Distance Between Three Equal Elements I](https://leetcode.com/problems/minimum-distance-between-three-equal-elements-i) - LC 3740
470. [Smallest Index With Equal Value](https://leetcode.com/problems/smallest-index-with-equal-value) - LC 2057
471. [Minimum Sum of Mountain Triplets I](https://leetcode.com/problems/minimum-sum-of-mountain-triplets-i) - LC 2908
472. [Maximum Value of an Ordered Triplet I](https://leetcode.com/problems/maximum-value-of-an-ordered-triplet-i) - LC 2873
473. [Buy Two Chocolates](https://leetcode.com/problems/buy-two-chocolates) - LC 2706
474. [Distance Between Bus Stops](https://leetcode.com/problems/distance-between-bus-stops) - LC 1184
475. [Find Numbers With Even Number of Digits](https://leetcode.com/problems/find-numbers-with-even-number-of-digits) - LC 1295
476. [Max Consecutive Ones](https://leetcode.com/problems/max-consecutive-ones) - LC 485
477. [Slowest Key](https://leetcode.com/problems/slowest-key) - LC 1629
478. [Teemo Attacking](https://leetcode.com/problems/teemo-attacking) - LC 495
479. [Minimum Right Shifts to Sort the Array](https://leetcode.com/problems/minimum-right-shifts-to-sort-the-array) - LC 2855
480. [Check if Array Is Sorted and Rotated](https://leetcode.com/problems/check-if-array-is-sorted-and-rotated) - LC 1752
481. [Check if Array Is Good](https://leetcode.com/problems/check-if-array-is-good) - LC 2784
482. [Semi-Ordered Permutation](https://leetcode.com/problems/semi-ordered-permutation) - LC 2717
483. [Maximum Population Year](https://leetcode.com/problems/maximum-population-year) - LC 1854
484. [Average Salary Excluding the Minimum and Maximum Salary](https://leetcode.com/problems/average-salary-excluding-the-minimum-and-maximum-salary) - LC 1491
485. [Last Visited Integers](https://leetcode.com/problems/last-visited-integers) - LC 2899
486. [Longest Strictly Increasing or Strictly Decreasing Subarray](https://leetcode.com/problems/longest-strictly-increasing-or-strictly-decreasing-subarray) - LC 3105
487. [Longest Continuous Increasing Subsequence](https://leetcode.com/problems/longest-continuous-increasing-subsequence) - LC 674
488. [Maximum Ascending Subarray Sum](https://leetcode.com/problems/maximum-ascending-subarray-sum) - LC 1800
489. [Element Appearing More Than 25% In Sorted Array](https://leetcode.com/problems/element-appearing-more-than-25-in-sorted-array) - LC 1287
490. [Check if All 1's Are at Least Length K Places Away](https://leetcode.com/problems/check-if-all-1s-are-at-least-length-k-places-away) - LC 1437
491. [Longer Contiguous Segments of Ones Than Zeros](https://leetcode.com/problems/longer-contiguous-segments-of-ones-than-zeros) - LC 1869
492. [Monotonic Array](https://leetcode.com/problems/monotonic-array) - LC 896
493. [Find Indices With Index and Value Difference I](https://leetcode.com/problems/find-indices-with-index-and-value-difference-i) - LC 2903
494. [Third Maximum Number](https://leetcode.com/problems/third-maximum-number) - LC 414
495. [Count Subarrays of Length Three With a Condition](https://leetcode.com/problems/count-subarrays-of-length-three-with-a-condition) - LC 3392
496. [Largest Number At Least Twice of Others](https://leetcode.com/problems/largest-number-at-least-twice-of-others) - LC 747
497. [Trionic Array I](https://leetcode.com/problems/trionic-array-i) - LC 3637
498. [Find Closest Number to Zero](https://leetcode.com/problems/find-closest-number-to-zero) - LC 2239
499. [Determine the Winner of a Bowling Game](https://leetcode.com/problems/determine-the-winner-of-a-bowling-game) - LC 2660
500. [Maximum Difference Between Increasing Elements](https://leetcode.com/problems/maximum-difference-between-increasing-elements) - LC 2016
501. [Minimum Distance to the Target Element](https://leetcode.com/problems/minimum-distance-to-the-target-element) - LC 1848
502. [Longest Unequal Adjacent Groups Subsequence I](https://leetcode.com/problems/longest-unequal-adjacent-groups-subsequence-i) - LC 2900
503. [Adjacent Increasing Subarrays Detection I](https://leetcode.com/problems/adjacent-increasing-subarrays-detection-i) - LC 3349
504. [1-Bit and 2-Bit Characters](https://leetcode.com/problems/1-bit-and-2-bit-characters) - LC 717
505. [Longest Alternating Subarray](https://leetcode.com/problems/longest-alternating-subarray) - LC 2765
506. [Count the Number of Incremovable Subarrays I](https://leetcode.com/problems/count-the-number-of-incremovable-subarrays-i) - LC 2970
507. [Find the Largest Almost Missing Integer](https://leetcode.com/problems/find-the-largest-almost-missing-integer) - LC 3471
508. [Remove One Element to Make the Array Strictly Increasing](https://leetcode.com/problems/remove-one-element-to-make-the-array-strictly-increasing) - LC 1909
509. [Valid Mountain Array](https://leetcode.com/problems/valid-mountain-array) - LC 941
510. [Partition Array Into Three Parts With Equal Sum](https://leetcode.com/problems/partition-array-into-three-parts-with-equal-sum) - LC 1013
511. [Count Elements With Strictly Smaller and Greater Elements](https://leetcode.com/problems/count-elements-with-strictly-smaller-and-greater-elements) - LC 2148
512. [Longest Even-Odd Subarray With Threshold](https://leetcode.com/problems/longest-even-odd-subarray-with-threshold) - LC 2760
513. [Summary Ranges](https://leetcode.com/problems/summary-ranges) - LC 228
514. [Binary Prefix Divisible By 5](https://leetcode.com/problems/binary-prefix-divisible-by-5) - LC 1018
515. [Minimum Operations to Make Columns Strictly Increasing](https://leetcode.com/problems/minimum-operations-to-make-columns-strictly-increasing) - LC 3402
516. [Number of Lines to Write String](https://leetcode.com/problems/number-of-lines-to-write-string) - LC 806 (Array; also String)

## String (114)

517. [Score of a String](https://leetcode.com/problems/score-of-a-string) - LC 3110
518. [Final Value of Variable After Performing Operations](https://leetcode.com/problems/final-value-of-variable-after-performing-operations) - LC 2011
519. [Find Words Containing Character](https://leetcode.com/problems/find-words-containing-character) - LC 2942
520. [Defanging an IP Address](https://leetcode.com/problems/defanging-an-ip-address) - LC 1108
521. [Convert Date to Binary](https://leetcode.com/problems/convert-date-to-binary) - LC 3280
522. [Reverse Degree of a String](https://leetcode.com/problems/reverse-degree-of-a-string) - LC 3498
523. [Goal Parser Interpretation](https://leetcode.com/problems/goal-parser-interpretation) - LC 1678
524. [Split a String in Balanced Strings](https://leetcode.com/problems/split-a-string-in-balanced-strings) - LC 1221
525. [Truncate Sentence](https://leetcode.com/problems/truncate-sentence) - LC 1816
526. [Maximum Number of Words Found in Sentences](https://leetcode.com/problems/maximum-number-of-words-found-in-sentences) - LC 2114
527. [Reverse Prefix of Word](https://leetcode.com/problems/reverse-prefix-of-word) - LC 2000
528. [Check if Two String Arrays are Equivalent](https://leetcode.com/problems/check-if-two-string-arrays-are-equivalent) - LC 1662
529. [Shuffle String](https://leetcode.com/problems/shuffle-string) - LC 1528
530. [To Lower Case](https://leetcode.com/problems/to-lower-case) - LC 709
531. [Counting Words With a Given Prefix](https://leetcode.com/problems/counting-words-with-a-given-prefix) - LC 2185
532. [Check if the Sentence Is Pangram](https://leetcode.com/problems/check-if-the-sentence-is-pangram) - LC 1832
533. [Cells in a Range on an Excel Sheet](https://leetcode.com/problems/cells-in-a-range-on-an-excel-sheet) - LC 2194
534. [Sorting the Sentence](https://leetcode.com/problems/sorting-the-sentence) - LC 1859
535. [Reverse Words in a String III](https://leetcode.com/problems/reverse-words-in-a-string-iii) - LC 557
536. [Find First Palindromic String in the Array](https://leetcode.com/problems/find-first-palindromic-string-in-the-array) - LC 2108
537. [Number of Changing Keys](https://leetcode.com/problems/number-of-changing-keys) - LC 3019
538. [Decrypt String from Alphabet to Integer Mapping](https://leetcode.com/problems/decrypt-string-from-alphabet-to-integer-mapping) - LC 1309
539. [Remove Trailing Zeros From a String](https://leetcode.com/problems/remove-trailing-zeros-from-a-string) - LC 2710
540. [Determine if String Halves Are Alike](https://leetcode.com/problems/determine-if-string-halves-are-alike) - LC 1704
541. [Check if a String Is an Acronym of Words](https://leetcode.com/problems/check-if-a-string-is-an-acronym-of-words) - LC 2828
542. [Maximum Odd Binary Number](https://leetcode.com/problems/maximum-odd-binary-number) - LC 2864
543. [Replace All Digits With Characters](https://leetcode.com/problems/replace-all-digits-with-characters) - LC 1844
544. [Clear Digits](https://leetcode.com/problems/clear-digits) - LC 3174
545. [Check Balanced String](https://leetcode.com/problems/check-balanced-string) - LC 3340
546. [Number of Strings That Appear as Substrings in Word](https://leetcode.com/problems/number-of-strings-that-appear-as-substrings-in-word) - LC 1967
547. [Check if Digits Are Equal in String After Operations I](https://leetcode.com/problems/check-if-digits-are-equal-in-string-after-operations-i) - LC 3461
548. [Faulty Keyboard](https://leetcode.com/problems/faulty-keyboard) - LC 2810
549. [Count Prefixes and Suffixes Pairs I](https://leetcode.com/problems/count-prefix-and-suffix-pairs-i) - LC 3042
550. [Percentage of Letter in String](https://leetcode.com/problems/percentage-of-letter-in-string) - LC 2278
551. [Maximum Value of a String in an Array](https://leetcode.com/problems/maximum-value-of-a-string-in-an-array) - LC 2496
552. [Delete Characters to Make Fancy String](https://leetcode.com/problems/delete-characters-to-make-fancy-string) - LC 1957
553. [Split Strings by Separator](https://leetcode.com/problems/split-strings-by-separator) - LC 2788
554. [Furthest Point From Origin](https://leetcode.com/problems/furthest-point-from-origin) - LC 2833
555. [Check if All A's Appears Before All B's](https://leetcode.com/problems/check-if-all-as-appears-before-all-bs) - LC 2124
556. [Check if Numbers Are Ascending in a Sentence](https://leetcode.com/problems/check-if-numbers-are-ascending-in-a-sentence) - LC 2042
557. [Count Vowel Substrings of a String](https://leetcode.com/problems/count-vowel-substrings-of-a-string) - LC 2062
558. [Find the K-th Character in String Game I](https://leetcode.com/problems/find-the-k-th-character-in-string-game-i) - LC 3304
559. [Find the Original Typed String I](https://leetcode.com/problems/find-the-original-typed-string-i) - LC 3330
560. [Check if Word Equals Summation of Two Words](https://leetcode.com/problems/check-if-word-equals-summation-of-two-words) - LC 1880
561. [Sum of Digits of String After Convert](https://leetcode.com/problems/sum-of-digits-of-string-after-convert) - LC 1945
562. [Capitalize the Title](https://leetcode.com/problems/capitalize-the-title) - LC 2129
563. [Reformat Date](https://leetcode.com/problems/reformat-date) - LC 1507
564. [Reverse String II](https://leetcode.com/problems/reverse-string-ii) - LC 541
565. [Thousand Separator](https://leetcode.com/problems/thousand-separator) - LC 1556
566. [Count Binary Substrings](https://leetcode.com/problems/count-binary-substrings) - LC 696
567. [Rotate String](https://leetcode.com/problems/rotate-string) - LC 796
568. [Existence of a Substring in a String and Its Reverse](https://leetcode.com/problems/existence-of-a-substring-in-a-string-and-its-reverse) - LC 3083
569. [Consecutive Characters](https://leetcode.com/problems/consecutive-characters) - LC 1446
570. [Longest Nice Substring](https://leetcode.com/problems/longest-nice-substring) - LC 1763
571. [Check if Strings Can be Made Equal With Operations I](https://leetcode.com/problems/check-if-strings-can-be-made-equal-with-operations-i) - LC 2839
572. [Longest Uncommon Subsequence I](https://leetcode.com/problems/longest-uncommon-subsequence-i) - LC 521
573. [Odd String Difference](https://leetcode.com/problems/odd-string-difference) - LC 2451
574. [Number of Senior Citizens](https://leetcode.com/problems/number-of-senior-citizens) - LC 2678
575. [Substrings of Size Three With Distinct Characters](https://leetcode.com/problems/substrings-of-size-three-with-distinct-characters) - LC 1876
576. [String Matching in an Array](https://leetcode.com/problems/string-matching-in-an-array) - LC 1408
577. [Shortest Distance to a Character](https://leetcode.com/problems/shortest-distance-to-a-character) - LC 821
578. [Largest 3-Same-Digit Number in String](https://leetcode.com/problems/largest-3-same-digit-number-in-string) - LC 2264
579. [Circular Sentence](https://leetcode.com/problems/circular-sentence) - LC 2490
580. [Goat Latin](https://leetcode.com/problems/goat-latin) - LC 824
581. [Number of Valid Words in a Sentence](https://leetcode.com/problems/number-of-valid-words-in-a-sentence) - LC 2047
582. [Equal Score Substrings](https://leetcode.com/problems/equal-score-substrings) - LC 3707
583. [Reformat the String](https://leetcode.com/problems/reformat-the-string) - LC 1417
584. [Find the Encrypted String](https://leetcode.com/problems/find-the-encrypted-string) - LC 3210
585. [Longest Common Prefix](https://leetcode.com/problems/longest-common-prefix) - LC 14
586. [Substring Matching Pattern](https://leetcode.com/problems/substring-matching-pattern) - LC 3407
587. [Find the K-Beauty of a Number](https://leetcode.com/problems/find-the-k-beauty-of-a-number) - LC 2269
588. [Length of Last Word](https://leetcode.com/problems/length-of-last-word) - LC 58
589. [Repeated Substring Pattern](https://leetcode.com/problems/repeated-substring-pattern) - LC 459
590. [Detect Capital](https://leetcode.com/problems/detect-capital) - LC 520
591. [Maximum Repeating Substring](https://leetcode.com/problems/maximum-repeating-substring) - LC 1668
592. [Lexicographically Smallest String After a Swap](https://leetcode.com/problems/lexicographically-smallest-string-after-a-swap) - LC 3216
593. [Find the Longest Balanced Substring of a Binary String](https://leetcode.com/problems/find-the-longest-balanced-substring-of-a-binary-string) - LC 2609
594. [License Key Formatting](https://leetcode.com/problems/license-key-formatting) - LC 482
595. [Reformat Phone Number](https://leetcode.com/problems/reformat-phone-number) - LC 1694
596. [Largest Odd Number in String](https://leetcode.com/problems/largest-odd-number-in-string) - LC 1903
597. [Check if One String Swap Can Make Strings Equal](https://leetcode.com/problems/check-if-one-string-swap-can-make-strings-equal) - LC 1790
598. [Check if Binary String Has At Most One Segment of Ones](https://leetcode.com/problems/check-if-binary-string-has-at-most-one-segment-of-ones) - LC 1784
599. [Remove Digit From Number to Maximize Result](https://leetcode.com/problems/remove-digit-from-number-to-maximize-result) - LC 2259
600. [Positions of Large Groups](https://leetcode.com/problems/positions-of-large-groups) - LC 830
601. [Vowel Consonant Score](https://leetcode.com/problems/vowel-consonant-score) - LC 3813
602. [Rearrange Spaces Between Words](https://leetcode.com/problems/rearrange-spaces-between-words) - LC 1592
603. [Latest Time by Replacing Hidden Digits](https://leetcode.com/problems/latest-time-by-replacing-hidden-digits) - LC 1736
604. [Latest Time You Can Obtain After Replacing Characters](https://leetcode.com/problems/latest-time-you-can-obtain-after-replacing-characters) - LC 3114
605. [Find Special Substring of Length K](https://leetcode.com/problems/find-special-substring-of-length-k) - LC 3456
606. [Make Three Strings Equal](https://leetcode.com/problems/make-three-strings-equal) - LC 2937
607. [Generate Tag for Video Caption](https://leetcode.com/problems/generate-tag-for-video-caption) - LC 3582
608. [Calculate Digit Sum of a String](https://leetcode.com/problems/calculate-digit-sum-of-a-string) - LC 2243
609. [Detect Pattern of Length M Repeated K or More Times](https://leetcode.com/problems/detect-pattern-of-length-m-repeated-k-or-more-times) - LC 1566
610. [Check if a Word Occurs As a Prefix of Any Word in a Sentence](https://leetcode.com/problems/check-if-a-word-occurs-as-a-prefix-of-any-word-in-a-sentence) - LC 1455
611. [Count Prefixes of a Given String](https://leetcode.com/problems/count-prefixes-of-a-given-string) - LC 2255
612. [Count the Number of Vowel Strings in Range](https://leetcode.com/problems/count-the-number-of-vowel-strings-in-range) - LC 2586
613. [Check if String Is a Prefix of Array](https://leetcode.com/problems/check-if-string-is-a-prefix-of-array) - LC 1961
614. [Shortest Distance to Target String in a Circular Array](https://leetcode.com/problems/shortest-distance-to-target-string-in-a-circular-array) - LC 2515
615. [Student Attendance Record I](https://leetcode.com/problems/student-attendance-record-i) - LC 551
616. [Number of Segments in a String](https://leetcode.com/problems/number-of-segments-in-a-string) - LC 434
617. [Number of Different Integers in a String](https://leetcode.com/problems/number-of-different-integers-in-a-string) - LC 1805
618. [Occurrences After Bigram](https://leetcode.com/problems/occurrences-after-bigram) - LC 1078
619. [Remove Palindromic Subsequences](https://leetcode.com/problems/remove-palindromic-subsequences) - LC 1332 (String; also Greedy)
620. [Second Largest Digit in a String](https://leetcode.com/problems/second-largest-digit-in-a-string) - LC 1796
621. [Check if Two Events Have Conflict](https://leetcode.com/problems/determine-if-two-events-have-conflict) - LC 2446
622. [Valid Word](https://leetcode.com/problems/valid-word) - LC 3136
623. [Count the Number of Special Characters I](https://leetcode.com/problems/count-the-number-of-special-characters-i) - LC 3120
624. [Minimum Changes to Make Alternating Binary String](https://leetcode.com/problems/minimum-changes-to-make-alternating-binary-string) - LC 1758
625. [Minimum Number of Pushes to Type Word I](https://leetcode.com/problems/minimum-number-of-pushes-to-type-word-i) - LC 3014
626. [Number of Valid Clock Times](https://leetcode.com/problems/number-of-valid-clock-times) - LC 2437
627. [Count Substrings That Satisfy K-Constraint I](https://leetcode.com/problems/count-substrings-that-satisfy-k-constraint-i) - LC 3258
628. [Minimum Moves to Convert String](https://leetcode.com/problems/minimum-moves-to-convert-string) - LC 2027
629. [Replace All ?'s to Avoid Consecutive Repeating Characters](https://leetcode.com/problems/replace-all-s-to-avoid-consecutive-repeating-characters) - LC 1576
630. [Minimum Number of Flips to Reverse Binary String](https://leetcode.com/problems/minimum-number-of-flips-to-reverse-binary-string) - LC 3750

---

## Summary

| Category                    | Count   |
| --------------------------- | ------- |
| LinkedList                  | 8       |
| Tree                        | 24      |
| BST                         | 8       |
| N-ary Tree                  | 3       |
| Stack                       | 13      |
| Queue                       | 4       |
| Heap                        | 3       |
| Matrix                      | 23      |
| Simulation / Implementation | 16      |
| Design                      | 6       |
| Sorting                     | 39      |
| Binary Search               | 11      |
| Two Pointers                | 18      |
| Sliding Window              | 6       |
| Prefix Sum                  | 11      |
| Math                        | 115     |
| Bit Manipulation            | 21      |
| Recursion                   | 0       |
| Greedy                      | 1       |
| DP                          | 3       |
| **Set**                     | 37      |
| **Map**                     | 69      |
| **Array**                   | 77      |
| **String**                  | 114     |
| **Total**                   | **630** |

> **Note**: counts above are an approximate tally; the post contents are authoritative. Problems with multiple valid classifications were assigned to the **most specific** category.

---

## Notes

- **The order is most specific → most general.** A problem is classified by its **primary** technique. If two techniques apply equally, the more specific one wins (e.g. "Two Sum IV - Input is a BST" → BST, not Map).
- **Set and Map are the bridge categories** — used when no specific data structure is forced, but a hash set or hash map is essential for the optimal solution.
- **Array** is the fallback for problems that just walk through an array without a special data structure or technique. **String** is the final fallback.
- Some problems intentionally appear in **two categories** (linked from the secondary one in parentheses) for visibility — e.g. _Intersection of Two Linked Lists_ is primarily LinkedList but can also be solved with a Set.

---

Good luck, and happy learning!

---

This page might get updated from time to time.
I also posted this in LeetCode, it might become old soon - https://leetcode.com/discuss/post/8308959/all-leetcode-easy-problems-categorized-b-ryyv/
