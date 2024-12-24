# A_Star_Map_Route_Planning
This project based on A*, OSM, IO2D, to implement map route planning.

This is not the Udacity course project, all codes are based on the libraries mentioned above and finished by myself. The udacity A* route planning project is: https://github.com/jeffliulab/Udacity_Fork_Only_No_Derivatives_CppND-Route-Planning-Project

# Developing Process

**V0(Now)** => V1: Can load map and plot a simple route => V2: Final Implementation

# Directory

```
My_AStar_Planner/
├── CMakeLists.txt      # Custom CMake configuration file
├── src/
│   ├── main.cpp        # Main program entry point
│   ├── AStar.cpp       # A* algorithm implementation
│   ├── MapParser.cpp   # OSM data parsing logic
│   ├── Visualizer.cpp  # IO2D visualization logic
│   └── ...            
├── include/
│   ├── AStar.h         # Header file for A* algorithm
│   ├── MapParser.h     # Header file for map parsing
│   ├── Visualizer.h    # Header file for visualization
│   └── ...
├── thirdparty/         # Third-party libraries (e.g., IO2D, OSM tools)
│   ├── IO2D/           # IO2D visualization library
│   └── OSM_Lib/        # OSM data library
├── map.osm            # OpenStreetMap data file
└── README.md          # Custom project documentation

```
