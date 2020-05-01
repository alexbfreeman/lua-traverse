# lua-traverse

This lua module will give you the ability to walk live objects in a similar manner to how the GC does. It will traverse VM objects.

You can implement your own function that gathers the the information you need. Then call the function `traverse` passing your function as a parameter. There are two functions already implemented, they can also server as an example: `countreferences` and `findallpaths`. 
