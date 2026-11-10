# goldragon-persona

The definition of the complex Gold Dragon Persona: the being the living names and
talks to, as the Flow Nexus runs it. One `Configure` family per file, in the
form Flow 0.53.3 and later read:

- `metaflows-0533.datom`: every permaflow, its modules, launch and purpose.
- `models-0533.datom`: the native model each model name runs.
- `thresholds-0533.datom`: each native model's context mark.

CriomOS-home reads them from this repository, writes each to
`~/.local/state/flow-declarations/` under its own name, and the Flow Nexus
configuration unit replays them into the running Nexus.
