# Individual_Portfolio _Smart_Environments
- **The background:**\
 This part is in https://github.com/OliveDunphy123/DSSE_Individual_Portfolio-/blob/main/02_01_Background.ipynb
- **Methodology and data source used**\
  For objective 1, we used administrative boundaries, traffic datasets, industrial datasets which have different sectors and emissions, air pollution emissions.\
  For objective 2, we used traffic performance data which includes number of transactions and vehicles from National Toll Collection System. And emission data which includes emission of road transport, such as NOX, PM2.5 and CH4.\
  For objective 3, we used air pollution data more specifically is annual concentration of PM 2.5, and data on rate of death caused by respiratory diseases.\
  The more detailed information about data source is in the link https://github.com/hudsonpassos85/DSSE/raw/main/Report%20and%20Presentation/Data%20Availability.xlsx. Including the time frame, spatial distribution and data type.\
  However, for objective 1 I participated, In  short the methodology is extract the vales of traffic, industrial and emission of NOx in respectively province ,after geting the information of traffic, industrial and emissions, use feature importance analysis to find the contributions of these sectors on emissions .\
  We achieved this by many steps:\
  1. Google poosible datasets we need , analysis the data structure and select suitable useful data.
  2. Indentify data issues and fix it: drop the NULL and unreasonable values.
  3. Modify the data format and filter data we want to use, like only select NOx emission in air pollution dataset without selecting CH4 or PM2.5 emissions.
  4. Integrate processed provinces, traffic, industrial and NOx emission data into one final dataframe.
  5. Applying the most polular feature importance analysis machine learning model which is XGBoost to analysis the final dataframe.\
  The vivid workflow diagram and datasets used in objective 1 are as follows, but detailed methodology is in (02_02_Details about the thinking process and problem solving in objective 1)\
  ![methods](https://github.com/hudsonpassos85/DSSE/blob/main/images/figure01.jpg?raw=true)
  ![data availablity](https://github.com/hudsonpassos85/DSSE/blob/main/images/figure02.jpg?raw=true)\

  
  
- **Details about the implementation**
  
- **Results**
  
- **Conclusions both on the results as well as on the accomplishment of the goal**
