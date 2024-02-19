Forked from https://github.com/autowarefoundation/autoware_individual_params
# autoware_individual_params

This repository stores parameters that change depending on each vehicle.

## Usage:
### example1 (do not set vehicle_id)
$ ros2 launch autoware_launch autoware.launch.xml sensor_model:=<YOUR-VEHICLE-NAME>_sensor_kit vehicle_model:=<YOUR-VEHICLE-NAME>_vehicle
### example2 (set vehicle_id as VEHICLE_1)
$ ros2 launch autoware_launch autoware.launch.xml sensor_model:=<YOUR-VEHICLE-NAME>_sensor_kit vehicle_model:=<YOUR-VEHICLE-NAME>_vehicle vehicle_id:=GOSLING_2
### example3 (set vehicle_id as VEHICLE_2)
$ ros2 launch autoware_launch autoware.launch.xml sensor_model:=<YOUR-VEHICLE-NAME>_sensor_kit vehicle_model:=<YOUR-VEHICLE-NAME>_vehicle vehicle_id:=VEHICLE_2