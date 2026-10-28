# Public research roadmap

48+N is an ongoing programme with **two active directions**, not a single final demonstrator. The directions develop alongside several supporting research strands; each has its own experimental evidence and validation requirements.

- **Shadow — continuing low-level exchange:** Human reactions and corrections, short-horizon motion prediction, robot-local responses and protection, weak-link operation, and feedback to the operator.
- **MechaLink — human-directed task coordination:** Task meaning and revision, robot capability allocation, action selection, and the physical effects of changing a plan during execution.
- **Supporting work:** Real RGB-D sensing and reference quality, motion representation, robot visual re-observation, SO-101 simulation, and staged preparation for physical evaluation.

Two distinct robotics papers are in development: Shadow is targeted toward IEEE RA-L; the independent MechaLink study is still establishing the evidence needed for a standalone contribution. The two are parts of a longer-term research programme, not an assertion of completed integration or published results.

## Evidence gates for next claims

| Question | Evidence needed before a stronger claim |
|---|---|
| Is the measurement meaningful? | Independent checks of geometry and reference quality under the intended conditions |
| Does prediction help? | Strong simple baselines and an evaluation whose exposure and reference limits are explicit |
| Does high-level coordination help? | A fair comparison in which a more ordinary controller cannot already explain the outcome |
| Does the physical loop work? | Verified hardware and separately authorized evaluation of applied actions and observed outcomes |
| Can it transfer? | New embodiment/task evidence; an architecture diagram is insufficient |

No date or successful outcome is promised. These are research questions. Any further disclosure of methods, figures, data or code requires a separate review.
