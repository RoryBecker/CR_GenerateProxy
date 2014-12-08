'Generate Proxy' for CodeRush
================
Generates a Proxy class A, of Source class B, without altering B.

This is useful for mocking Webservices. One can generate a proxy and then extract an interface from the proxy. 

One can now mock the interface safe in the knowledge that it accurately represents the proxy and the source class.

The generated Proxy provides wrapper methods and properties for all the public methods and properties on the source class. It takes an instance of the source class in it's constructor, redirecting calls made to itself to this inner instance.

Usage 
===
  * Place the caret on the source class name.
  * Activate the "Generate Proxy" Code Provider.

OR

  * Place caret on any Type reference.
  * Activate the "Generate Proxy" Code Provider.

A new Proxy class will be generated with a constructor which takes a single instance of the base type from which the which takes an instance of the source in it's constructor.
