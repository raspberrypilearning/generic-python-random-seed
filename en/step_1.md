Python’s `randint` function generates numbers that appear random, but they aren't really! If you add a starting number, called **seed**, and if this seed is unchanged each time the code is run, the same sequence of numbers in the same order will always be generated.

Try it yourself using the example below. Run the program several times and look at the random numbers that are generated each time.

<iframe src="https://trinket.io/embed/python/fd410928c2" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

If you don't specify a seed, Python will pick its own seed each time you call the `randint` function, making the numbers appear to be random.
