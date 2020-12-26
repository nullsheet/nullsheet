# Nulsheet

```css
:root {

  /* identity colors */
  --primary-color: #6b46c1;
  --primary-light-color: #8560fc;
  --primary-dark-color: #4d3793;
  --secondary-color: #2ee9b4;
  --secondary-light-color: #69f9cc;
  --secondary-dark-color: #009B6F;
  --tertiary-color: #2ee9b4;
  --tertiary-light-color: #69f9cc;
  --tertiary-dark-color: #009B6F;

  /* semantic colors */
  --success-color: #28a745;
  --success-light-color: #28a745;
  --success-dark-color: #28a745;
  --warning-color: #ffc107;
  --warning-light-color: #ffc107;
  --warning-dark-color: #ffc107;
  --danger-color: #dc3545;
  --danger-light-color: #dc3545;
  --danger-dark-color: #dc3545;

  /* markup colors */
  --soft-color: #fff;
  --soft-light-color: transparent;
  --soft-dark-color: #f1f1f1;
  --neutral-color: rgb(0,0,0,0.6);
  --neutral-light-color: rgb(0,0,0,0.6);
  --neutral-dark-color: rgb(0,0,0,0.6);
  --heavy-color: rgb(0,0,0,0.6);
  --heavy-light-color: rgb(0,0,0,0.6);
  --heavy-dark-color: rgb(0,0,0,0.6);

  /* font families */
  --primary-font-family: 'Arial';
  --secondary-font-family: 'Tahoma';
  --tertiary-font-family: 'Tahoma';

  /* columns */
  --x-columns: 12;
  --y-columns: 12;
  --y-height: 100%;
  --x-width: 100%;

  /* ultilities */
  --border-radius: 0.25rem;
  --line-height: 0.1;
  --opacity: 0.5;
  --spacer: 0.25rem;

}
```

## Colors

- variation = a z
- number = 1 2 3
- type = i s m
- state = h a f // rethink

### Background Colors

```
.(media)bg[type][number](variation)(state)
```

### Border Colors

```
.(media)bc[type][number](variation)(position)(state)
```

### Text Colors

```
.(media)c[type][number](variation)(state)
```

## Horizontal Columns

- variation = a z
- number = 1 ... 24
- unit = vw

### width

```
.(media)x[number](variation)
```

### number of columns

```
.(media)xn[number]
```

### column unit

```
.(media)xvw
```

## Vertical Columns

- variation = a z
- number = 1 ... 24
- unit = vw

### height

```
.(media)y[number](variation)
```

### number of columns

```
.(media)yn[number]
```

### column unit

```
.(media)yvh
```

## Depth

- number = 1 ... 24

```
.(media)z[number]
```

## Fonts

### Font Family

- number = 1 2 3

```
.(media)ff[number]
```

### Font Size

- number = 1 ... 24

```
.(media)fs[number]
```

### Font Weight

- number = 1 ... 10

```
.(media)fw[number]
```

## Visibility

```
.(media)off
```

## Vertical rows

- position = y t b sa se sb

```
.(media)y[position]
```

## Horizontal rows

- position = x t b sa se sb

```
.(media)x[position]
```

## Flex Orders

- number = 1 ... 24

```
.(media)fo[number]
```

## Paddings

- number = 0 ... 24
- position = t b l r x y

```
.(media)p[number](position)
```

## Margins

- number = 0 ... 24
- position = t b l r x y

```
.(media)m[number](position)
```

## Shadows

???

## Containers

```
.(media)x
```

## Opacity

- number = 0 ... 20

```
.(media)op[number]
```

## Text Transform

- variation = u l c

```
.(media)tt[variation]
```

## Cursor

???

## Line Height

- number = 1 ... 24

```
.(media)lh[number]
```

## Border Width

- number = 0 ... 24
- position = t b l r x y

```
.(media)bw[number](position)
```

## Border Radius

- number = 0 ... 24
- position tl tr bl br t b l r

```
.(media)br[number](position)
```

## Positions

- position = r a f s
- y = t b
- x = r l

```
.(media)p[position][y][x]
```