TASK 4:

PART A:

THE THOUGHT PROCESS:

It might seem at first that using unlimited number of actuators might be
of great help in the precise movements of the surface but on closer
inspection one would find out that on increasing the number of a
actuators, till one point the degree of freedom of the system would be
increasing, which will help the robot have more precise and effective
movements but after a certain point a big difficulty would arise as
perfectly coordinating large number of actuators to get the desired
angle/tilt of the platform would become a hassle and would be very
difficult and time-memory extensive, hence slowing down the response
time, thus immediately losing the crux of the robot\'s ability and
ultimately the ball would be difficult to balance. Hence I propose a
model where there wouldn\'t be too less or too much of the actuators.

Another question arises on what type of actuators to use: Rotary or
linear. But this is not much of a problem as even linear actuators at
their core are just rotary actuators with additional mechanism to
convert the rotary motion in linear motion with the help of rack and
pinion gears and belts and pulleys.

Another point to be noted is that as the movement changes of the
platform have to be very quick, sudden changes by the actuators may
result in jerk or vibration production in the platform , which may
hinder the inverse kinematic motion calculations and would lead to
miscalculation of the amount of tilt required. This challenge is
overcame by using air bladders/cushions. They are essentially kind of
lubricants or suspension systems of the robo. Air bladders can act like
an adaptive suspension system, they can inflate or deflate to adjust the
robo\'s height or posture, helping it regain balance. It would provide
smooth and flexible adjustments in the robo\'s stance, as opposed to
traditional rigid mechanisms like motors or springs. It will allow for
quick adjustments to the robo\'s height or posture. This helps maintain
the robo\'s balance even when it encounters unexpected disturbances like
external forces or uneven terrain.

There can be many options to choose for geometry of platform but we will
be using

THE DESIGN:

The platform would be circular in shape with three support arms on the
circumference at 120 degrees each, along with an actuator at the centre.
All the actuator are connected at the bottom to the base. Between
actuator and platform air bladders are attached for smoother movement.
Connected to the base, at the top would be a camera which will help
record the position of the ball using computer vision. Computer vision
uses machine learning model to identify and distinguish the ball from
its surrounding. The basic theory of the ball balancing robot is that we
need to move the ball from its current coordinate to the center of the
platform. Another reason why I chose a circular platform is that instead
of writing coordinates in x and y it can be written in polar coordinates
r and theta, which will be easier to solve. Now, using the coded inverse
kinematics equations we calculate by how much each actuator should move
to tilt the platform by just the right amount. The actuator in the
center helps in moving the platform up and down, hence adding another
degree of freedom to the platform. By increasing the DOF, additional
precise control over the ball is gained. Pros of the improvement added
include higher stability, precise control and movement in all
directions, whereas major roadblocks include high cost due to having
high quality sensors, increased complexity to code due to added
actuators, and more power required.
