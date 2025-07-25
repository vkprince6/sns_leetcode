# LeetCode Problems - Concepts, Related Practice & Links

Summarizes the key concepts learned from each problem, along with 2 related practice problems and direct LeetCode links.

---

## Arrays & Strings (Sliding Window, Binary Search, Matrix)

| Problem | Concepts Learned | Related Practice |
|---------|-----------------|------------------|
| [Rotate Image (48)](https://leetcode.com/problems/rotate-image/) | In-place matrix rotation using transpose + reverse; index mapping `(i,j)->(j,n-1-i)` | [Spiral Matrix (54)](https://leetcode.com/problems/spiral-matrix/), [Spiral Matrix II (59)](https://leetcode.com/problems/spiral-matrix-ii/) |
| [Spiral Matrix (54)](https://leetcode.com/problems/spiral-matrix/) | Matrix traversal layer by layer with boundary pointers | [Spiral Matrix II (59)](https://leetcode.com/problems/spiral-matrix-ii/), [Merge Sorted Array (88)](https://leetcode.com/problems/merge-sorted-array/) |
| [Search in Rotated Sorted Array (33)](https://leetcode.com/problems/search-in-rotated-sorted-array/) | Modified binary search in rotated sorted array | [Search in Rotated Sorted Array II (81)](https://leetcode.com/problems/search-in-rotated-sorted-array-ii/), [Find Peak Element (162)](https://leetcode.com/problems/find-peak-element/) |
| [Find Minimum in Rotated Sorted Array (153)](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array/) | Binary search to find rotation pivot (min element) | [Find Minimum in Rotated Sorted Array II (154)](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array-ii/), [First Bad Version (278)](https://leetcode.com/problems/first-bad-version/) |
| [Longest Repeating Character Replacement (424)](https://leetcode.com/problems/longest-repeating-character-replacement/) | Sliding window, frequency count, max freq in window | [Longest Substring Without Repeating (3)](https://leetcode.com/problems/longest-substring-without-repeating-characters/), [Longest Substring with At Most K Distinct (340)](https://leetcode.com/problems/longest-substring-with-at-most-k-distinct-characters/) |
| [Sliding Window Maximum (239)](https://leetcode.com/problems/sliding-window-maximum/) | Sliding window with monotonic deque | [Minimum Window Substring (76)](https://leetcode.com/problems/minimum-window-substring/), [Shortest Subarray with Sum >= K (862)](https://leetcode.com/problems/shortest-subarray-with-sum-at-least-k/) |
| [Minimum Size Subarray Sum (209)](https://leetcode.com/problems/minimum-size-subarray-sum/) | Sliding window two-pointer technique for minimal length | [Fruit Into Baskets (904)](https://leetcode.com/problems/fruit-into-baskets/), [3Sum Closest](https://leetcode.com/problems/3sum-closest/) |
| [Largest Rectangle in Histogram (84)](https://leetcode.com/problems/largest-rectangle-in-histogram/) | Monotonic stack to find nearest smaller left/right | [Maximal Rectangle (85)](https://leetcode.com/problems/maximal-rectangle/), [Count Submatrices With All Ones (1504)](https://leetcode.com/problems/count-submatrices-with-all-ones/) |
| [Maximal Rectangle (85)](https://leetcode.com/problems/maximal-rectangle/) | 2D -> histogram heights + Largest Rectangle in Histogram | [Count Submatrices With All Ones (1504)](https://leetcode.com/problems/count-submatrices-with-all-ones/), [N-Queens II (52)](https://leetcode.com/problems/n-queens-ii/) |
| [Find All Anagrams in a String (438)](https://leetcode.com/problems/find-all-anagrams-in-a-string/) | Sliding window with char frequency array | [Minimum Window Substring (76)](https://leetcode.com/problems/minimum-window-substring/), [Permutation in String (567)](https://leetcode.com/problems/permutation-in-string/) |

---

## Linked List & Advanced Data Structures

| Problem | Concepts Learned | Related Practice |
|---------|-----------------|------------------|
| [Copy List with Random Pointer (138)](https://leetcode.com/problems/copy-list-with-random-pointer/) | Deep copy with hash map or interleaving | [Intersection of Two Linked Lists (160)](https://leetcode.com/problems/intersection-of-two-linked-lists/), [Populating Next Right Pointers (117)](https://leetcode.com/problems/populating-next-right-pointers-in-each-node-ii/) |
| [Sort List (148)](https://leetcode.com/problems/sort-list/) | Merge sort on linked list; split using slow/fast pointer | [Merge Two Sorted Lists (21)](https://leetcode.com/problems/merge-two-sorted-lists/), [Merge k Sorted Lists (23)](https://leetcode.com/problems/merge-k-sorted-lists/) |
| [Intersection of Two Linked Lists (160)](https://leetcode.com/problems/intersection-of-two-linked-lists/) | Two-pointer technique to detect intersection | [Linked List Cycle II (142)](https://leetcode.com/problems/linked-list-cycle-ii/), [Palindrome Linked List (234)](https://leetcode.com/problems/palindrome-linked-list/) |
| [Flatten a Multilevel Doubly Linked List (430)](https://leetcode.com/problems/flatten-a-multilevel-doubly-linked-list/) | DFS or stack-based traversal to flatten hierarchy | [Binary Tree Right Side View (199)](https://leetcode.com/problems/binary-tree-right-side-view/), [As Far from Land as Possible (1162)](https://leetcode.com/problems/as-far-from-land-as-possible/) |
| [Design Skiplist (1206)](https://leetcode.com/problems/design-skiplist/) | Probabilistic multi-level list for O(log n) ops | [LRU Cache (146)](https://leetcode.com/problems/lru-cache/), [Design Linked List (707)](https://leetcode.com/problems/design-linked-list/) |
| [Design Twitter (355)](https://leetcode.com/problems/design-twitter/) | System design: min-heap or ordered feed + user graph | [Insert Delete GetRandom O(1) (380)](https://leetcode.com/problems/insert-delete-getrandom-o1/), [Flatten Nested List Iterator (341)](https://leetcode.com/problems/flatten-nested-list-iterator/) |

---

## Graphs & BFS/DFS/Union-Find

| Problem | Concepts Learned | Related Practice |
|---------|-----------------|------------------|
| [Number of Islands (200)](https://leetcode.com/problems/number-of-islands/) | BFS/DFS flood-fill on grid, count components | [Max Area of Island (695)](https://leetcode.com/problems/max-area-of-island/), [Island Perimeter (463)](https://leetcode.com/problems/island-perimeter/) |
| [Max Area of Island (695)](https://leetcode.com/problems/max-area-of-island/) | DFS/BFS area aggregation for connected components | [Flood Fill (733)](https://leetcode.com/problems/flood-fill/), [Number of Enclaves (1020)](https://leetcode.com/problems/number-of-enclaves/) |
| [Clone Graph (133)](https://leetcode.com/problems/clone-graph/) | Graph traversal BFS/DFS + hash map for deep copy | [Copy List with Random Pointer (138)](https://leetcode.com/problems/copy-list-with-random-pointer/), [Graph Valid Tree (261)](https://leetcode.com/problems/graph-valid-tree/) |
| [Pacific Atlantic Water Flow (417)](https://leetcode.com/problems/pacific-atlantic-water-flow/) | Multi-source BFS/DFS from ocean borders | [Surrounded Regions (130)](https://leetcode.com/problems/surrounded-regions/), [01 Matrix (542)](https://leetcode.com/problems/01-matrix/) |
| [Surrounded Regions (130)](https://leetcode.com/problems/surrounded-regions/) | Multi-source flood-fill from boundary | [Pacific Atlantic Water Flow (417)](https://leetcode.com/problems/pacific-atlantic-water-flow/), [Flood Fill (733)](https://leetcode.com/problems/flood-fill/) |
| [Word Search II (212)](https://leetcode.com/problems/word-search-ii/) | Backtracking with Trie pruning | [Word Search (79)](https://leetcode.com/problems/word-search/), [Longest Word in Dictionary (720)](https://leetcode.com/problems/longest-word-in-dictionary/) |
| [Minimum Height Trees (310)](https://leetcode.com/problems/minimum-height-trees/) | Tree centroids via leaf trimming (BFS layers) | [Course Schedule (207)](https://leetcode.com/problems/course-schedule/), [Graph Valid Tree (261)](https://leetcode.com/problems/graph-valid-tree/) |
| [Redundant Connection (684)](https://leetcode.com/problems/redundant-connection/) | Union-Find to detect first cycle edge | [Redundant Connection II (685)](https://leetcode.com/problems/redundant-connection-ii/), [Graph Valid Tree (261)](https://leetcode.com/problems/graph-valid-tree/) |
| [Graph Valid Tree (261)](https://leetcode.com/problems/graph-valid-tree/) | Connectivity + acyclicity check with DFS or Union-Find | [Number of Connected Components (323)](https://leetcode.com/problems/number-of-connected-components-in-an-undirected-graph/), [Course Schedule (207)](https://leetcode.com/problems/course-schedule/) |
| [Network Delay Time (743)](https://leetcode.com/problems/network-delay-time/) | Dijkstra’s algorithm (min-heap) or Bellman-Ford for shortest path | [Cheapest Flights Within K Stops (787)](https://leetcode.com/problems/cheapest-flights-within-k-stops/), [Path With Minimum Effort (1631)](https://leetcode.com/problems/path-with-minimum-effort/) |
| [Alien Dictionary (269)](https://leetcode.com/problems/alien-dictionary/) | Topological sort on directed graph (Kahn’s algorithm / DFS) | [Course Schedule II (210)](https://leetcode.com/problems/course-schedule-ii/), [Sequence Reconstruction (444)](https://leetcode.com/problems/sequence-reconstruction/) |

---

## Advanced Heaps & Intervals

| Problem | Concepts Learned | Related Practice |
|---------|-----------------|------------------|
| [Find Median from Data Stream (295)](https://leetcode.com/problems/find-median-from-data-stream/) | Two heaps (max-heap + min-heap) to maintain streaming median | [Sliding Window Median (480)](https://leetcode.com/problems/sliding-window-median/), [IPO (502)](https://leetcode.com/problems/ipo/) |
| [Sliding Window Median (480)](https://leetcode.com/problems/sliding-window-median/) | Dual heaps with lazy removal or multiset balancing | [Find Median from Data Stream (295)](https://leetcode.com/problems/find-median-from-data-stream/), [Kth Largest Element in a Stream (703)](https://leetcode.com/problems/kth-largest-element-in-a-stream/) |
| [Task Scheduler (621)](https://leetcode.com/problems/task-scheduler/) | Greedy with max-heap for task frequencies + cooldown intervals | [Reorganize String (767)](https://leetcode.com/problems/reorganize-string/), [Minimum Interval to Include Each Query (1851)](https://leetcode.com/problems/minimum-interval-to-include-each-query/) |
| [Minimum Number of Arrows to Burst Balloons (452)](https://leetcode.com/problems/minimum-number-of-arrows-to-burst-balloons/) | Greedy interval scheduling by sorting end points | [Non-overlapping Intervals (435)](https://leetcode.com/problems/non-overlapping-intervals/), [Merge Intervals (56)](https://leetcode.com/problems/merge-intervals/) |
| [Car Fleet (853)](https://leetcode.com/problems/car-fleet/) | Sort + stack-based simulation of fleet merging | [Car Fleet II (1776)](https://leetcode.com/problems/car-fleet-ii/), [Minimum Number of Arrows to Burst Balloons (452)](https://leetcode.com/problems/minimum-number-of-arrows-to-burst-balloons/) |
| [Minimum Interval to Include Each Query (1851)](https://leetcode.com/problems/minimum-interval-to-include-each-query/) | Sort + min-heap for active intervals | [Meeting Rooms II (253)](https://leetcode.com/problems/meeting-rooms-ii/), [Task Scheduler (621)](https://leetcode.com/problems/task-scheduler/) |

---

## Key Techniques Covered

- **Sliding Window**: character replacement, window maximum, minimal subarray sum  
- **Binary Search Variants**: rotated arrays, peak finding, pivot search  
- **Monotonic Stack**: largest rectangle in histogram, maximal rectangle  
- **Graph Traversals (BFS/DFS)**: islands, Pacific Atlantic, clone graph  
- **Shortest Path & Topological Sort**: Dijkstra, Kahn’s algorithm  
- **Union-Find (DSU)**: redundant connections, valid tree detection  
- **Linked List Techniques**: two-pointer, merge sort, deep copy  
- **Backtracking + Trie**: word search II  
- **Greedy + Sorting for Intervals**: car fleet, arrows, meeting rooms  
- **Heaps/Priority Queues**: median data stream, task scheduler  
- **System Design**: skiplist, mini-twitter  

---
