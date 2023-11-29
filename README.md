# ICTD-IITD: Drought intensity and frequency
Team members: Rittwick, Tirumal

Steps to reproduce: 
1. Create your google earth engine account: https://www.linkedin.com/pulse/step-by-step-create-your-google-earth-engine-account-khang-vu-tien/
2. Run the following script: https://code.earthengine.google.com/ee188c555d19de2f34dcac39c32d6cb4. Import the corresponding shape file for the region of interest and rename it as block and provide the block_name and execute the script. The script by default will try to export the result to the 'kharif-drought-block-wise' asset.  The script will calculate the drought frequency and intensity for each microwatershed. For a particular year if the number of micro water sheds are more than 100 then we divided the number in batches of 100 and the generated output will be stored. For example for Mandalgarh block  we have 386 micro-watersheds so it is divided into parts of 100 like "Mandalgarh_part_0_kharif_drought_frequency_intensity_2022", "Mandalgarh_part_1_kharif_drought_frequency_intensity_2022", "Mandalgarh_part_2_kharif_drought_frequency_intensity_2022",  "Mandalgarh_part_3_kharif_drought_frequency_intensity_2022" and so on.
3. Run the following script: https://code.earthengine.google.com/8983410a96472db2edd9690702fc5f6e. The above parts are merged to get the final drought outputs for all the micro-watersheds in that particular block.
