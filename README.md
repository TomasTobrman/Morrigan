# Morrigan
2D game engine in C for macOS

Check out this projects [Trello](https://trello.com/b/vdL7sXwB/morrigan) for the Roadmap and current progress



## Architecture [WIP]

```
└────────────────────────────────────────────┘
┌────────────────────────────────────────────┐
│ Core                                       │
│ ┌────────┐ ┌───────────┐ ┌───────┐ ┌─────┐ │
│ │ Logger │ │ Assertion │ │ Entry │ │ RNG │ │
│ └────────┘ └───────────┘ └───────┘ └─────┘ │
│ ┌───────────┐ ┌────────┐ ┌───────────────┐ │
│ │ Profiling │ │ String │ │ Engine Config │ │
│ └───────────┘ └────────┘ └───────────────┘ │
└────────────────────────────────────────────┘
┌────────────────────────────────────────────┐
│ Platform Layer                             │
│ ┌─────┐ ┌────────┐ ┌──────────┐ ┌────────┐ │
│ │ API │ │ Window │ │ File I/O │ │ Memory │ │
│ └─────┘ └────────┘ └──────────┘ └────────┘ │
└────────────────────────────────────────────┘
```

