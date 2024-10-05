> [!NOTE]
> If you find our repository useful don't forget to star!

<h3 align="center">
  <img src="assets/hawktuah.jpg" width="256" alt="Playboi Carti">
</h3>

<h1 align="center">#RBXFLAG$ GRAÏL$</h1>

<h4 align="center">Join our Discord Server to contribute & expand our list (We need you)</h4>
<h5 align="center">https://discord.gg/HNe7fzR9xg</h5>

<h1 align="center">Physics (Abusive)</h1>

### Random High Jumps
```json
{
    "FFlagSimAdaptiveTimesteppingDefault2": "True",
    "DFFlagSimHumanoidTimestepModelUpdate": "True"
}
```
### No Animations
> [!NOTE]
> **Stops the game from trying to replicate your animations in the server. You dont have animations in the server but you do for your client**
```json
{
    "DFIntReplicatorAnimationTrackLimitPerAnimator": "-1"
}
```
### Stick unanchored parts to you
> [!TIP]
> **- = up, + = down**
```json
{
    "DFIntSolidFloorPercentForceApplication": "-1000",
    "DFIntNonSolidFloorPercentForceApplication": "-5000"
}
```
### Max Raycast Distance
> [!NOTE]
> **Raycasting is the use of intersection tests to solve problems in Roblox. The most common use of raycasting is to determine the first object intersected by a ray. This is done by casting a virtual ray from a certain point in a direction and determining the first surface it intersected with.**

> [!TIP]
> **Break legs collision from 2 to -inf, kinda break camera on values over 3 noclip cam on 3**
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
### Invisible 2
> [!NOTE]
> **Locks your character's position on the server to (0, 0, 0), having the side effect of turning you invisible. This only affects the server and other clients, not you. server-sided things that rely on your position, like clicking to get tools, will not function. In some games these can be abusable. Here is a list of them: [Link](assets/lists/experiences/specific.md)**
```json
{
    "DFIntGameNetPVHeaderTranslationZeroCutoffExponent": "10"
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
### Noclip 3
###### @burgerboxer & @dis_spencer
```json
{
    "FFlagDebugSimDefaultPrimalSolver": "True",
    "DFIntMaximumFreefallMoveTimeInTenths": "1000",
    "DFIntDebugSimPrimalStiffness": "0"
}
```
### Freeze
```json
{
    "FFlagDebugSimDefaultPrimalSolver": "True",
    "DFIntDebugSimPrimalLineSearch": "0"
}
```
### Hip Height
> [!NOTE]
> **Very controllable bounce, only works with negative values**

> [!TIP]
> **0 allows you to hover**
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
### Network Ownership
> [!NOTE]
> better [network ownership](https://create.roblox.com/docs/physics/network-ownership) of parts

> [!CAUTION]
> **This might get you banned in some games with anticheats (Limbobbia)**
```json
{
    "DFIntMinClientSimulationRadius": "2147000000",
    "DFIntMinimalSimRadiusBuffer": "2147000000",
    "DFIntMaxClientSimulationRadius": "2147000000"
}
```
### Low Gravity 1
> [!NOTE]
> `'FFlagDebugSimDefaultPrimalSolver' : True`  
> This flag enables the new simulation engine or whatever it is.

> [!CAUTION]
> `'DFIntDebugSimPrimalLineSearch' : 1`  
> This setting is a poor man's gravity/flight. The default value is 100:
> - **Above 0:** Low gravity.
> - **Below 1 to -1:** Will make gameplay weird, especially with physics.
> - **Below -1:** Acts as a poor man's fly mode (not really usable).
###### [@Amity](https://www.youtube.com/watch?v=5M411LL17B0)
```json
{
    "FFlagDebugSimDefaultPrimalSolver": "True",
    "DFIntDebugSimPrimalLineSearch": "3"
}
```
### Low Gravity 2
> [!CAUTION]
> **This is more buggy**
```json
{
  "FFlagDebugSimDefaultPrimalSolver": "True",
  "DFIntDebugSimPrimalPreconditioner": "100",
  "DFIntDebugSimPrimalPreconditionerMinExp": "100",
  "DFIntDebugSimPrimalNewtonIts": "1",
  "FFlagDebugSimDefaultPrimalSolver": "True",
  "DFIntDebugSimPrimalWarmstartVelocity": "-150",
  "DFIntDebugSimPrimalWarmstartForce": "-775",
  "DFIntDebugSimPrimalToleranceInv": "1"
}
```
### Low Gravity 2 Control on Parts Improvement
```json
{
    "FFlagDebugSimDefaultPrimalSolver": "True",
    "DFIntDebugSimPrimalNewtonIts": "1",
    "DFIntDebugSimPrimalPreconditioner": "15",
    "DFIntDebugSimPrimalPreconditionerMinExp": "10",
    "DFIntDebugSimPrimalToleranceInv": "1",
    "DFIntDebugSimPrimalWarmstartForce": "-150",
    "DFIntDebugSimPrimalWarmstartVelocity": "100"
}
```
### Void Unanchored Parts
```json
{
    "FFlagDebugSimDefaultPrimalSolver": "True",
    "DFIntDebugSimPrimalLineSearch": "222"
}
```
### Backwards SpeedHax
> [!WARNING]
> **Bugginess and speed depend on the value of `DFIntDebugSimPrimalWarmstartForce`. Recommended values are `775` and the value I put.**

> [!TIP]
> **For `DFIntDebugSimPrimalWarmstartVelocity`, it’s recommended to use a value of `150`. However, it might be difficult to control.**

> [!NOTE]
> **I may not have found this first, but I discovered this by myself.**
```json
{
  "DFIntDebugSimPrimalNewtonIts": "1",
  "DFIntDebugSimPrimalPreconditioner": "69",
  "DFIntDebugSimPrimalPreconditionerMinExp": "69",
  "DFIntDebugSimPrimalToleranceInv": "1",
  "DFIntDebugSimPrimalWarmstartForce": "-885",
  "DFIntDebugSimPrimalWarmstartVelocity": "-350",
  "FFlagDebugSimDefaultPrimalSolver": "True"
}
```
### Vehicle Speed 2
> [!TIP]
> **Adjust `DFIntDebugSimPrimalWarmstartVelocity` or `DFIntBulletContactBreakOrthogonalThresholdPercent` and find the best values for you**
```json
{
    "DFIntDebugSimPrimalLineSearch": "50",
    "DFIntDebugSimPrimalWarmstartVelocity": "103",
    "DFIntDebugSimPrimalStiffness": "300",
    "DFIntBulletContactBreakOrthogonalThresholdPercent": "10000"
}
```
### real god mode fr
###### fake @pyhlou
> [!TIP]
> Disconnect your internet before joining a game and turn it on again
```json
{
    "DFIntGameNetOptimizeParallelPhysicsSendAssemblyBatch": "0"
}
```

<h1 align="center">Abusive Visuals</h1>

### Buggy ZPlane Camera
```json
{
    "FIntCameraFarZPlane": "1"
}
```
### Xray
```json
{
    "DFIntCullFactorPixelThresholdMainViewHighQuality": "10000",
    "DFIntCullFactorPixelThresholdMainViewLowQuality": "10000",
    "DFIntCullFactorPixelThresholdShadowMapHighQuality": "10000",
    "DFIntCullFactorPixelThresholdShadowMapLowQuality": "10000"
}
```

<h4 align="center">⁺ You've reached the bottom of the list! ⁺</h4>

<div align="center">
<table>
  <tr>
    <th>Label</th>
    <th>Type</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>Flag</td>
    <td>bool</td>
    <td>A boolean variable that can be either true or false.</td>
  </tr>
  <tr>
    <td>Int</td>
    <td>int</td>
    <td>An integer variable used to store whole numbers.</td>
  </tr>
  <tr>
    <td>String</td>
    <td>string</td>
    <td>A variable used to store a sequence of characters.</td>
  </tr>
</table>

<table>
  <tr>
    <th>Prefix</th>
    <th>Label</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>F</td>
    <td>Fast</td>
    <td>A regular fastvariable that is initialized once<br/>and does not change until a new session begins.</td>
  </tr>
  <tr>
    <td>DF</td>
    <td>Dynamic Fast</td>
    <td>A fastvariable that can change at run-time, and<br/>automatically updates every 5 minutes.</td>
  </tr>
</table>
<div align="center">
  
  [![License](https://img.shields.io/github/license/pizzaboxer/bloxstrap)](https://github.com/espresso-soft/rbxflags/blob/main/LICENSE)
  [![Version](https://img.shields.io/github/v/release/espresso-soft/rbxflags?color=7a39fb)](https://github.com/espresso-soft/rbxflags/releases/latest)
  [![Discord](https://img.shields.io/discord/1241247795470536725?logo=discord&logoColor=white&label=discord&color=4d3dff)](https://discord.gg/HNe7fzR9xg)

</div>
<h4 align="center">© 2024 Espresso Softworks All Rights Reserved.</h4>
