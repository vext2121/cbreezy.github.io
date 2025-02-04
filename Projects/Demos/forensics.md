# Putting Together a Digital Forensic Investigation Using Autopsy Forensic Software

#### Configuring Autopsy with Our Forensic Data
  To begin analyzing the forensic data collected against the suspect John Smith we must open and configure the Autopsy software with our forensic image (essentially a snapshot of the Operating system while John Smith was using it.) First, run the Autopsy software and initiate a new case file configuration by clicking “New Case” on the welcome screen and reaching the New Case Identification Screen as shown below. The “Case Name”  section will be the name of the directory housing all of your case data for the investigation. For this example, the case name will be“FindJohn”. “FindJohn” will be stored in a base directory we choose here in the “Base Directory” section-—we can see the example directory path below. A case number is optional depending on our use case.
<img src="{{site.baseurl | prepend: site.url}}Assets/Images/Autopsy/Autopsy1.png" alt="New Case" />

  In the figure below we can see 5 steps on the left-hand menu. The settings in step 1 “Select Host” remain default as we move on to configuring the forensic data source in step 2 “Select Data Source Type.” 
<img src="{{site.baseurl | prepend: site.url}}Assets/Images/Autopsy/Autopsy9.png" alt="Select Data Source Type" />
> While Autopsy allows us to analyze a digital forensic image, it does not create the image itself. This is done by imaging software such as FTK Imager or EnCase forensic software. In this scenario, we already have our forensic image and select “Disk Image or VM File” as our data source type.
Step 3 “Select Data Source” requires us to input the file path for the forensic image, as shown below. 
<img src="{{site.baseurl | prepend: site.url}}Assets/Images/Autopsy/Autopsy2.png" alt="Select Data Source" />
We leave step 4 “Configure Ingest” on default settings, and step 5 “Add Data Source” simply notifying us that the forensic image was successfully uploaded to Autopsy.
<img src="{{site.baseurl | prepend: site.url}}Assets/Images/Autopsy/Autopsy3.png" alt="Add Data Source" />

  Once the Autopsy software is finally configured for our case analysis, we move forward exporting any files of interest to the designated “FindJohn” directory. (we will explore this exporting process after finding items of interest.) For now, we are finally ready to analyze the forensic image and compile our case against John Smith. 

#### Basics of Autopsy User Interface
  The Autopsy forensic analysis software provides intuitive access to detailed metadata--data describing the files saved on a given device. Metadata is crucial for digital forensic investigators to explore how devices of interest were exploited by malicious actors. We can see how Autopsy organizes this data in the example figure below containing a "Confidential" file for a simulated oil company. 
<img src="{{site.baseurl | prepend: site.url}}Assets/Images/Autopsy/Autopsy6.png" alt="User Interface Example" />
> For example, the "Deleted Files" tab, on the left-hand menu, compiles deleted > files for the investigator’s convenience (Shown near the red X on the
> left->hand menu). 
> 
> Below that, there is a tab called “Data Artifacts” showing file ownership,
> file modification dates, and more depending on the file type. Using these
> software tools we can find unusual metada and confirm their relevance to the case.
> 
> Another tab called “Application”, located just under the central window,
> shows how a given file would appear to an end user in its appropriate
> application—-think of viewing a Word document in Microsoft Word. We see an
> example of this in the image below where a document is displayed how it would > appear in it’s appropriate software interface. 

#### Building a Case Against John Smith
  After analyzing the evidence collected from John Smith’s computer image, numerous instances of malicous action can be uncovered. For instance, within the deleted files section of the Autopsy report a number of documents and images were deleted within a short time frame; as we can see below.
<img src="{{site.baseurl | prepend: site.url}}Assets/Images/Autopsy/Autopsy10.png" alt="Hidden Files" />
  As well,  we can see a file titled “Business_Strategy.pdf” was shown to have the term “Confidential” highlighted in red. This file is residing on John Smith's computer while he has yet to prove clearance for confidential clearance.
<img src="{{site.baseurl | prepend: site.url}}Assets/Images/Autopsy/Autopsy6.png" alt="User Interface Example" />
  Furthermore, the metada for this file shows the owner to be a user named Mike Morris, who is clearly not our friend John Smith.
<img src="{{site.baseurl | prepend: site.url}}Assets/Images/Autopsy/Autopsy8.png" alt="8" />

  As we explore forensic data we will identify abnormal activity such as this and export them to our investigation folder as shown below. 
<img src="{{site.baseurl | prepend: site.url}}Assets/Images/Autopsy/Autopsy4.png" alt="4" />
>right-click on the file of interest and simply click extract file(s).
<img src="{{site.baseurl | prepend: site.url}}Assets/Images/Autopsy/Autopsy5.png" alt="5" />
> This shows the directory tree where our FindJohn evidence files will go.

#### Configuring Autopsy with Our Forensic Data
  And there we go! A start to finish guide on how to configure the Autopsy forensic analysis software. While were already provided a forensic image for this investigation, we still configured the software to ingest our data, created a directory for our evidence, and compiled evidence of malicious activity into our investigation directory. We can carry this conceptual knowledge over to other forensic software such as FTK Imager or EnCase to perform investigations and even learn to create our own forensic images as well. Hope this helped, now go make the internet safer!
