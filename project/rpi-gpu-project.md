# High-performance multi-stream camera system for Raspberry Pi

This project is aimed at developing a high-performance multi-stream camera system for the Raspberry Pi, with a focus on low-level software development and GPU optimization for camera hardware. The goal is to build a replacement driver for the RaspiMjpeg library using the open-source V4L2 driver, enabling multiple camera streams and improved functionality.

## Description
This is a challenging project for students interested in low-level software development and GPU optimisation for camera hardware.

The RaspiMjpeg library currently has four elements that make it useful.  From a single camera stream, it can:
1.	Provides the resized mjpeg stream to feed the main preview
2.	full resolution video recording to h264 /mp4.
3.	allows for still image capture
4.	provides h264 motion vectors for use in the motion detection

There currently exists a library that can talk with the cameras called ‘libcamera’, however, it will only provide a single stream through the software stack (see resources).  This will be your starting point for looking at how the open source V4L2 driver operates.

The end goal is to create a much better camera app for the Raspberry Pi to replace the “RPi Web Cam Interface” which has 1.5k stars and 490 forks on GitHub.

You will be provided camera and computer hardware for testing purposes when required.

## Scope
- Develop a V4L2-based driver to replace the RaspiMjpeg library.
- Ensure the new driver supports the following functionalities:
  1. Provide resized MJPEG streams for main preview.
  2. Enable full-resolution video recording in H.264/MP4 format.
  3. Allow for high-quality still image capture.
  4. Provide H.264 motion vectors for motion detection.
- Integrate the new driver with the existing RPi Web Cam Interface project, potentially rewriting it in another language if necessary.
- Ensure compatibility with all models of the Raspberry Pi and camera modules.
- Feed the final work upstream to benefit the broader Raspberry Pi community.

## Resources
- [RPi_Cam_Web_Interface GitHub](https://github.com/silvanmelchior/RPi_Cam_Web_Interface)
- [RaspiMjpeg Library](https://github.com/roberttidey/userland/tree/master/host_applications/linux/apps/raspicam)
- [Libcamera Documentation](https://www.raspberrypi.com/documentation/computers/camera_software.html#libcamera-still)
- [V4L2 Documentation](https://www.kernel.org/doc/html/latest/userspace-api/media/v4l/v4l2.html)

## Timeline

**Week 1-2:**
- **Milestone 1: Project Planning and Initial Research**
- Define project objectives and detailed requirements.
- Research the existing RaspiMjpeg library, V4L2 driver, and libcamera library.
- Set up the development environment with the necessary hardware (Raspberry Pi and cameras).
- GitHub repository setup

**Week 3-4:**
- **Milestone 2: Understanding and Experimenting with V4L2**
- Study the V4L2 driver documentation and existing implementations.
- Experiment with V4L2 to understand its capabilities and limitations.
- Identify key components needed to support multiple camera streams.
- GitHub workflows established (both automated and team review process).
- Check-In Presentation #1

**Week 5-6:**
- **Milestone 3: Development of the New V4L2-Based Driver**
- Begin developing the new driver based on the V4L2 framework.
- Implement functionality to provide resized MJPEG streams.
- Ensure the driver can interface with the Raspberry Pi's camera hardware.

**Week 7-8:**
- **Milestone 4: Adding Full-Resolution Video Recording**
- Extend the driver to support full-resolution H.264/MP4 video recording.
- Optimize the driver for GPU acceleration to handle high-resolution video streams efficiently.

**Week 9-10:**
- **Milestone 5: Implementing Still Image Capture and Motion Detection**
- Add functionality for high-quality still image capture.
- Integrate H.264 motion vectors to support motion detection capabilities.
- Test and refine these features to ensure reliability and performance.

**Week 11:**
- **Milestone 6: Integration with RPi Web Cam Interface**
- Integrate the new driver with your new web system (comparable to RPi Web Cam)
- Ensure seamless functionality and user experience.

**Week 12:**
- **Milestone 7: Testing and Optimization**
- Conduct comprehensive testing across different Raspberry Pi models and camera modules.
- Optimize the driver for performance and stability.
- Gather feedback and make necessary adjustments.

**Week 13:**
- **Milestone 8: Final Presentation and Submission**
- Prepare a comprehensive presentation summarizing the project, methodologies, findings, and conclusions.
- Submit the final report, source code, and documentation.
- Ensure the project is ready for upstream contribution to the Raspberry Pi community.

## Expected Deliverables
- V4L2-Based Camera Driver: A high-performance driver supporting multiple camera streams and enhanced functionalities.
- Integrated RPi Web Cam Interface: A fully integrated and potentially rewritten interface to support the new driver.
- Documentation: Detailed guides on installation, configuration, and usage of the new driver.
- Source Code: Open-source codebase for community use and contribution.
- Performance Metrics: Metrics and benchmarks demonstrating the performance improvements and capabilities of the new driver.
- Presentation: A final presentation summarizing the project, methodologies, findings, and conclusions.
