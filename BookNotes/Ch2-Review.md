# Review/Basics

## Notation

First, a note on notation. There are three main quantities we'll be looking at:

|Quantity|Notation|Example|
|---|---|---|
|Instantaneous Values | lowercase (italic) | $v(t)$ or $i(t)$|
|RMS Values | Upper-Normal Case | V or I |
|RMS Phasors | Upper-Italic | $V$ or $I$ |

## Instantaneous Functions

We will refer to the time-domain version of instantaneous signals as we have seen previously, except we'll be mainly dealing with sinusoidal signals of the following form:

```math
\textrm{Voltage: } v(t) = \textrm{V}_{\textrm{max}}\cos(\omega t + \delta)
```
```math
\textrm{Current: } i(t) = \textrm{I}_{\textrm{max}}\cos(\omega t + \delta)
```
Here we have **two main parameters**:

- Phase angle $\delta$ when referenced to an unshifted cosine $$\cos(\omega t)$$
- Maximum value (i.e. amplitudes)


## RMS Value (aka *Effective Value*)

When working with sinusoids, sometimes we're more interested in the average power delivered in one cycle to a resistive load, and an equivalent DC current or voltage that can be used to transfer the same amout of power.

This is known as the root mean square value, and is found by simply dividing the amplitude of the sinusoidal function by $\sqrt{2}$.
```math
\textrm{RMS Voltage: } \textrm{V} = \frac{\textrm{V}_{\textrm{max}}}{\sqrt{2}}
```

## RMS Phasors

Now, we can try and combine the notations above into an easier, more compact form known as the phasor. First we should recall **Euler's Identity**, which tells us

```math
e^{j\delta} = \cos(\delta) + j\sin(\delta)
```

With this we can form the following relationship, which can be a nice way of writing down values. Now, just recall that

$$\textrm{V}_{\textrm{max}} = \sqrt{2}\cdot \textrm{V}$$

```math
V = \textrm{V}_{\textrm{max}} e^{j(\omega t + \delta)} = \textrm{V}_{\textrm{max}}e^{j\delta}e^{j\omega t}
```
Now, we can extract the **instantaneous value** information from the above, by taking the real part of it, giving us

```math
v(t) = \textrm{Re}[V] = 
```




















