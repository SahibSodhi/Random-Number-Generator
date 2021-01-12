# Random-Number-Generator

- Generate randomness based on a clock drift instead of using random module.

- Once you have getrandbits(k), it is straigforward to get a random integer in range [a, b], including both end points.

- To test the quality of getrandbits(k), dieharder utility could be used:
```
 $ python3 random-from-time.py | dieharder -a -g 200
 ```
