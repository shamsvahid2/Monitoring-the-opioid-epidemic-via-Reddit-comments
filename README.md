# Monitoring-the-opioid-epidemic-via-Reddit-comments
This repo tries to understand how the use of different opioid drug names changes over time (for four popular categories).
We use  [RedMed](https://github.com/alavertu/redmed) , a python package library, to detect different brand names for opioid pain-relief medicine.

The results are as follows:

1. number of comments:
![alt text](https://github.com/shamsvahid2/Monitoring-the-opioid-epidemic-via-Reddit-comments/blob/main/result/res1_comment_time_series_19-21.png)

2. Nromlised number of comments:

![alt text](https://github.com/shamsvahid2/Monitoring-the-opioid-epidemic-via-Reddit-comments/blob/main/result/res1_comment_time_series-normlised_19-21.png)

(for interactive plots, please download .html files from the results' folder)

**Interpreting results of phase spaces:**
We use taken's embedding theorem to reconstruct the phase space; for example see the following phase spaces (oxycodone 2019 and 2021):

1. 2019:
![alt text](https://github.com/shamsvahid2/Monitoring-the-opioid-epidemic-via-Reddit-comments/blob/main/dynamic-related-results/2019-OX-Dynamic.png)
2. 2021:
![alt text](https://github.com/shamsvahid2/Monitoring-the-opioid-epidemic-via-Reddit-comments/blob/main/dynamic-related-results/2021-OX-Dynamic.png)

It seems that the dynamic of 2020 is different from 2021 and 2019 and 2021 and 2019 seem to be similar.
__In addition, an annual periodic Behavior is apparent in this dynamic. It may be because of seasonal disease, so we need to debias our time series from these fluctuations before considering peaks and drops of time series.__
