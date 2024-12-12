# [VRT Calculator - Visit NOW](http://vatcalc.irish)

A user-friendly web application designed to help vehicle owners in Ireland estimate their Vehicle Registration Tax (VRT) based on various vehicle attributes. Whether you're purchasing a new vehicle or reassessing your current one, this tool provides accurate VRT calculations tailored to your vehicle's specifications.

![Screenshot of Irish VRT Calculator Main Page](https://github.com/VRT-Calculator/.github/blob/main/screen01.png)
![Screenshot of Irish VRT Calculator Result Page](https://github.com/VRT-Calculator/.github/blob/main/screen02.png)

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [How It Works](#how-it-works)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Project Overview

The **Irish VRT Calculator** is a web-based tool designed to help vehicle owners in Ireland calculate their Vehicle Registration Tax (VRT) effortlessly. By inputting various vehicle attributes such as value, CO₂ emissions, NOx emissions, engine size, fuel type, and vehicle age, users can obtain accurate VRT estimates. The calculator also allows users to view and manage their previous calculations, ensuring easy reference and record-keeping.

## Features
- **Detailed Input Fields**: Enter vehicle value, CO₂ emissions, NOx emissions, engine size, fuel type, and vehicle age to get precise VRT estimates.
- **Accessibility**: Built with accessibility in mind, utilizing ARIA roles and labels to ensure usability for all users.
- **Previous Calculations**: View and manage your past VRT calculations for easy reference.
- **Data Management**: Reset calculations, clear history, and download your results as a PDF for your records.
- **Responsive Design**: Optimized for both desktop and mobile devices, ensuring a seamless experience across all platforms.

## Installation

To set up the Irish VRT Calculator on your local machine, follow these steps:

1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/irish-vrt-calculator.git](https://github.com/VRT-Calculator/.github.git
    ```

2. **Navigate to the project folder:**

    ```bash
    cd irish-vrt-calculator
    ```

3. **Open the `index.html` file in your browser:**

    You can open the file directly, or host it via a local server for a better development experience.

    If you have Python installed, you can serve the app locally:

    ```bash
    # For Python 3.x
    python -m http.server 8000
    ```

4. **Visit `http://localhost:8000` in your browser.**

## Usage

1. **Open the application** by navigating to the `index.html` file in your browser or via the local server.

2. **Enter Vehicle Details:**
    - **Name (optional)**: Provide a name for your calculation for easy reference.
    - **Vehicle Value (€)**: Input the value of your vehicle in euros.
    - **CO₂ Emissions (g/km)**: Enter the CO₂ emissions of your vehicle.
    - **NOx Emissions**: Specify the NOx emissions.
    - **NOx Emissions Unit**: Select the unit of NOx emissions (mg/km or mg/kWh).
    - **Engine Size (cc)**: Input the engine size in cubic centimeters.
    - **Fuel Type**: Choose the type of fuel your vehicle uses (Petrol, Diesel, Electric, Hybrid, Other).
    - **Vehicle Age (years)**: Enter the age of your vehicle in years.

3. **Calculate VRT:**
    - Click the **"Calculate VRT"** button to generate your VRT estimate.

4. **View Results:**
    - The result will be displayed on the next step, along with a list of your previous calculations.

5. **Manage Calculations:**
    - **Back**: Return to the input form to make changes.
    - **Reset**: Clear all input fields.
    - **Clear History**: Remove all previous calculations.
    - **Download PDF**: Save your calculation results as a PDF document.

## How It Works

1. **Data Input:** Users enter their vehicle details, including value, emissions, engine size, fuel type, and age.

2. **VRT Calculation:**
    - The application processes the input data using predefined tax rules to calculate the Vehicle Registration Tax.
    - The calculation considers factors such as CO₂ and NOx emissions, engine size, fuel type, and vehicle age to ensure accurate estimates.

3. **Result Display:**
    - The calculated VRT is displayed to the user along with a summary of their input.
    - Previous calculations are listed for easy reference and management.

4. **Data Management:**
    - Users can reset the form, clear their calculation history, or download their results as a PDF for their records.

## Technologies Used
- **HTML5**: For structuring the content.
- **CSS3**: For styling and responsive design.
- **JavaScript**: For interactivity and calculations.
- **ARIA Attributes**: To improve accessibility.

## Contributing

Contributions are welcome! Whether it's reporting bugs, suggesting features, or submitting pull requests, your input helps make this project better.

1. **Fork the repository.**
2. **Create a new branch:**

    ```bash
    git checkout -b feature/YourFeature
    ```

3. **Make your changes.**
4. **Commit your changes:**

    ```bash
    git commit -m "Add YourFeature"
    ```

5. **Push to your branch:**

    ```bash
    git push origin feature/YourFeature
    ```

6. **Open a pull request.**

Please ensure your contributions adhere to the project's Code of Conduct.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- **Open-Source Community:** For providing valuable resources and inspiration.
