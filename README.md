# Introduction

ROSWELD is a planning, monitoring and control software suite on an industrial quality level, for heavy industrial robot applications. The ROSWELD framework is built upon the synergy of available ROS components, being upgraded to the industrial quality level; with the new, high-tech modules for heavy robot applications developed within ROSWELD. Additionally, the graphical multi-platform user interface FlexGui 4.0 with the Technology Readiness Level (TRL) 9 (official Horizon 2020 TRL scale), is already a standard ROS tool to create easy-to-use interfaces to ROS-based robot and software applications. 

A part of ROSWELD will be programming and planning software on TRL6 and will be adapted and exported to general ROS components. In addition, ROSWELD will use the following ROS components:
- algorithms for path planning
- roscore for basic messaging
- rosbridge for platform-independent communication
- rosbag for logging and debugging
- MoveIt! for robot-independent movement planning
- FlexGui 4.0

Additionally, ROSWELD will provide interfaces to robots and standard CAM systems, to ensure the portability between different platforms, and thus, preparing the ROSWELD technology to be applied in various industrial environments. To ensure an optimal use of the ROSWELD framework, , knowledge of the following components and areas is required:
- ROS and MoveIt!
- FlexGui 4.0
- Basic knowledge related to NACHI, Hyundai, or OTC industrial robots including:
	- Robot system configuration and setup
	- Robot operation
	- Programming and multi-threading
	- File operation and remote access
- Basic knowledge of the welding processes and related equipment

## Packages

The complete ROSWELD project built up from the following repositories:
- [rosweld_tools](https://github.com/PPM-Robotics-AS/rosweld_tools): backend software.
- [rosweld_tools_examples](https://github.com/PPM-Robotics-AS/rosweld_tools_examples): an example project for demonstration, including UI, lab setup and virtual environment.
- [rosweld_drivers](https://github.com/PPM-Robotics-AS/rosweld_drivers): NACHI, OTC and Hyundai robot drivers, uEpsilon and iLAN MEL scanner drivers, IP Camera driver with authentication, OTC WPS driver.
- [rosweld_robot](https://github.com/PPM-Robotics-AS/rosweld_robot): NACHI, OTC and Hyundai robot programs.
- [FlexGui 4.0](https://github.com/PPM-Robotics-AS/flexgui4.0): User interface for the project.
- [ppm_lab](https://github.com/PPM-Robotics-AS/ppm_lab): urdf model of the virtual environment.
- [ppm_lab_control](https://github.com/PPM-Robotics-AS/ppm_lab_control): MoveIt! Control package for the ppm_lab virtual environment.

## Documentation

For user and installation manuals, please visit [rosweld_documentation](https://github.com/PPM-Robotics-AS/rosweld_documentation) repository.
- ROSWELD code documentation [html](https://github.com/PPM-Robotics-AS/rosweld_documentation) format
- ROSWELD user documentation and installation manual [pdf](https://github.com/PPM-Robotics-AS/rosweld_documentation/pdf/ROSweld Documentation.pdf)
- FlexGui 4.0 user manual [pdf](https://github.com/PPM-Robotics-AS/rosweld_documentation/pdf/FlexGui User Documentation.pdf)

## License

Licensed under the [Apache License, Version 2.0 (the "License")](http://www.apache.org/licenses/LICENSE-2.0);
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
