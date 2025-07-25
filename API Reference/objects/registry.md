# REGISTRY
The registry a database containing the core and all other objects of sliver.
This is a place where you can modify just about anything, so be careful and know what you're doing.

```c
REGISTRY.version         // Contains the version of sliver.
REGISTRY.init            // Contains the root starting point of sliver.
REGISTRY.start           // Contains the starting point of the sliver instance.
REGISTRY.sessions        // Contains all collected sessions.
REGISTRY.session         // Contains the session that is currently in use.
REGISTRY.session_history // Contains a buffer of the last 100 sessions.
REGISTRY.commands        // Contains all commands of sliver.
REGISTRY.cmd_history     // Contains a buffer of the last 100 used commands.
REGISTRY.vars            // Contains all variables.
REGISTRY.macros          // Contains all macros.
REGISTRY.wordlists       // Contains all wordlists.
REGISTRY.exploitdb       // Contains a collection of known exploits.
REGISTRY.libs            // Contains a collection of imported libraries.
REGISTRY.dlls            // Contains a collection of imported dlls.
```