---
layout: post
title:  "Wave Particle Duality And Canonical Quantization"
description: "Whether it's your wife coming home from the mall with yet another bag that she doesn't need, but she bought it *because it was on sale*, a coworker snapping at you because he had a bad day, or a road rage incident that ended in legal repercussions, human behavior shows no shortage of irrationality and I'm sure you've been left scratching your head on more than one occasion...
"
date:   2019-08-19 11:13:11 +0300
image: "/images/canonical/orbits.png"
---
In the previous [article](), we looked at Lagrangian mechanics, explaining that the Euler-Lagrange formula can be retrieved from the minimum action principle. Hamilton went a bit further than that, and he came up with some new equations of motion, so instead of using a single second-degree equation, we now have two. The two formulations are entirely equivalent, but in some cases it's beneficial to use Hamilton's approach. Mathematically, Hamilton's formula is a [Legendre transform]() of the Euler-Lagrange equation.

![commodus](/images/canonical/hamiltonian.svg){:class="img-responsive"}

*q*, the [generalized coordinates](https://en.wikipedia.org/wiki/Generalized_coordinates), and *p*, the generalized momentum together give us the *canonical coordinates*. *H*, the Hamiltonian, is the total energy of the system. So if we know the *state* of the system at an initial moment in time, we can calculate it using this formula. 

One of quantum physics's first conceptual problems was how one could reconcile the wavy aspects manifested in experiments with the fact the measurements for particle positions always find particles in one location in space and not spread out, a concept known as wave-particle duality.

Physicists knew how to mathematically describes waves, and Schrodinger's equation is such an example.

![commodus](/images/canonical/schrodinger.svg){:class="img-responsive"}

A quick note on waves: describing them in terms of complex numbers is very convenient because complex numbers have both an amplitude and a phase. Also, a quick mathematical interlude: *operators act on a function and produce another function. Examples are the differentiation, integration, multiplying with a constant, etc.*

Max Born came up with the idea of treating the square of the amplitude of the wave function as probability for finding the particle at a location in space, a postulate called the *Born rule*. The main idea behind canonical quantization is you promote physical quantities from a classical theory such as momentum or the Hamiltonian to operators that act on a wave-function. You then use the Born rule on the wave function to get probabilities for finding the particle in an area by integration.

Which in a nutshell is how you get the Schrodinger equation. You start by defining the 

![commodus](/images/canonical/orbits.png){:class="img-responsive"}

So what exactly is the problem?