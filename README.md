# CV & Resume Builder

A professional, free, and open-source resume and cover letter builder with split-screen editing, modern templates, and real-time live preview.

## 🚀 Features

* **Real-Time Live Preview**: See your changes instantly as you type.
* **Multiple Professional Templates**: Choose from a variety of ATS-friendly designs (Modern, Professional, Minimalist, Creative, Executive, Tech, Single Column).
* **Cover Letter Builder**: Includes a rich text editor for crafting the perfect cover letter.
* **Advanced Customization**:
  * Adjust page margins dynamically (10mm - 30mm) directly from the preview or editor.
  * Select page formats (A4, US Letter).
  * Customize typography (font family, font size).
  * Change theme colors.
* **Dark Mode Support**: Fully optimized for both light and dark mode environments.
* **Zoom Controls**: Zoom in, zoom out, or fit the preview to your screen for detailed editing.
* **Export to PDF**: Easily print or save your resume as a PDF using the browser's native print functionality.
* **Responsive Design**: Works beautifully across different screen sizes.

## 🛠️ Tech Stack

* **Frontend Framework**: [React 19](https://react.dev/)
* **Build Tool**: [Vite](https://vitejs.dev/)
* **Styling**: [Tailwind CSS](https://tailwindcss.com/)
* **Icons**: [Lucide React](https://lucide.dev/)
* **Language**: [TypeScript](https://www.typescriptlang.org/)

## 📂 Project Structure

```text
├── components/
│   ├── BuilderPage.tsx       # Main builder interface (split-screen)
│   ├── ResumeEditor.tsx      # Form inputs for resume data
│   ├── CoverLetterEditor.tsx # Form inputs for cover letter
│   ├── ResumePreview.tsx     # Live preview rendering
│   ├── ResumeTemplates.tsx   # Collection of resume designs
│   ├── RichTextEditor.tsx    # WYSIWYG editor for cover letters
│   └── ...                   # Other UI components (Navbar, LandingPage, etc.)
├── types.ts                  # TypeScript interfaces and default data
├── App.tsx                   # Main application routing/state
├── main.tsx                  # React entry point
├── index.css                 # Global styles and Tailwind directives
└── package.json              # Project dependencies
```

## 💻 Getting Started

### Prerequisites

Ensure you have [Node.js](https://nodejs.org/) installed on your machine.

### Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. Open your browser and navigate to the local development URL provided by Vite (usually `http://localhost:5173` or `http://localhost:3000`).

## 📝 Usage Guide

1. **Choose a Template**: Start by selecting a template that fits your industry and style.
2. **Fill in Details**: Use the left panel to input your personal information, experience, education, skills, and projects.
3. **Customize Layout**: Go to the "Theme & Layout" section to adjust colors, fonts, margins, and page format (A4/Letter).
4. **Write a Cover Letter**: Switch to the Cover Letter tab to draft a personalized letter using the built-in rich text editor.
5. **Download/Print**: Once satisfied, click the "Download PDF" or "Print" button to save your document.

## 🤝 Contributing

Contributions are welcome! If you have ideas for new templates, features, or bug fixes:
1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.

## 📄 License

This project is open-source and available under the MIT License.
