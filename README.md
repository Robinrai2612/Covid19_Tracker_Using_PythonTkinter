# COVID-19-TRACKER-APPLICATION

## Get Covid-19 Data Country Wise
This Python program is designed to retrieve and display Covid-19 data for multiple countries in a graphical format. It utilizes the Tkinter library for the user interface and Matplotlib for creating data visualizations.

## Table of Contents
1. Requirements
2. Usage
3. How It Works
4. Notes
5. Contributing
6. License
7. Requirements
8. Before running this program, ensure you have the following prerequisites installed:

### Python 3.x
1. The covid library (pip install covid)
2. The matplotlib library (pip install matplotlib)

## Usage
Clone or download this repository to your local machine.

Open a terminal or command prompt and navigate to the directory where you saved the code files.

Run the program using the following command:

Copy code
python covid_data_app.py
The GUI application will open, allowing you to input the names of the countries for which you want to retrieve Covid-19 data.

Enter the country names, separating them with commas or spaces (not both), and click the "Get Data" button.

The program will fetch the data and display it graphically using Matplotlib.

## How It Works
The program's main functionality is contained in the showdata() function, which is called when the "Get Data" button is clicked.

It retrieves Covid-19 data for the specified countries using the covid library and stores it in lists.

Matplotlib is used to create a graphical representation of the data, with bar graphs showing confirmed cases, active cases, recovered cases, and deaths for each country.

The color-coded legend on the graph indicates the meaning of each bar's color.

If incorrect details are entered (e.g., country names separated by both commas and spaces), the program will provide an error message.

## Notes
Please make sure to enter country names correctly, differentiating them with either commas or spaces, but not both.

This program uses external libraries (covid and matplotlib), so ensure you have them installed before running the code.

This code is meant for educational purposes and may not be up-to-date with the latest data sources or APIs for Covid-19 information.

## Contributing
Feel free to contribute to this project by improving the code, fixing bugs, or adding new features. Pull requests are welcome!

## License
This project is licensed under the MIT License - see the LICENSE file for details.
