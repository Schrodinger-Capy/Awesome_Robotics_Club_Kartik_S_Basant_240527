TASK 4:

PART B:

I have four different approaches to detect the ball position on the 2D
platform, in case we don\'t use computer vison. They are discussed as
follows:

1\) Piezoelectric Material sensors: We can make the platform in such a
way that it consists of many small chips made up of piezoelectric
material like(Lead Zirconate Titanate, Polyvinylidene Fluoride or
Quartz). Piezoelectric materials have a property that they generate a
voltage when mechanical stress (like pressure, impact, or vibration) is
applied to them. This property can be used in this project. We can use
hundreds of very tiny piezoelectric chips spread out on the surface like
a grid. By noticing, where a voltage change is measured, we can code a
program which tells us the coordinates of the current ball position,
which then can be used in the inverse kinematics formulas to calculate
by how much degree the platform needs to be tilted. Pros of using
piezoelectric materials include good sensitivity and immediate detection
of abrupt voltage changes which means low latency. But on the other hand
there are a few challenges as well, first the wiring and coding part
will be a little more complex as there will be a hundreds of tiny
piezo-sensors which would need to be monitored for reading change to
detect the position accurately, secondly if need be replacing the
sensors would be a big challenge, the cost part can be handled by using
cheaper piezo materials but it will come at a cost of lower sensitivity.
But we can strike a balance between all the challenges and use more
dense collection of the piezo for more accurate coordinate tracking.

2\) Ultraviolet Rays sensors/tracking : We can cover the circumference
of the platform with multiple UV sensors covering 360 degree angle. And
we would paint the ball with a UV-sensitive/fluorescent paint which
would be easily reflected and then identified and detected by the
sensors. It has many benefits like, it provides really accurate and
rapid coordinate tracking along with being cost effective. But it could
also face challenges as natural light coming from sun also constitutes
UV light which could hinder the sensors in accurately measuring the
ball\'s position, also prolonged UV exposure is harmful for humans.

3\) Force Sensitive Resistance sensors/tracking: Like the piezo-material
sensors, we can cover the whole platform with hundreds of the tiny FSRs.
This is also the technique used in dance tap games which detect which
cell the person has placed his foot on. When a force is applied on one
of the cell, its resistance changes which can be recorded by the circuit
using voltage change measurement and thus using the coordinates of the
grid, the position of the ball can be tracked. Pros include being
cost-effective, durable and having a simple setup. But it also has its
challenges as it does not really provide a really accurate tracking
mechanism, and the resistance values may differ depending upon the
temperature and calibration errors.

4\) Magnetic Ball(Hall Effect based) tracking: We will use a ball made
up of permanent magnets for this technique. The platform would be made
up of tiny hall sensors which detect a change in magnetic field produced
by the ball, this data then can be processed to extract the coordinates
of the ball. Benefits if using hall sensors include efficient and fast
tracking and low cost maintenance along with little power supply need
for the hall sensors. But it has a serious drawback i.e. it can\'t be
used near a powerful electronic device or a magnet as there magnetic
field may hinder with the readings. Another major challenge is that the
magnetic field of the ball may hinder with the electronics of the robo
and may hinder the data transfer process. But it can be overcome by
using shielding or software filtering.
