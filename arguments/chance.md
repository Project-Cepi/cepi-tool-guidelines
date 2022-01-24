# Chance

When providing the user ability to set chance, use a Double argument in the form of a percentage. For example:

`/chance 40.8` will give a 40.8% chance of succeeding.

## Implementation

```kotlin
ThreadLocalRandom.current().nextDouble(100.0) <= chance
```
