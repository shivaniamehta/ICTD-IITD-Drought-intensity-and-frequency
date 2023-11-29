# ICTD-IITD: Drought intensity and frequency
Team members: Rittwick, Tirumal

Steps to reproduce: 
1. Create your google earth engine account: https://www.linkedin.com/pulse/step-by-step-create-your-google-earth-engine-account-khang-vu-tien/
2. Run the following script: https://code.earthengine.google.com/ee188c555d19de2f34dcac39c32d6cb4. 
3. 
4.
5.
6.
7. To get the Frequency and Intensity of Drought for any region of interest of your choice, import the corresponding shape file for the region of interest and rename it as block and provide the block\_name and execute the script. The script by default will try to export the result to the 'kharif-drought-block-wise' asset.  The script will calculate the drought frequency and intensity. For a particular year if the number of micro water sheds are more than 100 then we divided the number in batches of 100 and the generated output will be stored. For example for Mandalgarh block  we have 386 micro-watersheds so it is divided into parts of 100 like 
"Mandalgarh\_part\_0\_kharif\_drought\_frequency\_intensity\_2022", 
\\
"Mandalgarh\_part\_1\_kharif\_drought\_frequency\_intensity\_2022", 
\\
"Mandalgarh\_part\_2\_kharif\_drought\_frequency\_intensity\_2022",  
\\
"Mandalgarh\_part\_3\_kharif\_drought\_frequency\_intensity\_2022"  then these results are merged to get drought results for all the micro-watersheds in that particular block. The above mentioned merging task can be achieved by providing the links to the \href{https://code.earthengine.google.com/8983410a96472db2edd9690702fc5f6e}{script} to get the final drought output for all the micro watersheds for that block
