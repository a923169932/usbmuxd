# usbmuxd-win32

*A socket daemon to multiplex connections from and to iOS devices.*

*This branch replaces libusb1.0 functions with libusb-win32 functions, in order to better support Windows 7*


Links
Homepage: https://libimobiledevice.org/
Repository: https://git.libimobiledevice.org/usbmuxd.git
Repository (Mirror): https://github.com/libimobiledevice/usbmuxd.git
Issue Tracker: https://github.com/libimobiledevice/usbmuxd/issues
Mailing List: https://lists.libimobiledevice.org/mailman/listinfo/libimobiledevice-devel
Twitter: https://twitter.com/libimobiledev
License
This library and utilities are licensed under the GNU General Public License v3.0, also included in the repository in the COPYING.GPLv3 file.

Credits
The initial usbmuxd daemon implementation was authored by Hector Martin.

Apple, iPhone, iPad, iPod, iPod Touch, Apple TV, Apple Watch, Mac, iOS, iPadOS, tvOS, watchOS, and macOS are trademarks of Apple Inc.

usbmuxd is an independent software application and has not been authorized, sponsored, or otherwise approved by Apple Inc.

README Updated on: 2020-06-13

For general questions about usbmuxd, see http://github.com/libimobiledevice/usbmuxd. For questions specific to Visual C++, feel free to use the GitHub issue tracker

How to get the latest binaries
The binaries for usbmuxd are added as an artifact to each Azure Pipeline build. Check the status of the latest build and download the .zip file.

On Windows, you'll need to install the following dependencies:

Microsoft Visual C++ Redistributable Packages for Visual Studio 2015
Microsoft Visual C++ Redistributable Packages for Visual Studio 2012 Update 4
Building on Windows
You can open usbmuxd.sln in Visual Studio and restore the packages and build from there, or from the commandline:

nuget restore
msbuild usbmuxd.sln


