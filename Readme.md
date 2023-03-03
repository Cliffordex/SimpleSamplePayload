Sample payload for SimpleHooker

You can hook an application like Notepad, and this payload will open a dialog box.

BEWARE: Do not edit any process memory directly! 
This is in a separate thread, so unless you pause the main thread, bad things will happen.
Also, do not edit anything statically.
ASLR (Address space layout randomization) will change and you will write something you don't mean to.
