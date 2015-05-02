# Graphics

[index](index.html)

## Globals

#### ScreenBuffer

```extern unsigned char screenBuffer[LCD_BUFFER_SIZE];```

## Macros

#### ABS(x)

#### SIGN(x)

## Functions

#### Refresh

```void refresh(void);```

#### Clear

```void clear(void);```

#### Set Pixel

```void set_pixel(unsigned char x, unsigned char y, unsigned char value);```

#### Draw Line

```void draw_line(unsigned char x1, unsigned char y1, unsigned x2, unsigned
char y2);```

#### Draw Characters

```void draw_character(unsigned char character, unsinged char top_left_x, unsigned char top_left_y);```

#### Draw String

```void draw_string(unsigned char *characters, unsigned char top_left_x, unsigned char top_left_y);```

## Function Skeletons Present

#### Draw Ball

```void drawBall(unsigned char x, unsigned char y);```

#### Draw Box 1

```void drawBox1(unsigned char y);```

#### Draw Box 2

```void drawBox2(unsigned char y);```
