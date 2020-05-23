# Windows-10-Home-Feature-Update-Delay
Windows 10 Home Feature Update Delay 

1.Open Start Menu

2.Open up Run 

3.Type regedit

4.Find the following registry enty
Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\WindowsUpdate\UX\Settings

5.Select BranchReadinessLevel right click with mouse and select 
Modify> Decimal set value to 20

6.Select DeferFeatureUpdatesPeriodInDays right click with mouse and select 
Modify>Decimal set value 365

Select DeferQualityUpdatesPeriodInDays right click with mouse and select 
Modify> Decimal set value 4 

7.Exit

See attached picture for details.
