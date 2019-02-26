# ndisapi

Windows Packet Filter (https://www.ntkernel.com/windows-packet-filter/) API library 

Documentation: https://www.ntkernel.com/docs/windows-packet-filter-documentation/

Library projects:

ndisapi.dll - native Win32 DLL wrapper (x86/x64)

ndisapi.lib - native Win32 static library wrapper (x86/x64)

ndisapi.net - .NET C++/CLI mixed class library (x86/x64)

ndisapi.vs2012 - Visual Studio 2012 project for native Win32 DLL wrapper (x86/x64). Provides support for the Windows XP/2003.

ndisapi.vc6 - Visual C++ 6.0 project for native Win32 DLL wrapper. Provides support for the legacy Windows versions prior Windows XP/2003.

Examples:

dnstrace - native C++ sample, intercepts DNS responses and decodes their content to the console. Has configurations to link NDISAPI statically and dynamically.

ethernet_bridge - native C++ sample, implements bridging wired and wireless networks. More information https://www.ntkernel.com/bridging-networks-with-windows-packet-filter/

TestDotNet - C# sample demonstrates the NDISAPI usage in several filtering scenarios. Available ion x86 and x64 configurations. AnyCPU configuration is not available due to the C++/CLI nature of ndisapi.net wrapper (see https://github.com/kevin-marshall/Managed.AnyCPU for the workaround). Projects references PacketDotNet (https://github.com/chmorgan/packetnet) for dumping network packets headers.


