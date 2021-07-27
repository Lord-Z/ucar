# ucar
ucar model urdf description

## how to use
put this package into ucar_ws/src

recode base_driver.launch

just add 

<include file="$(find ucar_description)/launch/model.launch.xml" />

is fine

then when you open rviz ,you can see ucar's model
