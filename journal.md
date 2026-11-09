Phase 1
The ?? operator provides a default value (false) if no saved value exists. Without it, the result could be null, which cannot be assigned to a non-nullable bool.

Phase 2
Testing file writes with the console helps make sure the data saves correctly before displaying it in the UI. The NoteStorage class keeps file operations separate, making the code easier to organize and maintain.