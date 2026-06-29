# Python Data Structures Fundamentals

Notes I put together while getting back up to speed on Python's built-in collections
before starting on LeetCode. Mostly stuff I already knew, organized into one place I
can skim before grinding problems, plus a couple of gaps (stacks/queues from scratch)
I went back and nailed down properly.

## What's in here

`python_ds_fundamentals.ipynb` — a runnable notebook covering:

- **Lists** — creation, common methods, slicing, iteration patterns (`enumerate`, `zip`, reverse iteration)
- **Dicts** — creation, lookups, `Counter`, `defaultdict`
- **Sets** — creation, set algebra (union/intersection/difference), why `x in set` beats `x in list`
- **Stacks** — using a plain `list` (LIFO)
- **Queues** — using `collections.deque` (FIFO), and why `list.pop(0)` is a trap
- **Tuples** — quick note on immutability and using them as dict keys
- Time complexity tables for all of the above
- A quick decision guide ("need X → use Y")
- A self-check list at the end to confirm I actually know this without looking it up

## Why a notebook instead of a plain `.md`

Wanted the code blocks to actually run, not just sit there as text — easier to poke
at examples and tweak them while reviewing.

## How to use it

Clone it and open in Jupyter / VS Code / Colab:

```bash
jupyter notebook python_ds_fundamentals.ipynb
```

Every cell runs top to bottom with no external dependencies — just the Python
standard library (`collections.Counter`, `collections.deque`).
