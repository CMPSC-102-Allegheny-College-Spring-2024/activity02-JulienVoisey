# Data Types

TODO: Please remove the TODO markers and notes from this file
so that the final document is written in a professional fashion
suitable for publication. If you have questions about how to
structure, format, and write this document, please ask for a
preliminary assessment of your work in advance of the deadline.

## Julien Voisey

## Program Output

### What is the output from running the following commands?

Use a fenced code block to provide the output for this command.

- `python demonstrate-variable-limitations.py`

```
The value of a feasible number is 115792089237316195423570985008687907853269984665640564039457584007913129639936

The value of another feasible number is 179769313486231590772930519078902473361797697894230657273430081157732675805500963132708477322407536021120113879871393357658789768814416622492847430639474124377767893424865485276302219601246094119453082952085005768838150682342462881473913110540827237163350510684586298239947245938479716304835356329624224137216
```

Use a fenced code block to provide the output for this command.

- `python compare-variables.py`

```
1.0 is not the same as 1.1
1.0 is the same as 1.0
.33333 + .33333 + .33333 is not equal to 1
.33333333333 + .33333333333 + .3333333333 is not equal to 1
The value of 1/3 is 0.3333333333333333
0.3333333333333333 + 0.3333333333333333 + 0.3333333333333333 is equal to 1
1/3 + 1/3 + 1/3 is equal 1
```

## Program Questions

### Why is it not feasible to perform the computation `2**2**100`?

The computation 2**2**100 involves exponentiation with extremely large numbers. As a result, the device is not able to present the output as it is just too big of an output. There is not enough processing power for the computer to perform such astronomical numbers.

### What is the value of `1/3` according to the Python language? Why?

The value of 1/3 is represented in the python language as a floating point number, where there are many decimals. In the case of 1/3, the value will be 0.3333333333333333. As a result, because there are so many decimals, typically python will provide a rough estimate for the fraction but that the value represented above is the value for 1/3.

### Why is the value of `.33333 + .33333 + .33333 == 1` equal to `False`?

The reason why `.33333 + .33333 + .33333 == 1` equals to `False` is due to precision of the values. When you are saying `== 1`, you are saying it equals to 1 which will not be true in this case because the decimals will result in the output being close to 1, but not precisely 1. The close answer to 1 represents how floating point numbers are more precise than using fractions that will provide are more rough estimate.

(Did you remember to add your name?!)