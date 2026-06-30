# UAV Image Copy Field Trial Tool

## Overview

The **UAV Image Copy Field Trial Tool** is a GUI-based application designed to extract and copy UAV images from large agricultural field trials.

Users can select images for a specific area using either:

1. **An existing shapefile boundary**, or
2. **A user-defined Area of Interest (AOI)** drawn directly on an interactive map.

The tool automatically identifies images whose GPS locations fall within the selected area and copies them to a new folder.

---

## Key Features

- GUI-based interface (no programming required)
- Supports multiple UAV sensors (e.g., Sentera 65R)
- Select images using a **shapefile boundary**
- Draw a custom **AOI directly on the map**
- Interactive map visualization inside the GUI
- Adjustable buffer distance in **meters, feet, or drone passes**
- Preserve original folder structure
- Export selected images to a new folder
- Generate summary statistics and logs
- Designed for agricultural researchers, breeders, and farmers

---

## Workflow

### Option 1: Draw AOI on Map

1. Select **Draw AOI on Map**.
2. Select the image folder.
3. Click **Load Image GPS Points**.
4. Draw an AOI on the map.
5. Click **Finish AOI**.
6. Click **Run Image Copy**.

### Example: Loaded GPS Points

![Loaded GPS Points](screenshots/01_loaded_points.png)

### Example: Draw AOI and Select Images

Images inside the AOI are shown in **red**, while images outside are shown in **blue**.

![AOI Selection](screenshots/02_draw_aoi.png)

---

### Option 2: Use Existing Shapefile

1. Select **Use Shapefile**.
2. Browse to the shapefile boundary.
3. Select the image folder.
4. Select the output folder.
5. Click **Run Image Copy**.

![Shapefile Selection](screenshots/03_shapefile_mode.png)

---

## Buffer Options

Users can define a boundary buffer using:

- Meters
- Feet
- Drone Passes

Example using feet as the buffer unit:

![Buffer Units](screenshots/04_buffer_feet.png)

---

## Output

The tool provides:

- Total image groups
- Copied/inside images
- Outside images
- Images without GPS information
- Log messages

---

## Software Distribution

This software is distributed as a standalone Windows executable (.exe).

No Python installation is required.

---

## Developed By


Developer: **Ramita Shah**
**Paulo Flores Lab (ABEN)**  
Department of Agricultural and Biosystems Engineering  
North Dakota State University (NDSU)

## License

This software is distributed for academic, research, and educational use only. The source code is not publicly available. See the LICENSE file for details.

