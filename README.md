Lab 1: Square Roots and Specifications
=====

For this part of the lab activity, clone this repository to your local machine. Then:
* Add `mySqrt/MySqrt.jar` as a library to use through Eclipse (similar to Part A);
* Add the Javadoc path appropriately;
* Test the `sqrt( )` method that is part of the `MySqrt` class;
* Describe the behaviour of `MySqrt.sqrt( )` in a text file named `mySqrt.txt`.

The following is a specification on `MySqrt.sqrt( )` and you should be able to see this via Javadoc support as well:
```
	/**
	 * My own implementation of the sqrt( ) function.
	 * @param x the parameter for which we would like to find the square root.
	 * @return y such that y*y == x (with some epsilon accuracy) if x >= 0 else return -1.
	 */
	
	public static double sqrt( double x )
```

A procedural specification tells us what a method does without telling us how the method is implemented.

Does the implementation, based on your testing, satisfy the specification? If the implementation does not satisfy the spec then describe how it does not. If it does satisfy the specification then is the behaviour one that is *expected*? Are there specific problems with the specification itself? 

* Add your observations to `mySqrt.txt`.
* Create a **private** BitBucket repository called `lab1b` and add the lab session TA as a user for that repository.
* Include only `mySqrt.txt` in the local repository, commit and push it to BitBucket.

_Think about what you have learnt from this lab activity. MP0 will be released soon._

