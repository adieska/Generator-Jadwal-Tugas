## 2025-05-03 - Avoid O(N) Array Filtering inside Nested Component Map Loops
**Learning:** Calling array filter methods inside render map loops (e.g. `items.filter(...)` for each member in each role pool) leads to O(N * M) time complexity per render, causing input lag during user keystrokes.
**Action:** Pre-compute role duty counts into an O(1) hash map `roleDutyCounts` using `useMemo` so member tag renders can look up duty counts instantly.
