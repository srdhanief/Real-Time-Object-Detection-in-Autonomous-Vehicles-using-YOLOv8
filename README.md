<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
</head>
<body>
  <h1>🚀 YOLOv8: Cutting-Edge Object Detection</h1>
  <div style="text-align:center;">
    <a href="https://ultralytics.com/yolov8" target="_blank">
      <img style="width:100%;" src="https://miro.medium.com/v2/resize:fit:1100/format:webp/1*9gavyPR_Z0NHBm8mu6Z5dA.png" alt="YOLOv8 Banner" />
    </a>
  </div>
  <p>
    <a href="https://github.com/ultralytics/ultralytics">Ultralytics YOLOv8</a> is a fast, accurate, and easy-to-use model for object detection, segmentation, and classification, building on years of YOLO advancements.
  </p>

  <h2>🚗 Real-Time Object Detection in Autonomous Vehicles using YOLOv8</h2>

  <h3>📌 Project Overview</h3>
  <p>
    Utilizes <strong>YOLOv8</strong> for <strong>real-time detection of vehicles, pedestrians, and traffic signals etc</strong> in autonomous vehicle settings, enhancing road safety with practical computer vision deployment.
  </p>

  <h3>📂 Dataset</h3>
  <p>
    This project uses a <strong>Roboflow-hosted self-driving car dataset</strong> containing images and annotations for cars, pedestrians, and traffic signals. The dataset was integrated using the Roboflow API, ensuring organized, version-controlled, and YOLOv8-ready dataset management for effective training and validation.
  </p>

  <h3>🛠️ Installation</h3>
  <pre><code>pip install ultralytics roboflow</code></pre>

  <h3>⚡ Quick Usage</h3>
  <pre><code>yolo detect train data=data.yaml model=yolov8n.pt epochs=50 imgsz=640</code></pre>
  <p>For detailed exploration, see the <a href="https://github.com/srdhanief/Real-Time-Object-Detection-in-Autonomous-Vehicles-using-YOLOv8/blob/main/Real_Time_Detection_in_Autonomous_Vehicles_YOLOv8.ipynb">project notebook</a>.</p>

  <h3>📈 Results</h3>
  <p>✅ Effective real-time detection of road objects.</p>
  <p>✅ Evaluation metrics:</p>
  <div style="text-align:center;">
    <img src="runs/detect/train/confusion_matrix.png" width="45%" alt="Confusion Matrix">
    <img src="runs/detect/train/F1_curve.png" width="45%" alt="F1 Curve">
  </div>
  <ul>
    <li><strong>Confusion Matrix:</strong> Shows the performance of the model by comparing predicted classes with true classes.</li>
    <li><strong>F1 Curve:</strong> Displays the balance between precision and recall, indicating the model's accuracy across thresholds.</li>
  </ul>

  <h3>📜 License</h3>
  <p>MIT License</p>

  <hr />
  <p><em>⚡ Powered by YOLOv8</em></p>
</body>
</html>
