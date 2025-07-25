# REGISTRY
The registry a database containing the core and all other objects of sliver.
This is a place where you can modify just about anything, so be careful and know what you're doing.

```c
Registry.version         // Contains the version of sliver.
Registry.init            // Contains the root starting point of sliver.
Registry.start           // Contains the starting point of the sliver instance.
Registry.sessions        // Contains all collected sessions.
Registry.session         // Contains the session that is currently in use.
Registry.session_history // Contains a buffer of the last 100 sessions.
Registry.commands        // Contains all commands of sliver.
Registry.cmd_history     // Contains a buffer of the last 100 used commands.
Registry.vars            // Contains all variables.
Registry.macros          // Contains all macros.
Registry.wordlists       // Contains all wordlists.
Registry.exploitdb       // Contains a collection of known exploits.
Registry.libs            // Contains a collection of imported libraries.
Registry.dlls            // Contains a collection of imported dlls.
```