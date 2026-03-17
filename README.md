# CGPA Studio

A beautiful, interactive CGPA calculator that allows students to track their academic performance across multiple semesters, combine previous GPA data, and export results as PNG images.

![CGPA Studio Screenshot](https://via.placeholder.com/800x450?text=CGPA+Studio+Preview)

## ✨ Features

- **📚 Semester-Based Tracking** - Organize courses by semesters with customizable names
- **📊 Percentage to GPA Conversion** - Automatic conversion using standard 5.0 scale (70-100 → 5.0, 60-69 → 4.0, etc.)
- **🧮 Cumulative CGPA Calculation** - Combines all semesters with optional previous GPA data
- **📸 Export as PNG** - Save your CGPA results as high-resolution images for sharing or records
- **🎨 Modern UI/UX** - Glass-morphism design with smooth animations, hover effects, and micro-interactions
- **📱 Fully Responsive** - Optimized for mobile, tablet, and desktop screens
- **🔄 Real-time Updates** - CGPA recalculates as you enter data
- **⚡ Quick Actions** - Add/remove courses and semesters with one click

## 🎯 How It Works

1. **Enter Course Data**: For each course, input:
   - Course name
   - Credit hours (supports 0.5 increments)
   - Percentage score (0-100)

2. **Manage Semesters**: 
   - Add new semesters using the "New sem" button
   - Rename semesters by clicking on the title
   - Add or remove courses within each semester

3. **Include Previous GPA** (Optional):
   - Enter your previous cumulative GPA
   - Enter total credits earned so far
   - The calculator will combine with current semester data

4. **View Results**:
   - Cumulative CGPA (3 decimal places)
   - Total credits counted
   - Updates automatically or click "update CGPA"

5. **Export**: Click "Save as PNG" to capture the entire calculator as an image

## 📈 GPA Conversion Scale

| Percentage Range | Grade Point |
|------------------|-------------|
| 70 - 100 | 5.0 (A) |
| 60 - 69 | 4.0 (B) |
| 50 - 59 | 3.0 (C) |
| 45 - 49 | 2.0 (D) |
| 40 - 44 | 1.0 (E) |
| 0 - 39 | 0.0 (F) |

## 🚀 Getting Started

### Option 1: Direct Usage
1. Download the `index.html` file
2. Open it in any modern web browser (Chrome, Firefox, Safari, Edge)
3. Start adding your courses!

### Option 2: Host Your Own
Simply upload the HTML file to any web server or hosting service. No build process or dependencies required (except html2canvas loaded via CDN).

## 🛠️ Technical Details

- **Pure HTML/CSS/JavaScript** - No frameworks or build tools needed
- **html2canvas** - Used for PNG export functionality (loaded via CDN)
- **CSS Features**:
  - Glass-morphism effects with backdrop-filter
  - Flexbox for responsive layouts
  - CSS animations and transitions
  - Media queries for mobile optimization

## 📱 Responsive Breakpoints

- **Desktop**: Full layout with horizontal course rows
- **Tablet**: Adjusted spacing and font sizes
- **Mobile (<600px)**: Stacked course cards, compact buttons
- **Small mobile (<380px)**: Further optimized touch targets

## 🎨 UI/UX Highlights

- **Floating Header Animation**: Subtle hover effect on main title
- **Card Lift Effects**: Semester cards rise on hover
- **Button Feedback**: Scale animations on click
- **Smooth Transitions**: All interactive elements have gentle transitions
- **Visual Hierarchy**: Clear separation between sections
- **Color Coding**: Grade scale uses distinct colors for easy reference

## 📋 Use Cases

- **University Students**: Track semester-by-semester progress
- **Academic Advisors**: Help students project future GPA scenarios
- **Self-Study Learners**: Monitor performance across multiple courses
- **Scholarship Applications**: Calculate and save proof of academic standing

## 🔧 Customization Options

You can easily modify:
- **GPA Scale**: Edit the `percentageToGPA()` function in JavaScript
- **Color Scheme**: Update CSS variables and gradients
- **Default Data**: Change the `getDefaultSemesters()` function
- **Export Quality**: Adjust the `scale` parameter in html2canvas options

## 🌟 Why CGPA Studio?

- **No Installation Required**: Works directly in browser
- **Privacy-Focused**: All data stays on your device
- **Visual Feedback**: See results update in real-time
- **Portable Results**: Save as images for records or sharing
- **Student-Friendly**: Intuitive interface designed for quick data entry

## 📝 License

Free to use for personal and educational purposes. Attribution appreciated but not required.

---

**Made with ❤️ for students everywhere**
