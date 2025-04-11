# Path-planning-autonomous-vehicles
Supervised learning-based path planning system for autonomous vehicles using Random Forest
# 🚗 Path Planning in Autonomous Vehicles using Supervised Learning

This project demonstrates a supervised learning approach for path planning in autonomous vehicles. Inspired by traditional algorithms like RRT* and Artificial Potential Fields (APF), this implementation uses a machine learning model to predict vehicle movement decisions (e.g., LEFT, RIGHT, FORWARD, STOP) based on environmental features.

---

## 🎯 Objective

To develop a machine learning model using the Random Forest Classifier that accurately predicts the vehicle's next move based on current state and surroundings like obstacle proximity, lane position, velocity, road type, etc.


📊 Dataset Details

A synthetic dataset was generated with 10,000 records including:

x, y: Current coordinates of the vehicle

goal_x, goal_y: Target destination

obstacle_distance & obstacle_angle: Data about nearby obstacles

road_curvature, road_type, lane_position, velocity, step_size

decision_label: Target class label (FORWARD, LEFT, RIGHT, STOP)

🧠 ML Model

Algorithm: Random Forest Classifier

Accuracy: ~97.5%

Feature importance used to optimize performance

Final model saved as .pkl for deployment

💡 Future Enhancements

Integrate real-world sensor data (LIDAR, radar)

Extend to RNN/LSTM for sequence-based prediction

Add reinforcement learning for adaptive path control

Real-time integration with vehicle simulation environments
