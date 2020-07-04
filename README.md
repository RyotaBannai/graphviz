# graphviz

Playground for drawing graphs specified in DOT language scripts.

- [Arrow Shapes](http://graphviz.gitlab.io/doc/info/arrows.html)
- how to handle overlapping edges?
  - `edge concentrators (concentrate=true)`: Merge multiple edges with a common endpoint into single edges, and have partially parallel edges share parts of their path.
  - `ports` : Edges can have their origin and endpoint on a specific port (n, ne, e, se, s, sw, w, nw, w, c, \_). Depending on the edge ports, the edge changes its form (spline).
  - `invisible nodes` : There may be cases where introducing invisible nodes to route edges can have the desired effect.
  - [reference](https://stackoverflow.com/questions/3967600/how-to-prevent-edges-in-graphviz-to-overlap-each-other)
