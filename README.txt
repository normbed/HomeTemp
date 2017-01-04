This project is a basic html page presenting a graphic of my Home Temperarature system.
A RaspberryPi collects data from two sensors (one outside, one inside) and periodicly saves 
their data in a text file on a NFS mounted directory of a Linux server. 
Using the text data file, the Linux server calls gnuplot to generate a graphic file for display on the web page.

For the moment, this project illustrates only the html web pages, not the RappberryPI code or gnuplot. 
A typical formatted text file is supplied to emulated the RaspBerryPi for the temperature data.


The web browser connects the index.html page.
3 Files are involved for this demo:

- index.html: 		The main html page
- details.html		Description page
- temperature.gif	Graphic of temperature.





   




  