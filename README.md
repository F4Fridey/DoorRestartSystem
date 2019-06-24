# Door Restart System
This is a SCP SL plugin that allows for the facility to have a "door software restart". This means all doors are closed and locked for about 10 seconds, then unlocked.

# Installation
Download and place the DoorRestartSystem.dll file (found <a href="https://github.com/F4Fridey/DoorRestartSystem/releases" target="_blank">here</a>) into you sm_plugins foler in you server. Then customise the following configs:

# Configs
`drs_door_restart_enabled: true/false` (defaults to true)<br>
`drs_door_restart_min: time` (the minimun time before a restart happens, in seconds, default is 300)<br>
`drs_door_restart_max: time` (the maximum time before a restart happens, in seconds, default is 360)<br>
`drs_repeat_restarts: true/false` Have restarts happen more than once per round. Defaults to false.<br>
`drs_lockdown_duration: time` Duration of lockdown in seconds. Defaults to 10 seconds.<br>
