# casadi_kin_dyn

Package for generation of symbolic (SX) expressions of robot kinematics and dynamics. Based on URDF and Pinocchio.

## What has changed?

In comparison to the original [casadi_kin_dyn](https://github.com/ADVRHumanoids/casadi_kin_dyn) repository, such changes were made:

- Migration to `cmeel`-based packaging
- Use `pre-commit` to prettify repository
- Added `torque`, `potentialEnergy`, `kineticEnergy` regressors
- Added `jacobian time derivative` mapping
- Added `jacobian of CoM` mapping

# v1.6.7

- Added ability to set `root_joint` to `FreeFlyer` joint

# v1.6.8

- `root_joint` is now transformed to enum that can be freely extended with Pinocchio JointModel types.
