# FIDE Chess Players – Interactive Visualizations

## Project Structure

project-root/
├── viz/
│   ├── line_graph.html
│   ├── bar_graph.html
│   └── bubble_worldmap.html
├── data/
│   ├── ratings.tsv.gz
│   ├── players.tsv
│   ├── countries.tsv
│   └── world.geojson
├── vendor/
│   └── d3-7.8.5/
└── README.md


## Dependency

The file world.geojson is required for the World Bubble Map visualization. It needs to be placed inside data folder: project-root/data/world.geojson

## Run Visualizations

### Running the Visualizations:
Step 1: Open a terminal

### Step 2: Start a local HTTP server
Run the following command: python3 -m http.server 8000

### Step 3: Open the visualizations in a browser

Open your browser and go to: http://localhost:8000/viz/

Then you can choose the visualisation to open : Line Graph, Bar Graph, Bubble World Map
