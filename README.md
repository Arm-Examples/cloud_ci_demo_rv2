# DEPRECATED

Use [Arm-Examples/AVH_CI_Template](https://github.com/Arm-Examples/AVH_CI_Template) instead.

-------

# Complex cloud-based CI demo

This repository showcases how to use GitHub Actions together with a Docker image to run CI test automatically in the cloud.

Another example is available in [Arm-Examples/cloud_ci_demo_basic](https://github.com/Arm-Examples/cloud_ci_demo_basic).

## Structure

|Directory         |Description                                        |
|------------------|---------------------------------------------------|
|/rtx5_rv2         |CMSIS-RTOS2 validation example with result logging |
|.github/workflows/|GitHub Actions workflow for the example            |

## Usage

Fork the repository and push some changes to it. Instantaneously, the GitHub Actions kick in and start to run through the flow.
