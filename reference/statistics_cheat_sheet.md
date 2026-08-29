# Statistics Cheat Sheet

This reference sheet grows with the course. It should contain ideas after they
have been introduced in a lesson, not before. The goal is for this file to feel
like a familiar map of concepts you have already met, not a wall of mysterious
notation.

## Lesson 1: Describing Starlight

These concepts summarize repeated brightness measurements of the same star.

### Mean

The **mean** is the ordinary average:

$$
\text{mean} = \frac{\text{sum of measurements}}{\text{number of measurements}}
$$

Astronomy meaning: the mean is a balance-point estimate of the star's measured
brightness. It works well when the measurements are tightly grouped and no one
value is suspiciously extreme.

### Median

The **median** is the middle value after sorting the measurements.

Astronomy meaning: the median describes a typical brightness reading. It is less
pulled around by one unusual measurement than the mean.

### Range

The **range** is:

$$
\text{range} = \text{largest measurement} - \text{smallest measurement}
$$

Astronomy meaning: the range tells us the full observed width of the telescope
readings.

### Spread

**Spread** means how much the measurements vary around a representative value.

Astronomy meaning: spread helps describe how stable or uncertain the repeated
brightness measurements are.

### Variance

**Variance** is based on the average squared distance from the mean.

Astronomy meaning: variance gives a computational way to measure spread, but it
is in squared brightness units, so it is less intuitive to interpret directly.

### Standard Deviation

The **standard deviation** is the square root of the variance.

Astronomy meaning: standard deviation is the typical distance of a measurement
from the mean, in the original brightness units.

### Outlier

An **outlier** is a measurement far away from the rest of the data.

Astronomy meaning: an outlier might be an instrument problem, a reduction issue,
or a real astronomical clue. It should be investigated, not automatically
ignored.
