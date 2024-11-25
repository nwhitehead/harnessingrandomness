# Harnessing Randomness
## A programming love note to precisely reproducible chaos

This book is about how you can harness the power of pseudorandom number generation in your programs.
Example code is in Python, demos use Python in a Pyodide notebook for interactive play.

First half is an explanation of stuff with small running examples.

* Random number generation (bits and bytes)
    * Algorithms
    * Reproducibility
    * Seeding
    * Skipping
* Continuous Distributions
    * Simple ops
    * Transformation functions
    * Rejection sampling
    * Other techniques
* Discrete Distributions
    * Mostly accurate distributions
    * Weighted sampling
* Lower discrepancy
    * Binning
    * Permutations
    * Quasirandomness
* Independent streams
    * Direct PRNG support
    * Multi-seeding techniques
    * Combining with continuous distributions
* Noise
    * Perlin
    * Simplex
    * Layering
    * Noise transformations

Second half is applications.
* Music
    * Timing variations
    * Parameters
        * Simple instrument
    * PaulStretch random phasing
        * Time stop
        * Random sample of input to make stop grain glitches
    * Ambient chords
* Graphics
    * Noise and textures
    * Clouds

What is the relation to procedural generation? Maybe the second part is more on the procedural generation side.

Second book: how to write and sell a technical book…

Third book: how to create a system for writing technical books…
