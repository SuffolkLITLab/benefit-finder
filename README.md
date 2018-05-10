# Public Benefits Finder How-To
<p> (1) First, you must familiarize yourself with the platforms used to create the Public Benefits Finder: QnA Markup and GitHub. QnA Markup is the markup language used to create the interactive questionnaires. It is user-friendly and displays the questionnaire similar to an iMessage conversation. And we hosted the questionnaires with GitHub, which is open-source. I recommend you use the following resources on the platforms’ respective websites: </p>
<p> (a) QnA Markup: https://www.qnamarkup.org/syntax/ </p>
<p> (b)	GitHub: https://help.github.com/ </P>
<p> (2)	Once you familiarize yourself with QnA Markup and GitHub, you must request access to the GitHub repository where all the Public Benefits Finder documents are stored. </p>
<p> (a) Create a GitHub account at https://github.com/join/. </p>
<p> (b) Request access to the GitHub repository from Professor Colarusso. </p>
<p> (c) You should see the following on your computer screen: </p>
<p> <img width="843" alt="github screen shot 1" src="https://user-images.githubusercontent.com/34524600/39898207-cedbf318-5483-11e8-966c-9e8e9eb4c470.png"> </p>
<p> (d)	The “Public Benefits Finder Documents” folder contains a backup of our work on the project including, but not limited to, QnA files, research, and the 2018 Clinnovation Presentation. </p>
<p> (e)	The additional .txt files (e.g. SNAPQNA.txt) and their corresponding .html (SNAPQNA.html) files are the live questionnaires. </p>
<p> (f)	The JavaScript file (script.js) is referenced in the Public Benefits Finder for calculations in regard to the Federal Poverty Guidelines. </p>
<p> (g)	Here is where you upload new benefit QnA Markups and edit the “IntroBenefitsQNA” (https://aambrogio.github.io/LIT-QNAs/IntroBenefitsQNA.html) so users can access all benefit questionnaires from a central hub. </P>
<p> (3)	In order to host a new benefit program QnA, follow the steps below: </p>
<p> (a)	Open up the questionnaire you created in QnA Markup. It should look like the following: </p> 
<p> ![qna screen shot 1](https://user-images.githubusercontent.com/34524600/39898670-c8fcef7c-5485-11e8-8ce9-36500b3d398c.png) </p>
<p> (b)	Once your QnA is open, you must convert the .txt file to a .html file. You do this by clicking the dropdown menu in the upper right-hand corner with “Interactive” as the default.  </p>
<p> <img width="1268" alt="qna screen shot 2" src="https://user-images.githubusercontent.com/34524600/39898617-8ba04a48-5485-11e8-93eb-eb21f4950f8e.png"> </p>
<p> (c)	After you locate the dropdown menu, select “HTML full page.” </p> 
<p> <img width="1266" alt="qna screen shot 3" src="https://user-images.githubusercontent.com/34524600/39898631-9939c6e8-5485-11e8-8fa9-f8a5427dd60d.png"> </p>
<p> (d)	Then click “Save HTML to file.” FYI I am going to save a test file as the generic “QnA_page” for these instructions. </p> 
<p> <img width="1266" alt="qna screen shot 4" src="https://user-images.githubusercontent.com/34524600/39898641-a927e9c2-5485-11e8-92c5-2835933da8d1.png"> </p>
<p> (e)	Locate the .html file you just created (it is likely in your “Downloads” folder) and upload it to the Benefit Finder GitHub repository. You can do this simply by clicking “Upload files.”  </p>
<p> <img width="843" alt="github screen shot 2" src="https://user-images.githubusercontent.com/34524600/39898261-0022535e-5484-11e8-94dd-7bda20bb734f.png"> </p>
<p> (f)	You can either drag and drop the .html file onto the screen itself or you can use “choose your files” to locate and upload it. I recommend dragging the file from your folder onto the screen as it is more efficient. </p> 
<p> <img width="1253" alt="github screen shot 3" src="https://user-images.githubusercontent.com/34524600/39898324-3926bb5e-5484-11e8-9a8a-adb730221612.png"> </p>
<p> (g)	After you drag the .html file onto the screen, you must click “Commit changes.” In GitHub “Commit changes” is akin to confirming the uploads or changes you have made. </p>
<p> <img width="1248" alt="github screen shot 4" src="https://user-images.githubusercontent.com/34524600/39898354-55bd34e6-5484-11e8-8c7c-3adb4f95ac84.png"> </p>
<p> (h)	Your .html file should now be located in the repository. </p> 
<p> <img width="1271" alt="github screen shot 5" src="https://user-images.githubusercontent.com/34524600/39898385-6fda92ec-5484-11e8-86b5-429ed52c518b.png"> </p>
<p> (i)	Now you can test whether or not the .html file is hosted by entering the following URL in your browser: http://suffolklitlab.org/benefit-finder/nameofyourhtmlfile. If you see your QnA in the browser, then it was hosted correctly. If you see a 404 error page, something went wrong. I would first ensure you typed the URL correct. If the URL is correct, I would consult with Professor Colarusso. </p>
<p> <img width="1273" alt="github screen shot 6" src="https://user-images.githubusercontent.com/34524600/39898467-d3dacf96-5484-11e8-8ec2-424288d4c53a.png"> </p>
<p> (4)	Assuming you did not run into problems hosting the new QnA, the next step is to “marry” it with the “IntroBenefitsQNA” to ensure users can access it from the central hub we created. It is relatively simple, but this requires replacing the existing “IntroBenefitsQNA.html” file with an updated file each time you add another benefit program. </p> 
<p> (a)	First, you must edit the “IntroBenefitsQNA.txt” file (not the .html file). </p>
<p> <img width="843" alt="github screen shot 7" src="https://user-images.githubusercontent.com/34524600/39898514-051564fe-5485-11e8-8aed-69fdb3395796.png"> </p>
<p> (b)	Open the “IntroBenefitsQNA.txt” file in GitHub and locate the following set of questions. </p>  
<p> <img width="1268" alt="github screen shot 8" src="https://user-images.githubusercontent.com/34524600/39898538-217cd4ba-5485-11e8-9d80-92a79df67a30.png"> </p>
<p> <img width="1262" alt="github screen shot 9" src="https://user-images.githubusercontent.com/34524600/39898561-37f05046-5485-11e8-93ae-c6b34bfd54ef.png"> </p>
<p> <img width="1198" alt="github screen shot 10" src="https://user-images.githubusercontent.com/34524600/39898570-426e7368-5485-11e8-9f4b-f7ed08d84aae.png"> </p>
<p> (c)	As you can see, we added links to the individual benefits program QnA questionnaires. You can simply add an additional link to the newly created benefit program’s .html file. Refer to the QnA syntax page reference at the beginning for how to do this. </p>
<p> (d)	Once you have updated the “IntroBenefitsQNA.txt” file, you must save the .txt file on your computer by right-clicking the file in GitHub and clicking “Save link as…” Then follow the steps detailed in #3 above to create a new .html file and host it. Please be sure to keep the file name the same, otherwise it will not replace the old file in GitHub. </P>
<p> (5)	You are done! The final step is to test it in the browser at http://suffolklitlab.org/benefit-finder/IntroBenefitsQNA. If you run into problems, Professor Colarusso is an invaluable resource. </p>
