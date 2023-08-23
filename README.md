# export-usd-option

in Resource/OmniversePlugin/config.json
```json
{
  "SessionName" : "Default",
  "EndSessionRemoveInactiveSkelRoot" : true,
  "MsgRemoveInactiveSkelRoot" : false,
  "EndSessionRenameReplacedSkelRoot" : false,
  "PreferNewLightSchema" : true,
  "SyncConstraintSkelEveryFrame" : true,
  "PropSkelResetScale" : true,
  "ResetScaleBeforeTransferPropSkel" : false,
  "BakeMouthOpen" : false,  ---> change to true
  "AbsolutePathTex" : true,
  "DeleteLiveFolder" : true
}
```
1. change BakeMouthOpen to true,
(don't need to reopen AP, config is read every-time export button pressed)
2. export USD, the character

