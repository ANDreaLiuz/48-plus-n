# Architecture: goals, preparation and realization

The intended flow is **human goal → observation → Shadow preparation → explicit human authority → MechaLink coordination → embodiment executor → feedback**.

This is a conceptual organization of the research, not a public specification of the private controller, authorization protocol or unpublished algorithms.

## Shadow: prepare under uncertainty

Shadow studies ongoing low-level human–robot coordination: human corrections, short-horizon prediction, robot-local response and feedback to the operator. Predictive preparation is one part of this intended loop. Forecast quality must be interpreted against the observation reference and an appropriate baseline. A prediction does not itself authorize an action.

## MechaLink: realize a goal through a body

MechaLink concerns the task goal, the capabilities of a proposed embodiment and the coordination needed to realize an authorized task. A simulation can test a bounded realization under controlled assumptions. It cannot establish hardware readiness, correctness in a different scene or superiority to a strong ordinary controller.

## The human and the feedback path

The person supplies the goal and remains the source of task authority. The system must distinguish an expected state from an observed outcome. The feedback path in the [original diagram](assets/architecture.svg) is marked as an intended integration relationship, rather than evidence that the entire physical loop has run.

The public abstraction intentionally omits private state machines, gates, thresholds, policy implementations and unpublished method combinations.
