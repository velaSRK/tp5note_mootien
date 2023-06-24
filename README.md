# tp5note_mootien



https://github.com/velaSRK/tp5note_mootien.git

Extraire le fichier catkin_ws.zip

Partie 1


    • En utilisant le terminal allez dans le workspace catkin : $ cd catkin_ws 
    • lancer le setup.bash: $ source devel/setup.bash
    • aller dans le fichier catkin_ws/src/mobile_manipulator_body/urdf
    • puis lancez: roslaunch urdf_tutorial display.launch model:=robot_arm.urdf
    • choisiser le parametre ‘world’ dans fixed frame

partie 2

    • allez dans le workspace catkin: cd catking_ws
    • lancer le setup.bash: $ source devel/setup.bash
    • ensuite lancez: roslaunch ri_arm_config demo.launch
partie 3

    • allez dans le workspace catkin: cd catking_ws
    • lancer le setup.bash: $ source catkin_ws/devel/setup.bash
    • roslaunch ri_arm_control direct.launch pour la cinematique directe
    • roslaunch ri_arm_control direct.launch pour la cinematique indirecte
