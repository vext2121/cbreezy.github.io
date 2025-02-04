# Putting Together a Digital Forensic Investigation Using Autopsy Imaging Software

To begin analyzing the forensic data collected against the suspect John Smith we must open and configure the Autopsy software. First, run the Autopsy software and initiate a new case file configuration by clicking “New Case” on the welcome screen and reaching the New Case Identification Screen as shown below. The “Case Name”  section will be the name of the directory housing all of your case data for the investigation. For this example, the case name will be“FindJohn”. “FindJohn” will be stored in a base directory we choose here in the “Base Directory” section - we can see the example directory path below. A case number is optional depending on our use case.
<img src="{{site.baseurl | prepend: site.url}}Assets/Images/Autopsy/Autopsy1.png" alt="1" />

In the figure below we can see 5 steps. The settings in step 1 “Select Host” remain default as we move on to configuring the forensic data source in step 2 “Select Data Source Type.” While Autopsy allows us to analyze a digital forensic image, it does not create the image itself. This is done by imaging software such as FTK Imager or EnCase forensic software. In this scenario, we already have our forensic image and select “Disk Image or VM File” as our data source type. Step 3 “Select Data Source” requires us to input the file path for the forensic image, as shown below. We leave step 4 “Configure Ingest” on default settings, and step 5 “Add Data Source” simply notifying us that the forensic image was successfully uploaded to Autopsy.

<img src="{{site.baseurl | prepend: site.url}}Assets/Images/Autopsy/Autopsy9.png" alt="9" />

<img src="{{site.baseurl | prepend: site.url}}Assets/Images/Autopsy/Autopsy2.png" alt="2" />

<img src="{{site.baseurl | prepend: site.url}}Assets/Images/Autopsy/Autopsy3.png" alt="3" />

Once the Autopsy software is finally configured for our case analysis, we move forward exporting any files of interest to the designated “FindJohn” directory. Now, we are finally ready to analyze the forensic image and compile our case against John Smith. 

<img src="{{site.baseurl | prepend: site.url}}Assets/Images/Autopsy/Autopsy6.png" alt="6" />

<img src="{{site.baseurl | prepend: site.url}}Assets/Images/Autopsy/Autopsy7.png" alt="7" />

<img src="{{site.baseurl | prepend: site.url}}Assets/Images/Autopsy/Autopsy8.png" alt="8" />

<img src="{{site.baseurl | prepend: site.url}}Assets/Images/Autopsy/Autopsy4.png" alt="4" />

<img src="{{site.baseurl | prepend: site.url}}Assets/Images/Autopsy/Autopsy5.png" alt="5" />
