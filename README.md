# barcode-reader-dlls

Windows DLL builds of the [libdmtx](https://sourceforge.net/p/libdmtx/libdmtx/) and
[ZBar](http://zbar.sourceforge.net/) barcode readers, made available here for the benefit
of [pylibdmtx](https://github.com/NaturalHistoryMuseum/pylibdmtx) and
[pyzbar](https://github.com/NaturalHistoryMuseum/pyzbar/) respectively.

* libdmtx 32-bit: `libzbar-32.dll`
* libdmtx 64-bit: `libzbar-64.dll`
* zbar 32-bit: `libiconv-2.dll` and `libzbar-32.dll`
* zbar 64-bit: `libiconv.dll` and `libzbar-64.dll`

ZBar is licensed under the [GNU Lesser General Public License, version 2.1](http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html).
libdmtx is licensed under [Simplified BSD license with an alternate waiver option](https://sourceforge.net/p/libdmtx/libdmtx/ci/master/tree/LICENSE).

The DLLs require the
[Visual C++ Redistributable Packages for Visual Studio 2013](https://www.microsoft.com/en-US/download/details.aspx?id=40784).
Install ``vcredist_x64.exe`` if using 64-bit Python, ``vcredist_x86.exe`` if
using 32-bit Python.
