# Container Home Layout Tool

The Container Home Layout Tool is an interactive web application that allows users to visually design the footprint of a container home by dragging and dropping standard shipping container templates (20' HC and 40' HC) onto a grid. This tool is designed to be intuitive and user-friendly, with a modern interface inspired by sleek, futuristic design principles. It calculates the total square footage of the placed containers and provides options to rotate, delete, or clear the design.

## Features

- **Drag-and-Drop Interface**: Drag 20' HC or 40' HC container templates from the palette to the design area.
- **Grid-Based Design**: Containers snap to a 10x10 pixel grid for precise placement.
- **Interactive Controls**:
  - **Rotate**: Rotate a selected container by 90 degrees.
  - **Delete**: Remove a selected container.
  - **Clear All**: Reset the design area.
- **Square Footage Calculation**: Automatically updates the total footprint in square feet based on placed containers.
- **Responsive Design**: Works seamlessly on desktop and mobile devices, with a stacked layout on smaller screens.
- **Modern UI**: Clean typography, smooth animations, and a professional color scheme for an engaging user experience.
- **Call to Action**: Links to Oasis Engineering for professional plans and structural modifications.

## Usage

1. **Open the Tool**: Load `container_home_layout_tool.html` in a modern web browser (e.g., Chrome, Firefox, Safari).
2. **Drag Containers**: From the "Container Palette" on the left, drag a 20' HC or 40' HC container to the design area.
3. **Position and Adjust**:
   - Containers snap to a grid for easy alignment.
   - Click a placed container to select it (highlighted with a red border).
   - Use the "Rotate (90°)" button to rotate the selected container.
   - Use the "Delete" button to remove the selected container.
   - Use the "Clear All" button to reset the design area (requires confirmation).
4. **View Square Footage**: The total footprint is displayed in real-time below the design area.
5. **Get Professional Plans**: Click the "Get Custom Engineered Plans" button to contact Oasis Engineering for professional services.

## Setup

To run the tool locally:

1. **Clone or Download**:
   - Download the `container_home_layout_tool.html` file or clone the repository if hosted.
2. **Host the File**:
   - Place the file in a directory and open it directly in a web browser, or
   - Use a local server (e.g., `python -m http.server` or VS Code’s Live Server) to serve the file for optimal performance.
3. **Internet Connection**:
   - Ensure an internet connection is available, as the tool loads external dependencies (Interact.js and Google Fonts) from CDNs.

## Dependencies

- **Interact.js**: Used for drag-and-drop and interactive functionality. Loaded via CDN: `https://cdn.jsdelivr.net/npm/interactjs/dist/interact.min.js`
- **Google Fonts (Inter)**: Provides the modern typography. Loaded via: `https://fonts.googleapis.com/css2?family=Inter:wght@400;500;700&display=swap`

No additional installation is required, as all dependencies are fetched from CDNs.

## License

This project is unlicensed. For custom licensing terms, please contact Oasis Engineering.

## Contact

For professional engineering plans, structural modifications, or permit-ready drawings, visit [Oasis Engineering](https://oasisengineering.com/) or contact them directly at [Oasis Engineering Contact](https://oasisengineering.com/contact).