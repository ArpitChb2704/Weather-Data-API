# Weather-Data-API

This project provides an API for accessing historical weather data of various stations across Europe. 
The data is sourced from the [European Climate Assessment & Dataset (ECA&D)](http://www.ecad.eu).

## Project Structure

- `main.py`: The main Flask application file that sets up the API endpoints.
- `templates/home.html`: The HTML file for the home page displaying the station list and usage instructions.
- `data/`: Folder containing all the weather data files.

## Requirements

- Python 3.x
- Flask
- Pandas

## Usage
__URL format__: http://127.0.0.1:5000/api/v1/station/date
__For one station for one date__: http://127.0.0.1:5000/api/v1/10/1988-10-25
__For one station for all dates__ : http://127.0.0.1:5000/api/v1/10
__For one station for one year__ : http://127.0.0.1:5000/api/v1/yearly/10/1988

## File Description
### main.py
This is the main application file that sets up the Flask server and routes for the API endpoints. It handles the request logic and serves the HTML template.

### templates/home.html
This HTML file is the template for displaying the weather data. It should be placed in a templates folder at the same level as main.py.
## Images
![Screenshot 2024-06-13 at 6 15 22 PM](https://github.com/ArpitChb2704/Weather-Data-API/assets/156332722/34ced7a5-5d15-4b9b-95db-85dfab9b8c9a)
![Screenshot 2024-06-13 at 6 26 59 PM](https://github.com/ArpitChb2704/Weather-Data-API/assets/156332722/e874f287-9c4b-42d5-9256-acaae90523ce)
![Screenshot 2024-06-13 at 6 27 27 PM](https://github.com/ArpitChb2704/Weather-Data-API/assets/156332722/2ae289be-e9e9-433e-a386-0dc77e14e31b)


