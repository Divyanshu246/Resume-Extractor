# 📧 Resume Contact Extractor

A powerful, full-stack web application that automatically extracts email addresses and phone numbers from resume files and exports them to Excel format. Built with modern web technologies and featuring a sleek, responsive user interface.

![Screenshot 2025-05-27 224508](https://github.com/user-attachments/assets/7edebdd6-40ef-4c21-8818-f7580183ea68)

![Screenshot 2025-05-27 224525](https://github.com/user-attachments/assets/5893153f-0a96-44ef-a112-71cd40295746)

## ✨ Features

### 🚀 Core Functionality
- **Smart Contact Extraction**: Advanced regex patterns to detect emails and phone numbers
- **Multiple File Format Support**: PDF, DOC, DOCX, and TXT files
- **Excel Export**: One-click export to professional Excel spreadsheets
- **Duplicate Detection**: Automatically removes duplicate entries
- **Real-time Processing**: Instant feedback with loading indicators

### 🎨 User Experience
- **Drag & Drop Interface**: Intuitive file upload with drag-and-drop support
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI**: Glass-morphism effects, smooth animations, and gradient backgrounds
- **Interactive Elements**: Hover effects and smooth transitions
- **Error Handling**: Comprehensive validation and user-friendly error messages

### 📊 Data Visualization
- **Statistics Dashboard**: Real-time counts of extracted contacts
- **Organized Display**: Separate cards for emails and phone numbers
- **Data Table**: Professional table view with sorting capabilities
- **Export Preview**: Review data before exporting

## 🛠️ Technology Stack

### Frontend
- **HTML5**: Semantic markup and modern web standards
- **CSS3**: Advanced styling with flexbox, grid, and animations
- **JavaScript (ES6+)**: Modern JavaScript with async/await and DOM manipulation

### Libraries & Dependencies
- **XLSX.js**: Excel file generation and manipulation
- **Mammoth.js**: Word document (.docx) text extraction
- **Font Awesome Icons**: Beautiful iconography (via Unicode)

## 📋 Requirements
### File Format Support
- **PDF**: Portable Document Format (with text layer)
- **DOC/DOCX**: Microsoft Word documents
- **TXT**: Plain text files

## 🚀 Quick Start

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/resume-contact-extractor.git
cd resume-contact-extractor
```

### 2. Open in Browser
```bash
# Simply open the index.html file in your web browser
open index.html
# or
python -m http.server 8000  # For local development server
```

### 3. Start Extracting
1. Open the application in your browser
2. Upload a resume file (drag & drop or click to browse)
3. Wait for automatic processing
4. Review extracted contacts
5. Export to Excel format

## 📖 Usage Guide

### Uploading Files
1. **Drag & Drop**: Simply drag your resume file onto the upload area
2. **File Browser**: Click "Choose File" to select from your computer
3. **Supported Formats**: PDF, DOC, DOCX, TXT (max 10MB recommended)

### Viewing Results
- **Statistics**: View total count of emails and phone numbers found
- **Contact Cards**: Browse extracted information in organized cards
- **Data Table**: See all contacts in a professional table format

### Exporting Data
1. Click the "Export to Excel" button
2. File automatically downloads with timestamp
3. Open in Excel, Google Sheets, or any spreadsheet application

## 🔧 Customization

### Regex Patterns
The application uses advanced regex patterns for contact extraction:

```javascript
// Email Pattern
const emailRegex = /\b[A-Za-z0-9._%+-]+@[A-Za-z0-9.-]+\.[A-Z|a-z]{2,}\b/g;

// Phone Pattern (US Format)
const phoneRegex = /(\+?1[-.\s]?)?(\(?[0-9]{3}\)?[-.\s]?[0-9]{3}[-.\s]?[0-9]{4}|\b[0-9]{3}[-.\s]?[0-9]{3}[-.\s]?[0-9]{4}\b)/g;
```

### Styling Customization
Modify the CSS variables in the `<style>` section to customize colors and themes:

```css
:root {
  --primary-gradient: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  --success-color: #28a745;
  --border-radius: 15px;
}
```

## 🧪 Testing

### Manual Testing Checklist
- [ ] File upload (drag & drop)
- [ ] File upload (click to browse)
- [ ] PDF text extraction
- [ ] Word document processing
- [ ] Email detection accuracy
- [ ] Phone number detection
- [ ] Excel export functionality
- [ ] Responsive design on mobile
- [ ] Error handling for invalid files

### Test Files
Include sample resume files in your testing:
- `sample-resume.pdf`
- `sample-resume.docx`
- `sample-resume.txt`

## 🤝 Contributing

We welcome contributions! Please follow these steps:

1. **Fork the Repository**
2. **Create a Feature Branch**
   ```bash
   git checkout -b feature/amazing-feature
   ```
3. **Commit Changes**
   ```bash
   git commit -m 'Add amazing feature'
   ```
4. **Push to Branch**
   ```bash
   git push origin feature/amazing-feature
   ```
5. **Open a Pull Request**

### Contribution Guidelines
- Follow existing code style and formatting
- Add comments for complex logic
- Test thoroughly before submitting
- Update documentation as needed

## 🐛 Known Issues & Limitations

### Current Limitations
- **PDF Processing**: Currently uses simulated extraction (requires PDF.js integration for full functionality)
- **File Size**: Recommended maximum file size is 10MB for optimal performance
- **Browser Storage**: Uses in-memory storage only (no persistent data)

### Planned Improvements
- [ ] Full PDF text extraction integration
- [ ] Batch file processing
- [ ] Advanced contact validation
- [ ] Multiple export formats (CSV, JSON)
- [ ] Contact deduplication improvements
- [ ] Cloud storage integration

## 🙏 Acknowledgments

- **XLSX.js**: Amazing library for Excel file generation
- **Mammoth.js**: Excellent Word document processing
- **Font Awesome**: Beautiful icons and symbols
- **MDN Web Docs**: Comprehensive web development resources


**[⬆ Back to Top](#-resume-contact-extractor)**

Made with ❤️ by Divyanshu Bisht

</div>
