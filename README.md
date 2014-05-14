newStorage
==========

This class allow you to create a storage variable. In this storage variable you can store an objec or an arraylist or an array or an array bideminsional or an array tridimensional.

Are asking yourself what difference between arraylist and array, don't you?

The difference is that an arraylist has a limit of position (You can overwrite the limit default), so when this limit is reached no more information can be stored on it, but can be updated or removed (removing allow to added a new information) while array there is no limit of position. An array can have as much as necessary position.

To create a storage variable, just type the script below

    var store = new newStorage({
      type:"array", //The type of storage. ("object, "array","arraylist","array2d","array3d")
      maxLength:20,  //Setting the max limit for arraylist is 20. It will only affect when you inform type:"arraylist"
      max2DLength:20,  //Setting the max limit for array bidimensional is 20. It will only affect when you inform type:"array2d",
      max3DLength:20,  //Setting the max limit for array tridimensional is 20. It will only affect when you inform type:"array3d"
    });
  
Then you can use all the methods that this class offer to you. But be careful, there are methods that can only work with specific type of store.

For exemple:

There is method called add.

This method only work for storage with one dimensional.

To add information on a bidimensional store the method is add2D.

To add information on a tridimensional store the methods is add3D.

This class is still in development. So be pacient and soon it will be avaliable.
