
# Reducing Fatal Accidents with AI

Final project for the Building AI course

## Summary

A small smart device installed in the car that helps drivers avoid fatal accidents. It analyzes the road up to 200 meters ahead, predicts the movement of nearby risks, and tells the driver what to do in time.

## Background

Every day, a huge number of people die because of road accidents.
Many accidents happen because the driver cannot see the danger in time, especially at night, in fog, or in rain. Sometimes the driver is tired or distracted and reacts too late.

My personal motivation is to help many people and drivers and reduce these fatal accidents.
Because a few extra seconds to react can save a life.

Problems this project solves:
* Drivers cannot see pedestrians, animals, or cars in darkness
* Drivers react too late to sudden dangers
* Drivers don't know what other cars around them are doing

## How is it used?

The device is installed in the car and works automatically while driving. It is useful in all situations, especially at night, in fog, in rain, and on fast roads.

The users are all car drivers.

How it works:
1. Radar scans the road up to 200 meters ahead and detects cars, motorcycles, people and animals, even in darkness.
2. Thermal Camera detects people and animals by their heat, even at night.
3. Small Radio shares information between cars, like location and speed. This is not the car radio, it is only for sharing information.
4. The AI collects information from the 3 devices, analyzes it together, and predicts the movement of all nearby risks.
5. The AI gives the final result to the driver: Slow down, Speed up, or Keep the same speed.

When danger is detected, the driver is warned in two ways at the same time:
* Sound alert
* Red light on the dashboard

## Data sources and AI methods

The data comes from 3 sources in real-time inside the device:
* Radar: sends waves and receives them back to measure distance and speed of objects
* Thermal Camera: detects heat of people and animals
* Radio: receives location and speed from other cars

The AI method is sensor fusion + prediction:
The AI combines all the data together, predicts where each object will move next, calculates the probability of a collision, and decides the best advice for the driver.

No personal data is collected. Only road and driving information is used.

## Challenges

What this project does NOT solve:
* It does not drive the car automatically, it only warns and advises the driver
* It cannot prevent all accidents, if the driver ignores the warning
* It needs other cars to also have the device to share information by radio

Limitations and ethical considerations:
* The system must be very fast and accurate, a false alarm can distract the driver
* The system must work in bad weather and at night
* Privacy: the radio must only share location and speed for safety, not personal information

## What next?

How this project could grow:
* Test it in real night, fog and rain conditions
* Improve the prediction of movement
* Connect with the car system for automatic braking if the driver does not react
* Make the device small and cheap so every car can have it

To move on, I would need help with hardware, real car testing, and improving the AI model.

## Acknowledgments

* Idea inspired by the need to reduce fatal road accidents and help drivers
* Building AI course by Reaktor Innovations and University of Helsinki