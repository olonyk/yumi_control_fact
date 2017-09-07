# yumi_control_fact


This package contains a set of scripts for controlling YuMi via MoveIt! Python interface

For running them, bringup YuMi! (simulated or in real life), run the demo_online launch file from yumi_moveit_config, and execute the following command in a terminal:

```
rosrun yumi_control_fact yumi_control.py [host_ip] [host_port]
```
where [host_ip] [host_port] are optional arguments specifying the ip address and the port of the server node respectively. The default values of these parameters are 'localhost' and '5000'.


## Credits

Yoshua Nava (yoshua.nava.chocron@gmail.com), Guðmundur F. Hallgrímsson (gudhal@kth.se) and Junxun Luo (junxun@kth.se) heavily contributed to the development of the Python scripts presented, as part of their work at KTH-RPL.

