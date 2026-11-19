# game-of-life

Conway's Game of Life in [Knave](https://knave-lang.org), animated in the terminal on a 40x20 grid whose edges wrap around.

## Install

Install Knave 0.18.0 with Cargo, which [rustup](https://rustup.rs) installs:

```sh
cargo install knave --version 0.18.0 --locked
```

## Run

```sh
knave run -- [pattern] [generations]
```

| Argument | Values | Default |
| --- | --- | --- |
| `pattern` | `glider`, `blinker`, `r-pentomino` | `glider` |
| `generations` | a whole number | `100` |

## Test

```sh
knave test
```
