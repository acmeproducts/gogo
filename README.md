<div align="center">
<img width="1200" height="475" alt="GHBanner" src="https://github.com/user-attachments/assets/0aa67016-6eaf-458a-adb2-6e31a0763ed6" />
</div>

# Orbital8 Goji Version

This is a single-page application for managing and organizing images from cloud storage providers like Google Drive and OneDrive. It is built with plain HTML, CSS, and JavaScript.

## Purpose

The main purpose of this application is to provide a user-friendly interface for sorting and tagging images stored in the cloud. It allows users to connect to their Google Drive or OneDrive account, select a folder of images, and then organize them into different "stacks" (e.g., "inbox", "keep", "recycle").

## Features

- **Cloud Storage Integration**: Connect to Google Drive and OneDrive to access your images.
- **Image Stacks**: Organize your images into four stacks: "Inbox", "Maybe", "Keep", and "Recycle".
- **Gesture-based Sorting**: Use swipe gestures to quickly move images between stacks.
- **Image Tagging**: Add tags to your images for better organization and searching.
- **Metadata Extraction**: Extracts and displays metadata from PNG files.
- **Grid View**: View your images in a grid layout for a better overview.
- **Focus Mode**: A distraction-free mode for focusing on a single image.
- **Local Caching**: Uses IndexedDB to cache folder data for faster loading times.
- **Data Export**: Export image data and metadata to a CSV file.

## Run Locally

This is a simple HTML/JavaScript application and does not require any build process or dependencies to be installed. To run the application locally, simply open the `index.html` file in a web browser.

**Note**: Due to browser security restrictions, the application may not work correctly if you open the `index.html` file directly from your local file system (i.e., using a `file:///` URL). It is recommended to use a simple local web server to serve the file.

### Using a Local Web Server (Optional)

If you have Python installed, you can easily start a local web server by running the following command in the root directory of the project:

```bash
python -m http.server
```

Then, open your web browser and navigate to `http://localhost:8000`.

## Project Structure

The entire application is contained within the `index.html` file. This includes the HTML structure, CSS styles, and JavaScript logic. The project was initially set up as a TypeScript project, but the TypeScript files (`index.tsx`, `tsconfig.json`, `vite.config.ts`) are not used and will be removed.
