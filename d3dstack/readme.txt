Unlike other samples, which are available from CodeSampler.com, this sample 
does not ship with the necessary .dlls to run it. You'll need to download and
install a SDK to work with this sample.

Follow the steps outlined below to compile and run this sample.

-------------------------------------------------------------------------------

1. If you haven't already, you'll need to download and install the 
   Tokamak Game Physics SDK v1.21

   http://www.tokamakphysics.com/

   Installation basically consists of unzipping the file "tokamak_lib_1_21.zip"
   to somewhere on yoiur machine for safe keeping. I unzipped mine to C:\.

-------------------------------------------------------------------------------

2. The last step is to add some new paths to Visual Studio so the header and
   library files for Tokamak can be located for compiling:

   To set these, navigate the menus to "Tools->Options". When the Options" 
   dialog opens, expand the tree control on the left to 
   "Projects->VC++ Directories" and add the following:

   Add these to Visual Studio's include path:

   C:\tokamak_lib_1_21\include

   Add these to Visual Studio's library path:

   C:\tokamak_lib_1_21\lib
   
-------------------------------------------------------------------------------

