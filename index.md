---
layout: default
title: Home
---
Econ 204 // Spring 2024

2024-01-29

<math display='block'>
 <semantics>
  <mrow>
   <msqrt>
    <mrow>
     <msup>
      <mi>a</mi>
      <mn>2</mn>
     </msup>
     <mo>+</mo><msup>
      <mi>b</mi>
      <mn>2</mn>
     </msup>
     </mrow>
   </msqrt>
   </mrow>
  <annotation encoding='MathType-MTEF'>MathType@MTEF@5@5@+=
  feaahGart1ev3aaatCvAUfeBSjuyZL2yd9gzLbvyNv2CaerbuLwBLn
  hiov2DGi1BTfMBaeXatLxBI9gBaerbd9wDYLwzYbItLDharqqtubsr
  4rNCHbGeaGqiVu0Je9sqqrpepC0xbbL8F4rqqrFfpeea0xe9Lq=Jc9
  vqaqpepm0xbba9pwe9Q8fs0=yqaqpepae9pg0FirpepeKkFr0xfr=x
  fr=xb9adbaqaaeGaciGaaiaabeqaamaabaabaaGcbaWaaOaaaeaaca
  WGHbWaaWbaaSqabeaacaaIYaaaaOGaey4kaSIaamOyamaaCaaaleqa
  baGaaGOmaaaaaeqaaaaa@3A92@
  </annotation>
 </semantics>
</math>

now testing something that <math>
 <semantics>
  <mrow>
   <msqrt>
    <mrow>
     <msup>
      <mi>a</mi>
      <mn>2</mn>
     </msup>
     <mo>+</mo><msup>
      <mi>b</mi>
      <mn>2</mn>
     </msup>
     </mrow>
   </msqrt>
   </mrow>
  <annotation encoding='MathType-MTEF'>MathType@MTEF@5@5@+=
  feaahGart1ev3aqatCvAUfeBSjuyZL2yd9gzLbvyNv2CaerbuLwBLn
  hiov2DGi1BTfMBaeXatLxBI9gBaerbd9wDYLwzYbItLDharqqtubsr
  4rNCHbGeaGqiVu0Je9sqqrpepC0xbbL8F4rqqrFfpeea0xe9Lq=Jc9
  vqaqpepm0xbba9pwe9Q8fs0=yqaqpepae9pg0FirpepeKkFr0xfr=x
  fr=xb9adbaqaaeGaciGaaiaabeqaamaabaabaaGcbaWaaOaaaeaaca
  WGHbWaaWbaaSqabeaacaaIYaaaaOGaey4kaSIaamOyamaaCaaaleqa
  baGaaGOmaaaaaeqaaaaa@3A93@
  </annotation>
 </semantics>
</math>
should have been inline


**Quantitative Variables in Finite Populations and Samples:**

**Notation, Definitions, and Facts**

**I. QUANTITATIVE VARIABLES IN POPULATIONS**

<u>Notation<u>

A ***finite population*** consists of $N$ elements, labelled $I =
1,\...,N$, where $N$ is a real number.

$X$ is the name of a quantitative variable (QVAR).

For $I = 1,\...,N$, ${X_I}$ is the value of $X$ for elements
$I$.

<u>Definition: The population mean of a QVAR<u>

The ***population mean of a QVAR*** $X$ is represented by the symbol
$\mu_X$ , and defined as

$mu_X = \frac{\sum\limits_{I = 1}^N{X_I}}{N}$

<u>Definition: A deviation from the population mean of a QVAR for a given
element<u>

A ***deviation from the population*** ***mean of a QVAR*** $X$
***for a given element*** is the difference between the value of $X$
for the given element and the population mean of $X.$ The deviation
from the population mean of $X$ for element $I$is represented by
the symbol $D{X_I}$:

$D_{X_I} = {X_I} - {\mu_X}$

<u>Fact<u>

For any finite population and any QVAR $X$, if you find the
deviation from the population mean of $X$ for every element in the
population, and then add up all those deviations, you will find that the
sum is zero.

To put that more succinctly: for any finite population and any
quantitative variable $X$, the sum of the deviations from the means
is always equal to 0.

This is true no matter how many elements there are in the population and
no matter what the values of $X$ are for the elements.

More formally: Given a finite population consisting of any number
$N$ of elements, and given any values
$X_1,X_2,...,X_N$ of a QVAR $X$,

> $\sum\limits_{I = 1}^N D_{X_I} = 0$

or equivalently,

> $\sum\limits_{I = 1}^N \left(X_I -\mu _X \right) =
> 0$

<u>Proof of this fact<u>

We can prove this equality through several steps of algebra. Every step is just a rearrangement of terms.

$$\begin{array}{l}\sum\limits_{I = 1}^N D_{X_I} =
\sum\limits_{I = 1}^N {\left( X_I - \mu_X \right)}
\\\,\,\,\,\,\,\,\,\,\,\,\,\,\,\, = \sum\limits_{I
= 1}^N X_I - \sum\limits_{I = 1}^N \mu_X
\\\,\,\,\,\,\,\,\,\,\,\,\,\,\,\, = \sum\limits_{I
= 1}^N X_I - N{\mu_X}\\\,\,\,\,\,\,\,\,\,\,\,\,\,\,\, = N\left(
\frac{\sum\limits_{I = 1}^N X_I}{N} \right) - N{\mu_X}\\\,\,\,\,\,\,\,\,\,\,\,\,\,\,\, = N{\mu _X} -N{\mu _X}\\\,\,\,\,\,\,\,\,\,\,\,\,\,\,\, = 0\end{array}$$

<u>Definition: The population mean absolute deviation of a
QVAR<u>

The ***population mean absolute deviation*** ***of a QVAR*** $X$ is
represented by the symbol $MA{D_X}$, and defined as

$$MA{D_X} = \frac{\sum\limits_{I = 1}^N \left(| X_I - \mu_X \right|)}{N}$$

<u>Definition: The population variance of a QVAR<u>

The ***population variance*** ***of a QVAR*** $X$ is represented by the symbol $\sigma_X^2$, and defined as

$$\sigma_X^2 = \frac{\sum\limits_{I = 1}^N \left( X_I - \mu_X \right)^2}{N}$$
