# Wasserstein Geometry-Aware Adaptive Control via Meta-Learning

Official implementation of the ICML 2026 paper
**"Wasserstein Geometry-Aware Adaptive Control via Meta-Learning"**.

> **Note:** The code is currently being cleaned up for release. A complete,
> runnable version will be uploaded here shortly. Thank you for your patience.

## Overview

This repository implements **Wass-MD**, an adaptive controller for nonlinear
systems under unknown disturbances. The method lifts parameter adaptation from
finite-dimensional Euclidean space into Wasserstein space, and uses
meta-learning to jointly optimize the nonlinear feature representation, the
control/adaptation gains, and the transport geometry. The learned controller is
evaluated on a fully-actuated planar rotorcraft (PFAR) and an underactuated
PVTOL vehicle, including under distributional shift between training and test
wind conditions.

