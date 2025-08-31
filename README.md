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


<h1 align="center">❤️ Heart Disease Prediction App</h1>

<p align="center">
  <b>Machine Learning + Streamlit</b><br>
  An interactive web app to predict heart disease risk using Logistic Regression.
</p>

<hr>

<h2>📖 Overview</h2>
<p>
This project is a sleek <b>ML-powered web application</b> built with <b>Streamlit</b>. 
It allows users to input health details (age, cholesterol, chest pain type, etc.) and predicts 
whether they are at risk of <b>heart disease</b> using a <b>Logistic Regression Model</b>.
</p>

<ul>
  <li>✔️ Simple and interactive interface</li>
  <li>✔️ Real-time prediction</li>
  <li>✔️ Visual feedback (Green = Healthy, Red = At Risk)</li>
</ul>

<hr>

<h2>🌟 Features</h2>
<ul>
  <li>🏥 Patient detail input form with user-friendly options</li>
  <li>⚡ Instant prediction with Logistic Regression</li>
  <li>🎨 Clean Streamlit UI with sidebar info</li>
  <li>✅ Displays results clearly with success/error messages</li>
</ul>

<hr>

<h2>🛠️ Tech Stack</h2>
<ul>
  <li>Python 3.x</li>
  <li>Pandas & NumPy – Data handling</li>
  <li>Scikit-learn – Logistic Regression Model</li>
  <li>Streamlit – Interactive UI</li>
</ul>

<hr>

<h2>📂 Project Structure</h2>
<pre>
heart-disease-prediction/
│── app.py                 # Streamlit web app
│── heart.csv              # Dataset (UCI Heart Disease dataset)
│── README.md              # Documentation
</pre>

<hr>

<h2>📸 Example Output</h2>
<p>
<b>Healthy Prediction:</b> ✅ The person does NOT have Heart Disease. <br>
<b>Risk Prediction:</b> ❌ The person HAS Heart Disease.
</p>
<p>(Add screenshots of the Streamlit app interface here)</p>

<hr>

<h2>📈 Future Improvements</h2>
<ul>
  <li>🔍 Show probability percentage instead of just Yes/No</li>
  <li>📊 Add charts for dataset insights</li>
  <li>💾 Load pre-trained model with pickle (faster startup)</li>
  <li>☁️ Deploy live app on Streamlit Cloud</li>
</ul>

<hr>

<h2>👤 Author</h2>
<p>
<b>Sarmad Rj</b><br>
📧 Email: sarmadrajpoot291@gmail.com <br>
🌐 GitHub: <a href="https://github.com/yourusername">yourusername</a>
</p>

<hr>

<p align="center"><i>⚠️ Disclaimer: This project is for educational purposes only. It should not be used for real medical diagnosis.</i></p>


<hr>

<p align="center"><i>⚠️ Disclaimer: This project is for educational purposes only. Detection accuracy depends on dataset & training. Not for production security use.</i></p>

<h1 align="center">🪪 ID Card Extractor & Form Filler</h1>

<p align="center">
  <b>OCR + Streamlit</b><br>
  Extract, review, and edit ID card details automatically with EasyOCR.
</p>

<hr>

<h2>📖 Overview</h2>
<p>
This project is an <b>interactive web app</b> that can extract details from ID cards using <b>OCR (EasyOCR)</b> 
and display them in an editable form. It also provides a manual entry option for users who prefer to 
fill in their details directly.
</p>

<ul>
  <li>✔️ Upload ID Card → Extract details automatically</li>
  <li>✔️ Manual Entry → Fill in details by hand</li>
  <li>✔️ Edit & Save → Review OCR results and correct if needed</li>
</ul>

<hr>

<h2>🌟 Features</h2>
<ul>
  <li>📷 OCR extraction of Name, CNIC, Dates, Gender, etc.</li>
  <li>📝 Manual entry option with clean form</li>
  <li>🔄 Editable pre-filled forms for higher accuracy</li>
  <li>✅ Smart regex patterns for CNIC & Date validation</li>
  <li>🇵🇰 Default Country of Stay: Pakistan</li>
</ul>

<hr>

<h2>🛠️ Tech Stack</h2>
<ul>
  <li>Python 3.x</li>
  <li>Streamlit – Interactive UI</li>
  <li>EasyOCR – Optical Character Recognition</li>
  <li>Regex – Pattern matching (CNIC, Dates, Gender)</li>
</ul>

<hr>

<h2>📂 Project Structure</h2>
<pre>
id-card-extractor/
│── app.py                 # Streamlit app
│── sample_id.jpg          # Sample ID card (for demo)
│── README.md              # Documentation
</pre>

<hr>

<h2>📸 Example Output</h2>
<p>
<b>Manual Entry:</b> Fill details in a structured form.<br>
<b>OCR Mode:</b> Upload ID card → Extracted details appear in editable form.<br>
</p>
<p>(Add screenshots of Streamlit tabs & OCR extraction here)</p>

<hr>

<h2>📈 Future Improvements</h2>
<ul>
  <li>🖼️ Better OCR accuracy with preprocessing</li>
  <li>📄 Export results to PDF/JSON</li>
  <li>🌍 Multi-language support (Urdu + English)</li>
  <li>🔐 Auto-delete uploaded files for privacy</li>
</ul>

<hr>

<h2>👤 Author</h2>
<p>
<b>Sarmad Rj</b><br>
📧 Email: sarmadrajpoot291@gmail.com <br>
🌐 GitHub: <a href="https://github.com/yourusername">yourusername</a>
</p>

