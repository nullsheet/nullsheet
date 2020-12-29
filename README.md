# Nulsheet

```css
:root {

 /* identity colors */
  --primary-color: #d22365;
  --primary-light-color: #ff94bd;
  --primary-dark-color: #530020;
  --secondary-color:#6b46c1;
  --secondary-light-color: #ceb9ff;
  --secondary-dark-color: #311e6d;
  --tertiary-color:#2ee9b4;
  --tertiary-light-color: #a4ffe5;
  --tertiary-dark-color:#004d37;

  /* semantic colors */
  --success-color: #75c38f;
  --success-light-color:#e5f7ec;
  --success-dark-color:#315542;
  --warning-color: #ffc400;
  --warning-light-color: #fbf6b4;
  --warning-dark-color: #663d1d;
  --danger-color:#ff3838;
  --danger-light-color: #f7e7e6;
  --danger-dark-color: #950000;

  /* markup colors */
  --soft-color: #fff;
  --soft-light-color: transparent;
  --soft-dark-color: #e6e6e6;
  --neutral-color: #b3b3b3;
  --neutral-light-color: #e7e7e7;
  --neutral-dark-color: #999999;
  --heavy-color: #282c34;
  --heavy-light-color: #575f70;
  --heavy-dark-color:#0d0f11;

  /* font families */
  --primary-font-family: 'Arial';
  --secondary-font-family: 'Tahoma';
  --tertiary-font-family: 'Tahoma';

  /* ultilities */
  --border-radius: 0.25rem;
  --line-height: 0.1;
  --opacity: 0.05;
  --spacer: 0.25rem;
  --box-shadow: 2px;

}
```

medias = xs: sm- sm: sm+ md- md: md+ lg- lg: lg+ xl: pt:

## Colors

- variation = a z
- number = 1 2 3
- type = i s m
- state = :h :a :f

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

## Box Shadows

- number = 0 ... 24

```
.(media)bs[number]
```

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