# Unexpected Behavior of removeIf on Mutable Collections in Kotlin

This example demonstrates a potential point of confusion when using the `removeIf` function with mutable collections (Lists and Sets) in Kotlin.  The function modifies the original collection directly, which might not be immediately obvious to developers accustomed to immutable approaches.

The `bug.kt` file shows how `removeIf` alters the `list` and `set` collections in place.

The `bugSolution.kt` (not strictly a solution, but an illustration) emphasizes this behavior and offers a strategy for handling situations where you need to preserve the original collection.
