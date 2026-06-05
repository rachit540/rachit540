# Rachit Srivastava
**Software Engineer | Node.js • React • Python • Automation**

Passionate about building robust web applications, writing resilient automated testing suites, and experimenting with computer vision and scripting utilities.

---

### 🛠️ Core Technical Stack

- **Backend & DB**: Node.js, Express, REST APIs, JSON databases (LowDB)
- **Frontend & Styling**: React 19, Tailwind CSS v4, Responsive Design, CSS3
- **Automation & Testing**: Playwright E2E Testing, Automated Retry Architectures, Screenshot Capture
- **Languages & Utilities**: Python, NumPy, Pillow, OpenCV (computer vision)
- **Development Tooling**: Git, VS Code, Environment Management

---

### 🚀 Featured Open Source Work

#### 1. [MedQR](https://github.com/rachit540/MEDQR)
*A full-stack emergency medical profile generator and dynamic QR router.*
- **Backend**: Express server running on Node.js using LowDB for lightweight local state. Passwords securely hashed with **bcryptjs** (with salt rounds) prior to database serialization.
- **Frontend**: Responsive React 19 application utilizing Tailwind CSS v4 for clean, high-contrast layouts.
- **Dynamic Routing**: QR Code canvas encodes dynamic profile redirection links (`/emergency/:uuid`) rather than static text dumps, allowing real-time profile updates.
- **Emergency Layout**: Highly visible, mobile-optimized interface with instant action items (e.g., click-to-call) specifically designed for first responders.

#### 2. [OTP Login Automation](https://github.com/rachit540/otp-login-automation)
*A modular Node.js test-automation framework using Playwright for OTP verification flows.*
- **Modular Architecture**: Clean separation between configurations, browser control wrappers, SMS mockup servers, logger modules, and main orchestration workflows.
- **Resiliency**: Built-in HTTP retry policies (`withRetry`) to handle intermittent page latency or network drops during SMS retrieval.
- **Troubleshooting**: Integrated failure screen capture and transaction logs writing to local JSON log structures.

#### 3. [Real-Time HSV Color Tracker](https://github.com/rachit540/Color-Detection-ML-project)
*A command-line computer vision utility in Python for object outline tracking.*
- **OpenCV Filtering**: Captures live webcam feeds, converts BGR streams to HSV color space, and segments specific colors using dynamic hue tolerances.
- **Dynamic Thresholding**: Handles complex hue wrap-around conditions (like Red) near boundary limits.
- **CLI Argparse**: Integrated command-line configurations enabling custom color (BGR) targets and webcam hardware select options.

---

### 🌐 Let's Connect

- **LinkedIn**: [Rachit Srivastava](https://www.linkedin.com/in/rachit-srivastav-623309369/)
- **Email**: [rachit.srivastav540@gmail.com](mailto:rachit.srivastav540@gmail.com)
