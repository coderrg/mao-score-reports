The code in this repo is used to generate score reports for TAMS Mu Alpha Theta (MAO) using AMC12A, AMC12B, F=ma A, F=ma B raw school reports.

Previously, MAO execs have asked students to message them if they want scores for a particular contest. This means that execs receive many new messages from different students everyday asking for a specific contest score, and then the execs have to manually find the email where the student's score is and send the student his/her score using Messenger. This is rather inefficient and unprofessional.

The code in this repo allows for the generation of individual student reports with all of the student's scores compiled into one document. It uses Levenshtein distance to combine score reports of students who might have misbubbled on a scantron for a test (for example, RHYTHMM instead of RHYTHM).

For use in future years, rename the results files for AMC12A/AMC12B/Fma with the same format as the files in this directory (the only thing different should be the year) and make sure they are csv files. Also, make sure to change the year-specific variables in compilation.py file like the year and cutoffs.

For a demo, start by downloading the files in this folder (data files only available for future execs, not on the public GitHub repo). Then, go to terminal and run "pip install -r requirements.txt" in order to get the necessary dependencies. You should then be ready to run compilation.py with the command "python compilation.py" on terminal in the same directory as the downloaded files. This will generate documents with each student's scores on F=ma A, F=ma B, AMC12A, and AMC12B for this school year (2019-2020).

Contact Rhythm Garg (typhoonrg@gmail.com) with any questions.
