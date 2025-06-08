# metro_route_optimizer
#  Hyderabad Metro Route Finder

Welcome to the **Hyderabad Metro Route Finder** – a smart and intuitive Streamlit web app that helps commuters find optimal metro routes between any two stations in Hyderabad. Whether you're a daily traveler or new to the city, this app makes it easy to navigate the metro like a pro!


## 🧠 Features

- 🔁 **Multiple Algorithms**: Choose from three pathfinding algorithms:
  - **Dijkstra**: Finds the shortest distance (in minutes).
  - **BFS (Breadth-First Search)**: Finds the route with the fewest number of stops.
  - **DFS (Depth-First Search)**: Shows a random valid path – more for educational exploration.

- 🗺️ **Interactive Route Summary**:
  - Displays the full path, time, and transfer hints.
  - Alerts you if a transfer *might* be required at major junctions (like Ameerpet or MG Bus Station).
  - Beautiful ticket-style summary with journey greeting!

- 📊 **Route Table View**: View all intermediate stations in a clean table.

- 🖼️ **Metro Map Reference**: View the metro map image for better visualization.


## 📂 Files Included

- `app.py`: The main Streamlit app with all logic and UI.
- `HYDF.xlsx`: Excel file with metro connection data (Source, Destination, Distance).
- `finimg.png`: An image of the Hyderabad Metro Map (for reference in the app).
- `README.md`: You're reading it right now!
