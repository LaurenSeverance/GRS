# GRS
Calculate genetic risk score and age of CAC scan using 23andMe v5 raw data

Instructions on Mac:

1. Download the repository: Click the green 'Clone or download' button in the top right corner of the main repository page. Choose the 'Download ZIP' option.

2. Locate and unzip the GRS-master folder: Open the Finder, navigate to the folder where your file was downloaded (i.e. your Downloads folder), and unzip the 'GRS-master.zip' file.

3. Prepare raw data: Download raw data from 23&Me (this software will only work with data from the v5 chip), and unzip the file so that it is a .txt file. Place this raw data .txt file into the unzipped GRS-master folder. The raw data file name will likely take the form 'genome_FirstName_LastName_v5_Full_201XXXXXXXXXXX.txt'.

4. Open a command line window: This can be done by opening the Finder and navigating to Applications --> Utilities --> Terminal

5. Change the current directory: In the command line (Terminal), navigate to the location of your downloaded GRS-master folder. If GRS-master is still in your Downloads folder, you can type a command of the form

    cd /Users/yourname/Downloads/GRS-master

    and press the return key. If executed correctly, you should see 'GRS-master' somewhere to the left of your cursor in the       Terminal.

6. Run the code: Type the command 

    python Calc_GRS.py rawData
    
    and press the return key. Replace rawData with the name of the patient's raw data file (ie                            genome_FirstName_LastName_v5_Full_201XXXXXXXXXXX.txt).
