# 🌙 Project 37: Moon Orbit

A 2D solar system animation demonstrating CSS `@keyframes` mechanics, coordinate centering, and transform function ordering.

## 🛠️ Key Architectural Concepts Mastered

1. **Transform Execution Order (`translate` vs `rotate`):**
   * Placed `translate(-50%, -50%)` before `rotate()` in keyframes to maintain fixed coordinate alignment over the parent center during 360-degree rotations.

2. **Absolute Parent-Child Coordinate Alignment:**
   * Combined `top: 50%` and `left: 50%` positioning anchors with negative offsets to center orbital paths directly over target elements.

3. **Infinite Keyframe Cycles:**
   * Configured smooth, continuous orbital rotation using `animation: orbit 5s linear infinite`.