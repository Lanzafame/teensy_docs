# Teensy LCD Library

[index](index.html)

## Globals

### Assigned PINs

DCPIN -> PORTB 5

RSTPIN -> PORTB 4

DINPIN -> PORTB 6

SCKPIN -> PORTF 7

SCEPIN -> PORTD 7

### LCD Command/Data

LCD_C -> 0

LCD_D -> 1

### LCD Contrast Level

LOW -> 0x2F

DEFAULT -> 0x3F

HIGH -> 0x4F

### CPU Frequencies

CPU_PRESCALE(n) -> (CLKPR = 0x80, CLKPR = (n))

CPU_8MHz -> 0x01

## Macros

#### Set Input

```SET_INPUT(portdir, pin)
```

#### Set Output

```SET_OUTPUT(portdir, pin)
```

#### Write To Output

```OUTPUT_WRITE(port, pin, value)
```

#### Write LOW to Output

```OUTPUT_LOW(port, pin)
```

#### Write HIGH to Output

```OUTPUT_HIGH(port, pint)
```

#### Read Line

```READ_LINE(port, pin)
```

