# DA382A NetLogo Agent-Based Simulation

This repository hosts a NetLogo model that explores interactions between two breeds of agents—citizens and cops—inside a small town. The model demonstrates how Belief–Desire–Intention (BDI) reasoning, message-based communication, and time-driven routines can be combined to produce rich agent behaviour.

## Directory structure

- `FinalTemplate/` – primary implementation of the model.
  - `FinalTemplate.nlogo` – main NetLogo model file that ties together all supporting `.nls` files.
  - `bdi.nls` – helpers for storing beliefs, intentions and executing actions in a BDI style.
  - `communication.nls` – message passing system that lets agents send and receive information.
  - `time_library.nls` – wrappers around the time extension for scheduling and querying dates.
  - `setupenvironment.nls` – builds the map: homes, workplaces, town square, prison and other landmarks.
  - `citizens.nls` – citizen-specific state and behaviour routines.
  - `cops.nls` – cop-specific state and behaviour routines.
  - `vid.nls` – utilities for recording the simulation with the `vid` extension.
- `PT_Template1/` – an earlier template kept for reference.

## Running the model

1. Open `FinalTemplate/FinalTemplate.nlogo` in NetLogo.
2. Press **Setup** to create the town and spawn agents.
3. Press **Go** to start the simulation.
4. Adjust parameters in the Interface tab or extend the `.nls` files to explore new behaviours.

## Development guidelines

Development should occur on separate branches. Avoid committing directly to `main`; merge only when features are stable and reviewed with the group.

## License

Add licensing information here if applicable.
