## crate squatting

Reserving one or more crate names on [crates.io](https://crates.io) for future use by publishing a placeholder crate. While this practice is not forbidden, it is also frowned upon by some, and can be reverted in extreme or malicious cases.

## dtolnay trick

See [**semver trick**](#semver-trick).

## eat your laundry

Metaphorical expression for a consequence of [undefined behavior](https://doc.rust-lang.org/reference/behavior-considered-undefined.html). It is often used in the Rust community as an alternative to [nasal demons](http://catb.org/jargon/html/N/nasal-demons.html).

## fearless concurrency

The expression stems from the capability of writing risk-free Rust code without data races or other memory safety bugs. Despite the loaded meaning, mentioning that "Rust has fearless concurrency" alone does not make a very good argument in a conversation on whether to use Rust. 

See also: [Fearless Concurrency with Rust](https://blog.rust-lang.org/2015/04/10/Fearless-Concurrency.html)

## Ferris

Ferris the crab is the [unofficial Rust mascot](https://rustacean.net).

## hearty boy

Higher-ranked trait bounds (HRTB).

It is a mnemonic for the HRTB acronym.

## owl result

`Result<(), ()>` - a result type with `()` for both `T` and `E` parameter types.

The brackets, empty tuples and comma resemble an owl's head.

## Pre-Poop Your Pants (PPYP)

In unsafe code, preemptively guarantee that a panic or incorrect API usage in safe code will result in logical errors rather than undefined behaviour. See [Pre-Pooping Your Pants With Rust](https://cglab.ca/~abeinges/blah/everyone-poops/#pre-pooping-your-pants)

## rewrite in Rust

Also known as _rewrite it in Rust_ (RIIR). A proposition or idea of porting existing software to Rust. See also [Rust Evangelism Strike Force](#rust-evangelism-strike-force).

## Rust Evangelism Strike Force

Acronym: RESF

A movement of proponents of Rust, who usually talk to their peers about the benefits of the language, and may also be in favor of [rewriting existing software in Rust](#rewrite-in-rust). As in all movements, different levels of adherence to the principles of the RESF exist, not all of which represent a healthy conduct. A zealous attitude may often be used for humor (see [/r/rustjerk](https://www.reddit.com/r/rustjerk)), but is not well regarded when taken seriously.

## Rustacean

A Rust developer. A word play between _Rust_ and _crustacean_, alluding to the mascot [Ferris](#ferris).

A community maintained list of Rustaceans is available at https://www.rustaceans.org.

## semver trick

A trick for Rust libraries to publish breaking changes without requiring other crates around the ecosystem to upgrade in a coordinated fashion.

Official reference: https://github.com/dtolnay/semver-trick

## toilet closure

`|_| ()`

A closure that takes one parameter and immediately drops it. Equivalent in behavior to [`std::mem::drop`](https://doc.rust-lang.org/std/mem/fn.drop.html). Named as such because it looks like a toilet (the flush tank and bowl) rotated 90 degrees counter-clockwise.

Despite `drop` being easier to type than the toilet closure, there is currently no community-wide consensus on whether one should write the former or the latter.

## turbo fish

`::<>`

The base syntax for defining type parameters explicitly when using a generic type or function.

See also [turbo.fish](https://turbo.fish).
