# QR Code Scanner

A modern, responsive web application for scanning QR codes using your device's camera or by uploading images. Built with vanilla JavaScript and the powerful `html5-qrcode` library.

## ScreenShots
![image](https://github.com/user-attachments/assets/a594d1bc-8491-4815-9458-1570d230472f)
![image](https://github.com/user-attachments/assets/2709ce1b-3680-478e-b5b2-d5c505b0fe77)


## 🌟 Features

- **Camera Scanning**: Real-time QR code scanning using your device's camera
- **Image Upload**: Upload and decode QR codes from image files
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **User-Friendly Interface**: Clean, intuitive UI with clear feedback
- **Cross-Platform**: Works in all modern browsers

## 🚀 Live Demo

Visit the live application: [QR Code Scanner](https://manneudaykiran.github.io/QR-Code-Generator/)

## 📱 Screenshots

- Camera scanning interface
- Image upload functionality
- Real-time QR code detection
- Clean, modern UI design

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling and responsive design
- **JavaScript (ES6+)**: Interactive functionality
- **html5-qrcode**: Powerful QR code scanning library

## 📋 Prerequisites

- Modern web browser with camera access
- HTTPS connection (required for camera access in most browsers)
- No additional installations needed!

## 🎯 Usage

### Camera Scanning
1. Open the application in your browser
2. Click "Start Camera Scan" button
3. Allow camera permissions when prompted
4. Point your camera at a QR code
5. The decoded text will appear automatically

### Image Upload
1. Click "Choose File" or drag an image
2. Select an image containing a QR code
3. The application will automatically decode and display the result

## 🔧 Installation & Setup

### Option 1: Direct Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/ManneUdayKiran/QR-Code-Generator.git
   ```
2. Navigate to the project directory:
   ```bash
   cd QR-Code-Generator
   ```
3. Open `index.html` in your web browser

### Option 2: Local Server (Recommended)
For better camera access, serve the files using a local server:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server

# Using PHP
php -S localhost:8000
```

Then visit `http://localhost:8000` in your browser.

## 📁 Project Structure

```
QR-Code-Generator/
├── index.html          # Main application file
├── README.md          # Project documentation
└── .gitignore         # Git ignore file
```

## 🔒 Browser Compatibility

- ✅ Chrome (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ⚠️ Internet Explorer (not supported)

## 🎨 Customization

### Styling
The application uses CSS for styling. You can customize the appearance by modifying the `<style>` section in `index.html`.

### Features
- Change camera settings in the `html5QrCode.start()` configuration
- Modify the QR box size and FPS for different scanning experiences
- Add additional error handling and user feedback

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

**Uday Kiran Manne**
- GitHub: [@ManneUdayKiran](https://github.com/ManneUdayKiran)

## 🙏 Acknowledgments

- [html5-qrcode](https://github.com/mebjas/html5-qrcode) library for QR code scanning capabilities
- Modern web standards for camera access and file handling

## 📞 Support

If you encounter any issues or have questions:
1. Check the [Issues](https://github.com/ManneUdayKiran/QR-Code-Generator/issues) page
2. Create a new issue with detailed information
3. Include browser version and device information

---

⭐ **Star this repository if you find it helpful!** 
