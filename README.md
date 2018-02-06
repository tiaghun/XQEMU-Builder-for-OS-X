# XQEMU-Builder-for-OS-X
A very small standalone Bash script that automatically downloads, builds, and install XQEMU (QEMU based Xbox emulator) for macOS El Capitan through High Sierra. The script also creates a build log for debugging purposes.

The following dependencies are required to build XQEMU on macOS:

1.) A command line package manager (i.e. MacPorts, Homebrew, or Fink.)  

2.) `pkg-config` installed.  

3.) `glib2` installed.  

4.) `/opt/local/bin/` and `/usr/local/bin/` directories in your PATH variable.  

5.) Xcode and Xcode Command Line Tools installed.  

# Usage

1.) Download script, move script to desired working directory.  

2.) Change to desired working directory and run `chmod u+x ./XQEMU_build_OSX`

3.) Run script, after git clone is finished it will download dependencies (`pixman` and `dtc`) to temp directory (`xqemu/`), and build.

4.) Log will be output to `./XQEMU_build.log`, and temporary directory will be deleted when installation finishes.
