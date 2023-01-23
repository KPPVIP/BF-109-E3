BF-109 E-3
----------


Features:
Detailed model
MGs are working
Breakable wings
Detailed cockpit
Bullet impacts and shattering glass
Proper LOD models



Credits:
Original model:
Wings of Prey
War Thunder


Model and textures ripped by:
Sabro


Textures, model reworking, converting:
SkylineGTRFreak




If you want to reduce the file size, you can: 

A) delete all of them except one or two or how many you want to have left. (Simply use OpenIV) 

B)extract the textures and resize them to 1024x1024 and reimport them 

It will cut the file size in half or less, but it looks too good with the 2048x2048p textures, so I have left them in there. 





Installation:

Delete the original stunt+hi.ytd file from the archive and replace the remaining 3 stunt files.

The model files get into:
x64e.rpf (main GTA V folder)

And the handling.meta gets into:
Update/update.rpf/common/data


Also note: If you're going to make a video of this mod, please link my channel as well (https://www.youtube.com/user/SkylineGTRR34Freak). I know that some of you guys make a pretty buck off this and since I'm giving you these mods for free, a little support would be welcomed.


If you already have a custom handling.meta, then replace the Stunt entry with the following (you will need Notepad++):


<Item type="CHandlingData">
      <handlingName>stunt</handlingName>
      <fMass value="2000.000000" />
      <fInitialDragCoeff value="8.000000" />
      <fPercentSubmerged value="75.000000" />
      <vecCentreOfMassOffset x="0.000000" y="-0.400000" z="0.000000" />
      <vecInertiaMultiplier x="1.000000" y="1.000000" z="1.000000" />
      <fDriveBiasFront value="1.000000" />
      <nInitialDriveGears value="1" />
      <fInitialDriveForce value="0.001000" />
      <fDriveInertia value="1.000000" />
      <fClutchChangeRateScaleUpShift value="1.300000" />
      <fClutchChangeRateScaleDownShift value="1.300000" />
      <fInitialDriveMaxFlatVel value="284.400000" />
      <fBrakeForce value="0.050000" />
      <fBrakeBiasFront value="0.600000" />
      <fHandBrakeForce value="0.700000" />
      <fSteeringLock value="55.000000" />
      <fTractionCurveMax value="1.150000" />
      <fTractionCurveMin value="0.800000" />
      <fTractionCurveLateral value="22.000000" />
      <fTractionSpringDeltaMax value="0.150000" />
      <fLowSpeedTractionLossMult value="0.000000" />
      <fCamberStiffnesss value="0.000000" />
      <fTractionBiasFront value="0.500000" />
      <fTractionLossMult value="1.000000" />
      <fSuspensionForce value="4.500000" />
      <fSuspensionCompDamp value="4.800000" />
      <fSuspensionReboundDamp value="4.800000" />
      <fSuspensionUpperLimit value="0.065000" />
      <fSuspensionLowerLimit value="-0.080000" />
      <fSuspensionRaise value="0.005000" />
      <fSuspensionBiasFront value="0.330000" />
      <fAntiRollBarForce value="0.000000" />
      <fAntiRollBarBiasFront value="0.000000" />
      <fRollCentreHeightFront value="0.800000" />
      <fRollCentreHeightRear value="0.800000" />
      <fCollisionDamageMult value="1.500000" />
      <fWeaponDamageMult value="0.500000" />
      <fDeformationDamageMult value="4.000000" />
      <fEngineDamageMult value="1.500000" />
      <fPetrolTankVolume value="65.000000" />
      <fOilVolume value="5.000000" />
      <fSeatOffsetDistX value="0.000000" />
      <fSeatOffsetDistY value="-0.300000" />
      <fSeatOffsetDistZ value="0.300000" />
      <nMonetaryValue value="45000" />
      <strModelFlags>1000000</strModelFlags>
      <strHandlingFlags>400120</strHandlingFlags>
      <strDamageFlags>20</strDamageFlags>
      <AIHandling>AVERAGE</AIHandling>
      <SubHandlingData>
        <Item type="CFlyingHandlingData">
          <fThrust value="1.000000" />
          <fThrustFallOff value="0.000160" />
          <fThrustVectoring value="0.000000" />
          <fYawMult value="-0.001000" />
          <fYawStabilise value="0.002000" />
          <fSideSlipMult value="0.050000" />
          <fRollMult value="0.008000" />
          <fRollStabilise value="-0.000000" />
          <fPitchMult value="0.002000" />
          <fPitchStabilise value="0.001400" />
          <fFormLiftMult value="0.000250" />
          <fAttackLiftMult value="0.011000" />
          <fAttackDiveMult value="0.011000" />
          <fGearDownDragV value="0.000000" />
          <fGearDownLiftMult value="1.000000" />
          <fWindMult value="0.150000" />
          <fMoveRes value="0.015000" />
          <vecTurnRes x="0.100000" y="0.700000" z="0.500000" />
          <vecSpeedRes x="0.030000" y="0.050000" z="0.050000" />
          <fGearDoorFrontOpen value="90.000000" />
          <fGearDoorRearOpen value="90.000000" />
          <fGearDoorRearOpen2 value="90.000000" />
          <fGearDoorRearMOpen value="90.000000" />
          <fTurublenceMagnitudeMax value="10.000000" />
          <fTurublenceForceMulti value="0.000200" />
          <fTurublenceRollTorqueMulti value="0.030000" />
          <fTurublencePitchTorqueMulti value="0.003500" />
          <fBodyDamageControlEffectMult value="0.100000" />
          <fInputSensitivityForDifficulty value="1.200000" />
          <fOnGroundYawBoostSpeedPeak value="3.000000" />
          <fOnGroundYawBoostSpeedCap value="6.000000" />
          <fEngineOffGlideMulti value="1.000000" />
          <handlingType>HANDLING_TYPE_FLYING</handlingType>
        </Item>
        <Item type="CVehicleWeaponHandlingData">
          <uWeaponHash>
            <Item>VEHICLE_WEAPON_PLAYER_BUZZARD</Item>
            <Item>VEHICLE_WEAPON_SPACE_ROCKET</Item>
            <Item />
          </uWeaponHash>
          <WeaponSeats content="int_array">
            0 
            0 
            0 
          </WeaponSeats>
          <fTurretSpeed content="float_array">
            0.000000	
            0.000000	
          </fTurretSpeed>
          <fTurretPitchMin content="float_array">
            0.000000	
            0.000000	
          </fTurretPitchMin>
          <fTurretPitchMax content="float_array">
            0.000000	
            0.000000	
          </fTurretPitchMax>
          <fTurretCamPitchMin content="float_array">
            0.000000	
            0.000000	
          </fTurretCamPitchMin>
          <fTurretCamPitchMax content="float_array">
            0.000000	
            0.000000	
          </fTurretCamPitchMax>
          <fBulletVelocityForGravity content="float_array">
            0.000000	
            0.000000	
          </fBulletVelocityForGravity>
          <fTurretPitchForwardMin content="float_array">
            0.000000	
            0.000000	
          </fTurretPitchForwardMin>
          <fUvAnimationMult value="0.000000" />
          <fMiscGadgetVar value="0.000000" />
          <fWheelImpactOffset value="0.000000" />
        </Item>
        <Item type="NULL" />
      </SubHandlingData>
    </Item>


I would advise using a Mods folder (More info at OpenIV)

And make a backup, I take no responsibility if any shit happens.

No editing without prior permission granted please.