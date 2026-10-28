# Research status

**Research in progress · Baseline release evidence reviewed 23 October 2026; selected subsequent frozen engineering records reviewed 28 October 2026.** Shadow and MechaLink are continuing, parallel research directions, supported by sensing, prediction, weak-link, robot perception and embodiment studies. Two distinct robotics papers are under development, with no submission or acceptance claimed.

| Area | Evidence reviewed | What can be concluded | What remains open |
|---|---|---|---|
| Shadow prediction | Historical recorded-data baselines and newer bounded development analyses | Predictive preparation is an active research question with implemented analysis and engineering | Consistent advantage over strong simple baselines, independent reference validity and population generalization |
| Sensing | Real camera acquisition and interface/measurement checks | Sensor software has been exercised on real devices | Full geometric validation, anatomical accuracy and robustness across operating conditions |
| MechaLink | Bounded SO-101 simulation task and visual re-observation development | Limited task execution has been exercised in simulation under stated scene/contact assumptions | High-level method advantage over ordinary baselines and transfer beyond those conditions |
| Simulated operator interaction | Generated operator-command checks in a bounded SO-101 MuJoCo interface exercised correction, HOLD and simulated settling | Simulated command consumption and resulting motion can be examined, without treating it as a formal comparison | HOLD acceptance is distinct from stopping and settling; real-time performance, human-study benefit, independent task benefit and physical-robot transfer remain unestablished |
| Physical realization | No reviewed evidence of robot-applied actions establishing the claimed complete loop | Physical robot benefit is not established | Hardware verification and a separately authorized physical evaluation |
| Cross-embodiment extension | Architecture and research framing | A research direction | Generalization to arbitrary tools, humanoids or bodies |
| Publication | Local working manuscripts and research planning | Manuscripts in preparation | Submission and acceptance are not established |

A completed software check does not establish anatomical correctness or safe physical operation. Real sensing is different from real robot execution. Simulation tasks do not establish a complete real-time human-to-robot interface.

Source reports, exact numerical comparisons and publication-sensitive details are retained in the separate private review process. An internal freeze records an artifact version; it is not independent validation or publication approval.
