# Vision-language-action-indoor-robot-with-semantic-navigation
About the Project
The project aims to develop an intelligent indoor robot that understands natural-language commands, plans tasks, navigates through indoor environments, detects objects, avoids obstacles, and verifies task completion.
Users can interact with the robot through a web-based dashboard and give commands such as:
- Go to the kitchen and find a water bottle.
- Navigate to the office.
- Find a chair.
- Return to home.
- Stop the robot immediately.
The system processes user commands, creates task plans, executes actions through permission-controlled tools, and displays robot activities through a real-time dashboard.

Algorithms Used
1. Natural Language Processing (NLP) – Understands and processes user commands.
2. Rule-Based Intent Detection – Identifies the intention behind user instructions.
3. Entity Extraction – Extracts destination names and object names from commands.
4. A Search Algorithm* – Finds an efficient path for robot navigation.
5. Semantic Reasoning – Understands room names, landmarks, and object relationships.
6. Task Planning – Breaks complex commands into smaller executable tasks.
7. Confidence-Based Decision Making – Uses confidence scores to support reliable decisions.
8. Object Detection Algorithm – Identifies objects using YOLO-based computer vision.
9. Path Replanning – Finds alternative routes when obstacles block the planned path.

Installation and Execution
 Prerequisites
- Python 3.11 or above
- Node.js 18 or above
- npm
- Visual Studio Code
- Git
1. Clone the Repository
2. Navigate to the Project Folder
3. Create a Virtual Environment
4. Install Backend Dependencies
5. Run the Backend Server
6. Install Frontend Dependencies
7. Run the Frontend
Open the application in your browser:
http://localhost:5173

Real-Time Object Detection
The project supports optional real-camera object detection using YOLO-based models.
The vision module supports:
- Image-based object detection.
- Webcam-based object detection.
- YOLOv8 object detection.
- YOLO-World open-vocabulary detection.
- Bounding-box visualization.
- Custom object prompts.

Note: Real-camera object detection is an optional vision workflow. Camera detections are not automatically converted into physical robot-map coordinates.

Testing
The project includes automated tests using Pytest.
Run the following command from the project root:
pytest
Testing covers:
- Command processing.
- Navigation and path planning.
- Obstacle avoidance.
- Object detection.
- Tool permissions.
- Safety management.
- Task verification.
- API functionality.

Docker Deployment
The application can also be executed using Docker Compose.
docker compose up --build
Open the dashboard:
http://localhost:8080

Future Enhancements
- Full ROS 2 and Nav2 integration.
- Gazebo-based robot simulation.
- SLAM-based mapping and localization.
- Integration of advanced Large Language Models (LLMs).
- Improved real-time object recognition.
- Physical indoor robot implementation.
- Multi-robot coordination.
- Advanced authentication and access control.





---

⭐ If you find this project interesting, don't forget to star the repository!
