# GearControl
Control of an aicraft tricycle landing gear system

## Problem Statement
The landing gear on UAS “X” consists of a nose gear, a left main gear, and a right main gear. These are individually hydraulically actuated. An electrically driven hydraulic pump supplies pressure to the hydraulic actuators. The controlling software can turn the pump on and off. A direction valve is set by the computer to either “up” or “down,” to allow the hydraulic pressure to either raise or lower the landing gear. Each leg of the gear has two limit switches: one that closes if the gear is up, and another that closes when it’s locked in the down position. To determine if the airplane is on the ground, an additional switch on the nose gear strut will close if the weight of the airplane is on the nose gear (commonly referred to as a “WoW switch”). The landing gear operation is controlled by the UAS operator in the ground control station, whose controls consist of a landing gear up/down lever and three display lights (one per leg) that can either be off, illuminated green (for down), or red (for in transit).

Design a requirements that sucessfuly meet the problem statement for safe retraction and deployment of the landing gear, and validate the controller design to these requirements
