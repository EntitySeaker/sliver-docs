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

# Session.New - function
The Session.New function will return a new session object.

```c
SESSION Session.New(
  STRING type,         // This should define the type of the session.
  OBJECT object,       // This should be the object.
  STRING loc_ip,       // This should define the session's local ip address.
  STRING pub_ip,       // This should define the session's public ip address.
  STRING hostname,     // This should define the computer's name.
  STRING current_user, // This should define the user owning the object.
  STRING path          // This should be the current working directory.
)
```

## Parameters

`type`

Type: **type**

This should define the type of session ex: init, start, shell, computer, file.

`object`

Type: **object**

The object connected to the session, this could be a shell object, computer object or file object.

`loc_ip`

Type: **string**

This should define the session's local ip address.

`pub_ip`

Type: **string**

This should define the session's public ip address.

`hostname`

Type: **string**

This should define the machine's name.

`current_user`

Type: **string**

This should define the user that owns the object of the session.

`path`

Type: **string**

This should define the current working directory, the default of this value is `null` which defaults to the user's home directory.
## Return value
Type: **session**

A session object is returned.