# dye_transfer_assay
The first part of this script combines distance matrices from multiple Excel files in a specified folder. The combined data is then saved to a new Excel file.
Then, only LY+ cells located within 150 um from the edge of the wound will be counted, then classified based on the treatment condition. The filtered results are then stored in another Excel file, a heatmap is also generated.

The second part of the script processes multiple Excel files in a specified folder, extracts GJ Green Area and Intersect Area data, and combines the results into a single DataFrame. The final DataFrame is saved to an Excel file. It also generates a barplot showing the Mean + SD.
Then, it makes a barplot of the combined results, removes outliers, test for normality of the data and runs the most appropiate statistical analysis
