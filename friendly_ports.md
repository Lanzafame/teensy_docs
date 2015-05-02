# Friendly Ports

[index](index.html)

## Macros

### LED0

Bitmask and register LED0 (left)

```
LED0
LED0_PORT
```

### LED1

Bitmask and register LED1 (right)
  
```
LED1
LED1_PORT
```

### LED2

Bitmask and register LED2 (the onboard LED)

```
LED2
LED2_PORT
```

### SW0

Bitmask and register switch 0 (left)

```
SW0
SW0_PORT
```

### SW1

Bitmask and register switch 1 (left)

```
SW1
SW1_PORT
```

### Turn LED ON

@param led [LED0|LED1|LED2]

```
turn_on(led)
```

### Turn LED OFF

@param led [LED0|LED1|LED2]

```
turn_off(led)
```

### Button Pressed

@param button [SW0|SW1]
@return bool

```
pressed(button)
```

### Wait Until

@param cond Boolean statement

```
wait_until( cond )
```

### Left Button Led Wait

@param zzz Nothing

```
db_wait(zzz)
```
