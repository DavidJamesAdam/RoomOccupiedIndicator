# RoomOccupiedIndicator
Problem: We have a reading nook in our place that we use. We never know if someone is in there and there have been times when we've been looking for someone for 5-10 minuites.

Solution: create an indicator that turns on when someone is occupying the room.

How: Since there's only one light source in the nook, and it's off if no one is in the room, creating a light dependant LED would show if someone is or is not in the nook.

Some notes: 
- The pico can also be powered via a micro USB power supply without battery. Just depending on where the breadboard is located. Schematic includes battery version, if powered via USB, just remove the battery leads from the breadboard.
- Breadboard/photo resistor has to be very close to lightsource in order for LED to light up fully.

![Nook_light_sensor_schem](https://github.com/DavidJamesAdam/RoomOccupiedIndicator/assets/51091241/96ad7c69-fdde-4c35-a7a7-07a9b9143733)
