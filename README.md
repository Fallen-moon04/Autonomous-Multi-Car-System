This report presents the development and implementation of an autonomous multi-car system
using Quanser QCar platforms. The project integrates computer vision-based object detection
using YOLOv8 in Python with traditional control algorithms implemented in Simulink. The
system demonstrates a leader-follower configuration where one vehicle autonomously follows
another using real-time camera feeds and deep learning-based detection. Key contributions
include a robust data augmentation pipeline for YOLOv8 training, multi-camera fusion for 360°
target detection, and seamless integration between Python-based vision processing and
Simulink-based control systems. Performance evaluation shows detection accuracy exceeding
90% with stable following behavior at speeds up to 0.3 m/s. The modular architecture enables
independent development and testing of various autonomous driving components while
maintaining system-level coordination.The system employs a dual-platform approach where computer vision tasks are handled in
Python using modern deep learning frameworks, while traditional control algorithms are
implemented in Simulink. This hybrid approach leverages the strengths of both environments:
Python's rich ecosystem for machine learning and Simulink's real-time control capabilities
