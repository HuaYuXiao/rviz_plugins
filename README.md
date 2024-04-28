# rviz_plugins

```xml
<library path="lib/librviz_plugins">
  <class name="rviz_plugins/Goal3DTool"
         type="rviz::Goal3DTool"
         base_class_type="rviz::Tool">
    <description>
      Tool for setting 3D goal
    </description>
  </class>

  <class name="rviz_plugins/ProbMapDisplay"
         type="rviz::ProbMapDisplay"
         base_class_type="rviz::Display">
    <description>
      Display of -inf +inf probabilistic occupancy grid map
    </description>
  </class>

  <class name="rviz_plugins/GameLikeInput"
         type="GameLikeInput"
         base_class_type="rviz::Tool">
    <description>
      game usage
    </description>
  </class>

  <class name="rviz_plugins/AerialMapDisplay"
         type="rviz::AerialMapDisplay"
         base_class_type="rviz::Display">
    <description>
      Display of aerial map
    </description>
  </class>

  <class name="rviz_plugins/MultiProbMapDisplay"
         type="rviz::MultiProbMapDisplay"
         base_class_type="rviz::Display">
    <description>
      Display of multiple -inf +inf probabilistic occupancy grid map
    </description>
  </class>

</library>
```

## How to Use

```bash
catkin_make install --source src/rviz_plugins --build build/rviz_plugins
```

