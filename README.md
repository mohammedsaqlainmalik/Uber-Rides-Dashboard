# Uber-Rides-Dashboard

# 1.Uber Ride Analytics Dashboard (Power BI):
- A Power BI dashboard analyzing ~150K Uber ride records to track completed bookings,revenue and track ride losses like (cancellations/incompletions) across vehicle types.

# 2.Business Question:
- Uber-type platforms lose revenue in two ways: rides that never happen like (cancelled) and rides that start but failed  due to issues like (driver not found, no-show etc.).
- This dashboard answers: How many bookings are completed vs how many lost and what's the revenue impact?
- How does that split (completed / canceled / incomplete) and do they vary by vehicle type? What's the trend in completed bookings and revenue over the year?
# 3.Data:
- ~150K row ride-level dataset containing (booking ID, vehicle type, ride status, revenue, distance, date etc and more)
- Vehicle type segmentation: Auto, Bike, Sedan, Premium, Uber XL etc.
## Key Metrics :
- Completed Bookings Value,Lost Bookings,Revenue,Avg. Distance,Completed Rides Value,Cancelled Rides Value,Incomplete Rides Value, Cancelled rides run at roughly double the rate of incomplete rides within this segment and its worth flagging as the larger of the two loss categories, though the dataset doesn't include a reason code, so the why behind cancellations vs. incompletions isn't something this data can answer.

# 4.Dashboard Views:
## Home: Landing page
### navigation Overview:
- Vehicle-type selector has (Auto, Bike, Sedan, Premium, Uber XL) with per-segment breakdown of completed/cancelled/incomplete rides, monthly / quaterly completed bookings trend, and monthly revenue trend.
- Tools Used to design it are Power BI (Power Query, DAX measures), data cleaning for duplicate/inconsistent booking records etc.
# 5.Limitations:
- No timestamp/reason-code granularity, so seasonal trends (e.g. Feb dip, Apr/Nov peaks) and cancellation causes can't be attributed to any specific driver and hence are flagged rather than guessed at. Dataset does not include cancellation reason codes,so loss categorization stops at cancelled vs incomplete rather than root cause.

# 6.Screenshots:
Preview: ![Alt text](https://github.com/mohammedsaqlainmalik/Uber-Rides-Dashboard/blob/main/Uber_CoverPage.png),
![Alt text](https://github.com/mohammedsaqlainmalik/Uber-Rides-Dashboard/blob/main/Uber_Rides_Performance_Dashborad.png)
