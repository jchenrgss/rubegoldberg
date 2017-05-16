## Introduction
The purpose of this project is to construct a visual representation of a real-life process, using a golf ball and various other built components to test and demonstrate energy and momentum-related concepts in physics. The particular model that I have chosen to construct is a representation of the merge sort algorithm, an efficient general-purpose comparison-based sorting algorithm used widely in the field of computer science.

Mergesort is a divide and conquer (top-down recursive) algorithm that runs in logarithmic time and linear space, and works by dividing an unsorted list of n elements into n sublists, each containing one element. The sublists are then merged repeatedly to produce new sorted sublists until there is only one sublist remaining (i.e. the original list, sorted). With a little extension, this process can be redefined in terms of energy and momentum, and represented using a rollercoaster-like machine.

## Description of the Model
![alt text](https://i.imgur.com/9RHOhLh.jpg "The completed machine")
The overall completed machine.

### Stage 1: Start to the vertical loop
The golf ball is simply released from the top of the first ramp, and the machine begins to operate. This represents the beginning of execution, and the first division of the original array. No comparisons need to be made at this point, which is why the golf ball moves quickly. The loop and perfectly inelastic collision represent calculations determining where to split the array.

![alt text](https://i.imgur.com/zFKh3wk.jpg "Stage 1A")
The initial ramp.

![alt text](https://i.imgur.com/6k1nynV.jpg "Stage 1B")
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


## Data


## Results
