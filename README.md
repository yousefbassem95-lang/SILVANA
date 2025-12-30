
Slivana<img width="865" height="863"<img width="404" height="894" alt="Screenshot from 2025-12-30 06-36-29" src="https://github.com/user-attachments/assets/c87711d5-95a6-44ea-9267-1d9ffc6f47eb" />
 alt="Pasted image" src="https://github.com/user-attachments/assets/0af4ffe6-697b-4e8a-b006-9aa810b6cfd8" />

Walkthrough - Ultimate Reverse Search Tool
I have successfully created a comprehensive Reverse Image and Video Search Tool.

Key Features Implemented
Core Search Engine Logic:

Supported Engines: Google Lens, Bing, Yandex, Tineye.
Video Processing: Automatically extracts frames from video files (
core/video_processor.py
) using opencv-python.
Resilience: Handles missing dependencies (like cv2) gracefully.
User Interfaces:

Web App (Default): A premium "Black & Red" local web interface with Drag & Drop, clickable results (open in new tab), and Download Report functionality.
CLI: A robust command-line interface.
GUI (Legacy): Graphical interface (available via --gui).
Assets & Branding:

Web Theme: "SILVANA" fused entity (Female Cyborg Mothership). Pure black background with neon red accents.
Red Theme: CLI/GUI branding elements are displayed in RED.
Banner: Custom "Spaceship" art.
User Icon: Integrated your specific ASCII icon 
basic
 (Displayed Top-Right in Web App).
Project Name: "SILVANA" rendered in ASCII art and modern glitch text.
Search Capabilities:

Engines: Google Lens, Bing, Yandex, TinEye, DupliChecker, Pinterest.
Dark Web: Ahmia.fi support (Requires Tor Browser).
Video: Frame extraction logic.
Download: Export search results to JSON.
Verification Results
I verified the CLI functionality using a generated test image.

Search Engine Verification
Google Lens: Direct image upload VERIFIED WORKING.
Yandex/Bing: Robust fallback to manual upload page (due to bot protections).
Tor/Ahmia: Launches Tor Browser connected to Dark Web search.
Web App
The sleek web interface is the default mode.

./venv/bin/python UltimateReverseSearch/main.py
CLI Guide (Step-by-Step)
For users preferring the terminal:

Activate Environment (If not already active):

source venv/bin/activate
Run Command:

python UltimateReverseSearch/main.py --cli --file <path_to_image_or_video>
Example: python UltimateReverseSearch/main.py --cli --file my_photo.jpg

View Results: The tool will print the ASCII banner in RED and open results in your default browser tabs automatically.

GUI
The GUI is configured to launch by default. It features:

Dark Mode (Cyborg Theme)
User Icon Display
File Browser and Results Log
Next Steps
Run pip install -r requirements.txt to install dependencies.
Run python main.py to start the application.
# SILVANA
