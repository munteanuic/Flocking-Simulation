# Flocking Simulation

## Author
Ioana Munteanu

## Demo
[Click here!](https://www.youtube.com/watch?v=h5s_Ff2kHNM)

## Installation
1. Download [Processing](https://processing.org/download/).
2. Clone the repository.
3. Open it in Processing and press 'Run'.

## Description
 - I designed a [boids](https://en.wikipedia.org/wiki/Boids) simulation that represents a school of fish in the ocean. Each fish was designed as a green triangle over a yellow triangle with an ellipse for the eye. The simulation will start with 25 fish and will generate 3 more fish per frame until it reaches 50. 
 - The user can turn on an off:
    -  alignment (steer towards the average heading of local flockmates)
    -  cohesion (steer to move towards the average position (center of mass) of local flockmates)
    -  separation (steer to avoid crowding local flockmates)
 
## User interaction
 - mouse left click: add more fish (up to 100)
 - S: separation feature on
 - s: separation feature off
 - C: cohesion feature on
 - c: cohesion feature off
 - A: alignment feature on
 - a: alignment feature off
 - F: 10 of the fish will follow the mouse and will disappear when then reach it (follow feature)
 - f: follow feature off
 - d: double the speed of the fish up to a maximum speed
 - h: reduce the speed of the fish by 2

## Programming language
- Processing 

## Libraries 
 - peasy: PeasyCam provides a dead-simple mouse-driven camera for Processing.

