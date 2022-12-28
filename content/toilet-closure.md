+++
title = "Toilet Closure"
+++
`|_| ()`
A closure that takes one parameter and immediately drops it.
Equivalent in behavior to [`std::mem::drop`](https://doc.rust-lang.org/std/mem/fn.drop.html),
although [not always interchangeable](https://stackoverflow.com/q/59023616/1233251).
Named as such because it looks like a toilet with the flush tank and bowl next to each other.
It may seem to be rotated 90 degrees counter-clockwise or observed from the side,
depending on personal perspective and interpretation.

Despite `drop` being easier to type than the toilet closure,
there is currently no community-wide consensus on whether one should write the former or the latter.
