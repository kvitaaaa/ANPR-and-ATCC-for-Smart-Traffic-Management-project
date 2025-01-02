#  ANPR and ATCC for Smart Traffic Management

##  Project Overview
This project creates an advanced traffic management system using Automatic Number Plate Recognition (ANPR) and Automatic Traffic Classification and Control (ATCC). It utilizes Deep Learning and Object Detection technologies to automate traffic monitoring and regulation in smart city environments.

### Key Features
-  Automatic Number Plate Recognition (ANPR)
-  Automatic Traffic Classification and Control (ATCC)
-  Data interpolation for precise tracking
-  Visualization capabilities

## Project Structure

- **CV_Basics/**: Computer vision and OCR learning materials   
- **Interpolated_results/**: CSV files with interpolated data for improved tracking  
- **number_plate_detection_model_training/**: Scripts and resources for model training  
- **models/**: Core detection and vehicle tracking implementation  
- **output/**: Generated result videos and processed outputs  
- **results/**: Initial vehicle detection CSV files  
- **testing/**: Files for testing the system  
- **.gitignore**: Git ignore rules for excluding unnecessary files  
- **add_missing_data.py**: Script for interpolating missing data in CSV files  
- **main.py**: Main execution script for vehicle detection  
- **requirements.txt**: Python dependencies for the project  
- **visualize.py**: Script to visualize results and create final video


### Results
- The output video can be accessed here : [link for output](https://drive.google.com/file/d/1KlAeAj3-_8RlvUYgMs_QkiYHBhyD7PGM/view?usp=sharing)



##  Workflow
1. Run `main.py` to initiate vehicle detection and generate the CSV output in the `results/ directory.
2. Execute `add_missing_data.py` to perform data interpolation and produce the enhanced CSV file in the `interpolated_results/` directory.
3.  Use `visualize.py` to create a visualization video using the interpolated data, saved in the `output/` directory.

## Setup and Installation
1. Clone the repository:
```bash
git clone [repository-url](https://github.com/kvitaaaa/ANPR-and-ATCC-for-Smart-Traffic-Management-project)
cd anpr-atcc-traffic-management
```

2. Create and activate virtual environment (recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Configure environment variables:
- Create a copy of `.env.example` (if provided) and rename it to `.env`
- Update the necessary secret keys and configurations

##  Running the Project


1. Replace the path to your input video and your desired output directory.

2. Run the main detection:
```bash
python main.py
```

3. Perform data interpolation:
```bash
python add_missing_data.py
```

4. Generate visualization:
```bash
python visualize.py
```

## License
ANPR and ATCC for Smart Traffic Management is released under the [License](LICENSE), allowing you to freely use, modify, and distribute the project.
