# Explain-the-model
Using the Shap Library

## Problem
Modern economies depend on the reliable and affordable delivery of electricity. Yet many places in the world are still affected by power outages.

One significant cause of power outages is overloading. Overloading occurs when too much power is drawn from an electric circuit at once. This can be avoided if we know when excess electricity is going to be used. Heating and cooling appliances consume the most power in a household.

In this challenge, we try to predict the electricity usage of heating and cooling appliances in a household based on internal and external temperatures and other weather conditions. Each observation measures electricity in a 10-minute interval. The temperatures and humidity have been averaged for 10-minute intervals.

Use the observations in the train dataset to train your model and predict the energy used in the test dataset.

## Dataset Description

Variable name	Description
Observation	-Observation ID
T1 -Temperature in kitchen area in Celsius
RH_1	-Humidity in kitchen area in %
T2	-Temperature in living room area in Celsius
RH_2	-Humidity in living room area in %
T3	-Temperature in laundry room area in Celsius
RH_3	-Humidity in laundry room area in %
T4	-Temperature in office room in Celsius
RH_4	-Humidity in office room in %
T5	-Temperature in bathroom in Celsius
RH_5	-Humidity in bathroom in %
T6	-Temperature outside the building (north side) in Celsius
RH_6	-Humidity outside the building (north side) in %
T7	-Temperature in ironing room in Celsius
RH_7	-Humidity in ironing room in %
T8	-Temperature in teenager room 2 in Celsius
RH_8	-Humidity in teenager room 2 in %
T9	-Temperature in parents room in Celsius
RH_9	-Humidity in parents room in %
To	-Temperature outside in Celsius
Pressure	-Outside pressure in mm Hg
RH_out	-Humidity outside in %
Wind speed	-Speed of wind outside in m/s
Visibility	-Visibility from outside measuring station in km
Tdewpoint	-Dew point temperature in Â°C
Energy	-Energy used by appliances in Wh
