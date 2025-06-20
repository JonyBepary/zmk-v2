# Combined Pin Mapping

## Left Side Pins
| Pin # | Original Label | Keyboard Function |
|:-----:|:---------------|:------------------|
| 1     | GND            | GND (Ground)      |
| 2     | D1 (P0.06)     | Col2              |
| 3     | D0 (P0.08)     | Row2              |
| 4     | GND            | GND (Ground)      |
| 5     | GND            | GND (Ground)      |
| 6     | D2 (P0.17)     | Unused (P0.17)    |
| 7     | D3 (P0.20)     | Col1              |
| 8     | D4 (P0.22)     | Row0              |
| 9     | D5 (P0.24)     | Row4              |
| 10    | D6 (P1.00)     | Row3              |
| 11    | D7 (P0.11)     | Col4              |
| 12    | D8 (P1.04)     | Col5              |
| 13    | D9 (P1.06)     | Col6              |

## Right Side Pins
| Pin # | Original Label | Keyboard Function |
|:-----:|:---------------|:------------------|
| 1     | BATTERY+       | BATTERY+          |
| 2     | BATTERY+       | BATTERY+          |
| 3     | GND            | GND (Ground)      |
| 4     | RESET          | RESET             |
| 5     | 3.3V           | 3.3V              |
| 6     | D21 (P0.31)    | Col7              |
| 7     | D20 (P0.29)    | Col8              |
| 8     | D19 (P0.02)    | Col9              |
| 9     | D18 (P1.15)    | Col10             |
| 10    | D15 (P1.13)    | Col11             |
| 11    | D14 (P1.11)    | Col12             |
| 12    | D16 (P0.10)    | Col13             |
| 13    | D10 (P0.09)    | Col14             |

## Middle Pins
| Pin # | Original Label | Keyboard Function |
|:-----:|:---------------|:------------------|
| 1     | D11 (P1.01)    | Col3              |
| 2     | D12 (P1.02)    | Row1              |
| 3     | D13 (P1.07)    | Col0              |













| Left Side Pins | Right Side Pins |
|---------------|----------------|
| GND           | BATTERY+       |
| D1 (P0.06)    | BATTERY+       |
| D0 (P0.08)    | GND            |
| GND           | RESET          |
| GND           | 3.3V           |
| D2 (P0.17)    | D21 (P0.31)    |
| D3 (P0.20)    | D20 (P0.29)    |
| D4 (P0.22)    | D19 (P0.02)    |
| D5 (P0.24)    | D18 (P1.15)    |
| D6 (P1.00)    | D15 (P1.13)    |
| D7 (P0.11)    | D14 (P1.11)    |
| D8 (P1.04)    | D16 (P0.10)    |
| D9 (P1.06)    | D10 (P0.09)    |



| Middle Pins   |
|---------------|
| D11 (P1.01)    |
| D12 (P1.02)    |
| D13 (P1.07)    |


### 2.2.2. keyboard

| Left Side Pins | Right Side Pins |
|---------------|----------------|
| GND           | BATTERY+       |
| Col2          | BATTERY+       |
| row2          | GND            |
| GND           | RESET          |
| GND           | 3.3V           |
| D2 (P0.17)    | col7    |
| col1 (P0.20)  | col8    |
| row0          | col9    |
| row4          | col10    |
| row3          | col11    |
| col4          | col12    |
| col5          | col13    |
| col6          | col14    |


| Middle Pins   |
|---------------|
| col3 (P1.02)         |
| row1 (P1.02)    |
| col0 (P1.07)    |


| Left Side Pins          | Middle Pins           | Right Side Pins         |
|-------------------------|------------------------|-------------------------|
| GND                     | D11 (P1.01) / col3    | BATTERY+                |
| D1 (P0.06) / Col2       | D12 (P1.02) / row1    | BATTERY+                |
| D0 (P0.08) / row2       | D13 (P1.07) / col0    | GND                     |
| GND                     |                        | RESET                   |
| GND                     |                        | 3.3V                    |
| D2 (P0.17)              |                        | D21 (P0.31) / col7      |
| D3 (P0.20) / col1       |                        | D20 (P0.29) / col8      |
| D4 (P0.22) / row0       |                        | D19 (P0.02) / col9      |
| D5 (P0.24) / row4       |                        | D18 (P1.15) / col10     |
| D6 (P1.00) / row3       |                        | D15 (P1.13) / col11     |
| D7 (P0.11) / col4       |                        | D14 (P1.11) / col12     |
| D8 (P1.04) / col5       |                        | D16 (P0.10) / col13     |
| D9 (P1.06) / col6       |                        | D10 (P0.09) / col14     |


# Layout

## Default Layer

```markdown
|------------|---------|---------|---------|---------|---------|---------|---------|---------|---------|---------|---------|---------|-----------|----------|
| **ESC**    | 1       | 2       | 3       | 4       | 5       | 6       | 7       | 8       | 9       | 0       | -       | =       | BKSPC     | DEL      |
|------------|---------|---------|---------|---------|---------|---------|---------|---------|---------|---------|---------|---------|-----------|----------|
| **TAB**    | Q       | W       | E       | R       | T       | Y       | U       | I       | O       | P       | [       | ]       | \         | PGUP     |
|------------|---------|---------|---------|---------|---------|---------|---------|---------|---------|---------|---------|---------|-----------|----------|
| **CAPS**   | A       | S       | D       | F       | G       | H       | J       | K       | L       | ;       | '       | ENTER   |           | PGDN     |
|------------|---------|---------|---------|---------|---------|---------|---------|---------|---------|---------|---------|---------|-----------|----------|
| **LSHIFT** |         | Z       | X       | C       | V       | B       | N       | M       | ,       | .       | /       | RSHIFT  | UP        | MOD      |
|------------|---------|---------|---------|---------|---------|---------|---------|---------|---------|---------|---------|---------|-----------|----------|
| **LCTRL**  | LCTRL   | LGUI    | LALT    |         |         |  SPACE  |         |         | RALT    | FN      | RCTRL   | LEFT    | DOWN      | RGHT     |
|------------|---------|---------|---------|---------|---------|---------|---------|---------|---------|---------|---------|---------|-----------|----------|

```

