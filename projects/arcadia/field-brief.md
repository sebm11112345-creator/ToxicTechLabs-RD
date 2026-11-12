# Arcadia field brief

## Objective
Develop a compact autonomous platform with robust perception and safe obstacle handling.

## Draft architecture
- Vision and depth stack
- IMU + odometry fusion
- Local planner
- Global mission scheduler
- Fault detection and fallback mode

## Review questions
- What failure states are unacceptable?
- Which constraints must be hard-coded?
- What sensor thresholds define safe operation?
