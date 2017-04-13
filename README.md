# rlencode

Example solution to the run length encoding problem.

The problem is as follows:

You are given a decoder that accepts alphanumeric strings. Each time
it encouters a pattern of the form 'Nxc' where N is any positive integer, x is
the literal x, and c is any alphanumeric character, it outputs c N times. E.g.

    decode("abc11xd44y") = "abcddddddddddd44y"

Write an encoder.

See e.g. http://www.geeksforgeeks.org/run-length-encoding/
