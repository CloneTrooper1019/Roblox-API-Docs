# Members

## ActuatorType
Type of the rotational actuator: None, Motor, or Servo. 

## AngularRestitution
Restitution of the two limits, or how elastic they are. Value in [0,1].

## AngularSpeed
Target angular speed. This value is unsigned as the servo will always move toward its target. Value in [0, inf).

## AngularVelocity
The target angular velocity of the motor in radians per second around the rotation axis. Value in [0, inf).

## CurrentAngle
Signed angle between the SecondaryAxis of Attchement0 and the SecondaryAxis of Attachment1 around the rotation axis. Value in [-180, 180].

## LimitsEnabled
Enables the angular limits on rotations around the main axis of Attachment0.

## LowerAngle
Lower limit for the angle from the SecondaryAxis of Attachment0 to the SecondaryAxis of Attachment1 around the rotation axis. Value in [-180, 180].

## MotorMaxAcceleration
The maximum angular acceleration of the motor in radians per second square. Value in [0, inf).

## MotorMaxTorque
The maximum torque the motor can apply to achieve the target angular velocity. Value in [0, inf).

## Radius
Radius of the in-game visual. Value in [0, inf).

## ServoMaxTorque
Maximum torque the servo motor can apply. Value in [0, inf).

## TargetAngle
Target angle for the SecondaryAxis of Attachment1 from the SecondaryAxis of Attachment0 around the rotation axis. Value in [-180, 180].

## UpperAngle
Upper limit for the angle from the SecondaryAxis of Attachment0 to the SecondaryAxis of Attachment1 around the rotation axis. Value in [-180, 180].