# Graph Challenge

This challenge is about representing a directed graph and implementing some methods.

Sample Graph:
```
     ┌───┐
     │ 0 │
     └───┘

  ┌────────────────────────┐
  │                        │
  │  ┌───┐     ┌───┐     ┌───┐     ┌───┐     ┌───┐
  │  │ 8 │ ──▶ │ 4 │ ──▶ │ 9 │ ──▶ │ 6 │ ──▶ │ 2 │
  │  └───┘     └───┘     └───┘     └───┘     └───┘
  │    │                   ▲
  │    └─────────┐         │
  │              ▼         │
  │  ┌───┐     ┌───┐     ┌───┐
  │  │ 1 │ ──▶ │ 3 │     │ 7 │
  │  └───┘     └───┘     └───┘
  │    │
  │    │
  │    ▼
  │  ┌───┐
  └▶ │ 5 │
     └───┘
```