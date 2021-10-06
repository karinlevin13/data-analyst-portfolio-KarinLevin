## Description of the data:
Each log entry is a user action or an event.
- *EventName* — event name
- *DeviceIDHash* — unique user identifier
- *EventTimestamp* — event time.
- *ExpId* — experiment number: 246 and 247 are the control groups, 248 is the test group.
The visits table (server logs with data on website visits):
- *Uid* — user's unique identifier
- *Device* — user's device
- *Start Ts* — session start date and time
- *End Ts* — session end date and time
- *Source Id* — identifier of the ad source the user came from
All dates in this table are in YYYY-MM-DD format.
The orders table (data on orders):
- *Uid* — unique identifier of the user making an order
- *Buy Ts* — order date and time
- *Revenue* — Yandex.Afisha's revenue from the order
The costs table (data on marketing expenses):
- *source_id* — ad source identifier
- *dt* — date
- *costs* — expenses on this ad source on this day


## Goal:

Find out :
- How people use the product
- When they start to buy
- How much money each customer brings
- When they pay off





## Libraries used:

pandas
matplotlib.pyplot
seaborn
plotly
scipy
math
datetime
re
numpy

## [Project](project_3_KarinLevin.ipynb)



