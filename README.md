# Windows-10-Home-Feature-Update-Delay
Windows 10 Home Feature Update Delay 

1.Open Start Menu

2.Open up Run 

3.Type regedit

4.Find the following registry entry
Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\WindowsUpdate\UpdatePolicy\PolicyState

# For Windows 10 Older Builds 1809,1903,1909
* Find the following registry entry
* Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\WindowsUpdate\UX\Settings

5.Select DeferFeatureUpdatesPeriodInDays right click with mouse and select 
Modify>Decimal set value 365

Select DeferQualityUpdatesPeriodInDays right click with mouse and select 
Modify> Decimal set value 0 

6.Exit

See attached pictures for details.
