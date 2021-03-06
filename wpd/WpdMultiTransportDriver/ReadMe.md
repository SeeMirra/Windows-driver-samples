WPD multi-transport sample driver
=================================

The WpdMultiTransportDriver sample demonstrates how you could extend the WpdHelloWorldDriver for a device that supports multiple transports. A transport is a protocol over which a portable device communicates with a computer. Example transports include Internet Protocol (IP), Bluetooth, and USB.

A number of portable devices now support multiple transports. For example, a number of cell phones support both Bluetooth and USB. Before Windows 7, if a user connected a portable device that supported multiple transports to their computer, the Windows Device Manager displayed a unique node for each transport. This implied that multiple devices had been installed and left the user confused. To resolve this, Windows now supports a multitransport driver model. This model ensures that only one node appears for each device.

For a complete description of this sample and its underlying code and functionality, refer to the [WPD MultiTransport Driver](http://msdn.microsoft.com/en-us/library/windows/hardware/ff597709) description in the Windows Driver Kit documentation.

Related topics
--------------

[WPD Design Guide](http://msdn.microsoft.com/en-us/library/windows/hardware/ff597864)

[WPD Driver Development Tools](http://msdn.microsoft.com/en-us/library/windows/hardware/ff597568)

[WPD Programming Guide](http://msdn.microsoft.com/en-us/library/windows/hardware/)
