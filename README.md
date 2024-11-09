# zmk-config

[![build](https://github.com/jbmorley/zmk-config/actions/workflows/build.yml/badge.svg)](https://github.com/jbmorley/zmk-config/actions/workflows/build.yml)

ZMK configurations for the Little Luggable and PsiBoard nice!nano based keyboards

## Little Luggable

Keyboard for the [Little Luggable cyberdeck](https://github.com/jbmorley/little-luggable).

![Little Luggable Keymap](images/little-luggable.png)

The most up-to-date version of the Little Luggable keyboard hardware and firmware can be found in the [Little Luggable](https://github.com/jbmorley/little-luggable) repository.

## PsiBoard

### Keyboard Matrix

The Psion Series 5 keyboard has the following keyboard matrix with bin numbering given for the 20-pin FFC connector:

|                         | Col 0 (20) | Col 1 (19)  | Col 2 (18) | Col 3 (17)   | Col 4 (16) | Col 5 (14) | Col 6 (13) | Col 7 (12) |
| ----------------------- | ---------- | ----------- | ---------- | ------------ | ---------- | ---------- | ---------- | ---------- |
| **Row 0 (15)**          |            | Z           | H          | Tab          | 1          | U          | Q          | 7          |
| **Row 1 (11)**          | Space      | X           | J          | A            | 2          | I          | W          | 8          |
| **Row 2 (10)**          | Up         | C           | K          | S            | 3          | O          | E          | 9          |
| **Row 3 (9)**           | , /        | V           | M          | D            | 4          | P          | R          | 0          |
| **Row 4 (8)**           | Left       | B           | . ?        | F            | 5          | L          | T          | Del        |
| **Row 5 (7)**           | Right      | N           | Down       | G            | 6          | Enter      | Y          | ‘ ~        |
| **Row 6 (6,5,4,3,2,1)** | Left Shift | Right Shift | Fn         | Left Control |            | Menu       | Esc        |            |

N.B. The left and right shift, function, control, menu and escape keys are broken out on individual data lines (6, 5, 4, 3, 2, and 1) to allow diodes to be used prior to combining them into a single addressable row.
