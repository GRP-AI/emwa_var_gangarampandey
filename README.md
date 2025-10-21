# EMWAVarTracker

A probabilistic forecasting tracker using Exponentially Weighted Moving Average (EWMA) variance estimation and Gaussian Mixture Models. Designed for adaptive prediction in volatile environments.

## Features
- Dual EWMA variance tracking (core and tail)
- Gaussian mixture density prediction
- Live and animated simulation modes
- Diagnostic visualization tools

## Usage
```python
from birdgame.trackers import EMWAVarTracker

tracker = EMWAVarTracker()
tracker.test_run(live=True)  # For live inference
