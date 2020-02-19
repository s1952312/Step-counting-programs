This project has created a set of program files that can be used to extract step count data from multiple .tif files in a directory.

The user should first use the batch measure intensities imagej macro to extract the z projection profiles of all the spots in their files.
    - The detection threshold should be previously determined.
    - Files with different conditions should be stored in seperate directories.
    - Results files are output as text and saved in the selected output directory.
        - These files are in the correct format for the next step.

The user should then open the trace viewer app in the matlab codes folder. 
    - Ensure the function files are downloaded and saved in the same directory as the app.
    - Load in relevant file. Matlab will sort the data and display the first trace.
    - Traces can be cycled through using the navigation buttons.
    
Alternatively batch measuring of the number of steps and conincidence in multiple files can be performed.
    - Run the step_counts_multiple_files code.
    - Pick the two source directories containing the generated results files.
    - Matlab will return cumulative counts and a text file contianing the locations of coincident spots.