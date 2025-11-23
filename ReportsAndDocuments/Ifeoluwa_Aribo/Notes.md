# Daily Work Log - November 7, 2025  
**Student Name:** Ifeoluwa Aribo  
**Student Number:** 300389564  

## Overview  
Today’s session focused on static security analysis of Android applications using **AndroBugs Framework** on **Kali Linux**. The goal was to extract APKs from an emulator, configure the analysis environment, and generate vulnerability reports for selected apps.

## Tasks Completed  
- Installed and configured Android Studio and AVD emulator.  
- Verified ADB connection and listed installed applications.  
- Identified target packages (Reddit and Tim Hortons) and retrieved their paths.  
- Pulled APKs from the emulator and organized project directories on Kali.  
- Cloned and configured AndroBugs_Framework from GitHub.  
- Fixed Python 2 compatibility issues and verified correct runtime setup.  
- Executed AndroBugs scans on Reddit.apk and TimHortons.apk.  
- Collected, reviewed, and summarized vulnerability reports.  
- Compared security findings between Reddit and Tim Hortons.  
- Created a prioritized risk report and recommendations for mitigation.  

## Achievements  
- Set up a working Android security testing environment on Kali Linux.  
- Successfully generated detailed static analysis reports.  
- Identified key security issues including:  
  - Implicit intent exposure  
  - Non-SSL network communication  
  - Exported components and external storage access  
- Documented results for both APKs and outlined risk mitigations.  
- Improved understanding of Android application vulnerability assessment.  

## Total Time Spent  
**7.75 hours**



# Daily Work Log - November 21, 2025  
**Student Name:** Ifeoluwa Aribo  
**Student Number:** 300389564  

## Overview  
Today's session focused on setting up the Mobile Security Framework (MobSF) environment, troubleshooting critical PDF generation functionality, and performing comprehensive static security analysis on Android applications. The goal was to establish a working security testing pipeline and generate detailed vulnerability reports.

## Tasks Completed  
- Installed and configured MobSF environment on the local system  
- Installed wkhtmltopdf dependency and configured system environment variables  
- Investigated and diagnosed PDF generation failure in MobSF reporting  
- Located PDF module using project-wide search and identified missing pdfkit configuration  
- Implemented code patch by adding wkhtmltopdf configuration to MobSF PDF handler  
- Validated the fix by restarting MobSF and confirming PDF generation functionality  
- Uploaded Tim Hortons APK into MobSF and performed complete static analysis  
- Uploaded Reddit APK and conducted comprehensive security assessment  
- Reviewed and analyzed security findings including permissions, code risks, and trackers  
- Generated final PDF security reports for both applications using the repaired system  

## Achievements  
- Successfully established a fully functional MobSF security testing environment  
- Diagnosed and resolved a critical PDF reporting issue through code-level troubleshooting  
- Demonstrated proficiency in dependency management and environment configuration  
- Generated comprehensive security assessment reports for two major applications  
- Identified and documented key security findings including dangerous permissions and potential vulnerabilities  
- Enhanced understanding of mobile application security testing methodologies and tools  

## Total Time Spent  
**6 hours, 20 minutes**