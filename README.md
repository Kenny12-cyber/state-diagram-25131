my specification on state diagram
.....................................
Main Components
..............
Active State:

The system begins in the Active state, where the traffic lights are operational and cycling through different signal phases (Green, Yellow, Red).
Green Phase:

Vehicles Can Go: This phase allows vehicles to move while the pedestrian signals are red, preventing pedestrian crossing.
Duration: This phase lasts approximately 30–60 seconds.
Once the timer expires, the system transitions to the Yellow Phase.
Yellow Phase:

Prepare to Stop: This phase indicates that vehicles should prepare to stop, giving a warning that the signal will soon change.
Duration: This phase lasts around 3–5 seconds.
After the timer for this phase expires, the system transitions to the Red Phase.
Red Phase:

Vehicles Must Stop: During this phase, vehicles are required to stop, and pedestrian signals may turn green to allow safe pedestrian crossing.
Duration: This phase also lasts about 30–60 seconds.
After this phase completes, the system returns to the Green Phase.
Transitions and Timers
Each phase has a timer that dictates the transition to the next phase. Once the timer for a specific phase expires, the system moves to the subsequent phase in the cycle.
Transitions occur in the following sequence:
Green ➔ Yellow ➔ Red ➔ back to Green.
Additional Features
The system includes several features for enhanced traffic management:

Emergency Vehicle Preemption: Allows the traffic lights to give priority to emergency vehicles, overriding the current cycle to provide a green light for quick passage.
Adaptive Traffic Control: Adjusts the timing of signals based on real-time traffic conditions to optimize flow.
Pedestrian Crossing Signals: Signals specifically for pedestrian crossings, possibly synchronized with the red light for vehicles.
Night Mode: The traffic lights may operate in a different mode or timing schedule during nighttime hours.
Maintenance Alerts: System alerts for maintenance, likely triggered by system diagnostics or failures.
