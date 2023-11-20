# BLASToise
School project work-line to help in the analysis of frequencies for genes of interest in custom made data bases.

 **Welcome to BLASToise**, this is a simple project for a entry level coding class in data reading and analysis. 

Start by downloading the full project as a zip folder by clicking on the green "Code" button in the github homepage for this project, and save the zip file in a location of your convenience. Alternatevely, you may use the SSH link to import into your operating systme via the git bash command. 

You will find the main folder titled "Python test Director". For the sake of accesibility and convenience, I suggest you make this your working directory when running this project. Within this folder you will find: Four .FASTA files that contain our genes of interest; A data folder titled "outpur_gbff_files" which holds all the genomes that we will use; and the main notebook with all the necessary coding for the run. 

Follow instructions in the notebook to get the two main components for the project: bipython, and BLAST+:

* To obtain biopython, simply enter in a command tab: pip install biopython
* To obtain BLAST+, open the link provided in the notebook. This will take you to a ftp page (File Transfer Protocol). **WARNING:** Due to time restrictions, this work-line was only tested in windows operating systems. For windows, download the installer by clicking "ncbi-blast-2.15.0+-win64.exe". Once downloaded, execute it, and answer all the requirements. When promped to select the destination of the documents, I suggest you save them in the main folder "Python test Director". Once completed, you should see a new folder appear titled "blast-2.15.0+". Do not mess with it :)

Once both biopython and BLAST+ have been succesfully added to your operating system, you are ready to execute the codes in the notebook in order. Make sure you modify the destination of each "input" and "output" files, to ensure the device is looking the file correctly. 

* Make sure that, when utilizing the command tabs to execute BLAST+ functions, you also specify the directory path for the "Python test Director" folder.
* Once the data base is created with "makeblastdb", you should not need to use this function anymore. However, you must execute the "blastn" function once for **each of your genetic targets**.
* Similarly, since we are creating four BLAST files, you must also make a four target .csv files (one for each target)
