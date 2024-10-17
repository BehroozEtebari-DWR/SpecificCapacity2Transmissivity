This Python script is designed to estimate Transmissivity using various empirical formulas and methods. 

### Input File:
To use this script, you may need to download the well completion reports from the California Department of Water Resources' (DWR) Online System for Well Completion Reports (OSWCR). The data can be accessed here:  
[Well Completion Reports - DWR](https://data.ca.gov/dataset/well-completion-reports/resource/6c6deb49-5977-4bc0-91dc-3d4ed3303a9d).

### Transmissivity Estimation Methods:
1. **Driscoll Approach (1986)**  
   - Units: gallons per day per foot (gpd/ft)  
   - Best suited for confined aquifers  
   - Empirical method based on data and experience in the field.
    You can find detailed information on these methods at the following link:  
   [Transmissivity Calculation Methods](http://www.aqtesolv.com/forum/transcap.asp).
2. **Cooper and Jacob Exact Equation (1946)**  
   - This method provides a more precise calculation using an exact equation.  
   - Details on the method can be found here: [Cooper and Jacob Method](http://www.aqtesolv.com/forum/transcap2.asp).

3. **Batu Empirical Equation (1998)**  
   - This is another empirical formula based on extensive field data for transmissivity estimation.

4. **Mace Empirical Equation for Fractured Bedrock (1997)**  
   - Specifically designed to estimate transmissivity in fractured bedrock formations.

5. **Razack & Huntley Empirical Equation (1991)**  
   - Another widely-used empirical method for calculating transmissivity, particularly effective in different geological settings.

Each of these methods has been implemented in the script, allowing for flexibility depending on the data and conditions of the aquifer being analyzed.
