Description: Removing the external/ directory which is not present in dfsg tarball.
Author: Francesco Paolo Lovergine <frankie@debian.org>
Forwarded: not-needed

--- a/config/generic.mak.in
+++ b/config/generic.mak.in
@@ -44,7 +44,7 @@ RPC_INCLUDES = @RPC_INCLUDES@
 
 UCB_STATICLIB = 
 
-TCL_INCLUDE = -I/usr/include/tcl8.3
+TCL_INCLUDE = -I/usr/include/tcl
 TCL_LINKLIB =
 
 #
--- a/makefile
+++ b/makefile
@@ -22,7 +22,7 @@ include $(TOPDIR)/config/common.mak
 #
 # Sub-directories that need to be built
 #
-subdirs	= external vpflib ogdi contrib
+subdirs	= vpflib ogdi contrib
 
 #
 # Default target to build everything in all sub-directories
--- a/ogdi/makefile
+++ b/ogdi/makefile
@@ -15,7 +15,7 @@ include $(TOPDIR)/config/common.mak
 #
 # Sub-directories that need to be built
 #
-subdirs	= include c-api glutil attr_driver driver gltpd examples
+subdirs	= include c-api glutil attr_driver driver gltpd tcl_interface
 
 #
 # Default target to build everything in all sub-directories
