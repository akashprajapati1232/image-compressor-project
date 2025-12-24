# Image Compressor
---

## Project Information

**Project Title:** Image Compressor  
**Project Type:** Minor Project  
**Course:** Bachelor of Computer Applications (BCA)  
**Semester:** 5th Semester (Odd Semester 2025)  
**Institution:** Bhagwant Institute of Technology, Muzaffarnagar  
**Department:** Computer Science Engineering & Application  

---

## Team Details

### Under the Guidance of:
**Mr. Sawan Kumar**

### Submitted By:
**BCA (5th Sem)**

| Name | Roll Number |
|------|-------------|
| Akash Prajapati | 237092010005 |
| Vivek Yadav | 237092010058 |
| Ajay Kumar | 237092010004 |

---

## Abstract

Image Compressor is a sophisticated browser-based web application designed to compress and optimize images without compromising visual quality. This project demonstrates the practical implementation of client-side image processing technologies, providing users with a privacy-focused, efficient, and user-friendly solution for reducing image file sizes. The application supports multiple image formats including JPG, PNG, JPEG, WEBP, GIF, HEIF/HEIC, ICO, and SVG, making it a versatile tool for various compression needs.

The project emphasizes three core principles:
1. **Privacy & Security** - All image processing happens locally in the browser; images never leave the user's device
2. **Performance & Efficiency** - Advanced algorithms optimize compression while maintaining quality
3. **Accessibility** - No registration required, completely free, and easy to use

---

## Project Objectives

### Primary Objectives
- Develop a client-side image compression tool that processes images entirely in the browser
- Implement multiple compression options (quality-based, dimension-based, and target size-based)
- Ensure user privacy by eliminating server-side image uploads
- Create an intuitive and responsive user interface suitable for all devices
- Support multiple image formats for versatile usage

### Secondary Objectives
- Integrate advanced cropping functionality for image customization
- Provide real-time preview of compressed images
- Display detailed image information (dimensions, file size)
- Implement drag-and-drop functionality for enhanced user experience
- Create comprehensive documentation for academic presentation

---

## Scope of the Project

### Included in Scope
- Browser-based image compression supporting JPG, PNG, JPEG, WEBP, GIF, HEIF/HEIC, ICO, and SVG formats
- Three compression modes:
  - Quality-based compression with adjustable slider (0-100%)
  - Dimension-based resizing with aspect ratio maintenance
  - Target file size compression
- Image cropping functionality using Cropper.js library
- Drag-and-drop file upload interface
- Real-time image preview and comparison
- Download functionality for compressed images
- Fully responsive design for mobile, tablet, and desktop devices
- Privacy-focused architecture with no server dependency

### Future Enhancements (Out of Current Scope)
- Batch image processing for multiple files
- Server-side API development for advanced features
- Before/after visual comparison sliders
- Image format conversion
- Automated unit testing framework
- Integration with cloud storage services

---

## Features

### Core Features
✅ **Multiple Format Support** - Compress JPG, PNG, JPEG, WEBP, GIF, HEIF/HEIC, ICO, and SVG images  
✅ **Flexible Compression Options** - Choose from quality, dimensions, or target size-based compression  
✅ **Image Cropping** - Crop images before compression with interactive cropping tool  
✅ **Privacy-First Approach** - All processing happens in-browser; no server uploads  
✅ **Drag & Drop Interface** - Easy file upload with drag-and-drop support  
✅ **Real-time Preview** - See compressed image before downloading  
✅ **Detailed Image Info** - View dimensions in pixels, mm, and cm, plus file size  
✅ **Responsive Design** - Works seamlessly on all screen sizes  
✅ **No Registration Required** - Use instantly without creating an account  
✅ **Completely Free** - No hidden costs or premium features  

### Advanced Features
- **Smart Compression Algorithms** - Intelligently reduce file size while preserving quality
- **Aspect Ratio Maintenance** - Automatically maintain aspect ratio during dimension changes
- **File Size Validation** - Maximum 10MB file size with user-friendly error messages
- **Modern UI/UX** - Glassmorphism design with smooth animations
- **Cross-browser Compatibility** - Works on Chrome, Firefox, Safari, and Edge

---

## Technology Stack

### Frontend Technologies
- **HTML5** - Semantic markup and structure
- **CSS3** - Modern styling with CSS Grid, Flexbox, and animations
  - Custom CSS variables for theming
  - Responsive design using media queries
  - Glassmorphism effects
- **JavaScript (Vanilla)** - Core application logic
  - Canvas API for image processing
  - File API for file handling
  - Drag and Drop API

### External Libraries
- **Cropper.js** (v1.5.13) - Advanced image cropping functionality
- **libheif.js** (v1.10.0) - HEIF/HEIC format support
- **Font Awesome** (v6.5.1) - Icon library
- **Google Fonts** - Poppins font family

### Development Tools
- **VS Code** - Primary code editor
- **Git** - Version control
- **GitHub** - Code repository hosting
- **Chrome DevTools** - Debugging and testing

---

## Project Structure

```
imagecompressor/
│
├── index.html              # Main application page
├── README.md               # Project documentation (this file)
│
├── css/
│   ├── styles.css          # Main stylesheet
│   ├── responsive.css      # Responsive design rules
│   └── crop.css            # Cropping functionality styles
│
├── js/
│   ├── script.js           # Main application logic
│   └── crop.js             # Image cropping functionality
│
├── assets/
│   ├── logo.svg            # Application logo
│   ├── favicon.svg         # Browser favicon
│   └── Team/               # Team member photos
│
└── pages/
    ├── about-us.html       # About page with team information
    ├── contact-us.html     # Contact information
    ├── privacy-policy.html # Privacy policy
    ├── terms-conditions.html # Terms and conditions
    └── page-template.html  # Template for new pages
```

---

## Installation & Setup

### Prerequisites
- Modern web browser (Chrome 90+, Firefox 88+, Safari 14+, or Edge 90+)
- No additional software installation required

### Method 1: Direct File Opening (Simple Demo)
1. Download or clone the project repository
2. Navigate to the project folder
3. Double-click `index.html` to open in your default browser
4. The application is ready to use!

### Method 2: Local Web Server (Recommended)

#### Using Python 3 (macOS/Linux)
```bash
# Navigate to project directory
cd /path/to/imagecompressor

# Start local server
python3 -m http.server 8000

# Open browser and visit
# http://localhost:8000
```

#### Using Python 3 (Windows)
```bash
# Navigate to project directory
cd C:\path\to\imagecompressor

# Start local server
python -m http.server 8000

# Open browser and visit
# http://localhost:8000
```

#### Using Node.js (http-server)
```bash
# Install http-server globally (one-time)
npm install -g http-server

# Navigate to project directory
cd /path/to/imagecompressor

# Start server
http-server -p 8000

# Open browser and visit
# http://localhost:8000
```

#### Using VS Code Live Server Extension
1. Install "Live Server" extension in VS Code
2. Right-click on `index.html`
3. Select "Open with Live Server"
4. Application opens automatically in browser

---

## Usage Guide

### Basic Workflow

#### Step 1: Upload an Image
- Click the "Choose an Image" button, or
- Drag and drop an image file into the upload area
- Supported formats: JPG, JPEG, PNG, WEBP, GIF, HEIF/HEIC, ICO, SVG
- Maximum file size: 10MB

#### Step 2: Choose Compression Settings
Select one of three compression modes:

**Quality Mode:**
- Adjust the compression slider (0-100%)
- Higher values = better quality, larger file size
- Lower values = more compression, smaller file size

**Dimensions Mode:**
- Enter desired width and/or height in pixels
- Aspect ratio is maintained automatically
- Leave one field empty to auto-calculate

**Target Size Mode:**
- Enter desired file size in KB
- Algorithm automatically adjusts compression to meet target

#### Step 3: Compress Image
- Click the "Compress Image" button
- Wait for processing to complete
- Preview the compressed image

#### Step 4: Download
- Click "Download Compressed Image" button
- File is saved to your default downloads folder
- Click "New Image" to compress another file

### Advanced Features

#### Image Cropping
1. Upload an image
2. Click the crop icon in the preview
3. Select the area you want to keep
4. Apply crop and proceed with compression

#### Viewing Image Details
After uploading, the app displays:
- Dimensions in pixels (px)
- Dimensions in millimeters (mm)
- Dimensions in centimeters (cm)
- Original file size

---

## Testing & Demonstration

### Test Cases for Project Viva

#### Test Case 1: Basic Compression
**Objective:** Compress a large JPEG image  
**Steps:**
1. Upload a 2-3 MB JPEG image
2. Set compression quality to 70%
3. Click "Compress Image"
4. Compare original vs compressed file size

**Expected Result:** File size reduced by 40-60% while maintaining visual quality

#### Test Case 2: Dimension Resizing
**Objective:** Resize image dimensions  
**Steps:**
1. Upload any image
2. Switch to "Dimensions" tab
3. Enter width: 800px (leave height empty)
4. Compress image

**Expected Result:** Image width is 800px, height adjusted proportionally

#### Test Case 3: Target Size Compression
**Objective:** Compress to specific file size  
**Steps:**
1. Upload a 1 MB image
2. Switch to "Target Size" tab
3. Enter target size: 200 KB
4. Compress image

**Expected Result:** Compressed file size is approximately 200 KB (±10%)

#### Test Case 4: Image Cropping
**Objective:** Crop and compress an image  
**Steps:**
1. Upload any image
2. Use crop tool to select a region
3. Apply crop
4. Compress the cropped image

**Expected Result:** Only selected region is compressed and downloaded

#### Test Case 5: Format Support
**Objective:** Test multiple image formats  
**Steps:**
1. Test with JPG, PNG, WEBP, and GIF files
2. Compress each format

**Expected Result:** All formats compress successfully

#### Test Case 6: Privacy Verification
**Objective:** Verify no server upload  
**Steps:**
1. Open browser developer tools (Network tab)
2. Upload and compress an image
3. Check network requests

**Expected Result:** No POST/PUT requests to external servers; all processing is local

---

## Project Methodology

### Development Approach
The project follows an iterative development methodology:

1. **Requirement Analysis** - Identified user needs for image compression
2. **Design Phase** - Created wireframes and UI mockups
3. **Implementation** - Developed features incrementally
4. **Testing** - Conducted thorough testing for each feature
5. **Documentation** - Prepared comprehensive documentation

### Algorithm Overview

#### Compression Algorithm
```
1. Load image file using File API
2. Create Image object and load file data
3. Draw image on HTML5 Canvas
4. Apply user-selected settings:
   - For quality mode: Use canvas.toDataURL() with quality parameter
   - For dimension mode: Resize canvas, then compress
   - For target size mode: Binary search for optimal quality
5. Convert canvas to Blob
6. Provide download link for compressed image
```

#### Target Size Algorithm (Binary Search)
```
1. Set initial quality range: min=0, max=100
2. While (not within target ±5%):
   a. Test quality = (min + max) / 2
   b. Compress with test quality
   c. If size > target: max = test quality
   d. If size < target: min = test quality
   e. Repeat until target reached or max iterations
3. Return best result
```

---

## Limitations & Constraints

### Current Limitations
- **File Size Limit:** Maximum 10MB per image (browser memory constraint)
- **Format Support:** HEIF/HEIC support depends on browser compatibility
- **Batch Processing:** Only one image at a time
- **Browser Dependency:** Requires modern browser with HTML5 Canvas support
- **Memory Usage:** Very large images may cause performance issues on low-end devices

### Browser Compatibility
- ✅ Chrome 90+ (Fully supported)
- ✅ Firefox 88+ (Fully supported)
- ✅ Safari 14+ (Fully supported, HEIF/HEIC may vary)
- ✅ Edge 90+ (Fully supported)
- ❌ Internet Explorer (Not supported)

---

## Security & Privacy

### Privacy Measures
- **Zero Server Upload:** All processing happens in the browser
- **No Data Collection:** No user data, images, or analytics collected
- **No Cookies:** Application does not use cookies
- **No Registration:** No personal information required
- **Local Processing:** Images never leave user's device

### Security Features
- **File Type Validation:** Only approved image formats accepted
- **Size Validation:** Maximum file size enforced
- **Client-Side Only:** No external API calls for image processing
- **HTTPS Recommended:** For deployment, HTTPS ensures secure connection

---

## Learning Outcomes

### Technical Skills Gained
- **HTML5 APIs:** Canvas API, File API, Drag and Drop API
- **JavaScript:** Asynchronous programming, event handling, DOM manipulation
- **CSS3:** Advanced styling, animations, responsive design
- **Image Processing:** Compression algorithms, format conversion, quality optimization
- **Web Development:** Modern web development practices and patterns

### Soft Skills Developed
- **Teamwork:** Collaborated with team members on different modules
- **Problem Solving:** Debugged complex issues with image processing
- **Project Management:** Planned and executed project timeline
- **Documentation:** Created comprehensive technical documentation
- **Presentation:** Prepared project for academic demonstration

---

## Acknowledgements

We would like to express our sincere gratitude to:

- **Mr. Sawan Kumar** - Our project guide, for his invaluable guidance, support, and mentorship throughout this project
- **Department of Computer Science Engineering & Application** - For providing resources and infrastructure
- **Bhagwant Institute of Technology, Muzaffarnagar** - For the opportunity to work on this minor project
- **Faculty Members** - For their feedback and suggestions during development
- **Classmates** - For testing the application and providing valuable feedback
- **Open Source Community** - For libraries and tools that made this project possible

---

## References

### Technical Documentation
1. MDN Web Docs - HTML5 Canvas API  
   https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API

2. MDN Web Docs - File API  
   https://developer.mozilla.org/en-US/docs/Web/API/File_API

3. Cropper.js Documentation  
   https://github.com/fengyuanchen/cropperjs

4. Image Compression Algorithms - Research Papers  
   Various academic papers on lossy and lossless compression

### Learning Resources
1. W3Schools - JavaScript Tutorial
2. CSS-Tricks - Modern CSS Techniques
3. JavaScript.info - Modern JavaScript Tutorial
4. Stack Overflow - Community Support

---

## Future Enhancements

### Planned Features
- **Batch Processing:** Compress multiple images simultaneously
- **Format Conversion:** Convert between different image formats
- **Advanced Filters:** Apply filters and effects before compression
- **Cloud Integration:** Optional cloud storage integration
- **Progressive Web App:** Install as standalone app
- **Comparison View:** Side-by-side before/after comparison
- **Compression History:** Keep track of recent compressions
- **Preset Profiles:** Quick compression profiles (Web, Social Media, Print, etc.)

### Scalability Considerations
- Implement Web Workers for better performance
- Add service workers for offline functionality
- Optimize algorithms for faster processing
- Implement lazy loading for better initial load times

---

## License

This project is developed as an academic assignment for BCA 5th Semester Minor Project.  
© 2025 Image Compressor - Developed by Akash Prajapati, Vivek Yadav, and Ajay Kumar

For academic and educational purposes only.

---

## Contact Information

### Team Members

**Akash Prajapati** (237092010005)  
GitHub: [@akashprajapati1232](https://github.com/akashprajapati1232)

**Vivek Yadav** (237092010058)

**Ajay Kumar** (237092010004)

### Institution
**Bhagwant Institute of Technology**  
Muzaffarnagar, Uttar Pradesh, India  
Department of Computer Science Engineering & Application

---

## Project Status

✅ **Status:** Completed and Ready for Submission  
📅 **Submission Date:** December 2025  
🎓 **Academic Year:** 2024-2025 (Odd Semester)

---

**Note:** This README serves as comprehensive documentation for the IMAGE COMPRESSORject, submitted as a BCA 5th Semester Minor Project at Bhagwant Institute of Technology, Muzaffarnagar.
