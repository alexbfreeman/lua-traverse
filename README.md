# lua-traverse

This lua module will give you the ability to walk live objects in a similar manner to how the GC does. It will traverse VM objects.

You can implement your own function that gathers the information you need. Next, you can call the function `traverse` passing your new function as a parameter. There are two functions already implemented, they can serve as an example: `countreferences` and `findallpaths`. 
