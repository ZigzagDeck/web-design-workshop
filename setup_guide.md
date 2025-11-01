# Web Design Workshop - Complete Setup Guide

## Step 1: Create Local Repository

1. **Create main folder:**
   ```bash
   mkdir web-design-workshop
   cd web-design-workshop
   ```

2. **Create folder structure:**
   ```bash
   mkdir experiment-01-bookstore-home
   mkdir experiment-02-login
   mkdir experiment-03-catalogue
   mkdir experiment-04-cart
   mkdir experiment-05-registration
   mkdir experiment-06-name-password-validation
   mkdir experiment-07-email-phone-validation
   mkdir experiment-08-css-styling
   mkdir experiment-09-css-links
   mkdir experiment-10-portfolio
   ```

## Step 2: Add Files to Each Experiment

### Experiment 01 - Bookstore Home
Create three files in `experiment-01-bookstore-home/`:
- `index.html` (with frameset)
- `top.html` (header with navigation)
- `left.html` (sidebar with categories)
- `main.html` (main content area)

### Experiment 02 - Login Page
Create in `experiment-02-login/`:
- `login.html`

### Experiment 03 - Catalogue Page
Create in `experiment-03-catalogue/`:
- `catalogue.html`

### Experiment 04 - Cart Page
Create in `experiment-04-cart/`:
- `cart.html`

### Experiment 05 - Registration Form
Create in `experiment-05-registration/`:
- `registration.html`

### Experiment 06 - Name & Password Validation
Create in `experiment-06-name-password-validation/`:
- `validation1.html`

### Experiment 07 - Email & Phone Validation
Create in `experiment-07-email-phone-validation/`:
- `validation2.html`

### Experiment 08 - CSS Styling
Create in `experiment-08-css-styling/`:
- `css-demo.html`

### Experiment 09 - CSS Links
Create in `experiment-09-css-links/`:
- `links-demo.html`

### Experiment 10 - Portfolio
Create in `experiment-10-portfolio/`:
- `index.html`

## Step 3: Initialize Git Repository

```bash
# Initialize git
git init

# Create README.md (copy content from first artifact)
# Create .gitignore file
echo "*.DS_Store" > .gitignore
echo "node_modules/" >> .gitignore

# Add all files
git add .

# Make initial commit
git commit -m "Initial commit: Web Design Workshop experiments"
```

## Step 4: Push to GitHub

1. **Create a new repository on GitHub:**
   - Go to https://github.com/new
   - Name: `web-design-workshop`
   - Don't initialize with README (we already have one)
   - Click "Create repository"

2. **Link and push:**
   ```bash
   git remote add origin https://github.com/YOUR_USERNAME/web-design-workshop.git
   git branch -M main
   git push -u origin main
   ```

## Step 5: Test Your Website

Open any HTML file in a browser:
- Navigate to any experiment folder
- Double-click the `.html` file
- It will open in your default browser

## Quick Reference - All Files Needed

```
web-design-workshop/
│
├── README.md
├── .gitignore
│
├── experiment-01-bookstore-home/
│   ├── index.html
│   ├── top.html
│   ├── left.html
│   └── main.html
│
├── experiment-02-login/
│   └── login.html
│
├── experiment-03-catalogue/
│   └── catalogue.html
│
├── experiment-04-cart/
│   └── cart.html
│
├── experiment-05-registration/
│   └── registration.html
│
├── experiment-06-name-password-validation/
│   └── validation1.html
│
├── experiment-07-email-phone-validation/
│   └── validation2.html
│
├── experiment-08-css-styling/
│   └── css-demo.html
│
├── experiment-09-css-links/
│   └── links-demo.html
│
└── experiment-10-portfolio/
    └── index.html
```

## Features of Each Experiment

1. **Bookstore Home** - Frame-based layout (Header, Sidebar, Main)
2. **Login** - Simple login form with styling
3. **Catalogue** - Grid of books with add to cart buttons
4. **Cart** - Shopping cart table with total
5. **Registration** - Complete form with all input types
6. **Validation 1** - JS validation for name & password
7. **Validation 2** - JS validation for email & phone
8. **CSS Styling** - Fonts, colors, background images
9. **CSS Links** - All link states (link, visited, hover, active)
10. **Portfolio** - Complete portfolio with smooth scroll

## Tips for Beginners

- All code is self-contained (no external dependencies)
- Use inline CSS and JavaScript for simplicity
- Comments are included for learning
- Code follows basic, readable patterns
- No frameworks or build tools needed

## Testing Checklist

- [ ] All HTML files open without errors
- [ ] Forms display correctly
- [ ] JavaScript validations work
- [ ] CSS styles apply properly
- [ ] Links navigate correctly
- [ ] Repository pushed to GitHub successfully

---

**Happy Coding! 🚀**