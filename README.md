# CoWIN vaccination districtwise slots availability using Python
Script to check the available slots for Covid-19 Vaccination Centers from CoWIN API (https://apisetu.gov.in/public/marketplace/api/cowin) in India.

# Installation Process:
## Recommended Method: Anaconda
The Anaconda is an easily-installable bundle of Python and many of the libraries used throughout this class.
The script is written in python notebook (.ipynb). So, we recommend Anaconda's Jupyter Notebook for the run. If you wish to use any other software, feel free to do so.

### Windows Users: Anaconda Installation
1. Download the Anaconda from (https://www.anaconda.com/products/individual)
2. Follow the instructions on the above page to run the installer.
3. Check for python version: Start the `Anaconda Prompt` terminal, which you can find in the Start menu. On the Terminal type `python --version`, which outputs the version number. Kindly use a version above 3.8.0.
4. Check whether Jupyter notebook is opening: Start the `Anaconda Prompt` terminal. Type `jupyter notebook`. A new browser window should open. 

# Contents of the repository
- Clone the repository or download the zip file. If you have downloaded the zip file, extract it.
- `cowin-vaccine-availability-districtwise.ipynb` - python script to generate the districtwise vaccine slot availability
- `requirements.txt` - librabries required to run the .ipynb files
- `state_id_mapping_generation.ipynb` - python script to generate the state id and its corresponding state name list.
- `State_ID_Mapping.csv` - state to id mapping excel generated after running `state_id_mapping_generation.ipynb`.
- `18+_Tripura_Vaccine_Availability.xlsx` and `45+_Tripura_Vaccine_Availability.xlsx` - output of the main script

# How to run the code
- Open the `Anaconda Prompt` terminal.
- Enter the command `cd !!location of the dowloaded/cloned file!!`. 
  As an example the command should look like this- `cd C:\Users\user_name\Downloads\CoWIN_vaccine_availability_districtwise`
- Install all the dependencies - `pip install -r requirements.txt`
- Run the jupyter notebook - `jupyter notebook`. A new browser window should open directing to the files present in the given location above.
- Run `cowin-vaccine-availability-districtwise.ipynb` to get the desired output as excel `Tripura_Vaccine_Availability`
