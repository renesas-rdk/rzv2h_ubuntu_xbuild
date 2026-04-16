# rzv2h_ubuntu_xbuild

## Overview

RZ/V2H Ubuntu XBuild is a Docker-based cross-build environment for ROS 2 applications targeting the RZ/V2H platform. It is designed to simplify the workflow for building, deploying, and debugging software from an Ubuntu host system.

This project is intended for developers who need a practical and reproducible environment for RZ/V2H application development, especially for robotics and edge AI use cases.

## Quick Start

To get started with RZ/V2H Ubuntu XBuild:

- Run the setup script on an Ubuntu 24.04 x86_64 host machine to create the Docker-based cross-compilation environment.

  ```bash
  wget https://github.com/renesas-rdk/ros2_demo_workspace/raw/refs/heads/main/common_utils/setup_rdk_docker.sh
  chmod +x setup_rdk_docker.sh
  ./setup_rdk_docker.sh
  ```

- Follow the instructions provided by the script to build the Docker image and set up the workspace.

After setup is complete, you can use the environment to cross-build and develop applications for the RZ/V2H target.

## Documentation

For full setup and development instructions, see the [Application Development Guide](https://renesas-rdk.github.io/rzv2h_rdk_documentation/latest/chapter-4/development_guide/development_guide.html).

## Troubleshooting

For common cross-compilation issues, see the [Cross-compilation FAQ](https://renesas-rdk.github.io/rzv2h_rdk_documentation/latest/chapter-4/development_guide/cross_build_faq.html).

## Limitations

For known limitations, see [Non-Relocatable Sysroot CMake Paths](https://renesas-rdk.github.io/rzv2h_rdk_documentation/latest/chapter-4/development_guide/cross_build_know_issue.html).

## Change Log

See [CHANGELOG](./CHANGELOG).