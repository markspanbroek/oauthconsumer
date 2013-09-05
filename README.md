OAuthConsumer
=============

Contains an OAuth consumer library for iOS.

This is a port to iOS and ARC.
The original OSX code can be found here: http://oauth.googlecode.com/svn/code/obj-c/.

Usage
-----
To use this library in your app, you need to follow these steps:

   * Add the XCode project from this repository to your app project. 
   * Set the User Header Search Path in XCode to include the folder where the OAuthConsumer header files are located, for instance: ${PROJECT_DIR}/OAuthConsumer
   * Add libOAuthConsumer.a to the libraries that your target is linked against
   * Add -ObjC to Other Linker Flags in XCode.

For more usage documentation, see: http://code.google.com/p/oauthconsumer/.