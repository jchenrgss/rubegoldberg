## Introduction
The purpose of this project is to construct a visual representation of a real-life process, using a golf ball and various other built components to test and demonstrate energy and momentum-related concepts in physics. The particular model that I have chosen to construct is a representation of the merge sort algorithm, an efficient general-purpose comparison-based sorting algorithm used widely in the field of computer science.

Mergesort is a divide and conquer (top-down recursive) algorithm that runs in logarithmic time and linear space, and works by dividing an unsorted list of n elements into n sublists, each containing one element. The sublists are then merged repeatedly to produce new sorted sublists until there is only one sublist remaining (i.e. the original list, sorted). With a little extension, this process can be redefined in terms of energy and momentum, and represented using a rollercoaster-like machine.

## Description of the Model
![alt text](https://i.imgur.com/9RHOhLh.jpg "The completed machine")
The overall completed machine.

### Building process
![alt text](https://i.imgur.com/bdvRLF8.jpg "Stage 0.1")

![alt text](https://i.imgur.com/EwQ1fFJ.jpg "Stage 0.2")

![alt text](https://i.imgur.com/peWFtN6.jpg "Stage 0.3")

![alt text](https://i.imgur.com/1qIikBz.jpg "Stage 0.4")

![alt text](https://i.imgur.com/92BADc3.jpg "Stage 0.5")

![alt text](https://i.imgur.com/szsejch.jpg "Stage 0.6")

Planning took approximately an hour, and actual construction took an entire day.

### Stage 1: Start to the vertical loop
The golf ball is simply released from the top of the first ramp, and the machine begins to operate. This represents the beginning of execution, and the first division of the original array. No comparisons need to be made at this point, which is why the golf ball moves quickly. The loop and perfectly inelastic collision represent calculations determining where to split the array.

![alt text](https://i.imgur.com/zFKh3wk.jpg "Stage 1.1")
The initial ramp.

![alt text](https://i.imgur.com/6k1nynV.jpg "Stage 1.2")
The vertical loop and perfectly inelastic collision.

### Stage 2: The first pulley
The original array is split into another subarray and another golf ball is launched to represent another function call. The algorithm moves one level deeper via recursion. When the first golf ball lands in the carriage box, its weights causes the box to drop, extending the string. The string, connected to a pulley above the second golf ball, is attached to the gate preventing the next ball from rolling down the second ramp, so when the pulley is triggered by the first ball, the second is able to begin rolling.

![alt text](https://i.imgur.com/EZ2zb3n.jpg "Stage 2.1")
The pulley system.

![alt text](https://i.imgur.com/Xh6Yzz4.jpg "Stage 2.2")
The second ramp.

### Stage 3: To the horizontal loop
This part is the same as the first stage, but is executed on the other half of the original array. The horizontal loop represents calculations determining where to split the array. At this point, the track turns 180 degrees, simply because there was not enough room to continue building forward.

![alt text](https://i.imgur.com/Jrzl5NG.jpg "Stage 3")
The horizontal loop.

### Stage 4: To the second pulley
The golf ball moves slowly through this flat section, representing the increased time it takes to further divide subarrays into more subarrays before they can be merged and thus sorted. After exiting the horizontal loop, the golf ball has very little speed, and also undergoes a partially elastic collision with another golf ball, again representing calculations determining where to split the array.

![alt text](https://i.imgur.com/TTtP2J3.jpg "Stage 4")
The fourth golf ball on the long straightway and the partially inelastic collision.

### Stage 5: To the lever
This section is twice as long, lengthwise, as the first split sections, representing the first two merged subarrays, with the hill and relatively flat track representing the few comparisons between elements while sorting the array. When the previous golf ball reaches the end of the straightway, it lands in another carriage box, pulling the attached string down, tilting the platform of the next golf ball and causing it to drop onto the next ramp.

![alt text](https://i.imgur.com/lK2MW3x.jpg "Stage 5.1")
The second carriage box at the end of the long straightway.

![alt text](https://i.imgur.com/saxQuyD.jpg "Stage 5.2")
The launcher for the fifth golf ball.

![alt text](https://i.imgur.com/MhaqCxK.jpg "Stage 5.3")
The first hill (difficult to see because of the angle).

![alt text](https://i.imgur.com/bxk4KQy.jpg "Stage 5.4")
A long ramp on a slight downward angle leading to the start of the next stage.

### Stage 6: To the launch
At this point, the other subarrays are merging together, performing comparisons (ball going uphill and more time required), and merging (going downhill; faster). The ball goes down more than up, representing increases in speed and the array becoming nearly sorted. When the fifth ball reaches the end of the long ramp, it hits the bottom half of a lever, causing it to swing about its pivot and hit the sixth golf ball positioned above it.

![alt text](https://i.imgur.com/g7ZZY4e.jpg "Stage 6.1")
The lever system to trigger the final golf ball.

![alt text](https://i.imgur.com/F4E3Z9s.jpg "Stage 6.2")
The second hill and following turn.

![alt text](https://i.imgur.com/zJU8HUq.jpg "Stage 6.3")
The third hill.

![alt text](https://i.imgur.com/VvxlMnd.jpg "Stage 6.4")
The final bend, leading downward to the launch ramp.

### Stage 7: To the end
The ball undergoes projectile motion representing the returning of the sorted array, followed by hitting a spring at the end of the track to represent the algorithm exiting with a successful exit code, indicating that the operation was ultimately successful. The ball launches across a 30-cm long gap at an angle of 45 degrees, and then hits the spring at the end, bouncing back slightly until it comes to a rest.

![alt text](https://i.imgur.com/lmVKOkZ.jpg "Stage 7.1")
The launch and landing ramps for projectile motion.

![alt text](https://i.imgur.com/fPwWloz.jpg "Stage 7.2")
The spring mounted at the end of the track.

## Hypotheses
Energy conservation and efficiency: due to friction, the machine will not conserve mechanical energy. Instead, it will all be converted into useless forms of energy such as thermal energy and sound energy for the ball to come to a complete stop at the end of the track. As such, whatever the energy input is, the energy output will always be zero and so the efficiency of the machine will be 0%.

Regarding the actual process of merge sort, no "energy" is required per se, but it can be interpreted as storage space. Addresses in a machine's physical memory can be manipulated and elements can be swapped, but there will always be the same number of total addresses regardless of the number of not necessarily distinct or contiguous subarrays. Regarding efficiency, the algorithm runs in logarithmic time, meaning that the runtime of the algorithm is logarithmic depending on the number of elements within the original array. This has nothing to do with physics and energy conservation, but it is interesting how one definition can be applied in multiple different ways, depending on the topic.

Conservation of momentum (collisions): despite colliding into many objects throughout the run of the machine, momentum was always conserved, though mechanical energy was not. For example, during the perfectly inelastic collision, the first golf ball travelled at a very high speed but then slowed down somewhat when it hit the stationary second ball. The system did not lose momentum; the total mass was suddenly increased and so velocity decreased as a result. Additionally, some kinetic energy was lost due to friction, but this did not affect the momentum.

In the partially elastic collison, the first ball travelled at a moderate speed toward the stationary target ball, and when it hit, most of the speed was 'transferred' to the second ball. The second ball started to move at a moderately slow speed forward, while the original ball was slowed down. If the velocities were added up however, a velocity equal to the velocity of the original ball before the collision would be achieved.

## Theoretical Background
### Forms of energy in the machine:
Gravitational potential energy: the golf balls start out at certain heights (for example, 1m), which provides an energy source that can be converted into kinetic energy to allow the balls to traverse the length of the track.

Kinetic energy: as the balls roll down ramps and hills, they increase in speed so that they are able to overcome obstacles such as loops and hills. This energy is converted from gravitational potential energy.

Thermal energy: as the balls travel along the track, some energy is lost as heat, slowing the ball down and increasing the time it takes for the machine to complete.

Sound energy: similar to thermal energy, some of the balls' mechanical (kinetic) energy is converted into sound energy when it rolls on the track and encounters collisions with other objects, which slows the ball down and increases the time it takes for the machine to complete.

Elastic potential energy: the spring at the end of the track provides a source of elastic energy; when the ball hits it, the spring compresses and then extends again, pushing the ball back in the opposite direction.

### Energy transfers
Gravitational potential energy -> kinetic energy: the golf ball starts out at certain heights (e.g. 1m), and then roll down ramps or hills, losing gravitational potential energy (height), as it converts to kinetic energy (speed). The speed allows the ball to complete the track and overcome obstacles along the way such as loops and hills.

Kinetic energy -> thermal energy: as the golf ball travels along the track, friction between the ball's surface and the track surface produce thermal energy via the transfer of heat. This slows the ball down, increasing the time it takes for the machine to complete.

Kinetic energy -> sound energy: similar to the loss of mechanical energy due to friction, when balls collide with other objects, sounds are produced (energy is converted from mechanical energy), which increases the time it takes for the machine to complete.

Kinetic energy -> elastic potential energy and vice versa: when the golf ball hits the spring, it compresses it and kinetic energy is converted to elastic potential energy (the ball loses speed but travels further into the spring). This is followed by the release of the elastic energy (like gravitational potential energy), extending and converting the stored energy into kinetic energy, increasing the speed of the ball.

### Conservation of Energy
This model was built and tested in real-life, with real-life conditions (such as friction!). As an open system, it is impossible that mechanical energy will be conserved perfectly. Kinetic energy will be converted into thermal and sound energy, and the machine will eventually finish, concluding with every ball motionless and stationary. If, somehow, the model was run in a closed system, where mechanical energy would be perfectly conserved, then the balls would continue rolling forever until acted on by an external force.

## Results
### Difficulties/Inconsistencies in completion
The machine is generally fairly consistent in operation and operates with few difficulties. For example, no golf balls usually fall off the track while in operation, the ball never stops at one portion of the track, and always clears the jump (projectile motion). However, one inconsistency lies in the trigger systems for the fifth and sixth golf balls. Since carboard is fairly sensisitive to vibrations, when the first ball is released from the starting point, the vibrations generated from travelling through the vertical loop often cause the other two balls to trigger early, decreasing the time the machine requires to run by a factor of three.

### Malfunctions over time
The machine is built with cardboard instead of wood to maintain an extremely low budget, and as such, is very prone to degradation and damage over time. Constant usage will produce vibrations, and as cardboard does not absorb vibrations very well, various supporting structures may come loose through excessive operation, leading to changes in track placement and causing a ball to fall off of a track. Additionally, cardboard warps significantly, and is often not very stable, so small changes may occur, changing the way the ball moves. To combat this, I added extra cardboard to hold other pieces of cardboard together, and used a lot of tape.

### Sources of error
1. During testing, the floor upon where the machine was placed may not have been entirely flat. For example, there are occasionally locations in classrooms where the floor is slightly warped, causing desks to wobble even if they are stable placed elsewhere in the classroom. The created gradient would cause all track pieces to change angle slightly, leading to possible malfunctions. For example, the trigger to the fifth golf ball was placed so that it would be unlikely for the ball to start rolling on its own (the platform was tilted back at a slight angle). If the floor underneath the machine was tilted slightly forward, then the angle of the platform would be reduced, and so this may explain why the ball triggered earlier than expected.

To prevent such an error from occuring, the machine should have been placed on a surface such as a lab bench, where it is more likely to be flat, and a ball should be placed on it to ensure that it does not roll in one direction or another, ensuring greater accuracy in testing and preventing malfunctionings from occuring.

2. The analysis for the perfectly inelastic collision may be partially wrong, because it is difficult to establish such a scenario. In most cases tested, the collision that occurred between two golf balls was partially elastic. To prevent such a collision from occuring, the second, stationary ball was placed close to the end of a stage so that when the first ball hit it, they would both fall off the track together, or at least appear to. In reality, instead of a perfectly inelastic collision taking place due to external factors and an inaccurate collision, it is possible that the collision that occurred was not actually perfectly inelastic, but was partially elastic due to the short timeframe for which the collision occured and results from previous trials.
