This GitHub repository contains supporting data and code for the MSU graduate thesis titled "A Comprehensive Study On Forest Management And Wildfire Trends In Dry Western Coniferous Regions Of The United States" by Rich Schonenberg.

File Descriptions:

adj_df: Excel file containing 86 Managed Fire operations (RX and WFU) that were burned over by Wildfires and Contain Dry Western Coniferous Forests along with attribute information.
CBIRegressiontool: This Rmarkdown script can be easily adapted to regress Composite burn index data with Satellite-derived fire severity (DNBR, RDNBR) to calibrate remotely sensed data to field-based assessments.
R_tool_clipping_RX_and_WF_Areas: This Rmarkdown script automates clipping overlapping polygon areas (WF and RX) located in two folders on a local machine, then clips each respective wildfire DNBR severity raster, by a stratification raster (in this specific case a 30x30m raster that contained Dry western conifer cover, south-facing aspects, and moderate slopes).
Data Visualization_code: R markdown file used to perform statistics and graphical representations of data from adj_df.

