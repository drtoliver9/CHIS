# CHIS
Novel Comprehensive Hurricane Impact Scale (CHIS)

Title and Description: “Composite Hurricane Impact Scale (CHIS) - A Holistic Hurricane Risk Assessment Tool,” explaining CHIS’s purpose to integrate multiple hurricane factors, validated through historical case studies, and linking to the research paper in docs/.

Installation: Requires Python 3.8+, with dependencies (pandas, numpy) in requirements.txt, installed via pip install -r requirements.txt. This aligns with data science project examples, ensuring technical setup is clear.

Usage: Demonstrates running chis_calculator.py with sample HURDAT2 data, computing scores with the weighted formula, and referencing NOAA’s dataset for context (NOAA Hurricane Data). This provides practical examples, as suggested by freecodecamp’s guide on READMEs.
	
Contributing: Encourages data submissions via Issues (CSV format matching HURDAT2) and code improvements via pull requests, with a link to CONTRIBUTING.md, fostering community input, similar to hurricaneexposure’s approach with open Issues for feedback.

License and Acknowledgments: Uses MIT License for open-source distribution, with acknowledgments to NOAA for HURDAT2 data and inspiration from hurricaneexposure, enhancing credibility.

Technical Details and Data Acceptance

The methodology involves Python scripts in src/, like chis_calculator.py, using pandas for data handling and numpy for calculations, as outlined earlier. Sample datasets in data/ are from NOAA’s HURDAT2, updated as of March 17, 2025, for Pacific data, and April 26, 2024, for Atlantic, including six-hourly information like winds and pressure, ensuring reliability. Accepting data via Issues involves CSV files matching HURDAT2 format, with columns like date, wind speed, surge height, rainfall, and duration, as detailed in the contribution section, aligning with open-source practices.




