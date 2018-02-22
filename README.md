# SSDPFinder
initial commit
This module for Majordomo (majordomo.smartliving.ru) provide opportunity for browsing UPNP devices


![ScreenShot](/screen.png)

Запись для себя
выключатель - состояние on off
<?xml version="1.0" encoding="utf-8"?>
<root xmlns="urn:schemas-upnp-org:device-1-0">
<specVersion>
<major>1</major>
<minor>0</minor>
</specVersion>

<device>
<deviceType>urn:schemas-upnp-org:device:BinaryLight:1</deviceType>
<friendlyName>Kitchen Lights</friendlyName>
<manufacturer>OpenedHand</manufacturer>
<modelName>Virtual Light</modelName>
<UDN>uuid:cc93d8e6-6b8b-4f60-87ca-228c36b5b0e8</UDN>

<serviceList>
<service>
<serviceType>urn:schemas-upnp-org:service:SwitchPower:1</serviceType>
<serviceId>urn:upnp-org:serviceId:SwitchPower:1</serviceId>
<SCPDURL>/SwitchPower1.xml</SCPDURL>
<controlURL>/SwitchPower/Control</controlURL>
<eventSubURL>/SwitchPower/Event</eventSubURL>
</service>
</serviceList>
</device>
</root>
