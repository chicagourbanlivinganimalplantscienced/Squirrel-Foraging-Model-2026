# Squirrel-Foraging-Model-2026
Mathematical model of squirrel risk-assessment near Pace 303 Bus Stop using Python and Doppler Effect analysis.

Project: Squirrel Behavioral Math (Feb 2026)This project models squirrel foraging distances ($x$) relative to traffic noise at the Pace 303 Bus Stop.

Key Features:Metabolic Calibration: Adjusting for Chicago winter temperatures (9°F to 26°F).

Doppler Integration: Modeling the "Fear Shift" as buses approach vs. depart.

Sensors used: Phyphox (Doppler/Frequency) and Decibel X (Amplitude).
Parameter,Symbol,Value,Units / Description
Hunger Level,f,11.5,Constant (Baseline metabolic state)
Foraging Reward,h,6.8,Seed density in grams
Metabolic Cost,p,10.0,Environmental stress at 9°F
Salt Bonus,c,-4.6,Sodium-driven incentive
Baseline Distance,x,32.0m,Measured distance from the road
Bravery Score,R,0.268,Calculated intersection threshold
