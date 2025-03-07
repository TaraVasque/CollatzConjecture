## Collatz Conjecture Visualizer
Welcome to the Collatz Conjecture Visualizer! This tool allows you to explore the famous Collatz sequence in a fun and interactive way. 
You can compute the sequence for any positive integer, visualize it as a chart, and download or upload the sequence data in JSON format.

## What is the Collatz Conjecture?
The Collatz Conjecture is a mathematical problem that involves taking any positive integer and applying the following rules:

If the number is even, divide it by 2.
If the number is odd, multiply it by 3 and add 1.
Repeat the process until the number reaches 1.
For example, starting with the number 6:

-6 (even) → 3
-3 (odd) → 10
-10 (even) → 5
-5 (odd) → 16
-16 (even) → 8
-8 (even) → 4
-4 (even) → 2
-2 (even) → 1
The sequence for 6 ends at 1.

## How to Use the Collatz Conjecture Visualizer
# 1. Enter a Starting Number
Type a positive integer in the "Enter start number" field. This is the number that will begin the Collatz sequence.
# 2. Start the Collatz Sequence
Click the "Start Collatz Sequence" button to calculate the sequence for the number you entered.
The tool will generate and display the full sequence, the number of steps it took, and a chart showing how the number changes at each step.
# 3. Visualize the Sequence
A line chart will appear below the buttons, showing the progression of the Collatz sequence for the entered number.
The x-axis represents the steps in the sequence.
The y-axis represents the values of the number at each step.
# 4. Download the Sequence Data as JSON
After the sequence is calculated, you can download the data by clicking the "Download as JSON" button. This will save a file containing:
The Collatz sequence.
The number of steps.
The peak and minimum values during the sequence.
Other metadata like processing time and average speed (hardcoded for simplicity).
# 5. Upload a Previously Saved JSON File
If you have a previously saved JSON file containing a Collatz sequence, you can upload it by clicking the "Upload JSON" button.
Once the file is uploaded, the tool will read the data and display the sequence and chart again based on the uploaded file.
# Features
Interactive Sequence Calculation: Enter any positive number to calculate its Collatz sequence and see it visualized in a dynamic chart.
Chart Visualization: The tool uses Chart.js to display a line graph of how the number evolves step by step.
Download/Upload JSON: Save the Collatz sequence as a JSON file or load an existing sequence for review or sharing.
Smooth and Responsive Design: The user interface is designed to be visually appealing with an animated gradient background, and it adapts to both desktop and mobile devices.
# Technologies Used
HTML5 – For the structure and layout of the webpage.
CSS3 – For styling the page with animations, responsive design, and modern effects.
JavaScript – For the functionality of calculating the Collatz sequence, handling user input, and generating the chart.
Chart.js – For rendering the line chart that visualizes the sequence.
FileSaver.js – For downloading the sequence data as a JSON file.

## How to Run Locally
# Clone the repository:

## bash
# Copy
`
git clone https://github.com/yourusername/collatz-visualizer.git
Navigate to the project folder:
`
## bash
# Copy
`
cd collatz-visualizer
Open the index.html file in your browser: You can open the index.html file directly in any modern browser to use the tool.
`
## License
This project is open source and available under the MIT License.

## Acknowledgements
Chart.js: For making the data visualization easy and beautiful.
FileSaver.js: For allowing us to save the Collatz data as a downloadable JSON file.
