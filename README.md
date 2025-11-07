# TACLion Skyn Sensor Data Processing Algorithm

This repository contains an adapted version of the code used to process data collected with the Skyn transdermal alcohol concentration sensor, described in this manuscript:

> **Transdermal alcohol concentration features predict alcohol-induced blackouts in college students**\
> Richards, V. L., Glenn, S. D., Turrisi, R. J., Mallett, K. A., Ackerman, S., & Russell, M. A. (2024).\
> Alcohol: Clinical and Experimental Research. 48(5), 880–888.\
> <https://doi.org/10.1111/acer.15290>

The original version of this algorithm included a weekend-level specification due to the study design. The following code has been adapted to process continuously collected data.

If you are interested in weekend-level processing, please contact [veronica-richards\@ou.edu](mailto:veronica-richards@ou.edu)

------------------------------------------------------------------------

## TACLion Skyn Data Processing Algorithm

📄 [TACLion_SkynProcessingCode.Rmd](TACLion_SkynProcessing_2025_11_06.Rmd)

## Test Data

📄 [TACLion_TestData.csv](Test_Data/TACLion_TestData_2025_11_06.csv)\
Sample data downloaded directly from the BACtrack Skyn research portal

📄 [IDs.csv](Test_Data/IDs.csv)\
Sample IDs to link test participants to Skyn data by email and device ID

## Sample Outputs

📄 [TAC_Episode_Plots.pdf](Sample_Outputs/tac.episode.plots.keep_2025_11_06_R.pdf)\
Plots of identified drinking episodes

📄 [Skyn_Features_Day_Level.csv](Sample_Outputs/Skyn_features_days_TACLion_testdata_2025_11_06.csv)\
Final data output containing TAC features for all days with Skyn data

------------------------------------------------------------------------

## Contact

For questions, please contact:\
📧 Veronica L. Richards — [veronica-richards\@ou.edu](mailto:veronica-richards@ou.edu)\
[Southern Plains Alcohol Research Lab on Consequences in Lived Environments](https://www.sparclelab.com/)\
