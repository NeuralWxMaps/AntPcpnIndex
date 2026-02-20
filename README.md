# AntPcpnIndex
Documenting values of Antecedent Precipitation Index across the United States since late 2021.

Using data collected from the Real Time Mesoscale Analysis(RTMA) dataset, hourly precipitation is summed up into six-hour periods. These 6-hour precipitation fields are added together iteratively, aftter multiplying the sum by around 0.95 before adding the next timestep. This corresponds to about a 24 hour reduction rate around 80 percent. This procedure, called Antecedent precipitation Index(API), has been in use by hydrologists for decades, as a proxy for how much moisture might be present in soils.  In this manner, moisture that falls on one day will gradually toward zero over about 14 days. 

Values in these images are in millimeters, so 25.4 mm equals 1 inch.  The color scale is also floating, depending on the maximum value across the domain.  Because of this, the wettest region will be plotted in red, but that value can range from less than 35 mm (less than about 1.50 inches) up to more than 200 mm (more than 8 inches).  White will always be zero and the dark blue will generally be less than 25 mm (1.00 inch), indicating areas that are experiencing localized drought. 

Since evaporation varies over the course of the year, I modified the reduction rate, from 0.98 during the months of December and January down to 0.93 in June and July.

Precipitation for this study, has been collected across the western United States since mid-October 2021. Collection of precipitation across the eastern United States occurred for a heavy rain event in July 2022 and for the landfall of major Hurricane Ian in late September 2022.  Additional eastern United States rainfall has now been collected since late March 2025. 

Values of API do not change over the course of six hours, or even from day to day, unless a significant amount of precipitation has recently fallen. Therefore, I only display the API every tenth day, specifically on the 5th, 15th and 25th of each month. API image files are being retained at the daily tiem scale, and the liquid precipitation data is being retained at 6-hour time resolution, to assist in conducting case studies. 

Plotting the data year after year will begin revealing climatological signals. Regions of possible flooding become evident as the value of API increases. Regions experiencing dry conditions or localized drought become evident as values of API approach zero. Over the past several summers, across the western United States, large and destructive wildfires have tended to occur in areas with the API at or near zero. 

The RTMA dataset is primarily derived from preipitation estimates of radar networks deployed across the United States. Biases in the estimated precipitation values are corrected by precipitation values reported by local rain gage networks. Since areal coverage of the national weather radar network is more complete over the eastern United States, reliable coverage of API across that region is more complete. Over the western United States, areas of low API may or may not be due to a lack of precipitation.  

<img src="/API_WrnUS2021/API_102600z.png">
