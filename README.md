# Bark: A Minimal StumpWM Configuration for Fullscreen Nyxt Instances

## Overview
Bark is a set of configs for [StumpWM](https://stumpwm.github.io/), aimed at running fullscreen instances of [Nyxt](https://nyxt.atlas.engineer/) to our ends, notably for use with [Sled](https://github.com/cloghouse/sled).
(Name is a double pun, clog x tree stump).

## Features

- **Fullscreen Nyxt Support**: Designed with fullscreen Nyxt browser instances in mind.
- **Integration with Sled**: Fully compatible with Sled, A Nyxt configuration aimed at clog.
- **Minimal Key Bindings**: Only the most essential shortcuts for managing windows and workspaces.
- **Easy To Learn**: Not intention for one to learn Stumpwm and friends to use it.

## Installation

### Prereqs
- [StumpWM](https://github.com/stumpwm/stumpwm)
- [Nyxt Browser](https://github.com/atlas-engineer/nyxt)
- [Sled](https://github.com/cloghouse/sled)

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/cloghouse/bark.git ~/.bark.d
  ```
2. Symlink the configuration:
   ```bash
   ln -s ~/.stumpwm.d/bark.d/init.lisp ~/.stumpwmrc
   ```
