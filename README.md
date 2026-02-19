# AntPcpnIndex
Documenting values of Antecedent Precipitation Index across the western and eastern United States.

Using data collected from the Real Time Mesoscale Analysis(RTMA) dataset, hourly precipitation is summed up into six-hour periods. These 6-hour precipitation fields are added together iteratively, aftter multiplying the sum by around 0.95 before adding the next timestep. This corresponds to about a 24 hour reduction rate around 80 percent. This procedure, called Antecedent precipitation Index(API), has been in use by hydrologists for decades, as a proxy for how much moisture might be present in soils.  In this manner, moisture that falls on one day will gradually toward zero over about 14 days. Values in these images are in millimeters, so 25.4 mm equals 1 inch.

Since evaporation varies over the course of the year, I modified the reduction rate, from 0.98 during the months of December and January down to 0.93 in June and July.

Precipitation across the western United States has been collected since mid-October 2021. Collection of precipitation across the eastern United States began in late March 2025.
Values of API do not change over the course of six hours, or even from day to day, unless a significant amount of precipitation has fallen. Therefore I only display the API on a daily basis.  Plotting the data year after year will begin revealing climatological signals. Regions of possible flooding become evident as the value of API increases. Regions experiencing dry conditions or localized drought become evident as values of API approach zero. Across the western United States over the past several summers, large and destructive wildfires have tended to occur in areas with API at or near zero.  

The RTMA dataset is primarily derived from preipitation estimates of radar networks deployed across the United States. Biases in the estimated precipitation values are corrected by precipitation values reported by local rain gage networks. Since areal coverage of the national weather radar network is more complete over the eastern United States, reliable coverage of API across that region is more complete. Over the western United States, areas of low API may or may not be due to a lack of precipitation.  

API_102100z.png
