<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

A T flip-flop is a clocked memory element that toggles its output every time the input T = 1. If T = 0, it simply holds its current state. This makes the T flip-flop extremely useful for building binary counters and frequency dividers, since each toggle halves the frequency of the signal going into it.

## How to test
Truth table of a T Flip Flop

| T | Q(t) | Q(t+): next state |
| - | ---- | ----------------- |
| 0 | 0    | 0 *(hold)*        |
| 0 | 1    | 1 *(hold)*        |
| 1 | 0    | 1 *(toggle)*      |
| 1 | 1    | 0 *(toggle)*      |
