# kalman-to_fpga-2025
7th sem project

Kalman Filter-Based Motion Artifact Reduction on FPGA
This project aims to reduce motion artifact noise in sensor-based systems by evaluating different adaptive filtering algorithms and implementing the best solution on an FPGA.
After testing multiple adaptive filters in MATLAB — including LMS, NLMS, and variants — the Kalman Filter was selected for its superior performance in maintaining signal quality while removing noise.

Highlights
1.MATLAB-based evaluation of multiple adaptive algorithms
2.Performance comparison using real/simulated motion artifact data
3.Kalman Filter chosen for FPGA implementation due to accuracy & stability
4.Hardware design optimized for real-time processing with minimal resource usage
5.Supports fixed-point arithmetic for FPGA efficiency

Applications
1.Wearable health devices (ECG, PPG, EEG)
2.Navigation and motion tracking
3.Robotics and control systems
4.Any system affected by motion-induced noise
