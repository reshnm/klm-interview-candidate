# Graph Challenge - Candidate Version

This challenge is about representing a directed graph and implementing some methods.
> Please treat the content of this challenge confidential. 

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