# A Simple Currency Converter

This project is a simple webs-scrapping Python-based Currency Converter (over 30 currencies).

Its UI uses `tkinter` library for the UI as displayed below:

<p align="center">
  <img src="https://user-images.githubusercontent.com/59763234/103484755-8c39fe00-4df1-11eb-8bb6-aedf64f6caa6.png" />
</p>


The FX is cached until the next request exceeds one day. The information comes from:
https://www.ecb.europa.eu/stats/eurofxref/eurofxref-daily.xml

## Project structure

The App usesa MVC architecture to improve readability, with driver found in `main.py`

## Testing

Basic Unit testing using `mock` library for the caching of webscraping is used.

## Deployment

A Dockerfile has been added so that users can create a Docker Image & Docker Container to run the App.

## Notable Dependencies

Python=3.9

For Webscrapping, we used:

- `requests`
- `bs4`

For testing, we used

- `unittest` (with Mocks)
