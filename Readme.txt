Find ableton user library: (usually \Documents\Ableton\User Library)
Place the patches in \User Library\Presets\Audio Effects\Max Audio Effect

Version 1 using spectral coordinates: IOSONO_Spectral.amxd
Version 2 using cartesian coordinates: IOSONO_Cartesian.amxd (assuming 5m width)

TODO add photo of automation

select correct channel

https://www.audinate.com/faq/how-can-i-tune-windows-pc-best-audio-performancethe following may also be required:

Set CStates to OFF
Disable Intel SpeedStep
Enable TurboBoost

foremost
'Flow Control' and 'Interrupt Moderation' can reduce the performance of your Ethernet interface and cause packets to be delayed. This is often the cause of late audio measurements on the Latency graph in Dante Controller for connections in and out of DVS. To configure Flow Control and Interrupt Moderation:
Go to Control Panel > Network and Internet > Network Connections
Right-click the network adaptor you use for Dante traffic, and select ‘Properties’
Click ‘Configure’
Select the ‘Advanced’ tab
Click ‘Flow Control’ and set the value to ‘Disabled’
Click ‘Interrupt Moderation’ and adjust for best performance (reduced latency vs. CPU usage)
Click OK


and important: use the correct adapter: incorrect one leads to reduced pc performance and signal loss (without error messages, so quite hard to find)