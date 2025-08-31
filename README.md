<h1 align="center">🔫 Firearm Detection with Real-Time Alerts</h1>

<p align="center">
  <b>YOLOv8 + OpenCV + SendGrid</b><br>
  Real-time firearm detection with automated email alerts and attached frames.
</p>

<hr>

<h2>📖 Overview</h2>
<p>
This project uses a <b>YOLOv8 object detection model</b> with <b>OpenCV</b> to monitor a live camera feed and detect firearms.
Whenever a firearm is detected:
</p>
<ul>
  <li>📸 A snapshot is saved</li>
  <li>📧 An <b>email alert</b> with the snapshot attached is sent via <b>SendGrid</b></li>
</ul>

<hr>

<h2>🌟 Features</h2>
<ul>
  <li>✅ Real-time firearm detection using YOLOv8</li>
  <li>✅ Automatic snapshot saving</li>
  <li>✅ Email alerts with attached images</li>
  <li>✅ Lightweight implementation with OpenCV</li>
</ul>

<hr>

<h2>🛠️ Tech Stack</h2>
<ul>
  <li>Python 3.x</li>
  <li>OpenCV – Live camera feed & image processing</li>
  <li>YOLOv8 (Ultralytics) – Object detection</li>
  <li>SendGrid API – Email alerts</li>
</ul>

<hr>

<h2>📂 Project Structure</h2>
<pre>
firearm-detection-alert/
│── main.py                # Main script
│── model.pt               # YOLO trained weights (not included in repo)
│── README.md              # Documentation
</pre>

<hr>

<h2>📸 Example Output</h2>
<p>Add a screenshot or sample detection image here (with bounding box on firearm).</p>

<hr>

<h2>📈 Future Improvements</h2>
<ul>
  <li>Support for multiple objects (e.g., knives, suspicious items)</li>
  <li>SMS / WhatsApp alerts</li>
  <li>Cloud storage for captured frames</li>
  <li>Integration with IP cameras</li>
</ul>

<hr>

<h2>👤 Author</h2>
<p>
<b>Sarmad Rj</b><br>
📧 Email: sarmadrajpoot291@gmail.com <br>
🌐 GitHub: <a href="https://github.com/yourusername">yourusername</a>
</p>

<hr>

<p align="center"><i>⚠️ Disclaimer: This project is for educational purposes only. Detection accuracy depends on dataset & training. Not for production security use.</i></p>
