# DataBaseManager_Issue


I tried to use this add-on. I can dowload and install it as described in documentation.

When I enable it in Project Settings, Godot returns the following issues:
```
 res://addons/godot_db_manager/db_interface.gd:15 - Parse Error: The identifier "gddb_constants" isn't declared in the current scope.
 modules/gdscript/gdscript.cpp:599 - Method failed. Returning: ERR_PARSE_ERROR

 res://addons/godot_db_manager/dlgs/new_db_dlg.gd:30 - Parse Error: The identifier "gddb_globals" isn't declared in the current scope.
 modules/gdscript/gdscript.cpp:599 - Method failed. Returning: ERR_PARSE_ERROR
```

However, I can start it in Project>Tools and the main window appears. After this point, the commands in File>New DB/Load DB don't answer.

OS : Windows10
Godot 3.2.2.stable

The error occured for downloads from the Godot Engine and Github.
