# Review/Basics

## Notation

First, a note on notation. There are three main quantities we'll be looking at:

|Quantity|Notation|Example|
|---|---|---|
|Instantaneous Values | lowercase (italic) | $v(t)$ or $i(t)$|
|RMS Values | Upper-Normal Case | $\textrm{V}$ or $\textrm{I}$ |
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

Recall that

$$\textrm{V}_{\textrm{max}} = \sqrt{2}\cdot \textrm{V}$$

Now, using the format below

```math
\textrm{V}_{\textrm{max}} e^{j(\omega t + \delta)} = \sqrt{2}\textrm{V}e^{j\delta}e^{j\omega t}
```
we can extract the **instantaneous value** information from the above, by taking the real part of it, giving us

```math
v(t) = \textrm{Re}[\textrm{V}_{\textrm{max}} e^{j(\omega t + \delta)}] = \textrm{Re}[\sqrt{2}\textrm{V}e^{j\delta}e^{j\omega t}]
```

Now, we'll introduce the **rms phasor**, which can be given in three forms,

```math
V =\textrm{V}e^{j\delta} = \textrm{V}\angle\delta =  \textrm{V}\cos(\delta) + j\textrm{V}\sin(\delta)
```

where $\textrm{V}$ is the **rms value** of the voltage (or current). 

## Phasors for Components

![image](https://user-images.githubusercontent.com/63083372/212562933-4b315fcb-03bf-407c-b43a-3bd67a511cf8.png)



















