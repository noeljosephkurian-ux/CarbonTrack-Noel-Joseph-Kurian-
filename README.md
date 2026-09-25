# CarbonTrack — Personal Carbon Footprint Calculator

## Project Overview

CarbonTrack is a web-based personal carbon footprint calculator designed to help users understand how their everyday activities contribute to carbon emissions.

The calculator allows users to enter information across five major categories:

- Food
- Transportation
- Electricity
- Waste
- General Consumption

Based on the entered information, the website provides an estimated carbon footprint, identifies the category contributing the most emissions, and provides suggestions to help users make more environmentally responsible choices.

The project is developed as an educational sustainability project using basic web technologies and simplified emission factors.

---

## Main Features

### 1. Personal Carbon Footprint Calculator

Users can enter lifestyle and consumption information across different environmental categories.

The calculator processes the entered data and estimates the user's carbon emissions in terms of **kg CO₂e**.

### 2. Five Environmental Categories

The calculator covers:

- **Food** — Estimates emissions associated with different food consumption habits.
- **Transportation** — Considers travel-related activities and modes of transport.
- **Electricity** — Estimates emissions based on electricity usage.
- **Waste** — Considers general waste generation and disposal.
- **Consumption** — Represents emissions associated with general purchasing and consumption habits.

### 3. Category-wise Results

After completing the calculator, users can view their estimated emissions for each category.

This makes it easier to understand which areas of their lifestyle contribute most to their overall carbon footprint.

### 4. Biggest Contributor Identification

CarbonTrack identifies the category with the highest estimated emissions and highlights it to the user.

This helps users focus their efforts on the area where changes could have the greatest potential impact.

### 5. Suggestions and Recommendations

The results page provides practical suggestions based on the calculated footprint.

These suggestions are intended to encourage more sustainable everyday choices.

### 6. "What If?" Scenarios

Users can explore possible changes to their lifestyle and see how those changes could affect their estimated carbon footprint.

This helps demonstrate the potential environmental impact of individual choices.

### 7. Responsive Design

The website is designed to work across different screen sizes, including:

- Desktop computers
- Laptops
- Tablets
- Mobile devices

### 8. Light and Dark Mode

The website includes both light and dark display modes to improve usability and provide users with a choice of interface appearance.

---

## Technologies Used

- **HTML5** — Used to create the structure and content of the website.
- **CSS3** — Used for styling, layout, responsive design and visual appearance.
- **JavaScript** — Used for calculator logic, user interaction, calculations, results and dynamic content.

No external backend or database is required.

---

## Project Structure

```text
CarbonTrack/
│
├── index.html
├── css/
|   └── style.css
├── js/
|   └── app.js
|   └── emissions.css
├── Documents/
│   └── CarbonTrack PPT.pptx
│   └── CarbonTrack_Final.pdf
│
└── README.md
```
## How to Run

### Method 1 — Open Directly
1. Download or clone the repository.
2. Extract the project files if downloaded as a ZIP.
3. Open index.html in a web browser.
4. The website can be used directly without installing any additional software.

### Method 2 — Using GitHub
1. Open the project repository.
2. Download the repository using Code → Download ZIP.
3. Extract the ZIP file.
4. Open index.html in a browser.

No Node.js, database, or server installation is required.

---

## How the Calculator Works
The calculator follows a simple process:
```text
User Input
    ↓
Activity Data
    ↓
Emission Factor
    ↓
Carbon Emission Calculation
    ↓
Category-wise Results
    ↓
Total Carbon Footprint
    ↓
Biggest Contributor
    ↓
Suggestions / What-If Scenarios
```
The basic calculation principle used by the project is:
```text
Carbon Emissions = Activity Data × Emission Factor
```
The calculated values from the different categories are combined to produce an estimated overall carbon footprint.
