


# Solar Radiation Measurement Data Analysis
## Project Overview

This project is focused on analyzing Solar Radiation Measurement Data, including various environmental parameters such as solar radiation, temperature, humidity, wind speed, and more. The analysis is carried out in Python, with a focus on Exploratory Data Analysis (EDA) and statistical insights to understand the data's behavior and patterns.

## Getting Started

### Prerequisites

Ensure that Python 3.x is installed on your system. You can create a virtual environment and install the necessary dependencies using the following commands:

```bash
# Create a virtual environment
python -m venv venv

# Activate the virtual environment
# On Windows
venv\Scripts\activate
# On macOS/Linux
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt
```

### Dataset

The dataset used in this project contains the following key columns:

- `Timestamp`: Date and time of each observation.
- `GHI`, `DNI`, `DHI`: Solar irradiance measurements.
- `ModA`, `ModB`: Sensor measurements.
- `Tamb`, `TModA`, `TModB`: Temperature measurements.
- `RH`: Relative Humidity.
- `WS`, `WSgust`, `WSstdev`: Wind speed and related measurements.
- `WD`, `WDstdev`: Wind direction and related measurements.
- `BP`: Barometric pressure.
- `Cleaning`: Indicator for cleaning events.
- `Precipitation`: Precipitation rate.
- `Comments`: Any additional notes.

### Running the Analysis

1. **EDA and Summary Statistics**: You can start by running the Jupyter notebooks located in the `notebooks/` directory. These notebooks contain the exploratory data analysis (EDA) and summary statistics.

2. **Data Cleaning**: The scripts in the `scripts/` directory, particularly `data_cleaning.py`, will help you clean and preprocess the data based on the initial EDA.

3. **Running Tests**: Unit tests for your analysis can be found in the `tests/` directory. Run these tests using `pytest`:

   ```bash
   pytest tests/
   ```

4. **CI/CD Pipeline**: The project includes a basic GitHub Actions workflow configured in `.github/workflows/unittests.yml` to run your tests automatically on every push.

### Bonus: Dashboard Development

If you wish to develop a dashboard to visualize the insights:

1. **Install Streamlit**:
   ```bash
   pip install streamlit
   ```

2. **Run the Dashboard**:
   ```bash
   streamlit run scripts/dashboard.py
   ```

3. **Deploy the Dashboard**: Deploy your dashboard using Streamlit Community Cloud or any other hosting service.

## Version Control

This project uses Git for version control. Ensure to follow good commit practices:

- Create descriptive commit messages.
- Work on separate branches for different tasks (e.g., `task-1`).
- Merge changes only after thorough testing and review.

## Contributing

Contributions are welcome! Please create a pull request with your changes and ensure that all tests pass before submitting.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- The Python community for providing excellent data analysis libraries.
- Any other resources, tutorials, or people you'd like to acknowledge.

```

### Notes:
- Customize the file according to specific tools or methods used in your project.
- Ensure all paths and instructions are up-to-date with your project's setup.