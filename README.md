# PULSATION Web Viewer
A scrappy web visualization tool for (variable) stars. May get updated going forward.

## Instructions

- Replace "data" folder with contents of downloaded archive
- Run "python -u -m http.server 8000" in command line (keep it open; it basically hosts the "webpage" on your local machine)
  - Note that you can replace 8000 with any other port number you want; just replace it in the URL below as well.
- Open "http://localhost:8000/index.html" on your preferred web browser
- Choose the data file from inside the data folder
  - The data file should have 1 line for each star, in the following format:
  - {object id} {folder path} {# of frames, F475W} {# of frames, F814W}
