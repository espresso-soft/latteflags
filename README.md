<h1 align="center">Primal Solver Flags</h1>

### This list is missing
* **Drunk Walk**
* **Air Spin**
#### Reasons: I FORGOT THE VALUES

### Freeze
```json
{
    "FFlagDebugSimDefaultPrimalSolver": "True",
    "DFIntDebugSimPrimalLineSearch": "0"
}
```
### Noclip 3
###### I found this btw
```json
{
    "FFlagDebugSimDefaultPrimalSolver": "True",
    "DFIntDebugSimPrimalStiffness": "0"
}
```
### Low Gravity 1
###### 'FFlagDebugSimDefaultPrimalSolver' : True, # Enable the new simulation engine or whatever it is
###### 'DFIntDebugSimPrimalLineSearch' : 1, # A poor man's gravity/flight [Default 100] (above 0 is low gravity | below 1 to -1 is will make gameplay weird when it comes to physics | below -1 is a poor mans fly (not really useable) 
###### credit [@Amity](https://www.youtube.com/watch?v=5M411LL17B0)
```json
{
    "FFlagDebugSimDefaultPrimalSolver": "True",
    "DFIntDebugSimPrimalLineSearch": "3"
}
```
### Void Unanchored Parts
```json
{
    "FFlagDebugSimDefaultPrimalSolver": "True",
    "DFIntDebugSimPrimalLineSearch": "222"
}
```
###  Buggy Low Gravity 2
```json
{
  "DFIntDebugSimPrimalPreconditioner": "100",
  "DFIntDebugSimPrimalPreconditionerMinExp": "100",
  "DFIntDebugSimPrimalNewtonIts": "1",
  "FFlagDebugSimDefaultPrimalSolver": "True",
  "DFIntDebugSimPrimalWarmstartVelocity": "-150",
  "DFIntDebugSimPrimalWarmstartForce": "-775",
  "DFIntDebugSimPrimalToleranceInv": "1"
}
```
### Backwards SpeedHax
#### Bugginess and Speed depends on the value of `DFIntDebugSimPrimalWarmstartForce` values i recommend are `775` and the value i put.
##### Also for `DFIntDebugSimPrimalWarmstartVelocity` probably use value `150` but its kinda hard to do it and control
###### I may have not found this first but i found this by myself btw
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
### Don't Touch The Wall!
```json
{
    "DFIntDebugSimPrimalNewtonIts": "-2147483647",
    "DFIntDebugSimPrimalToleranceInv": "-2147483647",
    "FFlagDebugSimDefaultPrimalSolver": "True"
}
```
### Vehicle Speed 1
```json
{
    "DFIntDebugSimPrimalWarmstartForce": "40",
    "DFIntDebugSimPrimalWarmstartVelocity": "102",
    "FFlagDebugSimDefaultPrimalSolver": "True",
    "DFIntDebugSimPrimalLineSearch": "41"
}
```
### Vehicle Speed 2
###### prob the same mess w the values maybe youll get something different
```json
{
    "DFIntDebugSimPrimalLineSearch": "50",
    "DFIntDebugSimPrimalWarmstartVelocity": "103",
    "DFIntDebugSimPrimalStiffness": "300",
    "DFIntBulletContactBreakOrthogonalThresholdPercent": "10000"
}
```
### Primal Solver Flags
###### Make an PR/Issue if you find anything!
```
[C++] DFFlagDebugSimPrimalDivideByMass
[C++] DFFlagDebugSimPrimalFeedback
[C++] DFFlagDebugSimPrimalImplicitSprings
[C++] DFFlagDebugSimPrimalLaggedFriction
[C++] DFIntDebugSimPrimalLineSearch
[C++] DFIntDebugSimPrimalNewtonIts
[C++] DFIntDebugSimPrimalPositionLinearIts
[C++] DFIntDebugSimPrimalPositionNewtonToleranceInvAng
[C++] DFIntDebugSimPrimalPositionNewtonToleranceInvLin
[C++] DFIntDebugSimPrimalPreconditioner
[C++] DFIntDebugSimPrimalPreconditionerMinExp
[C++] DFIntDebugSimPrimalStiffness
[C++] DFIntDebugSimPrimalStiffnessAngular
[C++] DFIntDebugSimPrimalStiffnessMax
[C++] DFIntDebugSimPrimalStiffnessMaxAngular
[C++] DFIntDebugSimPrimalStiffnessMin
[C++] DFIntDebugSimPrimalStiffnessMinAngular
[C++] DFIntDebugSimPrimalToleranceInv
[C++] DFIntDebugSimPrimalVelocityLinearIts
[C++] DFIntDebugSimPrimalVelocityNewtonToleranceInvAng
[C++] DFIntDebugSimPrimalVelocityNewtonToleranceInvLin
[C++] DFIntDebugSimPrimalWarmstartForce
[C++] DFIntDebugSimPrimalWarmstartLambda
[C++] DFIntDebugSimPrimalWarmstartVelocity
[C++] FFlagDebugSimDefaultPrimalSolver
[C++] FFlagDebugSimPrimalAugmented
[C++] FFlagDebugSimPrimalBallOnAxisGS
[C++] FFlagDebugSimPrimalBoxFriction
[C++] FFlagDebugSimPrimalCRConvergenceHistory
[C++] FFlagDebugSimPrimalDisableGS
[C++] FFlagDebugSimPrimalGSLump
[C++] FFlagDebugSimPrimalHybridStiffness
[C++] FFlagDebugSimPrimalInitializeImpulses
[C++] FFlagDebugSimPrimalLinearSolveStatsOutput
[C++] FFlagDebugSimPrimalUseDualStiffness
[C++] FFlagSimPrimalSolver
[C++] FIntDebugSimPrimalGSLumpAlpha
[C++] FIntDebugSimPrimalMaxLambda
[C++] FIntDebugSimPrimalMotorStiffnessBoost
[C++] FIntDebugSimPrimalNonlinearPrint
[C++] FIntDebugSimPrimalStabilization
[C++] FIntDebugSimPrimalStiffnessScaling
```

<h4 align="center">⁺ You've reached the bottom of the list! ⁺</h4>

<h3 align="center">
  <a href="https://playboicarti.com">
    <img src="https://github.com/user-attachments/assets/81d80677-8cc2-44c4-a739-19c59bc29b5c "256" alt="This never droppin">
  </a>
</h3>

<h3 align="center">All Red - Playboi Carti</h3>

<h1 align="center">NEVER DROPPING</h1>

<p align="center"><a href="https://raw.githubusercontent.com/MaximumADHD/Roblox-Client-Tracker/roblox/FVariables.txt">FVariables.txt</a></p>

<p align="center"><a href="https://github.com/MaximumADHD/Roblox-FFlag-Tracker">Roblox FFlag Tracker</a></p>
