# K18PG
Artificial Intelligence
🧭 Navigation Tracker
1. 🚀 Project Overview
Navigation Tracker is a Python-based desktop application that visualizes routes between two geographical locations using Google Maps. It offers a graphical user interface (GUI) built with Tkinter, uses Geopy to geocode addresses, and plots locations and paths on a map using gmplot.

🎯 Purpose and Goals
Allow users to enter source and destination locations.

Display a map with both locations marked.

Plot the navigation path between the two points using Google Maps.

✨ Key Features
GUI-based input for easy interaction

Geocoding using Geopy for converting text to coordinates

Google Map visualization with markers and route

HTML map output opened directly in a web browser

2. ⚙️ Installation and Setup
✅ Prerequisites
Python 3.7+

Internet connection (for geocoding via Geopy)

Npcap (for any additional packet-sniffing features, not used in this current script)

📦 Required Python Libraries
Install the required packages using pip:

bash
Copy
Edit
pip install gmplot geopy
Note: If pip is not recognized, ensure Python and pip are correctly installed and added to your system PATH.

🧱 Directory Setup
Clone the repository and navigate to the project directory:

bash
Copy
Edit
git clone https://github.com/YOUR_USERNAME/navigation-tracker.git
cd navigation-tracker
3. 📌 Usage
🖥️ Running the Application
Run the Python script:

bash
Copy
Edit
python navigation_tracker.py
👨‍💻 How to Use
Click ENTER on the main window.

In the new window, enter the source and destination addresses (currently hardcoded as "ecil hyderabad" and "charminar" — you can modify these in the code).

Click ENTER to generate a map.

A browser window will open displaying the route between the two locations.

The HTML map is saved to:
C:\Users\<YourUsername>\OneDrive\Desktop\scatter2.html
You can change this path in the script under gmap3.draw(...).

⚠️ Current Limitations
Input fields exist but are not yet linked to the geocoding logic (currently hardcoded).

No error handling for invalid locations.

HTML map file path is hardcoded.

4. 🤝 Contributing
We welcome contributions from the community! To get involved:

🐞 Submitting Issues
Go to the Issues tab

Create a new issue and describe the bug or feature request

🔀 Pull Requests
Fork this repository

Create a new branch (git checkout -b feature/my-feature)

Commit your changes

Push the branch to your fork

Open a Pull Request and describe your changes

✅ Code Review Guidelines
Use meaningful commit messages

Keep functions small and focused

Comment complex logic

Follow PEP8 guidelines


🙋‍♂️ Author
Developed by Vamshi
Feel free to connect on GitHub
