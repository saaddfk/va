# Minecraft Performance Analyzer

The **Minecraft Performance Analyzer** is a web-based tool that leverages TensorFlow.js and advanced analytics to evaluate Minecraft gameplay videos. This application assesses various performance metrics to provide insights and recommendations based on gameplay style.

## Banner and Screenshots

<!--- Add your banner image here -->
<!--- ![Banner](path/to/your/banner.png) -->

<!--- Add screenshots of your application interface here -->
<!--- ![Screenshot 1](path/to/your/screenshot1.png) -->
<!--- ![Screenshot 2](path/to/your/screenshot2.png) -->

*Consider uploading a banner image or screenshots to your repository to illustrate your application's interface. You can then uncomment the lines above and update the paths.*

## Key Features

- **Video Upload and Analysis**: Upload Minecraft gameplay videos and receive a comprehensive analysis report.
- **Adjustable Metrics**: Choose primary focus areas like PvP, building, or exploration.
- **Quality Settings**: Optimize analysis accuracy or speed for different device capabilities.
- **Calibration Options**: Customize element detection thresholds to enhance accuracy.
- **Dynamic Scoring and Recommendations**: Receive personalized improvement suggestions based on performance metrics.

## Getting Started

### Requirements

- Modern web browser (Chrome, Firefox, Safari)
- Internet connection
- Basic understanding of Minecraft gameplay

### Usage

1.  **Upload Video**: Drag and drop your Minecraft video into the upload area in `index.html` or click to select it.
2.  **Select Options**:
    *   Set your player name and game mode.
    *   Choose primary focus and analysis quality from the dropdowns.
3.  **Calibration (Optional)**:
    *   Click "Calibrate" to set custom thresholds for colors and UI elements.
4.  **Analyze**:
    *   Click "Analyze Performance" to start the analysis.
5.  **Review Results**: View your performance metrics, analysis details, and receive recommendations.

## Improvements

### User Interface Enhancements
*   Integrated a calibration button to allow users to fine-tune the analysis process by setting custom color thresholds and UI element bounds.
*   Added dropdown menus for selecting the primary focus and analysis quality, providing a tailored analysis experience.
*   Designed with Tailwind CSS to support dynamic light/dark themes for better user experience.

### Functional Enhancements
*   **Primary Focus Adjustment**: The system dynamically adjusts metric weights based on user-selected focus (e.g., PvP / Combat).
*   **Resolution Options**: Analysis quality can be set to 'Fast', 'Balanced', or 'Accurate', adapting to various device capabilities.
*   **Web Worker Utilization**: Moved intensive video processing tasks to a Web Worker, keeping the UI responsive.

*Note: Placeholder URLs, email addresses, and usernames should be updated with actual information where applicable throughout the project.*

(The "Improvements" section and the note about placeholders are taken from the issue description and existing `index.html` context. The "index file at repo" part of the issue's "Optimization" section seems to refer to `index.html` itself.)

## Deploying to GitHub Pages

This project is a static HTML, CSS, and JavaScript application and can be easily deployed using GitHub Pages.

To deploy the Minecraft Performance Analyzer:

1.  **Ensure your repository is on GitHub.**
2.  **Go to your repository's settings:**
    *   Navigate to your repository on GitHub.com.
    *   Click on the "Settings" tab.
3.  **Configure GitHub Pages:**
    *   In the left sidebar, click on "Pages".
    *   Under "Build and deployment", for the "Source", select "Deploy from a branch".
    *   Under "Branch", select your main branch (commonly `main` or `master`) and the `/ (root)` folder, then click "Save".
    *   If you prefer, you can create a dedicated `gh-pages` branch and deploy from there.
4.  **Access your site:**
    *   GitHub Pages will build your site and provide a URL (e.g., `https://your-username.github.io/your-repository-name/`).
    *   It might take a few minutes for the site to become available after the first deployment.
    *   Ensure your main HTML file is named `index.html` at the root of the branch you are deploying from.

Your application should then be accessible online via the provided GitHub Pages URL.
