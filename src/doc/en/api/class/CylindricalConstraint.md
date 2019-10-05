# Members

## AngularActuatorType
Type of angular actuator: None, Motor, or Servo. 

## AngularLimitsEnabled
Enables the angular limits around the rotation axis.

## AngularRestitution
Restitution of the two limits, or how elastic they are. Value in [0, 1]. 

## AngularSpeed
Target angular speed. This value is unsigned as the servo will always move toward its target. In radians per second. Value in [0, inf). 

## AngularVelocity
The target angular velocity of the motor in radians per second around the rotation axis. Value in [0, inf).

## CurrentAngle
Signed angle (in degrees) between the reference axis and the secondary axis of Attachment1 around the rotation axis. Value in [-180, 180]. 

## InclinationAngle
Direction of the rotation axis as an angle from the x-axis in the xy-plane of Attachment0. Value in [-180, 180]. 

## LowerAngle
Lower limit for the angle (in degrees) between the reference axis and the SecondaryAxis of Attachment1 around the rotation axis. Value in [-180, 180].

## MotorMaxAngularAcceleration
The maximum angular acceleration of the motor in radians per second squared. Value in [0, inf).

## MotorMaxTorque
The maximum torque the motor can apply to achieve the target angular velocity. The units are mass * studs^2 / second^2. Value in [0, inf).

## RotationAxisVisible
Enable the visibility of the rotation axis.

## ServoMaxTorque
Maximum torque the servo motor can apply. The units are mass * studs^2 / second^2. Value in [0, inf). 

## TargetAngle
 Target angle (in degrees) between the reference axis and the secondary axis of Attachment1 around the rotation axis. Value in [-180, 180].

## UpperAngle
Upper limit for the angle (in degrees) between the reference axis and the SecondaryAxis of Attachment1 around the rotation axis. Value in [-180, 180]. 

## WorldRotationAxis
The unit vector direction of the rotation axis in world coordinates.