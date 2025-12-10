<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

A D latch is a level-sensitive storage element that either stores a bit or passes it through depending on the enable signal. When EN = 1, the latch is transparent, meaning the output Q immediately follows the input D. When EN = 0, the latch holds its previous value, keeping Q unchanged regardless of changes at D. This makes the D latch useful for temporary data storage and for controlling when data is allowed to update in digital circuits.

## How to test
Truth table of a DLatch

| EN | D | Q(t) | Q(t+) (Qnext) |
| -- | - | ---- | ------------- |
| 0  | 0 | 0    | 0 *(hold)*    |
| 0  | 0 | 1    | 1 *(hold)*    |
| 0  | 1 | 0    | 0 *(hold)*    |
| 0  | 1 | 1    | 1 *(hold)*    |
| 1  | 0 | 0    | 0             |
| 1  | 0 | 1    | 0             |
| 1  | 1 | 0    | 1             |
| 1  | 1 | 1    | 1             |

