# Sprite

## Type

### Sprite

```
typedef struct sprite {
  float x;
  float y;
  byte width;
  byte height;
  byte is_visible;
  byte * bitmap;
  float dx;
  float dy;
} Sprite;
```

## Functions

### Init Sprite

```
void init_sprite(Sprite * sprite, byte x, byte y, byte width, byte height, byte * bitmap);
```

### Draw Sprite

```
void draw_sprite(Sprite * sprite);
```
