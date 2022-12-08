# Mission-162
Mission 162 Flights

## Mission
HABET Mission 162 is assigned to support the flights for the joint operation between the University of Iowa and Iowa State University. These flights are coordinating with a Near Space Payloads class being taught at the University of Iowa and the Make to Innovate and HABET program at ISU.

## Flight information
### HABET Flight L-162-A
Launched December 7th at 12:11 p.m. from Howe Hall in Ames, IA

### Spacecraft
The Gemini II spacecrafts were used

### Payloads
Coming soon

# Data Collected

## BERT Data
While BERT did transmit information, it was sporadic. However, the vital landing information was transmitted. BERT did NOT record data, the file had zero bytes. The cause is unknown at this time

## HAR Data
HAR Data was collected. HAR failed to transmit to Mission Control around 22K feet. This is being investigated but part of the problem seems to be with the pointing system for the antenna.

### Atmospheric Data
Below is the temperature data recorded. This was recorded with the onboard temperature since located on the Clue board. This board was located in the spacecraft.
<img
  src="Plots/har_temp_plot.png"
  alt="HAR Temperature"
  title="HAR Temperature Plot"
  style="display: inline-block; margin: 0 auto; max-width: 800px">

  Below is the Humidity Data recorded

  <img
  src="Plots/har_humidity_plot.png"
  alt="HAR humidity"
  title="HAR Humidity Plot"
  style="display: inline-block; margin: 0 auto; max-width: 800px">

Below is the Pressure Sensor data recorded. This was in a partially sealed case.
  <img
  src="Plots/har_pressure_plot.png"
  alt="HAR Pressure"
  title="HAR Pressure Plot"
  style="display: inline-block; margin: 0 auto; max-width: 800px">

Temperature data compared to the altitude as recorded by the GPS.

  <img
  src="Plots/tempalt_plot.png"
  alt="Temperature and Altitude"
  title="Temperature and Altitude Plot"
  style="display: inline-block; margin: 0 auto; max-width: 800px">

Temperature and Humidity Plot

<img
  src="Plots/temp_humidity.png"
  alt="Temperature and Humidity"
  title="Temperature and Humidity Plot"
  style="display: inline-block; margin: 0 auto; max-width: 800px">

### GPS Data

The following graphs are generated from the onboard GPS Unit. This includes Lat/Lon and Altitude data. We also plot this on a map using Tilemaps in Python.

<img
  src="Plots/gps_plot_nomap.png"
  alt="GPS Plot"
  title="GPS Plot"
  style="display: inline-block; margin: 0 auto; max-width: 800px">

<img
  src="Plots/3D_Map_View.png"
  alt="3D GPS Plot"
  title="3D GPS Plot"
  style="display: inline-block; margin: 0 auto; max-width: 800px">

We have confirmed that we have valid GPS data, so we can overlay this information using Tilemaps and Open Street Maps.

<img
  src="Plots/gps_plot_map.png"
  alt="GPS Plot on Map"
  title="GPS Plot using Open Street Maps"
  style="display: inline-block; margin: 0 auto; max-width: 800px">

The following is now zooming into the landing spot on the map
  <img
  src="Plots/gps_plot_landing.png"
  alt="GPS Plot Landing"
  title="GPS Plot of the landing"
  style="display: inline-block; margin: 0 auto; max-width: 800px">

### IMU Data
Since BERT malfunctioned, no IMU data was collected.


# Wrap up
Additional plots can be found in the Plots directory. You can find a KML file in the KML directory. Finally, the raw CSV file can be found in the Data folder.