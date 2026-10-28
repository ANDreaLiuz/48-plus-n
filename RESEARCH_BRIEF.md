# 48+N — PhD Research Brief

**Human-centered embodied intelligence · Baseline brief reviewed 23 October 2026**

## Research question

How can near-term motion information help a person direct an embodied system while task authority remains explicit? 48+N investigates this question through predictive preparation, human–robot interaction and task coordination across embodiment capabilities.

## Architecture

The intended architecture connects a human goal, sensing, Shadow's predictive preparation, explicit human authority, MechaLink's task and embodiment coordination, an executor and feedback. Shadow studies ongoing low-level coordination through human corrections, short-horizon prediction, robot-local response and feedback to the operator; MechaLink concerns what the task requires of a proposed body. Prediction supplies preparation, not permission.

## Engineering foundation

**Sensing:** Real RGB-D observations have been acquired with D455/D435i cameras, with frame, timing and software interface checks. A limited native camera-to-prediction-to-software-consumer path has also been recorded.

**Prediction:** GRU-based motion forecasts have been evaluated against simple baselines using recorded motion. Those comparisons make input availability, measurement reference and baseline choice part of the analysis.

**Simulation:** Ordinary SO-101 control in MuJoCo has exercised grasp, lift, transport, placement and retreat. Rendered RGB-D re-observation has informed updated target estimates in controlled tabletop cases. These tasks retain known scene geometry and simulator ground-truth contact checks.

## Validation limits

These are separate evidence streams, not a completed human-to-physical-robot evaluation. Current evidence does not establish anatomical accuracy, effective anticipation, population generalization or physical safety. A distinct high-level method advantage over ordinary controllers is also unproven. Independent reference quality, fair baseline comparisons and broader task conditions remain central evaluation needs.

## Prospective PhD direction

Prospective PhD work would investigate measurement-aware predictive interfaces and human-supervised embodied coordination. The evaluation question is whether preparation improves a meaningful task outcome beyond a strong simple baseline, without confusing observation, prediction, permission and applied action. Progress would require independent measurements, explicit uncertainty and separately authorized physical evaluation.

## Contribution and status

The engineering basis combines project integration and evaluation with established sensing, learning and simulation tools. MuJoCo, TheRobotStudio SO-101 designs, MuJoCo Menagerie and LeRobot ecosystem resources retain their upstream authorship. Research is in progress, and robotics manuscripts are in preparation; submission and acceptance are not claimed. This brief uses newly written text and shares no study recordings, unpublished implementation, numerical research tables or original research media.

