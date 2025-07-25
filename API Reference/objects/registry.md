# REGISTRY - object
The registry is a database containing the core and all other objects of sliver.
This is a place where you can modify just about anything, so be careful and know what you're doing.

```c
REGISTRY {
  STRING   version,         // Contains the version of sliver.
  SESSION  init,            // Contains the root starting point of sliver.
  SESSION  start,           // Contains the starting point of the sliver instance.
  ARRAY    sessions,        // Contains all collected sessions.
  SESSION* session,         // Contains a pointer to the session that is currently in use.
  ARRAY    session_history, // Contains a buffer of the last 100 sessions.
  MAP      commands,        // Contains all commands of sliver.
  ARRAY    cmd_history,     // Contains a buffer of the last 100 used commands.
  MAP      vars,            // Contains all variables.
  MAP      macros,          // Contains all macros.
  MAP      wordlists,       // Contains all wordlists.
  MAP      exploitdb,       // Contains a collection of known exploits.
  MAP      libs,            // Contains a collection of imported libraries.
  MAP      dlls             // Contains a collection of imported dlls.	
}
```