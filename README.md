# 3DGS Georeferenced Viewer - Azfa Ahmad Dzulvikar

## Overview

Welcome to the **3DGS Georeferenced Viewer** project! This repository contains a 3D viewer application for georeferenced data. The viewer allows you to visualize geospatial data with transformations and is part of the research I conducted for my thesis.

## Cloning the Repository

To get started with this project, you'll need to clone the repository to your local machine. You can do so using HTTPS.

### Steps:

1. Open a terminal or command prompt.
2. Run the following command to clone the repository:
   ```bash
   git clone https://github.com/masazfaa/tesisazfa-3DGSViewer.git
3. Once the repository is cloned, navigate into the project directory:

   ```bash
   cd tesisazfa-3DGSViewer
   ```

Now you have the project files on your local machine and are ready to start working with the viewer.

## Data Example

This repository contains sample data from my research journal. The data is available for use and can be tested within the viewer. The data is not yet published but will be shared once the research is complete. For now, the data files are available for local use in this repository.

### Example Data:

* The example data includes geospatial data files that you can load directly into the viewer.

## Data Transformation

Once you have successfully displayed the 3D viewer, you can import transformation data by following these steps:

1. **Load the Viewer**: Open the 3DGS Georeferenced Viewer in your browser or application.

2. **Import XML Data**:

   * In the viewer interface, click the **"Choose File"** button in the **XML file import container**.
   * Navigate to the folder where the data is located and select the file `WatuTugu-TransformationData.XML`.

3. **Transformation Selection**:

   * After selecting the XML file, you will need to choose the **transformation** to apply.
   * Choose **"UTM 49S"** as the transformation option to convert the data from the geocentric coordinate system to the **UTM 49S** coordinate reference system.

4. **Apply the Transformation**:

   * The data will now be transformed into the selected coordinate system. This step ensures that the data is in the correct spatial reference for proper visualization.

### Notes:

* The transformation data is initially in a **geocentric coordinate system**, so ensure you select the correct transformation.
* This step is crucial for accurately visualizing the data in the viewer with correct geospatial alignment.

## How to Use the Viewer

Once the viewer is set up, you can:

1. **Load Geospatial Data**:

   * Import geospatial data files (such as `.xml` files) directly into the viewer.
   * Use the "Choose File" button to load your XML data.

2. **View 3D Data**:

   * Once the data is imported, the viewer will display the geospatial data in 3D.
   * You can interact with the 3D visualization, rotate, zoom, and pan to explore the data.

3. **Apply Data Transformations**:

   * You can apply various transformations, such as **UTM 49S**, to adjust the data to the correct coordinate system for analysis.
   * The transformation will adjust the data's geospatial location and alignment in the viewer.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

If you have any questions or suggestions, feel free to contact me via [GitHub Issues](https://github.com/masazfaa/tesisazfa-3DGSViewer/issues).

---

Happy exploring, and I hope this tool helps you in your geospatial data analysis!

```

This **README** now includes detailed instructions, code snippets, and explanations for:

- Cloning the repository
- Importing data into the viewer
- Selecting and applying transformations

This will allow users to set up and utilize the 3DGS Georeferenced Viewer with ease. Let me know if you'd like any further revisions or clarifications!
```
