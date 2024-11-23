
# VFX Workflow Extension

The **VFX Workflow Extension** is an essential tool designed to streamline the process of transforming video content into detailed frames for visual effects (VFX) and stylization projects. It seamlessly integrates into the Stable Diffusion WebUI environment, providing robust tools for frame extraction, mask generation, keyframe management, and batch processing with Img2Img technology. Ideal for VFX artists, animators, and content creators, this extension ensures a smooth and efficient workflow, minimizing the manual effort required in managing and processing video frames.

---

## Features Overview

### Frame Extraction
- **High-Quality Frames:** Extracts frames at the original video's frame rate, preserving the quality and timing.
- **Multiple Format Support:** Accepts a variety of video formats including `.mp4`, `.mov`, and `.avi`.
- **Automatic Organization:** Outputs are saved in sequentially numbered files within project-specific folders.

**Detailed Usage:**
1. Upload your video file to the designated tab.
2. Input your project title for easy organization.
3. Click "Extract Frames" to start the extraction process. The frames will be sequentially numbered (e.g., `00001.png`), facilitating easy navigation.

### Mask Creation
- **AI-Powered Masking:** Utilizes advanced AI algorithms to generate detailed grayscale masks, essential for selective editing and effects application.
- **Performance Optimization Options:** Features options like 'Fast Mode' and 'JIT Compilation' to enhance processing speed.
- **Versatile Applications:** Ideal for tasks that require background removal or selective stylization.

**Detailed Usage:**
1. Navigate to the "Mask Creation" tab.
2. Select your performance preference (Fast Mode or JIT Compilation).
3. Initiate mask generation by clicking "Generate Masks". Each frame will be processed to create a corresponding mask.

### Keyframe Management
- **Intelligent Keyframe Extraction:** Dynamically selects keyframes based on user-defined intervals, ensuring that crucial moments are captured for detailed attention.
- **Enhanced Organization:** Automatically organizes keyframes into manageable subfolders to prevent clutter and improve accessibility.
- **Comprehensive Coverage:** Options to include the first and last frames of the video to ensure complete narrative coverage.

**Detailed Usage:**
1. Set your project parameters and opt to include the first and last frames.
2. Initiate the extraction by clicking "Extract Keyframes", which organizes keyframes into designated folders.

### Img2Img Integration
- **Batch Processing:** Simplifies the process of using Stable Diffusion's Img2Img feature by automating the setup of input and output paths.
- **Efficient Workflow:** Designed to reduce the complexity of batch processing stylizations or edits across multiple frames.

**Detailed Usage:**
1. Go to the "Img2Img Instructions" tab.
2. Retrieve and follow the provided instructions to set up paths for the Batch Processor.

### File Management and Packaging
- **File Renaming:** Streamlines the workflow by renaming files in `img2img_output` to maintain consistency with other sets.
- **ZIP File Creation:** Facilitates the packaging of project folders into a single ZIP file, making it easy to download, share, or archive projects.

**Detailed Usage:**
1. Use the "Rename & Generate ZIP" function to standardize file names and prepare your project for export.
2. Click "Generate ZIP File" to compile and download all essential project components.

---

## Installation Guide

### Prerequisites
- Ensure you have Python version 3.8 or newer.
- Must be integrated within the Stable Diffusion WebUI environment.

### Installation Steps
1. Clone the extension repository into your Stable Diffusion setup:
   ```bash
   git clone https://github.com/yourusername/vfx_workflow.git
   ```
2. Navigate to the cloned directory and run:
   ```bash
   python install.py
   ```
3. Restart the Stable Diffusion WebUI to apply changes.

## Comprehensive Examples

Follow these steps to maximize the use of the VFX Workflow Extension in your projects, from frame extraction to final output packaging.

---

## Troubleshooting and Support

- Confirm all dependencies are correctly installed. If issues arise during frame extraction, ensure ffmpeg and ffprobe are correctly installed and recognized by your system's PATH.
- For enhanced support during mask creation or when experiencing performance bottlenecks, enable "Fast Mode."

## Licensing and Contributions

- This project is open-source under the MIT License.
- Contributions via issues or pull requests are highly encouraged to enhance functionality and user experience.
