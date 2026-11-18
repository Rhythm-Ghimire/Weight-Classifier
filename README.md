# BMI Calculator (Weight Classifier)

A responsive single-page BMI calculator. Enter your age, gender, height, and weight to get your Body Mass Index and the weight category it falls in.

**Tech stack:** HTML, CSS, JavaScript (no frameworks or build step)

## Features

- Calculates BMI from height (cm) and weight (kg).
- Classifies the result using standard BMI ranges.
- Validates that every field is filled in and shows a pop-up message if not.
- Page sections for About, Calculator, Contact, and Social Media with smooth navigation.

## BMI categories

| BMI | Category |
|---|---|
| below 18.5 | Underweight |
| 18.5 – 24.9 | Healthy |
| 25 – 29.9 | Overweight |
| 30 – 34.9 | Obese |
| 35 and above | Extremely obese |

Formula: `BMI = weight (kg) / height (m)²`

> BMI is a general screening measure and not a medical diagnosis. Talk to a health professional for personal advice.

## Project structure

```
index.html   Page layout and form
style.css    Styling
script.js    Validation, BMI calculation, and result display
```

## Running it

No installation is needed. Download or clone the repo and open `index.html` in a browser.

```bash
git clone https://github.com/Rhythm-Ghimire/Weight-Classifier.git
cd Weight-Classifier
# then open index.html in your browser
```

## Author

**Rhythm Kashyap Ghimire**
[GitHub](https://github.com/Rhythm-Ghimire)
