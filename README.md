# C#: Atbash Cipher

Create an implementation of the atbash cipher, an ancient encryption system created in the Middle East.

The Atbash cipher is a simple substitution cipher that relies on
transposing all the letters in the alphabet such that the resulting
alphabet is backwards. The first letter is replaced with the last
letter, the second with the second-last, and so on.

An Atbash cipher for the Latin alphabet would be as follows:

```plain
Plain:  abcdefghijklmnopqrstuvwxyz
Cipher: zyxwvutsrqponmlkjihgfedcba
```

It is a very weak cipher because it only has one possible key, and it is
a simple monoalphabetic substitution cipher. However, this may not have
been an issue in the cipher's time.

Ciphertext is written out in groups of fixed length, the traditional group size
being 5 letters, and punctuation is excluded. This is to make it harder to guess
things based on word boundaries.

## Examples
- Encoding `test` gives `gvhg`
- Decoding `gvhg` gives `test`
- Decoding `gsvjf rxpyi ldmul cqfnk hlevi gsvoz abwlt` gives `The quick brown fox jumps over the lazy dog.`

Follow these instructions on how to [get your C# development environment set up][csharp-installation].

The exercises use NUnit. Follow [this guide][nunit-guide] to get started.

[csharp-installation]: https://github.com/exercism/xcsharp/blob/master/docs/INSTALLATION.md
[nunit-guide]: https://github.com/exercism/xcsharp/blob/master/docs/TESTS.md

## Source

Wikipedia [http://en.wikipedia.org/wiki/Atbash](http://en.wikipedia.org/wiki/Atbash)

This exercise is from the [C#][csharp] track on [Exercism][exercism]

[exercism]: http://exercism.io
[csharp]: http://exercism.io/languages/csharp



