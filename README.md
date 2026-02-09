# team-12-parking-lot-entry-and-exit-control

Rahul Bhattacharjee
Adam Zaitoun
Aberrahmene Naceri
Harkirat Maan
Marko Disic
Hussein Nassar





A municipality is revising the access control and staffing policies of a public parking lot. The municipality wants
you to develop an object-oriented software simulator to evaluate whether proposed policies reduce congestion at
entry and exit points.
The parking lot has a fixed number of parking spaces, two entry gates, and two exit gates. Not all gates are always
staffed.
Vehicles arrive intending to enter the parking lot and depart after a specified parking duration.
The time taken for a vehicle to enter or exit depends on:
• whether the driver has a prepaid permit or requires a ticket,
• the method of payment (cash, debit card, or permit validation),
• the number of vehicles currently waiting,
• a small random factor.
Assume that:
1. ticket issuance takes 25 seconds,
2. cash payment takes 90 seconds,
3. debit card payment takes 45 seconds,
4. permit validation takes 15 seconds.
Vehicles arriving when the lot is full may wait for a space to become available or leave immediately.
The municipality wants to be able to run the same pattern of vehicle arrivals under different gate staffing configu-
rations. Therefore, three separate programs are required:
• Vehicle arrival generator: Creates a file listing vehicles in order of arrival time, intended parking duration,
and payment method.
• Gate staffing configuration generator: Specifies when entry and exit gates are staffed and unstaffed.
• Simulation program: Reads both files and simulates vehicle flow through the parking lot.
At a minimum, the simulation should measure:
• average wait time at entry and exit gates,
• gate utilization and idle time,
• number of vehicles turned away,
• parking space utilization over time.
Here are some questions you might want to think about:
1. How does a vehicle choose which gate to enter or exit?
2. What happens if a gate closes while vehicles are queued?
3. Should permit holders be prioritized?
4. How long does it take to reassign staff between gates?
5. How does parking duration configuration affect congestion?
