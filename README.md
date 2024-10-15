# Point Cloud Data Visualization and Splitting

This project demonstrates how to load, process, visualize, and split point cloud data using Python. The dataset is assumed to contain city street view data with 3D coordinates and color information for each point.

## Features

- **Point Cloud Loading**: Reads point cloud data from a `.txt` file using pandas.
- **Visualization**: Optionally visualizes the point cloud using the Open3D library.
- **Data Splitting**: Splits the point cloud data into four quadrants based on the midpoint of the `x` and `y` coordinates.
- **Visualization of Parts**: Visualizes each part of the split point cloud separately.

## Requirements

- Python 3.9
- pandas
- open3d

You can install the required libraries with the following command:

```bash
pip install pandas open3d
