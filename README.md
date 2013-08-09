LBR-EX Enhanced Libraries, Scripts, and ULPs for Cadsoft Eagle
==============================================================
This document describes using the LBR-EX libraries and scripts as a global
replacement to the default libraries and scripts that ship with Eagle. In most
cases, you can globally update/upgrade designs that use the original Eagle
libraries via the "Update All" command in the schematic or board editor. These
library parts have been carefully updated and maintained to minimize drill
size differences, silkscreen text/widths and standardize package uses wherever
possible for consistency and accuracy. While it is likely mistakes do exist,
many commercial designs have been verified and placed into production using
these libraries. Great pain has been taken to assure the accuracy and
consistency across all the libraries contained in this package.

Perhaps one of the most useful upgrade libraries is the rc-master libraries
which replace the default rcl.lbr library that ships with Eagle. The library
rc-master-smd.lbr is designed specifically for SMD components while the library
rc-master.lbr contains SMD and through hole components. Great attention has been
given to these important libraries to provide a cleaner solution with consistent
silkscreen appearance and pad size/spacing suitable for commercial type work.
The ULP migrate-rc-master.ulp can be used to globally replace and migrate most
all parts in existing designs from rcl.lbr to the rc-master libraries.
A general description of the additional SCR and ULP utilities provided are
also described in this document. Please visit http://www.bobstarr.net for
additional information and see the README.PDF documentation for complete
information on using the libraries.
