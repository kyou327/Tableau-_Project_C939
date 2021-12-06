[My Tableau Workbook](https://public.tableau.com/shared/XR8PFXBG9?:display_count=n&:origin=viz_share_link)

## Summary

The goal of analyzing this dataset will to be to find and organize key relationships in the dataset to identify patterns between flight delays and individual airlines.
The dataset covers a complete decade, from September 2011 to August 2021. 
For most plots, 2011 has been left off as it only constitutes 4 months of the year, and skews the data. 

## Design

I tried to keep the plots simple while also making the most efficient use of dashboard space. Colors are bright but organized by hue. 
In the geographic data, green marks lower numbers which are more accessible variables, whereas red marks larger values which would correlate to 
less accessible variables. (ex. A state with deep red hue calculation for minutes equates to a very long wait time. A state with very green hue calculation 
means a very short average wait time.)
The aliases for delays and the metrics for individual states were both improved and added to allow for easier digestion of data without using the tooltip.

## Feedback

I shared my feedback on my personal discord server and hangout with people who are unfamiliar with Tableau and reading data visualization. 
A demographic who is going in fresh without knowing what they are looking at is a perfect target to get feedback on how to make the visualization more accessible to
the average person.
The primary feedback I received focused on easier interpretation. Among the requested changes were:
- Renaming the delay counts to more understandable aliases. 
- Showing the minutes on the map since its an average, like the percentages.
- Adjust the tooltip and aliases so it matches what the labels show.
- Make the story captions bigger without needing to scroll.
- Make the story panes automatic so they fit all monitor types.

## Resources

-[help.tableau.com](https://help.tableau.com/current/pro/desktop/en-us/default.htm)
-Special thanks to [Galen Busch](https://public.tableau.com/app/profile/galen.busch#!/?newProfile=&activeTab=0) for advice and tips on Tableau functionality.