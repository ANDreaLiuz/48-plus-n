# 48+N — PhD Research Brief

**Human-centered embodied intelligence · Baseline brief reviewed 23 October 2026**

## Research question

How can a person direct an embodied system while human reactions, uncertain observations, predictive preparation, robot-local feedback and changing task requirements unfold together? 48+N investigates this through two connected research directions: Shadow at the low-level interaction loop and MechaLink at the level of task meaning, embodied capabilities and human-directed revision. Human authority remains explicit.

## Architecture

The intended architecture connects a human goal, sensing, Shadow's predictive preparation, explicit human authority, MechaLink's task and embodiment coordination, an executor and feedback. Shadow studies ongoing low-level coordination through human corrections, short-horizon prediction, robot-local response and feedback to the operator; MechaLink concerns what the task requires of a proposed body. Prediction supplies preparation, not permission.

## Continuing research directions

**Shadow — low-level interaction:** Bidirectional human–robot coordination: immediate human corrections, short-horizon motion prediction, robot-local responses and protective behaviour, weak-link handling, and feedback to the operator. The goal is to establish what these mechanisms actually contribute under measured input and timing conditions.

**MechaLink — task and embodiment:** Interpreting human goals, allocating actions to a robot's capabilities, and handling in-execution revisions without losing valid physical state. The research tests such ideas against ordinary control and replanning alternatives.

These directions are developed in parallel, alongside sensing and calibration, motion representation, robot re-observation, simulation and future physical verification. Two related robotics papers are being developed: Shadow is being prepared with IEEE RA-L as the intended venue, and MechaLink is a separate developing study whose contribution remains under evaluation. Neither work is submitted or accepted.

## Engineering foundation

**Sensing:** Real RGB-D observations have been acquired with D455/D435i cameras, with frame, timing and software interface checks. A limited native camera-to-prediction-to-software-consumer path has also been recorded.

**Prediction:** GRU-based motion forecasts have been evaluated against simple baselines using recorded motion. Those comparisons make input availability, measurement reference and baseline choice part of the analysis.

**Simulation:** Ordinary SO-101 control in MuJoCo has exercised grasp, lift, transport, placement and retreat. Rendered RGB-D re-observation has informed updated target estimates in controlled tabletop cases. These tasks retain known scene geometry and simulator ground-truth contact checks.

## Validation limits

These are separate evidence streams, not a completed human-to-physical-robot evaluation. Current evidence does not establish anatomical accuracy, effective anticipation, population generalization or physical safety. A distinct high-level method advantage over ordinary controllers is also unproven. Independent reference quality, fair baseline comparisons and broader task conditions remain central evaluation needs.

## Prospective PhD direction

Prospective PhD work would deepen both connected directions: when low-level prediction and robot-local response add meaningful value in a human-directed control loop, and how task-level autonomy can adapt to changing human instructions and embodiment capabilities. Evaluations would compare against strong ordinary baselines while keeping observations, predictions, authorization, applied actions and measured outcomes distinct. Physical verification would follow calibration, independent measurement and separately authorized safety review.

## Contribution and status

The engineering basis combines project integration and evaluation with established sensing, learning and simulation tools. MuJoCo, TheRobotStudio SO-101 designs, MuJoCo Menagerie and LeRobot ecosystem resources retain their upstream authorship. Research is in progress, and robotics manuscripts are in preparation; submission and acceptance are not claimed. This brief uses newly written text and shares no study recordings, unpublished implementation, numerical research tables or original research media.

