# GripAndReleaseSwing
Demonstrates how to use gripper devices in a template program node

Grip and Release Swing demonstrates how to use gripper devices in a template program node.
In the program node contribution, the user can select a gripper among the registered grippers available in PolyScope. When a gripper has been selected, the selected gripper can be applied to the template node. This will insert two Gripper program nodes for the selected gripper: one node configured for a grip action and one node configured for a release action.

This example demonstrates how to:
* Get the list of grippers available in PolyScope
* Insert a Gripper program node for a specific gripper device in the program tree
* Configure a Gripper program node for grip and release actions

Note: To have grippers to select from in the program node, some of the gripper driver URCap samples (e.g. Simple Gripper) can be installed.

Information:
* Available from:
  * URCap API version 1.9.0.
  * PolyScope version 3.12.0/5.6.0.
* Main API interfaces: GripperManager, GripperProgramNodeFactory, GripperNode, GripConfigBuilder, ReleaseConfigBuilder, GripperDevice.
