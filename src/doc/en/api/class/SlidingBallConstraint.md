# Members

## ActuatorType
Type of linear actuator (along the axis of the slider): None, Motor, or Servo.

## CurrentPosition
Current position of Attachment1 with respect to Attachment0 along the slider axis. Value in (-inf, inf).

## LimitsEnabled
Enables the limits on the linear motion along the axis of the slider.

## LowerLimit
Lower limit for the position of Attachment1 with respect to Attachment0 along the slider axis. Value in (-inf, inf).

## MotorMaxAcceleration
The maximum acceleration of the motor in studs per second squared. Value in [0, inf).

## MotorMaxForce
The maximum force the motor can apply to achieve the target velocity. Units are mass * studs / seconds^2. Value in [0, inf).

## Restitution
Restitution of the two limits, or how elastic they are. Value in [0, 1].

## ServoMaxForce
Maximum force the servo motor can apply. Units are mass * studs / seconds^2. Value in [0, inf).

## Size
Size of the in-game visual associated with this constraint. Value in [0, inf).

## Speed
Target speed in studs per second. This value is unsigned as the servo will always move toward its target. Value in [0, inf).

## TargetPosition
Target position of Attachment1 with respect to Attachment0 along the slider axis. Value in (-inf, inf).

## UpperLimit
Upper limit for the position of Attachment1 with respect to Attachment0 along the slider axis. Value in (-inf, inf).

## Velocity
The target linear velocity of the motor in studs per second along the slider axis. Value in (-inf, inf).