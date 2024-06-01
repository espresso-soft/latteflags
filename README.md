<h3 align="center">♡</h3>

<h3 align="center">
  <img src="assets/asap.gif" width="256" alt="LIVE.LOVE.A$AP">
</h3>

<h1 align="center">plagiarizing simulator</h1>

#### Version: 6.1.24++
* **165 Currently Listed**
* `No Decals`
* **Textures currently don't work because "FFlagMSRefactor5" was removed, Roblox always removes the useful features instead of harmful stuff.**

## Bloxstrap How to Use:
1. **Open the [Bloxstrap Menu](https://github.com/pizzaboxer/bloxstrap).**
2. **Navigate to `Fast Flags` >> `Fast Flags Editor` >> `Import Json`.**
3. **Paste in the JSON.**
4. **Save and your good to go!**

<img src="/assets/tutorial.gif" width="750"/>

[Watch a Video Tutorial](https://www.youtube.com/watch?v=d7jzGM5kYO4)

## Normal Roblox Bootstrapper  How to Use:
###### You can also do Roblox Studio
1. **Navigate to your Roblox Installation directory. Typically found at `%localappdata%\Roblox\Versions\` or `C:\Program Files (x86)\Roblox\Versions`.**
2. **Identify the folder `version-xxxxxxxxxxxxxxxx` ~~containing `RobloxPlayerBeta.exe`~~ You can do this for Roblox Studio too.**
3. **Create a new folder named `ClientSettings`. Inside this folder, place the file `ClientAppSettings.json`.**
4. **Paste the JSON into `ClientAppSettings.json`. (You can utilize ChatGPT to format multiple JSONs for clarity if needed)**
5. **Save and your good to go!**
###### Do note that after roblox updates you have to paste in your fflags again.

[Watch a Video Tutorial](https://streamable.com/rk5an6)

## How to Use _PlaceFilter
1. **Add `_PlaceFilter` after the Fast Flag name.**
2. **Add a semicolon after the Value (`;`). Examples: `True;`, `1;`.**
3. **Include a Place ID after the semicolon. Examples: `True;4483381587`, `1;4483381587`.**
4. **Your configuration is complete!**

[Watch a Video Tutorial](https://www.youtube.com/watch?v=5XjhPF5ydJM)

 # List Navigation
* **[Rendering](https://github.com/collectivists/rbxflags/tree/main?tab=readme-ov-file#rendering)**
* **[Graphical](https://github.com/collectivists/rbxflags/tree/main?tab=readme-ov-file#graphical-settings)**
* **[UI](https://github.com/collectivists/rbxflags/tree/main?tab=readme-ov-file#user-interface)**
* **[Textures](https://github.com/collectivists/rbxflags/tree/main?tab=readme-ov-file#textures)**
* **[Physics](https://github.com/collectivists/rbxflags/tree/main?tab=readme-ov-file#physics)**
* **[Other FFlags](https://github.com/collectivists/rbxflags/tree/main?tab=readme-ov-file#other-fflags)**
* **[Links](https://github.com/collectivists/rbxflags/tree/main?tab=readme-ov-file#links)**

<img src="assets/bitdancer.png" width="888"/>

<h3 align="center">══════⊹⊱≼≽⊰⊹══════</h3>

<h1 align="center">Pride Month Exclusive</h1>

### Become gay!
```json
{
    "FFlagDebugDisplayUnthemedInstances": "True"
}
```


<h1 align="center">Rendering API</h1>

### Metal
###### MacOS Only
```json
{
    "FFlagDebugGraphicsPreferMetal": "True"
}
```
### Vulkan
```json
{
    "FFlagDebugGraphicsDisableDirect3D11": "True",
    "FFlagDebugGraphicsPreferVulkan": "True"
}
```
### OpenGL
```json
{
    "FFlagDebugGraphicsDisableDirect3D11": "True",
    "FFlagDebugGraphicsPreferOpenGL": "True"
}
```
### Direct X 10
```json
{
    "FFlagDebugGraphicsPreferD3D11FL10": "True"
}
```
### Direct X 11
```json
{
    "FFlagDebugGraphicsPreferD3D11": "True"
}
```

<h1 align="center">Lightning Technologies</h1>

### Voxel Lighting (Phase 1)
```json
{
    "DFFlagDebugRenderForceTechnologyVoxel": "True"
}
```
### Shadowmap Lighting (Phase 2)
```json
{
    "FFlagDebugForceFutureIsBrightPhase2": "True"
}
```
### Future Lighting (Phase 3)
```json
{
    "FFlagDebugForceFutureIsBrightPhase3": "True"
}
```

<h1 align="center">Graphical Settings <sup>& more</sup></h1>

### Semi Fullbright
```json
{
    "FFlagFastGPULightCulling3": "True",
    "FIntRenderShadowIntensity": "0",
    "DFIntCullFactorPixelThresholdShadowMapHighQuality ": "2147483647",
    "DFIntCullFactorPixelThresholdShadowMapLowQuality": "2147483647",
    "FFlagNewLightAttenuation": "True",
    "FIntRenderShadowmapBias": "-1",
    "DFFlagDebugPauseVoxelizer": "True"
}
```
### Draws a circle under avatars
```json
{
    "FFlagDebugAvatarChatVisualization": "True",
    "FFlagEnableInGameMenuChromeABTest2": "False"
}
```
### HyperThreading
```json
{
    "FFlagDebugCheckRenderThreading": "True",
    "FFlagRenderDebugCheckThreading2": "True"
}
```
### Maximum Threads
```json
{
    "FIntRuntimeMaxNumOfThreads": "2400"
}
```
### Minimum Threads
```json
{
    "FIntTaskSchedulerThreadMin": "3"
}
```
### Smoother Terrain
```json
{
    "FFlagDebugRenderingSetDeterministic": "True"
}
```
### Graphics Quality Level
```json
{
    "FIntRomarkStartWithGraphicQualityLevel": "1"
}
```
### Disable Player Shadows
```json
{
    "FIntRenderShadowIntensity": "0"
}
```
### Disable Shadows
```json
{
    "DFIntCullFactorPixelThresholdShadowMapHighQuality": "2147483647",
    "DFIntCullFactorPixelThresholdShadowMapLowQuality": "2147483647"
}
```
### Preserve rendering quality with display setting
```json
{
    "DFFlagDisableDPIScale": "True"
}
```
### Low Graphics Quality w/ Max Render Distance/FRM Quality Levels
###### Explanation: 1-6 Are low graphics, Above 6 are high graphics. Like the 1-21 graphics slider
```json
{
    "DFIntDebugFRMQualityLevelOverride": "1"
}
```

<h4 align="center">FRM Levels</h4>

```
Low

1 = 3
2 = 2
3 = 6

High

4 = 7
5 = 11
6 = 14
7 = 15 
8 = 17
9 = 18
10 = 21
```

### 21 Graphics Quality Slider
```json
{
    "FFlagCommitToGraphicsQualityFix": "True",
    "FFlagFixGraphicsQuality": "True"
}
```

### Low Render Distance
###### [FRM](https://github.com/collectivists/rbxflags/tree/main?tab=readme-ov-file#frm-levels)
```json
{
    "DFIntDebugRestrictGCDistance": "1"
}
```
### Disable Wind
```json
{
    "FFlagGlobalWindRendering": "False",
    "FFlagGlobalWindActivated": "False"
}
```
### Limits light updates
```json
{
    "FIntRenderLocalLightUpdatesMax": "8",
    "FIntRenderLocalLightUpdatesMin": "6"
}
```
### Disables fade in and fade out animation every light update
```json
{
    "FIntRenderLocalLightFadeInMs": "0"
}
```
### Makes avatars shiny 
###### [everything goes black on <3] ***[DFIntDebugFRMQualityLevelOverride is there to set your graphics to 10, You can change it to anything above 3: [Click here to view](https://github.com/collectivists/rbxflags/tree/main?tab=readme-ov-file#frm-levels) ]***
```json
{
    "DFIntRenderClampRoughnessMax": "-640000000",
    "DFIntDebugFRMQualityLevelOverride": "6"
}
```
### Disable PostFX
```json
{
    "FFlagDisablePostFx": "True"
}
```
### Pause Voxelizer/Disable Baked Shadows
```json
{
    "DFFlagDebugPauseVoxelizer": "True"
}
```
### Gray Sky
###### Only applies to games with the default skybox
```json
{
    "FFlagDebugSkyGray": "True"
}
```
### Disable Player Shadows
```json
{
    "FIntRenderShadowIntensity": "0"
}
```
### Force LOD on Meshes
```json
{
    "DFIntCSGLevelOfDetailSwitchingDistance": "0",
    "DFIntCSGLevelOfDetailSwitchingDistanceL12": "0",
    "DFIntCSGLevelOfDetailSwitchingDistanceL23": "0",
    "DFIntCSGLevelOfDetailSwitchingDistanceL34": "0"
}
```
### Lighting Attenuation
```json
{
    "FFlagNewLightAttenuation": "True"
}
```
### Enable GPULightCulling
###### Combine with [Lighting Attenuation](https://FastFlags/FastFlags-Collective/?tab=readme-ov-file#lighting-attenuation) for better vision
```json
{
    "FFlagFastGPULightCulling3": "True"
}
```
### Enable CPULightCulling
```json
{
    "FFlagDebugForceFSMCPULightCulling": "True"
}
```
### Frame Buffer
###### Explnation: 0 makes white screen 1-3 makes other players have laggy movement, 4 is stable has better performance than 10 and less input lag
```json
{
    "DFIntMaxFrameBufferSize": "4"
}
```
### Low Quallity Terrain Textures
###### 4 for less quality 16, 32, 64 for higher quality
```json
{
    "FIntTerrainArraySliceSize": "4"
}
```
### High Quality Textures 
###### *[1-3]*
```json
{
    "DFFlagTextureQualityOverrideEnabled": "True",
    "DFIntTextureQualityOverride": "3"
}
```
### Lower Quality Textures 
###### *[1-3]*
```json
{
    "DFIntPerformanceControlTextureQualityBestUtility": "-1"
}
```
### No avatar textures
```json
{
    "DFIntTextureCompositorActiveJobs": "0"
}
```
### No Decals
###### From: https://discord.gg/nKjV3mGq6R
```json
{
    "FIntDebugTextureManagerSkipMips": "-1"
}
```
### Remove Grass
```json
{
    "FIntFRMMinGrassDistance": "0",
    "FIntFRMMaxGrassDistance": "0",
    "FIntRenderGrassDetailStrands": "0",
    "FIntRenderGrassHeightScaler": "0"
}
```
### Force MSAA 
###### *[0, 1, 2, 4, 8]*
```json
{
    "FIntDebugForceMSAASamples": "4"
}
```
### ShadowMap Bias 
###### ***[Future & ShadowMap]***
```json
{
    "FIntRenderShadowmapBias": "75"
}
```
### Enables Network Debug Tracker menu
##### Instructions: CTRL+F8
```json
{
    "DFFlagDebugEnableInterpolationVisualizer": "True"
}
```
### Humanoid Outline
##### Draws an outline around every part and every humanoid
```json
{
    "DFFlagDebugDrawBroadPhaseAABBs": "True"
}
```
### fflag above but more complex
##### Draws an outline around every body part
```json
{
    "DFFlagDebugDrawBvhNodes": "True"
}
```
### Buggy ZPlane Camera
```json
{
    "FIntCameraFarZPlane": "1"
}
```
### Xray
###### too lazy to explain what it does, shout out to tyetonix
```json
{
    "DFIntCullFactorPixelThresholdMainViewHighQuality": "10000",
    "DFIntCullFactorPixelThresholdMainViewLowQuality": "10000",
    "DFIntCullFactorPixelThresholdShadowMapHighQuality": "10000",
    "DFIntCullFactorPixelThresholdShadowMapLowQuality": "10000"
}
```

<h1 align="center">User Interface</h1>

### Remove VR Toggle
```json
{
    "FFlagAlwaysShowVRToggleV3": "False"
}
```
### Break Collectible Icon
```json
{
    "FFlagDisplayCollectiblesIcon": "False"
}
```
### Favorite Item in-game
```json
{
    "FFlagEnableFavoriteButtonForUgc": "True"
}
```
### Home Sidebar Text
```json
{
    "FFlagEnableNavBarLabels3": "True"
}
```
### Revert New "Builder" Font
```json
{
    "FFlagUIBloxDevUseNewFontNameMapping": "False",
    "FFlagEnableNewFontNameMappingABTest2": "False",
    "FFlagAddArialToLegacyContent": "False",
    "FFlagAddGothamToLegacyContent": "False"
}
```
### FPS Unlocker in Roblox Menu Settings
```json
{
    "FFlagGameBasicSettingsFramerateCap5": "True",
    "DFIntTaskSchedulerTargetFps": "0"
}
```
### Revert spacing on errors
```json
{
    "FFlagErrorPromptResizesHeight": "False"
}
```
### GUI Hiding Toggles
```json
{
    "FFlagUserShowGuiHideToggles": "True",
    "GuiHidingApiSupport2": "True"
}
```
### Darker Dark Theme
```json
{
    "FFlagLuaAppUseUIBloxColorPalettes1": "True",
    "FFlagUIBloxUseNewThemeColorPalettes": "True"
}
```
### Subscriptions Page
```json
{
    "FFlagLuaAppDevSubsEnabled": "True"
}
```
### No Transparency V4 Menu **(2023)**
```json
{
    "FStringInGameMenuModernizationStickyBarForcedUserIds": "UserID"
}
```
### Revert Old Report Menu
```json
{
    "FStringReportAbuseMenuRoactForcedUserIds": "null",
    "FFlagEnableReportAbuseMenuRoactABTest2": "False",
    "FFlagEnableReportAbuseMenuRoact2": "False",
    "FFlagEnableReportAbuseMenuLayerOnV3": "False"
}
```
### Custom MicroProfile Scale
```json
{
    "DFIntMicroProfilerDpiScaleOverride":  "100"
}
```
### Hides gui
```json
{
    "FFlagDebugAdornsDisabled":  "True"
}
```
### Dont Render UI
```json
{
    "FFlagDebugDontRenderUI": "True"
}
```
### Dont Render Screen GUIs
```json
{
    "FFlagDebugDontRenderScreenGui": "True"
}
```
### Enable Audio Controller
```json
{
    "FFlagTrackerLodControllerDebugUI": "True"
}
```
### Disable Autocomplete
```json
{
    "FFlagEnableCommandAutocomplete": "False"
}
```
### Break Top Bar Menu
```json
{
    "FStringNewInGameMenuForcedUserIds": "UserID",
    "FFlagEnableInGameMenuChrome": "True"
}
```
### Chrome UI TopBar
```json
{
    "FFlagEnableInGameMenuChrome": "True",
    "FFlagEnableReportAbuseMenuRoactABTest2": "True",
    "FFlagChromeBetaFeature": "True",
    "FFlagEnableInGameMenuChromeABTest2": "True"
}
```
### Pin Chat on Chrome UI
```json
{
    "FFlagEnableChromePinnedChat": "True"
}
```
### Pin Buttons on Chrome UI
```json
{
    "FFlagEnableChromePinIntegrations": "True"
}
```
### Chrome UI Topbar Removal
```json
{
    "FFlagEnableInGameMenuChromeABTest2": "False",
    "FFlagEnableReportAbuseMenuRoactABTest2": "False"
}
```
### Disable Bubble Chat
```json
{
    "FFlagEnableBubbleChatFromChatService": "False"
}
```
### Disable Selfview
```json
{
    "FFlagCoreGuiTypeSelfViewPresent": "False"
}
```
### Disable Camera & Selfview
```json
{
    "FFlagSelfieViewEnabled": "True"
}
```
### Force Disable Camera
```json
{
    "DFFlagVideoCaptureServiceEnabled": "True"
}
```
### Disable Avatar Chat
```json
{
    "FFlagAvatarChatServiceEnabled3": "False"
}
```
### Remove VC Beta Badge
```json
{
    "FFlagVoiceBetaBadge": "False",
    "FFlagTopBarUseNewBadge": "False",
    "FFlagEnableBetaBadgeLearnMore": "False",
    "FFlagBetaBadgeLearnMoreLinkFormview": "False",
    "FFlagControlBetaBadgeWithGuac": "False",
    "FStringVoiceBetaBadgeLearnMoreLink": "null"
}
```
### Hide guis
###### ***Instructions: Replace "ID" with any group ID that you are in.***
| Key combination   | Action                                                                    |
| ----------------- | ------------------------------------------------------------------------- |
| Ctrl + Shift + B  | Toggles GUIs in 3D space (BillboardGuis, SurfaceGuis, etc)                |
| Ctrl + Shift + C  | Toggles game-defined ScreenGuis                                           |
| Ctrl + Shift + G  | Toggles Roblox CoreGuis                                                   |
| Ctrl + Shift + N  | Toggles player names, and other BillboardGuis that show up above a player |
```json
{
    "DFIntCanHideGuiGroupId": "ID"
}
```
### Disable Fullscreen Title Bar
```json
{
    "FIntFullscreenTitleBarTriggerDelayMillis": "3600000"
}
```
### Set Custom Font Size
```json
{
    "FIntFontSizePadding": "1"
}
```
### Set Custom Kick Message Lenght
```json
{
    "FIntMaxKickMessageLength": "1"
}
```

<h1 align="center">Textures</h1>

### Fix Textures
```json
{
    "FFlagMSRefactor5": "False"
}
```
### No Textures
```json
{
    "FStringPartTexturePackTable2022": "{\"glass\":{\"ids\":[\"rbxassetid://9873284556\",\"rbxassetid://9438453972\"],\"color\":[254,254,254,7]}}",
    "FStringPartTexturePackTablePre2022": "{\"glass\":{\"ids\":[\"rbxassetid://7547304948\",\"rbxassetid://7546645118\"],\"color\":[254,254,254,7]}}",
    "FStringTerrainMaterialTable2022": "",
    "FStringTerrainMaterialTablePre2022": "",
    "FFlagMSRefactor5": "False"
}
```
### Trollface Textures
```json
{
    "FStringPartTexturePackTable2022": "{\u0022foil\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[238,238,238,255]},\u0022asphalt\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[227,227,228,234]},\u0022basalt\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[160,160,158,238]},\u0022brick\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[229,214,205,227]},\u0022cobblestone\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[218,219,219,243]},\u0022concrete\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[225,225,224,255]},\u0022crackedlava\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[76,79,81,156]},\u0022diamondplate\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[210,210,210,255]},\u0022fabric\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[221,221,221,255]},\u0022glacier\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[225,229,229,243]},\u0022glass\u0022:{\u0022ids\u0022:[\u0022rbxassetid://9873284556\u0022,\u0022rbxassetid://9438453972\u0022],\u0022color\u0022:[254,254,254,7]},\u0022granite\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[210,206,200,255]},\u0022grass\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[196,196,189,241]},\u0022ground\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[165,165,160,240]},\u0022ice\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[235,239,241,248]},\u0022leafygrass\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[182,178,175,234]},\u0022limestone\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[250,248,243,250]},\u0022marble\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[181,183,193,249]},\u0022metal\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[226,226,226,255]},\u0022mud\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[193,192,193,252]},\u0022pavement\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[218,218,219,236]},\u0022pebble\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[204,203,201,234]},\u0022plastic\u0022:{\u0022ids\u0022:[\u0022\u0022,\u0022rbxassetid://9475422736\u0022],\u0022color\u0022:[255,255,255,255]},\u0022rock\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[211,211,210,248]},\u0022corrodedmetal\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[206,177,163,180]},\u0022salt\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[249,249,249,255]},\u0022sand\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[218,216,210,240]},\u0022sandstone\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[241,234,230,246]},\u0022slate\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[235,234,235,254]},\u0022snow\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[239,240,240,255]},\u0022wood\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[217,209,208,255]},\u0022woodplanks\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[207,208,206,254]}}",
    "FStringPartTexturePackTablePre2022": "{\u0022foil\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[238,238,238,255]},\u0022asphalt\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[227,227,228,234]},\u0022basalt\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[160,160,158,238]},\u0022brick\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[229,214,205,227]},\u0022cobblestone\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[218,219,219,243]},\u0022concrete\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[225,225,224,255]},\u0022crackedlava\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[76,79,81,156]},\u0022diamondplate\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[210,210,210,255]},\u0022fabric\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[221,221,221,255]},\u0022glacier\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[225,229,229,243]},\u0022glass\u0022:{\u0022ids\u0022:[\u0022rbxassetid://9873284556\u0022,\u0022rbxassetid://9438453972\u0022],\u0022color\u0022:[254,254,254,7]},\u0022granite\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[210,206,200,255]},\u0022grass\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[196,196,189,241]},\u0022ground\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[165,165,160,240]},\u0022ice\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[235,239,241,248]},\u0022leafygrass\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[182,178,175,234]},\u0022limestone\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[250,248,243,250]},\u0022marble\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[181,183,193,249]},\u0022metal\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[226,226,226,255]},\u0022mud\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[193,192,193,252]},\u0022pavement\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[218,218,219,236]},\u0022pebble\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[204,203,201,234]},\u0022plastic\u0022:{\u0022ids\u0022:[\u0022\u0022,\u0022rbxassetid://9475422736\u0022],\u0022color\u0022:[255,255,255,255]},\u0022rock\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[211,211,210,248]},\u0022corrodedmetal\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[206,177,163,180]},\u0022salt\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[249,249,249,255]},\u0022sand\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[218,216,210,240]},\u0022sandstone\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[241,234,230,246]},\u0022slate\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[235,234,235,254]},\u0022snow\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[239,240,240,255]},\u0022wood\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[217,209,208,255]},\u0022woodplanks\u0022:{\u0022ids\u0022:[\u0022rbxassetid://15482832278\u0022,\u0022rbxassetid://14983259444\u0022],\u0022color\u0022:[207,208,206,254]}}",
    "FFlagMSRefactor5": "False"
}
```

### Black Textures
```json
{
    "FStringPartTexturePackTable2022": "{\u0022foil\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022asphalt\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022basalt\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022brick\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022cobblestone\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022concrete\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022crackedlava\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022diamondplate\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022fabric\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022glacier\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022glass\u0022:{\u0022ids\u0022:[\"rbxassetid://9873284556\",\"rbxassetid://9438453972\"],\u0022color\u0022:[55, 55, 55, 255]},\u0022granite\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022grass\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022ground\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022ice\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022leafygrass\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022limestone\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022marble\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022metal\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022mud\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022pavement\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022pebble\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022plastic\u0022:{\u0022ids\u0022:[\u0022\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022rock\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022corrodedmetal\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022salt\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022sand\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022sandstone\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022slate\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022snow\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022wood\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022woodplanks\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]}}",
    "FStringPartTexturePackTablePre2022": "{\u0022foil\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022brick\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022cobblestone\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022concrete\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022diamondplate\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022fabric\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022glass\u0022:{\u0022ids\u0022:[\"rbxassetid://7547304948\",\"rbxassetid://7546645118\"],\u0022color\u0022:[55, 55, 55, 255]},\u0022granite\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022grass\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022ice\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022marble\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022metal\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022pebble\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022corrodedmetal\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022sand\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022slate\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022wood\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022woodplanks\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022asphalt\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022basalt\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022crackedlava\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022glacier\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022ground\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022leafygrass\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022limestone\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022mud\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022pavement\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022rock\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022salt\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022sandstone\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]},\u0022snow\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[55, 55, 55, 255]}}",
    "FFlagMSRefactor5": "False"
}
```
### White Textures
```json
{
    "FStringPartTexturePackTable2022": "{\u0022foil\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022asphalt\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022basalt\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022brick\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022cobblestone\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022concrete\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022crackedlava\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022diamondplate\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022fabric\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022glacier\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022glass\u0022:{\u0022ids\u0022:[\"rbxassetid://9873284556\",\"rbxassetid://9438453972\"],\u0022color\u0022:[255, 255, 255]},\u0022granite\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022grass\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022ground\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022ice\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022leafygrass\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022limestone\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022marble\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022metal\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022mud\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022pavement\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022pebble\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022plastic\u0022:{\u0022ids\u0022:[\u0022\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022rock\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022corrodedmetal\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022salt\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022sand\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022sandstone\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022slate\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022snow\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022wood\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022woodplanks\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]}}",
    "FStringPartTexturePackTablePre2022": "{\u0022foil\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022brick\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022cobblestone\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022concrete\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022diamondplate\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022fabric\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022glass\u0022:{\u0022ids\u0022:[\"rbxassetid://7547304948\",\"rbxassetid://7546645118\"],\u0022color\u0022:[255, 255, 255]},\u0022granite\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022grass\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022ice\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022marble\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022metal\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022pebble\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022corrodedmetal\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022sand\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022slate\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022wood\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022woodplanks\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022asphalt\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022basalt\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022crackedlava\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022glacier\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022ground\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022leafygrass\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022limestone\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022mud\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022pavement\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022rock\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022salt\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022sandstone\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]},\u0022snow\u0022:{\u0022ids\u0022:[\u0022rbxassetid://0\u0022,\u0022rbxassetid://0\u0022],\u0022color\u0022:[255, 255, 255]}}",
    "FFlagMSRefactor5" :"False"
}
```
### Minecraft Textures
````
{
    "FStringPartTexturePackTablePre2022": "{\"foil\":{\"ids\":[\"rbxassetid://9873266399\",\"rbxassetid://9438410239\"],\"color\":[238,238,238,255]},\"asphalt\":{\"ids\":[\"rbxassetid://9867974823\",\"rbxassetid://9844502433\"],\"color\":[227,227,228,234]},\"basalt\":{\"ids\":[\"rbxassetid://11545552824\",\"rbxassetid://11545440462\"],\"color\":[160,160,158,238]},\"brick\":{\"ids\":[\"rbxassetid://9924770651\",\"rbxassetid://9924770538\"],\"color\":[229,214,205,227]},\"cobblestone\":{\"ids\":[\"rbxassetid://9919719550\",\"rbxassetid://9438453972\"],\"color\":[218,219,219,243]},\"concrete\":{\"ids\":[\"rbxassetid://9924775913\",\"rbxassetid://9924775826\"],\"color\":[225,225,224,255]},\"crackedlava\":{\"ids\":[\"rbxassetid://9920485426\",\"rbxassetid://9438453972\"],\"color\":[76,79,81,156]},\"diamondplate\":{\"ids\":[\"rbxassetid://10237721036\",\"rbxassetid://9438453972\"],\"color\":[210,210,210,255]},\"fabric\":{\"ids\":[\"rbxassetid://9920517963\",\"rbxassetid://9438453972\"],\"color\":[221,221,221,255]},\"glacier\":{\"ids\":[\"rbxassetid://9920518995\",\"rbxassetid://9438453972\"],\"color\":[225,229,229,243]},\"glass\":{\"ids\":[\"rbxassetid://9873284556\",\"rbxassetid://9438453972\"],\"color\":[254,254,254,7]},\"granite\":{\"ids\":[\"rbxassetid://9920550720\",\"rbxassetid://9438453972\"],\"color\":[210,206,200,255]},\"grass\":{\"ids\":[\"rbxassetid://11152995545\",\"rbxassetid://9267183930\"],\"color\":[196,196,189,241]},\"ground\":{\"ids\":[\"rbxassetid://11546360009\",\"rbxassetid://11545533676\"],\"color\":[165,165,160,240]},\"ice\":{\"ids\":[\"rbxassetid://9920556429\",\"rbxassetid://9438453972\"],\"color\":[235,239,241,248]},\"leafygrass\":{\"ids\":[\"rbxassetid://11152995545\",\"rbxassetid://9267183930\"],\"color\":[182,178,175,234]},\"limestone\":{\"ids\":[\"rbxassetid://9920561624\",\"rbxassetid://9438453972\"],\"color\":[250,248,243,250]},\"marble\":{\"ids\":[\"rbxassetid://9873292869\",\"rbxassetid://9438453972\"],\"color\":[181,183,193,249]},\"metal\":{\"ids\":[\"rbxassetid://11546526557\",\"rbxassetid://11546431794\"],\"color\":[226,226,226,255]},\"mud\":{\"ids\":[\"rbxassetid://9920578676\",\"rbxassetid://9438453972\"],\"color\":[193,192,193,252]},\"pavement\":{\"ids\":[\"rbxassetid://11546539560\",\"rbxassetid://11546440685\"],\"color\":[218,218,219,236]},\"pebble\":{\"ids\":[\"rbxassetid://9920581197\",\"rbxassetid://9438453972\"],\"color\":[204,203,201,234]},\"plastic\":{\"ids\":[\"\",\"rbxassetid://9868015012\"],\"color\":[255,255,255,255]},\"rock\":{\"ids\":[\"rbxassetid://11546570730\",\"rbxassetid://11546456858\"],\"color\":[211,211,210,248]},\"corrodedmetal\":{\"ids\":[\"rbxassetid://11545623165\",\"rbxassetid://11545476330\"],\"color\":[206,177,163,180]},\"salt\":{\"ids\":[\"rbxassetid://9920590478\",\"rbxassetid://9438453972\"],\"color\":[249,249,249,255]},\"sand\":{\"ids\":[\"rbxassetid://11546588111\",\"rbxassetid://11546468464\"],\"color\":[218,216,210,240]},\"sandstone\":{\"ids\":[\"rbxassetid://9920596353\",\"rbxassetid://9438453972\"],\"color\":[241,234,230,246]},\"slate\":{\"ids\":[\"rbxassetid://9867974823\",\"rbxassetid://9844502433\"],\"color\":[235,234,235,254]},\"snow\":{\"ids\":[\"rbxassetid://11536062048\",\"rbxassetid://11108916253\"],\"color\":[239,240,240,255]},\"wood\":{\"ids\":[\"rbxassetid://9867974813\",\"rbxassetid://9844454989\"],\"color\":[217,209,208,255]},\"woodplanks\":{\"ids\":[\"rbxassetid://9867974813\",\"rbxassetid://9844454989\"],\"color\":[207,208,206,254]}}",
    "FFlagMSRefactor5": "False"
}
````

<h1 align="center">Physics</h1>

### omg i cant believe roblox is that dumb to do this...
```json
{
    "FIntPhysicsGridHierarchyLowestLevelInitBinCount": "199999999",
    "FIntPhysicsGridHierarchyLowestLevelInitBinCountWorldModel": "100000000",
    "FIntPhysicsSolverCollisionPoolBucketSize": "2147483647",
    "FIntPhysicsSolverCollisionPoolBucketSizeWorldModel": "2147483647"
}
```
### Crash Roblox
```json
{
    "DFIntTimestepArbiterThresholdCFLThou": "0"
}
```
### Stuttery Animation Fix
```json
{
    "DFIntTimestepArbiterThresholdCFLThou": "300"
}
```
### Remap R6 to R15 Rigs/Weird Movement
```json
{
    "FFlagRemapAnimationR6ToR15Rig": "True"
}
```
### Weird Leg Movement
```json
{
    "DFFlagAnimatorPostProcessIK": "True"
}
```
### Adjust Hip Height Clamps
###### https://www.roblox.com/bundles/63/Mage-Animation-Package
```json
{
    "DFIntHipHeightClamp": "-48"
}
```
### Random High Jumps
###### https://youtu.be/2JkA4hWCAWw
```json
{
    "FFlagSimAdaptiveTimesteppingDefault2": "True",
    "DFFlagSimHumanoidTimestepModelUpdate": "True"
}
```
### Drunk
```json
{
    "FFlagSimAdaptiveTimesteppingDefault2": "True",
    "DFIntSimAdaptiveHumanoidPDControllerSubstepMultiplier": "-999999",
    "DFFlagSimHumanoidTimestepModelUpdate": "True"
}
```
### No Animations
###### **Stops the game from trying to replicate your animations in the server. You dont have animations in the server but you do for your client**
```json
{
    "DFIntReplicatorAnimationTrackLimitPerAnimator": "-1"
}
```
### Stick unanchored parts to you
##### - = up, + = down
```json
{
    "DFIntSolidFloorPercentForceApplication": "-1000",
    "DFIntNonSolidFloorPercentForceApplication": "-5000"
}
```
### Max Raycast Distance
###### Raycasting is the use of intersection tests to solve problems in ROBLOX. The most common use of raycasting is to determine the first object intersected by a ray. This is done by casting a virtual ray from a certain point in a direction and determining the first surface it intersected with.
###### Break legs collision from 2 to -inf, kinda break camera on values over 3 noclip cam on 3
```json
{
    "DFIntRaycastMaxDistance": "3"
}
```
### Possible Super Jump
```json
{
    "DFIntNewRunningBaseGravityReductionFactorHundredth": "1500"
}
```
### Change DataSender Rate
###### a.k.a does not let you load games
```json
{
    "DFIntDataSenderRate": "-1"
}
```
### Disable Touch Events
```json
{
    "DFIntTouchSenderMaxBandwidthBps": "-1"
}
```
### Fake Lag
```json
{
    "DFIntS2PhysicsSenderRate": "1"
}
```
### Invisible 1
###### **Stops the physics on your character froms sending to the server so your character doesn't move for the server. You can move on your client.**
```json
{
    "DFIntS2PhysicsSenderRate": "-30"
}
```
### Invisible 2
###### Locks your character's position on the server to (0, 0, 0), having the side effect of turning you invisible. This only affects the server and other clients, not you. server-sided things that rely on your position, like clicking to get tools, will not function. In some games these can be abusable. Here is a list of them: [Link](https://docs.google.com/document/d/1_kQr-tkc97lcg7ZvFfJdt8UzaziIfwuJPrzR6sTOLHo/)
```json
{
    "DFIntGameNetPVHeaderTranslationZeroCutoffExponent": "10"
}
```
### Invisible 3
###### Restricts the client from sending any physics-related information. This means other people can topple you over.
```json
{
    "DFIntPhysicsSenderMaxBandwidthBps": "1",
    "DFIntPhysicsSenderMaxBandwidthBpsScaling": "0"
}
```
### Invisible 4 [GATEKEPT UNTIL LEAKED]
```
{
    "?": "-1",
    "?": "2147483647"
}
```
### Clientsided Invisible
```json
{
    "FIntParallelDynamicPartsFastClusterBatchSize": "-1",
}
```
### Warp & Slowmotion
```json
{
    "DFIntMaxMissedWorldStepsRemembered": "1"
}
```
```json
{
    "DFIntMaxMissedWorldStepsRemembered": "1000"
}
```
### Noclip 1
###### Adjust the value so you don't fall through the ground
```json
{
    "DFFlagAssemblyExtentsExpansionStudHundredth": "-50"
}
```
### Noclip 2
###### Adjust the value so you don't fall through the ground
```json
{
    "DFIntSimBroadPhasePairCountMax": "50"
}
```
### Hip Height
###### Very controllable bounce, only works with negative values, 0 allows you to hover
```json
{
    "DFIntMaxAltitudePDStickHipHeightPercent": "-200"
}
```
### Wallglide
```json
{
    "DFIntUnstickForceAttackInTenths": "-4"
}
```

<h1 align="center">other fflags</h1>

### New Camera Mode
```json
{
    "FFlagNewCameraControls": "True"
}
```
### Disable In-game Advertisements
```json
{
    "FFlagAdServiceEnabled": "False"
}
```
### Disable Telemetry 
```json
{
    "FFlagDebugDisableTelemetryEphemeralCounter": "True",
    "FFlagDebugDisableTelemetryEphemeralStat": "True",
    "FFlagDebugDisableTelemetryEventIngest": "True",
    "FFlagDebugDisableTelemetryPoint": "True",
    "FFlagDebugDisableTelemetryV2Counter": "True",
    "FFlagDebugDisableTelemetryV2Event": "True",
    "FFlagDebugDisableTelemetryV2Stat": "True"
}
```
### Adjust Scroll Speed
```json
{
    "FIntScrollWheelDeltaAmount": "140"
}
```
### Surf the web inside of Roblox
###### Click the Beta badge or the 13+ badge to open the webview browser.
```json
{
    "FFlagTopBarUseNewBadge": "True",
    "FStringTopBarBadgeLearnMoreLink": "https://google.com/",
    "FStringVoiceBetaBadgeLearnMoreLink": "https://google.com/"
}
```
### Sounds use physical velocity and become distorted
###### <2017
```json
{
    "FFlagSoundsUsePhysicalVelocity": "True"
}
```
### Audio Occlusion
```json
{
    "FFlagSoundsUsePhysicalVelocity": "True"
}
```
### Shows the state of a flag
```json
{
    "FStringDebugShowFlagState": "FLAG_HERE"
}
```
###### e.g
```json
{
    "FStringDebugShowFlagState": "DFIntTaskSchedulerTargetFps, ChannelName"
}
```
### MTU 
```json
{
    "DFIntConnectionMTUSize": "MTU_HERE"
}
```
### Increase Ping 
```json
{
    "DFIntDataSenderMaxBandwidthBps": "150"
}
```
### No Internet Disconnect 
###### *[You will still be kicked but the message wont show.]*
```json
{
    "DFFlagDebugDisableTimeoutDisconnect": "True"
}
```
### Quick Game Launch 
###### *[BUGGY]*
```json
{
    "FFlagEnableQuickGameLaunch": "True"
}
```
### Allows you to change voice chat distance 
###### default: [Min 7 Max 80]
```json
{
    "DFIntVoiceChatRollOffMinDistance": "7",
    "DFIntVoiceChatRollOffMaxDistance": "80"
}
```
### Disable In-Game Purchases
```json
{
    "DFFlagOrder66": "True"
}
```
### Disable Chat
```json
{
    "FFlagDebugForceChatDisabled": "True"
}
```
### Limit audios that are being played
```json
{
    "DFIntMaxLoadableAudioChannelCount": "1"
}
```
### Adds an UI in game, which highlights any part player touches (like ground, Meshes etc.). It's a non-functioning UI too. Also adds a blue circle to your humanoid.
```json
{
    "FFlagDebugHumanoidRendering": "True"
}
```
### Custom Disconnect Message
```json
{
    "FFlagReconnectDisabled": "True",
    "FStringReconnectDisabledReason": "You're stupid and I hate you"
}
```
### Display FPS
```json
{
    "FFlagDebugDisplayFPS": "True"
}
```
### Verified Badge
###### Clientsided
```json
{
    "FStringWhitelistVerifiedUserId": "UserID"
}
```
### Verified Badge on everyone
###### Clientsided
```json
{
    "FFlagOverridePlayerVerifiedBadge": "True"
}
```
### Applies cool colors to stuff
```json
{
    "FFlagDebugDisplayUnthemedInstances": "True"
}
```
### Show Outlined Chunks
```json
{
    "FFlagDebugLightGridShowChunks": "True"
}
```
### Show Outlined Chunks that are being interacted
```json
{
    "DFFlagDebugEnableStreamingSolverVisualization": "True"
}
```
### Remove Disconnect Blur/Loading Blur
```json
{
    "FIntRobloxGuiBlurIntensity": "0"
}
```
### Disable Dynamic Heads Animations
###### https://roblox.fandom.com/wiki/Dynamic_Head
```json
{
    "DFIntAnimationLodFacsDistanceMin": "0",
    "DFIntAnimationLodFacsDistanceMax": "0",
    "DFIntAnimationLodFacsVisibilityDenominator": "0"
}
```
### failsafehumanoid
###### gray avatars
```json
{
    "FFlagFailsafeHumanoid_3": "True"
}
```
### Automatically unmutes your mic on join (VC)
```json
{
    "FFlagDebugDefaultChannelStartMuted": "False"
}
```
### Overlay that shows what you type 
```json
{
    "FFlagDebugTextBoxServiceShowOverlay": "True"
}
```
### Ammount of lines to show at once for above
```json
{
    "DFIntTextBoxServiceHistorySize": "1"
}
```
### opt-out Experience Language
###### Removes the Experience Language option in settings
```json
{
    "FIntV1MenuLanguageSelectionFeaturePerMillageRollout": "0"
}
```
### Disable New Chat Translation Settings
```json
{
    "FFlagChatTranslationSettingEnabled3 ": "False"
}
```
### Lets you change the zoom out limit
###### Only applies to games that has not changed the default zoom limit
```json
{
    "FIntCameraMaxZoomDistance": "9999"
}
```
### Limits number of animations being played
```json
{
    "DFIntMaxActiveAnimationTracks": "0"
}
```
### Prevents Remote Events from running
```json
{
    "DFIntRemoteEventSingleInvocationSizeLimit": "1"
}
```
### Mess with voice chat volume
###### default 1000
```json
{
    "DFIntVoiceChatVolumeThousandths": "100000"
}
```
### Removes the head roll limit for face tracking
```json
{
    "DFIntAvatarFaceChatHeadRollLimitDegrees": "360"
}
```
### VR Controller transparency
```json
{
    "FIntVRTouchControllerTransparency": "0"
}
```
### No sounds
```json
{
    "FFlagDebugRomarkMockingAudioDevices": "True"
}
```
### Exclusive Fullscreen
```json
{
    "FFlagHandleAltEnterFullscreenManually": "False"
}
```
### logs stuff in dev console
```json
{
    "FStringDebugLuaLogLevel": "debug",
    "FStringDebugLuaLogPattern": "ExpChat/mountClientApp"
}
```
### Octree Validation
```json
{
    "FFlagDebugEnableOctreeValidation": "True"
}
```
### Limit Videos Playing
```json
{
    "DFIntVideoMaxNumberOfVideosPlaying": "0"
}
```
### Disable DSA Reporting In-game
###### @kezcn
```json
{
    "FFlagDSAIllegalContentReporting2": "False"
}
```
### Self Explanatory 1
```json
{
    "DFFlagDebugPrintDataPingBreakDown": "True"
}
```
### Self Explanatory 2
```json
{
    "DFFlagDebugAudioLogging": "True"
}
```
### Duplicate of Above
```json
{
    "DFFlagDebugAudioLogging2": "True"
}
```
### Self Explanatory 3
```json
{
    "FFlagTrackerLodControllerDebugUI": "True"
}
```
### Self Explanatory 4
###### Disable Drag Detectors
```json
{
    "FFlagDragDetectors1": "False"
}
```
### Self Explanatory 5
###### Disabe CTM Climbing
```json
{
    "FFlagUserClickToMoveSupportAgentCanClimb2": "False"
}
```
### Self Explanatory 6
###### Disabe Feedback Button in ESC
```json
{
    "FFlagDisableFeedbackSoothsayerCheck": "False"
}
```

<h1 align="center">Community Presets</h1>

### Improve Animation Speed, Visual Fidelity, and Ping
##### @DrPlaguenstein
```json
{
    "FFlagSimEnableDCD10": "True",
    "FFlagDebugGraphicsPreferD3D11FL10": "True",
    "DFIntBufferCompressionLevel": "0",
    "DFIntBufferCompressionThreshold": "100",
    "DFIntPerformanceControlFrameTimeMax": "1",
    "DFIntPerformanceControlFrameTimeMaxUtility": "-1",
    "FFlagPushFrameTimeToHarmony": "True",
    "FFlagUISUseLastFrameTimeInUpdateInputSignal": "True",
    "DFIntAnimatorThrottleMaxFramesToSkip": "1",
    "DFIntNumFramesAllowedToBeAboveError": "1",
    "DFIntVisibilityCheckRayCastLimitPerFrame": "10",
    "DFIntNetworkSchemaCompressionRatio": "100",
    "DFIntTimeBetweenSendConnectionAttemptsMS": "200"
}
```

### Extreme Latency
##### @DrPlaguenstein
```json
{
    "DFIntLargePacketQueueSizeCutoffMB": "1000",
    "DFIntMaxProcessPacketsJobScaling": "10000",
    "DFIntMaxProcessPacketsStepsAccumulated": "0",
    "DFIntMaxProcessPacketsStepsPerCyclic": "5000",
    "DFIntMegaReplicatorNetworkQualityProcessorUnit": "10"
}
```
### RCOOL
```json
{
    "FFlagHandleAltEnterFullscreenManually": "False",
    "FLogNetwork": "7",
    "DFIntTaskSchedulerTargetFps": "9999",
    "FFlagFixGraphicsQuality": "True",
    "FFlagDebugDisableTelemetryEphemeralCounter": "True",
    "FFlagDebugDisableTelemetryEphemeralStat": "True",
    "FIntRenderLocalLightFadeInMs": "0",
    "FFlagDebugDisableTelemetryEventIngest": "True",
    "FFlagDebugDisableTelemetryPoint": "True",
    "FFlagDebugDisableTelemetryV2Counter": "True",
    "FFlagDebugDisableTelemetryV2Event": "True",
    "FFlagDebugDisableTelemetryV2Stat": "True",
    "FStringPartTexturePackTable2022": "{\u0022glass\u0022:{\u0022ids\u0022:[\u0022rbxassetid://9873284556\u0022,\u0022rbxassetid://9438453972\u0022],\u0022color\u0022:[254,254,254,7]}}",
    "FStringPartTexturePackTablePre2022": "{\u0022glass\u0022:{\u0022ids\u0022:[\u0022rbxassetid://7547304948\u0022,\u0022rbxassetid://7546645118\u0022],\u0022color\u0022:[254,254,254,7]}}",
    "FStringTerrainMaterialTable2022": "",
    "FStringTerrainMaterialTablePre2022": "",
    "FFlagGlobalWindActivated": "False",
    "FFlagEnableBetaFacialAnimation2": "False",
    "FFlagFacialAnimationSupport1": "False",
    "DFIntAnimationLodFacsDistanceMin": "0",
    "DFIntAnimationLodFacsDistanceMax": "0",
    "DFIntAnimationLodFacsVisibilityDenominator": "0",
    "DFFlagEnableDynamicHeadByDefault": "False",
    "FIntRobloxGuiBlurIntensity": "0",
    "FFlagDebugRenderingSetDeterministic": "True",
    "DFIntCSGLevelOfDetailSwitchingDistance": "0",
    "DFIntCSGLevelOfDetailSwitchingDistanceL12": "0",
    "DFIntCSGLevelOfDetailSwitchingDistanceL23": "0",
    "DFIntCSGLevelOfDetailSwitchingDistanceL34": "0",
    "FIntRenderLocalLightUpdatesMax": "1",
    "FIntRenderLocalLightUpdatesMin": "1",
    "FFlagAdServiceEnabled": "False",
    "FFlagFastGPULightCulling3": "True",
    "FFlagNewLightAttenuation": "True",
    "FFlagGlobalWindRendering": "False",
    "FIntRenderShadowIntensity": "0",
    "FIntRenderShadowmapBias": "1",
    "FIntDebugForceMSAASamples": "-1",
    "FIntFRMMinGrassDistance": "0",
    "FFlagLuaAppUseUIBloxColorPalettes1": "True",
    "FFlagEnableCommandAutocomplete": "True",
    "FFlagUIBloxUseNewThemeColorPalettes": "True",
    "FIntFRMMaxGrassDistance": "0",
    "FFlagSoundsUsePhysicalVelocity": "True",
    "FIntRenderGrassDetailStrands": "0",
    "FFlagChromeBetaFeature": "False",
    "FFlagEnableInGameMenuChromeABTest2": "False",
    "FFlagEnableReportAbuseMenuRoactABTest2": "False",
    "FFlagEnableChromePinnedChat": "False",
    "FFlagEnableInGameMenuChrome": "False",
    "FFlagEnableInGameMenuChromeABTest": "False",
    "FFlagEnableInGameMenuChromeSignalAPI": "False",
    "FFlagPlayerListChromePushdown": "False",
    "FStringEnableChromePinnedChatForcedUserIds": "1",
    "FStringGameMenuChromeForcedUserIds": "1",
    "FFlagVoiceBetaBadge": "False",
    "FFlagTopBarUseNewBadge": "False",
    "FFlagEnableBetaBadgeLearnMore": "False",
    "FFlagBetaBadgeLearnMoreLinkFormview": "False",
    "FFlagControlBetaBadgeWithGuac": "False",
    "FStringVoiceBetaBadgeLearnMoreLink": "null",
    "FIntRenderGrassHeightScaler": "0",
    "DFFlagDebugRenderForceTechnologyVoxel": "True",
    "DFFlagDisableDPIScale": "True",
    "DFIntTextureCompositorActiveJobs": "0",
    "FFlagCoreGuiTypeSelfViewPresent": "False",
    "DFIntDebugFRMQualityLevelOverride": "1",
    "FFlagDisableNewIGMinDUA": "True",
    "FFlagPreloadAllFonts": "True",
    "FFlagCommitToGraphicsQualityFix": "True",
    "FFlagDebugSkyGray": "True",
    "DFIntMaxFrameBufferSize": "4",
    "FFlagRenderGpuTextureCompressor": "True",
    "FFlagGpuGeometryManager7": "True",
    "DFFlagPredictedOOM": "False",
    "DFIntPredictedOOMPercent": "0",
    "FFlagDisablePostFx": "True",
    "FFlagEnableQuickGameLaunch": "True",
    "DFFlagDebugPauseVoxelizer": "True",
    "FIntTerrainArraySliceSize": "4",
    "DFFlagTextureQualityOverrideEnabled": "True",
    "DFIntTextureQualityOverride": "1",
    "FFlagEnableAudioOutputDevice": "False"
}
```
### Network CPU RSS Tweaks
##### @DrPlaguenstein
```json
{
    "DFIntPhysicsReceiveNumParallelTasks": "20",
    "DFIntPhysicsAnalyticsHighFrequencyIntervalSec": "20",
    "FFlagSimAdaptiveMinorOptimizations": "True",
    "FIntSimWorldTaskQueueParallelTasks": "20",
    "FIntSmoothClusterTaskQueueMaxParallelTasks": "20",
    "DFIntReplicationDataCacheNumParallelTasks": "20",
    "DFIntMegaReplicatorNumParallelTasks": "20"
}
```

<h1 align="center">Links</h1>

### [Make Your Own Custom Roblox Textures](https://github.com/GoingCrazyDude/roblox-custom-textures/blob/main/README.md) *[Github Repo Link]*
### [Bloxstrap](https://github.com/pizzaboxer/bloxstrap) *[Github Repo Link]*
### [NVIDIA Shaders Guide](https://github.com/catb0x/Roblox-Shaders-Guide) *[Github Repo Link]*
### [EnableAnselForRoblox](https://github.com/DED0026/EnableAnselForRoblox) *[Github Repo Link]*
### [RCOOL](https://github.com/jamesgarry1/RCOOL) *[Github Repo Link]*
### [Bindable Lag Switch](https://github.com/Hermivore8151/Bindable-LagSwitch) *[Github Repo Link]*
### [MEGA FLAG LIST](https://discord.com/channels/1099468797410283540/1139962301991104582/1170417533355036712) *[Bloxstrap Server]*

<h4 align="center">‧⁺̣˚̣̣*̣̩⋆̩·̩̩୨˚̣̣̣̣͙୧·̩̩⋆̩*̣̩˚̣̣⁺̣‧ You've reached the bottom of the list! ‧⁺̣˚̣̣*̣̩⋆̩·̩̩୨˚̣̣̣̣͙୧·̩̩⋆̩*̣̩˚̣̣⁺̣‧୨</h4>

# List Information
* *Creation Date: 9:46 PM 08/25/2023*

<h3 align="center">
  <a href="https://open.spotify.com/track/2aJnyNu4PQxQ2lyj5boiMG">
    <img src="https://i.scdn.co/image/ab67616d0000b2730c471c36970b9406233842a5" width="128" alt="Listen on Spotify">
  </a>
</h3>

<h3 align="center">I Hate U - SZA</h3>

<h1 align="center">
  <a href="https://open.spotify.com/track/2aJnyNu4PQxQ2lyj5boiMG">
    <img src="https://upload.wikimedia.org/wikipedia/commons/2/26/Spotify_logo_with_text.svg" width="100">
  </a>
</h1>

<h4 align="center"><a href="https://discord.com/invite/EJQASQuPJn">Roblox Glitching Community</a>, <a href="https://discord.gg/nKjV3mGq6R">Bloxstrap</a>, People</h4>

<h4 align="center">"buddy u giv no credit!!!" 🤓 cry bout it boohoo</h3>

<h4 align="center">COLLECTIVISTS 2024®<sup>eal</sup></h4>

<p align="center"><a href="https://raw.githubusercontent.com/MaximumADHD/Roblox-Client-Tracker/roblox/FVariables.txt">FVariables.txt</a></p>

<p align="center"><a href="https://github.com/MaximumADHD/Roblox-FFlag-Tracker">Roblox FFlag Tracker</a></p>
