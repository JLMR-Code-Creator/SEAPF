SEAPF Executable

1. Prerequisites for Deployment (Developer users)
Verify that version 9.9 (R2020b) of the MATLAB Runtime is installed.   
If not, you can run the MATLAB Runtime installer.
To find its location, enter

2. Files to Deploy and Packaged (End users)
================================
- SEAPF.exe Executable file. Refer to the user's manual for proper use. 
- MATLAB_Runtime_R2020b_win64.zip : Refer to the user's manual for proper installation. 
    Note: if end users are unable to download the MATLAB Runtime using the
    instructions in the previous section, include it when building your 
    component by clicking the "Runtime included in package" link in the
    Deployment Tool.
- /DB It contains the supervised learning models and the images used in training. The images are used for similarity visualization with new samples.
- DSC00005.icc: Color profile for image color calibration, for more information see the user's manual.




