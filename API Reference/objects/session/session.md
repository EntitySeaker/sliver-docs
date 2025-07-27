# session - object
A session object is the object containing all information about a session, like it's object, home path etc. 

```c
session {
  STRING type,        // Contains the of the object inside the session.
  STRING local_ip,    // Contains the local ip of the session.
  STRING public_ip,   // Contains the public ip of the session.
  STRING get_home,    // Contains the path to the user's home directory.
  STRING active_user, // Contains the user that owns the object.
  OBJECT object,      // Contains the object of the session ex: shell.
  STRING path,        // Contains the path of the current working directory.
  STRING jumpfile,    // Contains the path to the jumpfile.
  MAP    data,        // Contains extra data about the session.	
}
```