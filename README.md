[![Build Status](https://travis-ci.org/nadasal/sdnada.svg?branch=master)](https://travis-ci.org/nadasal/sdnada)

**NOTE: This is a toy package created for MDS 524 for lab purposes. It is not meant to be terribly useful in its current form.**

# rtriangle

This package contains functions for to calculate the hypotenuse, perimeter, and area of 'rtriangle' class objects. It also creates 'rtriangle' class objects.
## Installation

```
devtools::install_github("nadasal/rtriangle")

```

## Quick Demo

```

library(rtriangle)

```

Converting to an 'rtriangle' class object with `rtriangle()`:

```

x <- rtriangle(3, 4)

class(x)

#> [1] "rtriangle"

```

calculating the hypotenuse of the triangle using `hypotenuse()`:

```

hyp <- hypotenuse(x)

print(hyp)

#> [1] 5

```

calculating the perimeter of the triangle using `perimeter()`:

```

peri <- perimeter(x)

print(peri)

#> [1] 12

```

calculating the area of the triangle using `area()`:

```

area <- area(x)

print(area)

#> [1] 6

```
