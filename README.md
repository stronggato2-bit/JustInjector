v1.5.0   Ma-Major Mi-Minor H-Hotfix
 | | |
Ma Mi H

PLEASE READ TEXT BELOW:
this script is almost fully vibecoded using gemini 3 flash and thinking mode sometimes, if i miss some credits, just let me know abt it before calling me skid

you can apply single or several (via json) fast flags
value is true/false/number
json example:
{
  "FFlagHandleAltEnterFullscreenManually": false,
  "FLogNetwork": 7,
  "FFlagFixGraphicsQuality": true,
  "DFFlagDisableDPIScale": true,
  "FFlagOptimizeNetwork": true,
  "FFlagOptimizeNetworkRouting": true,
  "FFlagOptimizeNetworkTransport": true,
  "FFlagOptimizeServerTickRate": true,
  "DFIntServerTickRate": 60,
  "DFIntRakNetResendRttMultiple": 1,
  "DFIntRaknetBandwidthPingSendEveryXSeconds": 1,
  "DFIntOptimizePingThreshold": 50,
  "DFIntPlayerNetworkUpdateQueueSize": 20,
  "DFIntPlayerNetworkUpdateRate": 60,
  "DFIntNetworkPrediction": 120,
  "DFIntNetworkLatencyTolerance": 1,
  "DFIntMinimalNetworkPrediction": 1,
  "DFIntMaxMissedWorldStepsRemembered": 1000
}

autoapply.json file in root folder of injector will auto-apply when injector starts (not working rn for some reason)

if roblox updated or fflags.hpp is missing, open roblox (in-game) and run FFlagsDumper.exe (fflags dumper isn't mine and i took it from person who skidded it)

you can enable/disable fastflags, changing value of existing fastflags in gridviewbox (gray box)

also added warning message if you already have fastflag (or fastflags) that you want to add

added some buttons like clear fflags and toggle fflags

deleted version from title of app, now its on top of this file

added factory reset button which restore default value to flags from 'factoryreset.json' file, thanks to MaximumADHD for the file

msg boxes translated to english for users (doesnt count as an update)

added presets list

added autosave fflags in editor (datagridview) when closing
added enabled/disabled state to autosave fflags

added console for logs
