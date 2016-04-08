# ROS-Project
Repository for Robotics Project Module on ROS platform and TurtleBot 2

Implementing a set of computer vision and autonomous navigation algorithms using **TutleBot 2** with **ROS Hydro**. LiDAR is used for mapping and AMCL approach to localize the robot in a map. Microsoft Kinect is used for capturing visual and depth information. 

The following tasks were implemented:

- Rao-Blackwellized particle filter based SLAM using [gmapping](http://wiki.ros.org/gmapping) and [rplidar](http://wiki.ros.org/rplidar)
- Face detection based on Viola-Jones algorithm using OpenCV
- Face Recognition based on Eigenface method using [ROS face recognition](https://github.com/procrob/face_recognition)
- Initial pose estimation using visual landmarks
- AR-Tag detection and localization
- All tasks were realized alongside using [SMACH framework](http://wiki.ros.org/smach) for concurrency

## Demo

Video demos can be found on Youtube:

-  [Demo1](https://youtu.be/3VN96tyYq-k)
-  [Demo2](https://youtu.be/chfMmpUmcWE)

## License

Licensed under the [MIT license](http://www.opensource.org/licenses/MIT)
