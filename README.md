# Leaf Damage Evaluation Macro
This repository contains a Fiji macro designed to evaluate leaf damage caused by salt stress treatment, a critical part of my PhD research. The macro processes images of leaves to determine the total leaf area and the damaged (senesced) area, outputting the data in a tabular format. This data can be further analyzed and visualized using tools like R or Python.

## Repository Contents
- [ ] **Standalone Macro**: Process a single photo of a leaf.
- [x] **Batch Processing Macro**: Process a list of files, each containing a single photo of a leaf.
- [ ] **R Visualization Script**: Visualize the proportion of damaged (senesced) areas.

## Example output
**An example of the analyzed figure.**
[![](https://github.com/ShuXingYu94/Leaf_Senescence_Index/blob/b8b8a82c4828309d388a9ae28f2d8614aeef309b/Sample%20image/Sample%20fig.jpg?raw=true "Title")](#)

## Usage Instructions
### Prerequisites
- **Fiji (ImageJ)**: Make sure you have Fiji installed. You can download it [here](https://imagej.net/ij/download.html).
- **R**: For data visualization, R needs to be installed. You can download it [here](https://www.r-project.org/).

### Photo Guidelines
Photos should be taken in a consistent environment (e.g., same background).
It is highly recommended to use a dedicated camera instead of a phone to ensure unified image quality.

### Parameters
*TBC.*

### Running the Macros
1. **Standalone Macro**:
- Open Fiji.
- Load the standalone macro.
- Open a single leaf photo.
- Run the macro to evaluate the total and damaged areas.

2. **Batch Processing Macro**:

- Open Fiji.
- Load the batch processing macro.
- Provide a directory of leaf photos.
- Run the macro to process all photos and generate a table of results.

3. **R Visualization Script**:
- Open R or RStudio.
- Load the provided R script.
- Import the table generated by the macro.
- Run the script to visualize the proportion of damaged (senesced) areas.

### Output
The output from the macro includes:

- Total leaf area
- Damaged (senesced) area
- Proportion of damaged area

This data is saved in a table format, which can be used for further analysis and visualization.

## Note
If you encounter any issues or have suggestions for improvement, feel free to open an issue or submit a pull request.