# goldragon-persona

The definition of the complex Gold Dragon Persona: the being the living names and
talks to, as the Flow Nexus runs it. One `Configure` family per file, in the
form Flow 0.53.3 and later read:

- `metaflows-0533.datom`: every permaflow, its modules, launch and purpose. An entry is
  `{ Address Root LeaveOuts SystemModules PromptModules Kind Tools Continuity Purpose Records }`:
  the leave-outs, each a name of the closed LeaveOut enum, are the third field, after the Root and
  before the system modules, and are an empty vector when the permaflow leaves nothing out.
- `models-0533.datom`: the native model each model name runs.
- `thresholds-0533.datom`: each native model's context mark.

These files preserve the authored declarations. The running configuration is held in
Flow's Memory, and the current Home deployment does not replay these files into it
automatically.
