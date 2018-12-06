# 6. MAC功能描述

## 6.1 设备类型和约定

以下有两种设备类型：

*  FFD可作为PAN协调器、协调器、设备、RFD-TX设备、RFD-RX设备或其任何组合进行操作。

*  RFD不能作为PAN协调器或协调器运行，但可以作为设备运行，RFD-TX设备，或RFD-RX设备



由MAC子层或PHY层指定和维护的常量和PAN信息库\(PIB\)属性用斜体写在文本中。

常量一般前缀为“a”，如aBaseSlotDuration, MAC常量列于表8-80，PHY常量列于表11-1。

MAC PIB属性有一个通用前缀“mac”，例如，macExtendedAddress，并被列在表8-81，而安全属性列在表9-8中。

PHY PIB属性的前缀一般为“phy”，如phyCurrentChannel，列于表11-2



MAC定义中的一些时间参数是以PHY符号为单位的。对于具有多个符号周期的PHYs，用于MAC参数的持续时间在PHY子句中定义。



广播短地址被定义为0xffff。广播PAN ID被定义为0xffff。广播地址是指广播短地址或64位广播MAC地址，在IEEE Std 802-2014中定义为0xffff ffff ffff。



