# gsutil

This directory contains the Python command line tool gsutil, which Google
has released as open source, to demonstrate the Google Cloud Storage API and to
provide a tool for manipulating data in the system.

## Prerequisites

Gsutil requires Python 2.6 or later.

To install gsutil take the following steps:

1. Pick a place where you want to install the software. You can
   install the code wherever you prefer; for brevity the instructions below
   assume you want to install in `$HOME/gsutil`.

2. To install gsutil on Linux/Unix or MacOS, open a shell window, change
   directories to where you downloaded the gsutil.tar.gz file, and do this:

   ```
   tar xfz gsutil.tar.gz -C $HOME
   ```

   Then add the following line to your `$HOME/.bashrc` shell initialization
   file:

   ```
   export PATH=${PATH}:$HOME/gsutil
   ```

   The next time you start a shell you should be able to run gsutil from
   the command line.

3. To install gsutil on Windows, install [cygwin](http://www.cygwin.com/),
   with at least version 2.6.5 of Python. Once you have that, start a shell
   and follow the Linux instructions above for unpacking and installing gsutil.

4. The first time you try to run gsutil, it will detect that you have no
   configuration file containing your credentials, interactively prompt you,
   and create the file.  

   After this you can use the tool.  Running gsutil with with no arguments
   will print a help summary.

For more information on installing and using gsutil, see
https://developers.google.com/storage/docs/gsutil
