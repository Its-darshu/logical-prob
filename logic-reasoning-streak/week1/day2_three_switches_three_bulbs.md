# Day 2 - Three Switches and Three Bulbs

## Problem Statement

There are three switches outside a closed room.

Inside the room, there are three bulbs.

Each switch controls exactly one bulb.

You may operate the switches in any way you want before entering the room.

You may enter the room only once.

Your task is to determine which switch controls which bulb.

---

## Constraints

* The door can be opened only one time
* After entering the room, switches cannot be touched again
* All bulbs look identical

---

## Solution

### Step 1

Turn ON switch 2 and leave it ON for 5 minutes.

### Step 2

Turn OFF switch 2.

### Step 3

Turn ON switch 3.

### Step 4

Enter the room immediately.

---

## Observation Inside the Room

* The bulb that is glowing is controlled by switch 3
* The bulb that is OFF but warm is controlled by switch 2
* The bulb that is OFF and cold is controlled by switch 1

---

## Logic Used

This problem uses three distinguishable bulb states:

* ON
* OFF but warm
* OFF and cold

These three states allow exact identification of all three switches.

---

## Interview Thinking

The key idea is to use hidden physical properties.

A bulb gives information not only through light but also through retained heat.

The interview tests whether you can use indirect information under restriction.

---

## LED Variant Analysis

If LED bulbs are used, this method becomes less reliable because LED bulbs generate very little heat.

In that case:

* heat difference may be weak
* warm and cold bulbs may feel similar

So the classic solution assumes traditional bulbs where heat is clearly detectable.

---

## Final Learning

A logic puzzle should be solved by:

Constraint → Hidden Property → Distinct States → Elimination

---

## Solved By

* Darshan
* Ashwath VH
