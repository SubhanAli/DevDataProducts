BMI Calculation
========================================================
author: Subhan
date: June 21, 2015

What is BMI?
========================================================

From Wikipedia: "The body mass index (BMI), or Quetelet index, is a value derived from the mass (weight) and height of an individual. The BMI is defined as the body mass divided by the square of the body height, and is universally expressed in units of kg/m2, resulting from weight in kilograms and height in metres. If pounds and inches are used, a conversion factor of 703 (kg/m2)/(lb/in2) must be applied. When the term BMI is used informally, the units are usually omitted."

BMI Formula
========================================================

Mass in pounds
Height in inches

BMI = (Mass//Height^2) * 703

Some sample BMIs
========================================================


```r
bmi <- function(weight,height) {
    value <- (weight/height^2)*703
    return(value)
}

bmi(175,72)
```

```
[1] 23.73167
```

```r
bmi(130,65)
```

```
[1] 21.63077
```

For more info
========================================================

Check out: https://en.wikipedia.org/?title=Body_mass_index
