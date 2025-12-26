# vehicular-technology
Traffic Light State Recognition + Rule-Based Planning
Project Update: Traffic Light State Recognition + Rule-Based Planning
1️⃣ Project Topic:
Traffic Light State Recognition + Rule-Based Planning for Autonomous Vehicles / Intelligent Driving Systems.
2️⃣ Dataset Selected:
LISA Traffic Light Dataset (via Kaggle)
3️⃣ Why LISA Dataset is Suitable:
Contains ~43,000 frames with annotated traffic lights.
Labels include RED / YELLOW / GREEN, matching our project requirements.
Annotations include bounding boxes, so we can detect and classify lights.
Images include day and night scenarios, making recognition more robust.
Realistic road scenarios from a moving vehicle, suitable for rule-based vehicle decision simulations.
4️⃣ Next Steps:
Preprocess dataset: crop traffic lights using bounding boxes.
Train a CNN classifier (RED / YELLOW / GREEN).
Evaluate model accuracy and confusion matrix.
Implement rule-based decision logic:
RED → STOP
GREEN → GO
YELLOW → Stop or continue based on safe distance
Test on sample images or video sequences for real-time decision-making.
5️⃣ Expected Outcome:
Accurately recognize traffic light state (target ~90%+ accuracy).
Make safe vehicle decisions based on traffic light detection.
