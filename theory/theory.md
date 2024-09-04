# Representing Euclid's Propositions

## The Basics

### Basic Constructions

```haskell
-- A straight line may be drawn from any point to any other point.
postulate1 :: (Point, Point) -> Line

-- A finite straight line may be produced to any length in a straight line.
postulate2 :: (Line, Point) -> Line

-- A circle may be described with any centre at any distance from that centre.
postulate3 :: (Point, Point) -> Circle
```



### Intersections

```haskell
intersect_line_line :: (Line, Line) -> [Point]
intersect_circ_line :: (Circle, Line) -> [Point]
intersect_circ_circ :: (Circle, Circle) -> [Point]
```



