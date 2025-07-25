# REGISTRY - object
The registry a database containing the core and all other objects of sliver.
This is a place where you can modify just about anything, so be careful and know what you're doing.

```c
REGISTRY {
  version         // Contains the version of sliver.
  init            // Contains the root starting point of sliver.
  start           // Contains the starting point of the sliver instance.
  sessions        // Contains all collected sessions.
  session         // Contains the session that is currently in use.
  session_history // Contains a buffer of the last 100 sessions.
  commands        // Contains all commands of sliver.
  cmd_history     // Contains a buffer of the last 100 used commands.
  vars            // Contains all variables.
  macros          // Contains all macros.
  wordlists       // Contains all wordlists.
  exploitdb       // Contains a collection of known exploits.
  libs            // Contains a collection of imported libraries.
  dlls            // Contains a collection of imported dlls.	
}
```