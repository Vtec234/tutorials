# Challenge 1: 
Add another `Set` to the diagram. So you should have 3 circles on your screen.

`.dsl`
```typescript
type Set
```

`.sty`
```typescript
forall Set x {
    x.icon = Circle {
        strokeWidth : 0.0
    }
}
```

_With changes:_
`.sub`
```
Set A
Set B
Set C
```

# Challenge 2:
Keep 3 sets. Represent `Set` as squares with `side` equal to `50.0`.

`.sub`
```
Set A
Set B
Set C
```

`.dsl`
```typescript
type Set
```

_With changes:_
`.sty`
```typescript
forall Set x {
    x.icon = Square {
        side : 50.0
    }
}
```

# Challenge 3:
Keep 3 sets. Represent `Set` as rectangles with `strokeWidth` set to `15.0`.

`.sub`
```
Set A
Set B
Set C
```

`.dsl`
```typescript
type Set
```

_With changes:_
`.sty`
```typescript
forall Set x {
    x.icon = Rectangle {
        strokeWidth : 15.0
    }
}
```

# Challenge 4
Keep 3 sets. For each set, represent `Set` as both a `Circle` and a `Square`.

`.sub`
```
Set A
Set B
Set C
```

`.dsl`
```typescript
type Set
```

_With changes:_
`.sty`
```typescript
forall Set x {
    x.icon = Rectangle{}
    x.icon2 = Square{}
}
```
