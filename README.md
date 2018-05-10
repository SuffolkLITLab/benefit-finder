# Public Benefits Finder How-To
<p> __(1)__ First, you must familiarize yourself with the platforms used to create the Public Benefits Finder: QnA Markup and GitHub. QnA Markup is the markup language used to create the interactive questionnaires. It is user-friendly and displays the questionnaire similar to an iMessage conversation. And we hosted the questionnaires with GitHub, which is open-source. I recommend you use the following resources on the platforms’ respective websites:
a)	QnA Markup: https://www.qnamarkup.org/syntax/
b)	GitHub: https://help.github.com/ </P>
<p> 2)	Once you familiarize yourself with QnA Markup and GitHub, you must request access to the GitHub repository where all the Public Benefits Finder documents are stored.
a)	Create a GitHub account at https://github.com/join/.
b)	Request access to the GitHub repository from Professor Colarusso.
c)	You should see the following on your computer screen: </p>
<p> https://github.com/SuffolkLITLab/benefit-finder/blob/master/Public%20Benefits%20Finder%20How-To/How-To%20Screen%20Shots/GitHub%20Screen%20Shot%20(1).png </p>
d)	The “Public Benefits Finder Documents” folder contains a backup of our work on the project including, but not limited to, QnA files, research, and the 2018 Clinnovation Presentation. 
e)	The additional .txt files (e.g. SNAPQNA.txt) and their corresponding .html (SNAPQNA.html) files are the live questionnaires.
f)	The JavaScript file (script.js) is referenced in the Public Benefits Finder for calculations in regard to the Federal Poverty Guidelines. 
g)	Here is where you upload new benefit QnA Markups and edit the “IntroBenefitsQNA” (https://aambrogio.github.io/LIT-QNAs/IntroBenefitsQNA.html) so users can access all benefit questionnaires from a central hub. </P>
<p> 3)	In order to host a new benefit program QnA, follow the steps below:
a)	Open up the questionnaire you created in QnA Markup. It should look like the following: 

b)	Once your QnA is open, you must convert the .txt file to a .html file. You do this by clicking the dropdown menu in the upper right-hand corner with “Interactive” as the default.  

c)	After you locate the dropdown menu, select “HTML full page.” 

d)	Then click “Save HTML to file.” FYI I am going to save a test file as the generic “QnA_page” for these instructions. 

e)	Locate the .html file you just created (it is likely in your “Downloads” folder) and upload it to the Benefit Finder GitHub repository. You can do this simply by clicking “Upload files.”  

f)	You can either drag and drop the .html file onto the screen itself or you can use “choose your files” to locate and upload it. I recommend dragging the file from your folder onto the screen as it is more efficient. 

g)	After you drag the .html file onto the screen, you must click “Commit changes.” In GitHub “Commit changes” is akin to confirming the uploads or changes you have made. 

h)	Your .html file should now be located in the repository. 

i)	Now you can test whether or not the .html file is hosted by entering the following URL in your browser: http://suffolklitlab.org/benefit-finder/nameofyourhtmlfile. If you see your QnA in the browser, then it was hosted correctly. If you see a 404 error page, something went wrong. I would first ensure you typed the URL correct. If the URL is correct, I would consult with Professor Colarusso.
</p>
<p> 4)	Assuming you did not run into problems hosting the new QnA, the next step is to “marry” it with the “IntroBenefitsQNA” to ensure users can access it from the central hub we created. It is relatively simple, but this requires replacing the existing “IntroBenefitsQNA.html” file with an updated file each time you add another benefit program. 
a)	First, you must edit the “IntroBenefitsQNA.txt” file (not the .html file). 
b)	Open the “IntroBenefitsQNA.txt” file in GitHub and locate the following set of questions.   
c)	As you can see, we added links to the individual benefits program QnA questionnaires. You can simply add an additional link to the newly created benefit program’s .html file. Refer to the QnA syntax page reference at the beginning for how to do this. 
d)	Once you have updated the “IntroBenefitsQNA.txt” file, you must save the .txt file on your computer by right-clicking the file in GitHub and clicking “Save link as…” Then follow the steps detailed in #3 above to create a new .html file and host it. Please be sure to keep the file name the same, otherwise it will not replace the old file in GitHub. </P>
<p> 5)	You are done! The final step is to test it in the browser at http://suffolklitlab.org/benefit-finder/IntroBenefitsQNA. If you run into problems, Professor Colarusso is an invaluable resource. </p>
