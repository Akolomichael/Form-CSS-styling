# Registration Form – CSS Styling Assignment

## Objective
This project implements a **styled registration form** using HTML5 form elements and modern CSS.  
The purpose is to demonstrate comprehensive CSS knowledge including typography, layout, form element styling, interactive states, and responsiveness.

---

## Project Structure
Form CSS styling/
├── index.html # Main registration form
├── style.css # Stylesheet for form design
└── README.md # Documentation

---

## Form Structure (HTML)
The form is organized into multiple `<fieldset>` sections with descriptive `<legend>` headings:

1. **Personal Information**
   - First name, Last name, Age
   - Gender (radio buttons)
   - Profile photo upload

2. **Contact Address and Information**
   - Email, Phone number, Personal website
   - Street address, City, Country (dropdown)
   - ZIP/Postal code
   - Preferred contact time

3. **Preferences & Interests**
   - Favorite color (color picker)
   - Experience level (range slider)
   - Birth month, Available week
   - Search keywords
   - Interests (checkboxes)
   - Education level (dropdown)
   - Password and Confirm password

4. **Feedback & Additional Information**
   - About yourself (textarea)
   - Suggestions for improvement
   - Resume upload
   - Newsletter subscription
   - Terms & Conditions / Privacy Policy agreement

5. **Form Actions**
   - **Register (Submit button)**
   - **Clear Form (Reset button)**

---

##  Styling (CSS)

### Global Styles
- Font: `'Segoe UI', Tahoma, Geneva, Verdana, sans-serif`
- Background: `#f9fafb`
- Base text color: `#1f2937`
- Form centered with **max-width 600px**, white background, padding, rounded corners, and subtle box-shadow.

### Typography
- Title (`<h1>`):  
  - Center-aligned  
  - Size: `1.8rem`  
  - Color: `#1e40af` (Primary Dark)  
- Labels:  
  - Block display  
  - Slight margin for spacing  
  - Color: `#1f2937`

### Fieldsets & Legends
- Fieldset: light gray border (`#d1d5db`), rounded corners, background `#f9fafb`
- Legend: bold, `1.1rem`, primary blue `#2563eb`

### Inputs, Selects & Textareas
- Full-width with padding and rounded corners
- Border: `1px solid #d1d5db`
- Placeholder text styled in `#6b7280` (light gray, italic)
- **Focus state**: border changes to `#2563eb`, glowing box-shadow

### Special Inputs
- **Range slider:** custom track + circular thumb styled in primary blue  
- **Color picker:** height adjusted to `44px`  
- **Checkboxes & radios:** styled with spacing and aligned labels  

### Buttons
- Base button: padded, rounded, bold text, transition effects  
- **Submit button:**  
  - Default: `#2563eb` (Primary Blue)  
  - Hover: `#1e40af` (Primary Dark)  
  - Active: `#3b82f6` (Primary Light, pressed)  
- **Reset button:**  
  - Default: `#6b7280` (Neutral Gray)  
  - Hover: `#4b5563`  
  - Active: `#374151`  
- **Accent options**: Purple and Pink button classes (`.btn-accent`, `.btn-accent-pink`)  
- Disabled state: muted gray background, reduced opacity, `cursor: not-allowed`

---

##  Color Palette
- **Primary Blue:** `#2563eb`  
- **Primary Dark:** `#1e40af`  
- **Primary Light:** `#3b82f6`  
- **Neutral Background:** `#f9fafb`  
- **White:** `#ffffff`  
- **Text Dark:** `#1f2937`  
- **Text Light:** `#6b7280`  
- **Border:** `#d1d5db`  
- **Accent Purple:** `#8b5cf6`  
- **Accent Pink:** `#ec4899`  

---

## Interactive States
- **Focus states:** inputs glow with blue border and shadow  
- **Hover states:** buttons darken smoothly  
- **Active states:** buttons shrink slightly with lighter color  
- **Disabled states:** gray-out with reduced opacity  

---

## 📱 Responsive Design
- Media query for screens `<640px`:
  - Form padding reduced  
  - Title font size reduced  
  - Buttons expand to full width with spacing  

---

## ⚙️ Features Demonstrated
- CSS box model: padding, margins, borders, width  
- Rounded corners with `border-radius`  
- Shadows for elevation  
- Transition effects for smooth state changes  
- Pseudo-classes: `:hover`, `:focus`, `:active`, `:disabled`  
- Custom styling of range sliders, file inputs, and color pickers  
- Responsive design with media queries  

---

##  How to Run
1. Clone/download the repository  
2. Open `index.html` in a browser  
3. Ensure `style.css` is linked in the `<head>` of your HTML:
   ```html
   <link rel="stylesheet" href="style.css">
   # author
   ## Michael Akolo
