# Customization
## Desktop Customization
* You need to install TaskbarX and Rainmeter from their sites and use the provided skins to make custom changes. After adding the accent clock, edit the clock file to
[Rainmeter]
Author=Mohak Chhaparwal
Version=1.0
License=Protected
BackgroundMode=1

[Accent]
Measure=Plugin
Plugin=SysColor
ColorType=DWM_COLOR
DisplayType=RGB


[AM/PM]
Measure=Time
Format=%p

[AM/PM Count]
MeasureName=AM/PM
Meter=String
X=190
Y=40
FontFace=Mistral
FontColor=255,255,255,200
FontSize=20
StringAlign=CENTER
StringStyle=Normal
AntiAlias=1
DynamicVariables=1


[Hour]
Measure=Time
Format=%I

[Hour Count]
Meter=STRING
MeasureName=Hour
X=20
Y=00
FontFace=Mistral
FontColor=[Accent],200
FontSize=110
StringAlign=Centre
StringStyle=Normal
AntiAlias=1
DynamicVariables=1


[Minute]
Measure=Time
Format=%M

[Minute Count]
Meter=STRING
MeasureName=Minute
X=30
Y=120
FontFace=Mistral
FontColor=[Accent],200
FontSize=100
StringAlign=Centre
StringStyle=normal
AntiAlias=1
DynamicVariables=1


[Date]
Measure=Time
Format=%b %d

[Date Count]
MeasureName=Date
Meter=String
X=90
Y=260
W=300
FontFace=Mistral
FontColor=255,255,255,200
FontSize=16
StringAlign=Right
StringStyle=normal
AntiAlias=1
DynamicVariables=1


[Divider]
Meter=IMAGE
SolidColor=[Accent],200
X=95
Y=260
W=1
H=25
DynamicVariables=1


[Year]
Measure=Time
Format=%Y

[Year Count]
MeasureName=Year
Meter=String
X=100
Y=260
W=300
FontFace=Mistral
FontColor=255,255,255,200
FontSize=16
StringAlign=Centre
StringStyle=normal
AntiAlias=1
DynamicVariables=1


[Divider 2]
Meter=IMAGE
SolidColor=[Accent],200
X=145
Y=260
W=1
H=25
DynamicVariables=1


[Day]
Measure=Time
Format=%a
            
[Day Count]
MeasureName=Day
Meter=String
X=150
Y=260
W=300
FontFace=Mistral
FontColor=255,255,255,200
FontSize=16
StringAlign=Left
StringStyle=normal
AntiAlias=1
DynamicVariables=1

* Then after installing the TaskbarX, open the configure.exe to change the opacity of the taskbar and change the position of icons on the taskbar to center.
# Make Windows look like Mac OS
* Install NextDock from their website and configure its theme as shown in the picture inside Screenshots
* Now install the Big Sur skin on your rainmeter . Customize the widgets and other features according to your likes. 
* Use the icons provided to replace the icons to be used on the Nexus Dock
* Enjoy your new windows experience.................
