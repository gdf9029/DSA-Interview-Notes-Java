# 30-Day DSA Plan — Algorithm Design & Implementation (Java)

This plan follows the attached 24CSE0317 course outline. It treats “get acquainted” as: attempt the problem yourself, understand a correct approach, write or trace the solution, and record its time/space complexity. It does not promise mastery of every advanced topic in 30 days.

## Priority and daily routine

The PDF labels **Units 1–5 as ST-1 (60% of the syllabus)** and **Units 6–9 as ST-2 (40%)**. Days 1–21 prioritize ST-1; Days 22–30 are a first pass through the rest of the outline.

Plan for about **4–5 hours a day**:

1. 20 min: recall yesterday’s patterns without notes.
2. 35–45 min: watch only the relevant video section; take 5–8 bullet notes.
3. 2.5–3 hours: solve the scheduled problems in Java. Give each a 25-minute independent attempt; then use a hint/editorial if needed, close it, and reproduce the solution yourself.
4. 20 min: log the pattern, complexity, mistake, and a date to retry. Re-attempt missed problems the next day and again 3–4 days later.

For LeetCode, use Java. Some lab prompts are implementation exercises rather than exact LeetCode questions; for those, write a small `main`/test harness or use the closest equivalent listed below. The outline does not include the statements for “Noise in the Library,” “balance a scale,” or its 30 contest questions, so use your instructor’s handout for those exact inputs/outputs. The outline has 45 named lab tasks and 30 additional contest slots. It does not give the contest prompts or full statements for three named hashing exercises; the schedule touches every named task and reserves all 30 contest slots. Treat the advanced-unit days as a first pass, not proof of mastery.

## Day-by-day schedule

| Day | Focus and work to complete |
|---|---|
| 1 | **Unit 1:** Big-O; time vs space; analyze loops and a recursive function. Implement prime factorization and Euclidean GCD. LeetCode practice: [Distinct Prime Factors of Product of Array](https://leetcode.com/problems/distinct-prime-factors-of-product-of-array/) and [Find Greatest Common Divisor of Array](https://leetcode.com/problems/find-greatest-common-divisor-of-array/). |
| 2 | Finish **Unit 1**: Josephus/distribute-in-a-circle ([Find the Winner of the Circular Game](https://leetcode.com/problems/find-the-winner-of-the-circular-game/)); compare brute-force and improved Two Sum ([Two Sum](https://leetcode.com/problems/two-sum/)); describe one randomized algorithm and solve [Shuffle an Array](https://leetcode.com/problems/shuffle-an-array/); implement a divide-and-conquer sort ([Sort an Array](https://leetcode.com/problems/sort-an-array/)). |
| 3 | **Unit 2:** prefix/suffix sums and difference arrays; two pointers. Solve pair sum K with a sorted array ([Two Sum II](https://leetcode.com/problems/two-sum-ii-input-array-is-sorted/)). Begin Practice Contest 2: 1 of its 3 medium array problems. |
| 4 | Fixed-size sliding window; solve maximum sum of a size-*k* window (LeetCode equivalent: [Maximum Average Subarray I](https://leetcode.com/problems/maximum-average-subarray-i/)). Finish Contest 2’s other 2 array problems. |
| 5 | In-place reversal, array rotation, partitioning. Solve [Rotate Array](https://leetcode.com/problems/rotate-array/). Begin Practice Contest 3: one mixed array/string problem. |
| 6 | String reverse, palindrome, anagram, compression, substrings. Solve [Valid Anagram](https://leetcode.com/problems/valid-anagram/), then finish Contest 3’s other 2 mixed problems. |
| 7 | Binary search; KMP prefix-function basics; Z-function; string matching and rolling-hash idea. Implement one search template; try [Find the Index of the First Occurrence in a String](https://leetcode.com/problems/find-the-index-of-the-first-occurrence-in-a-string/) and [Repeated DNA Sequences](https://leetcode.com/problems/repeated-dna-sequences/). |
| 8 | 1D DP on arrays: solve **LIS** ([Longest Increasing Subsequence](https://leetcode.com/problems/longest-increasing-subsequence/)) and **LCS** ([Longest Common Subsequence](https://leetcode.com/problems/longest-common-subsequence/)). Write the state, transition, base case, and complexity for each. |
| 9 | **Unit 3:** greedy choice, proof intuition, exchange argument, interval scheduling/activity selection. Solve [Non-overlapping Intervals](https://leetcode.com/problems/non-overlapping-intervals/) and [Minimum Number of Arrows to Burst Balloons](https://leetcode.com/problems/minimum-number-of-arrows-to-burst-balloons/). |
| 10 | Fractional knapsack, coin/fraction and min/max greedy examples. Implement fractional knapsack from a small custom input; compare its greedy choice with a case where greedy coin-change fails. |
| 11 | Job scheduling with deadlines/profit, meeting/task scheduling, greedy with sorting and priority queues. Implement the course’s job-sequencing exercise; use [Meeting Rooms II](https://leetcode.com/problems/meeting-rooms-ii/) for interval/heap practice. Complete Practice Contest 4: 3 greedy problems. |
| 12 | Greedy on strings (lexicographic/reordering) and greedy + DP hybrids. Complete Practice Contest 5: 3 mixed greedy/array/string problems. Re-solve the hardest miss from Days 9–11. |
| 13 | **Unit 4:** implement stack operations using an array; balanced parentheses ([Valid Parentheses](https://leetcode.com/problems/valid-parentheses/)); expression evaluation ([Evaluate Reverse Polish Notation](https://leetcode.com/problems/evaluate-reverse-polish-notation/)). |
| 14 | Monotonic stack and next-greater-element pattern ([Next Greater Element I](https://leetcode.com/problems/next-greater-element-i/)). Complete Practice Contest 6: 3 stack/queue problems; for each, identify whether a stack, queue, or deque fits. |
| 15 | Queue, circular queue, deque; implement the circular queue ([Design Circular Queue](https://leetcode.com/problems/design-circular-queue/)); solve sliding-window maximum ([Sliding Window Maximum](https://leetcode.com/problems/sliding-window-maximum/)). Review stack + greedy/DP combinations. |
| 16 | **Unit 5:** Java `HashMap`/`HashSet`, frequency counting, collisions (chaining vs open addressing). Attempt “Noise in the Library” from the instructor’s statement; do a HashMap frequency-count voting solution (practice: [Majority Element](https://leetcode.com/problems/majority-element/)). Begin Contest 7: 1 hashing problem. |
| 17 | Two Sum variants; “balance a scale with given weights” (use a HashSet of reachable sums; LeetCode practice: [Partition Equal Subset Sum](https://leetcode.com/problems/partition-equal-subset-sum/)); solve [Subarray Sum Equals K](https://leetcode.com/problems/subarray-sum-equals-k/). Contest 7: problem 2. |
| 18 | Subarray constraints, coordinate compression, string hashing/rolling hash and substring search. Use [Longest Duplicate Substring](https://leetcode.com/problems/longest-duplicate-substring/) to inspect rolling-hash tradeoffs. Contest 7: problem 3. |
| 19 | Map-based DP; solve [Word Break](https://leetcode.com/problems/word-break/) and one mixed hashing problem. Revisit the most error-prone concepts from Units 1–5. |
| 20 | **ST-1 review:** make a one-page pattern sheet for complexity, arrays/strings, greedy, stack/queue, hashing. Do a 90-minute closed-notes mixed set drawn from the problems already attempted. |
| 21 | **ST-1 mock and repair:** take a second timed set; review every miss and re-code at least 3 from a blank editor. Prioritize this day if the exam falls before Day 30. |
| 22 | **Unit 6:** recursion trees, base cases, DFS; implement Tower of Hanoi and generating binary strings of length *n*. Start Practice Contest 8: 1 backtracking problem. |
| 23 | Backtracking: subsets ([Subsets](https://leetcode.com/problems/subsets/)), string permutations ([Permutations](https://leetcode.com/problems/permutations/)), combinations ([Combinations](https://leetcode.com/problems/combinations/)), robot/grid paths ([Unique Paths](https://leetcode.com/problems/unique-paths/)). Finish Contest 8’s other 2 problems. |
| 24 | Backtracking with pruning: Sudoku ([Sudoku Solver](https://leetcode.com/problems/sudoku-solver/)), N-Queens ([N-Queens](https://leetcode.com/problems/n-queens/)), and Rat in a Maze/all paths (custom grid DFS; related: [Unique Paths III](https://leetcode.com/problems/unique-paths-iii/)). Contest 9: 3 mixed recursion/backtracking problems; at minimum attempt each and fully code one. |
| 25 | DP applications: 0/1 knapsack (practice equivalent: [Partition Equal Subset Sum](https://leetcode.com/problems/partition-equal-subset-sum/)); count ways using steps 1/2/3 (related: [N-th Tribonacci Number](https://leetcode.com/problems/n-th-tribonacci-number/)); Matrix Chain Multiplication (custom interval-DP table; related: [Minimum Score Triangulation of Polygon](https://leetcode.com/problems/minimum-score-triangulation-of-polygon/)). |
| 26 | **Unit 7:** implement preorder/inorder/postorder ([Binary Tree Preorder Traversal](https://leetcode.com/problems/binary-tree-preorder-traversal/), [Inorder](https://leetcode.com/problems/binary-tree-inorder-traversal/), [Postorder](https://leetcode.com/problems/binary-tree-postorder-traversal/)); height ([Maximum Depth of Binary Tree](https://leetcode.com/problems/maximum-depth-of-binary-tree/)); BST LCA ([Lowest Common Ancestor of a Binary Search Tree](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-search-tree/)); kth smallest ([Kth Smallest Element in a BST](https://leetcode.com/problems/kth-smallest-element-in-a-bst/)). Contest 10: 3 tree problems; use 1 as a fully coded timed problem. |
| 27 | Trees/BST/trie: search/insert/delete, validation, range sum, floor/ceil; diameter and path sum; max-independent-set idea; trie insert/search/prefix ([Implement Trie](https://leetcode.com/problems/implement-trie-prefix-tree/)). Contest 11: 3 mixed tree/DP problems; attempt all, code one fully, explain the other two. |
| 28 | **Unit 8:** min/max heap, Java `PriorityQueue`, stream min/max (practice: [Kth Largest Element in a Stream](https://leetcode.com/problems/kth-largest-element-in-a-stream/)); implement heap sort; write a checker for the max-heap property. |
| 29 | **Unit 9:** adjacency list, BFS/DFS, connected components, cycle detection, bipartite check; minimum-edge path by BFS; directed path ([All Paths From Source to Target](https://leetcode.com/problems/all-paths-from-source-to-target/)); number of islands ([Number of Islands](https://leetcode.com/problems/number-of-islands/)). |
| 30 | Shortest paths and graph algorithms: unweighted shortest path, Dijkstra ([Network Delay Time](https://leetcode.com/problems/network-delay-time/)), Bellman–Ford (custom graph with a negative edge), DSU, Kruskal/Prim (related: [Min Cost to Connect All Points](https://leetcode.com/problems/min-cost-to-connect-all-points/)), topological sort ([Course Schedule](https://leetcode.com/problems/course-schedule/)), DAG path/counting DP, and shortest-path DP. Finish by re-solving 2 ST-1 misses. |

### Reserved practice-contest slots

The PDF specifies the number and topic of these contest problems, but does not give the actual questions. Use course handouts if available; otherwise select unseen LeetCode problems of the matching topic/difficulty:

- Contest 2: 3 medium array problems (Day 4).
- Contest 3: 3 mixed array/string problems (Days 5–6).
- Contest 4: 3 greedy problems (Day 11).
- Contest 5: 3 mixed greedy + array/string problems (Day 12).
- Contest 6: 3 stack/queue problems (Day 14).
- Contest 7: 3 hashing/mapping problems (Days 16–18).
- Contests 8–9: 3 backtracking and 3 mixed recursion/backtracking problems (Days 22–24).
- Contests 10–11: 3 tree and 3 mixed tree/DP problems (Days 26–27).

## YouTube links

The course outline itself supplies these topic videos. Most teach the algorithm in another language; use them for the idea, then implement it in Java. The official Kunal playlist is the Java-first reference; the syllabus is at [Kunal’s course page](https://www.techwithkunal.com/courses/dsa).

- [Kunal Kushwaha — Java + DSA course playlist](https://www.youtube.com/playlist?list=PL9gnSGHSqcnr_DxHsP7AW9ftq0AtAyYqJ) — Java implementation reference; his official syllabus includes arrays, search/sort, complexity, recursion, linked data structures, trees, hashing, DP, heaps, and graphs.
- [Abdul Bari — Time complexity / algorithm analysis](https://www.youtube.com/watch?v=HfIH3czXc-8)
- [freeCodeCamp — Data Structures and Algorithms full course](https://www.youtube.com/watch?v=RBSGKlAvoiM)
- [Abdul Bari — Greedy method](https://www.youtube.com/watch?v=ARvQcqJ_-NY)
- [freeCodeCamp — Stack data structure](https://www.youtube.com/watch?v=wjI1WNcIntg)
- [Abdul Bari — Hashing](https://www.youtube.com/watch?v=shs0KM3wKv8)
- [Recursion and backtracking](https://www.youtube.com/watch?v=DKCbsiDBN6c)
- [William Fiset — Binary trees and BST](https://www.youtube.com/watch?v=fAAZixBzIAI)
- [Abdul Bari — Heap data structure](https://www.youtube.com/watch?v=t0Cq6tVNRBA)
- [William Fiset — Graph theory](https://www.youtube.com/watch?v=09_LlHjoEiY)
- [Striver A2Z DSA playlist](https://www.youtube.com/playlist?list=PLgUwDviBIf0oF6QL8m22w1hIDC1vJ_BHz) — optional topic-wise explanations and problem walk-throughs.
- [LeetCode Study Plans](https://leetcode.com/studyplan/) — optional topic practice lists.

For a one-month sprint, don’t watch a full course end-to-end. Watch the section for the day, then spend most of the session coding and reviewing misses. The Kunal Java course is explicitly organized around DSA concepts implemented in Java; the TakeUForward A2Z course and NeetCode roadmaps are useful topic/problem indexes, but their video code may use C++ or Python.
