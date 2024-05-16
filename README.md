# Technical-Support-Analysis
## INTRODUCTION
### In today’s world, businesses of all sizes rely heavily on technology for daily operations. Technical support plays a crucial role in maintaining these systems efficiently. This dataset from onyx data provides a real-life scenario for us to explore and analyze the functioning of technical support using Power BI.
## Overview
![ticket volume](https://github.com/vickkycodes/Technical-Support-Analysis/assets/103611857/282b803a-0134-4ada-9055-cd8e482b1ec6)
![slas](https://github.com/vickkycodes/Technical-Support-Analysis/assets/103611857/cf0bcc8e-c707-4643-884d-00512903ed53)
![ticket content](https://github.com/vickkycodes/Technical-Support-Analysis/assets/103611857/86179701-a528-4f06-ac23-551988dff855)

Feel free to interact with the dashboard [HERE](https://app.powerbi.com/view?r=eyJrIjoiOWQ2ZDY1OTktYTc2MC00ZmZkLWJhYzktNWJiNjk4MzkyNTVmIiwidCI6ImE2MzA5ODMxLTIxMGUtNDllNS04ZmY2LTI5ZGMwMDQxMjU5MCJ9)

## DATA TRANSFORMATION
#### With the use of datediff and time functions i was able to create new columns representing the time difference between ticket creation time, response time and resolution time also i created a new column representing the hour of ticket creation in order to get the peak creation times in the day. 
## KEY INSIGHTS

### General Metrics
1. Ticket Priorities:
   * Low Priority: 50.74% - 50.50%
   * Medium Priority: 31.11% - 31.48%
   * High Priority: 18.02% - 18.16%
#### Majority of the tickets are of low priority, with a significant portion being medium priority.

2. Response and Resolution Times
   * Average Response Time: 25 minutes
   * Average Resolution Time: 33 hours
   * Average Rating: 2 out of 5

### SLA (Service Level Agreement) Adherence
1. First Response Time:
   * Within SLA: 87.84%
   * SLA Violated: 12.16%
   * SLA Violated in Minutes: Average of 81 minutes
   * Within SLA in Minutes: Average of 17 minutes
   * #### High compliance with SLAs for the first response time, but there is still room for improvement.

2. Resolution Time:
   * Within SLA: 80.79%
   * SLA Violated: 19.21%
   * SLA Violated in Hours: Average of 90 hours
   * Within SLA in Hours: Average of 19 hours
#### Slightly lower adherence to resolution SLAs compared to first response SLAs.

3. Agent Performance:
   * Specific agents (e.g., Sheela Cutten, Bernard Beckley) show variation in SLA adherence, with Sheela Cutten having the highest within SLA for resolution.

### Ticket Content Analysis
1. Product Group:
    * Ready to use Software: Highest ticket volume (756)
    * Custom software development: 463 tickets
#### This Indicates that most support tickets are related to ready-to-use software.

2. Ticket Topics:
    * Pricing and Licensing: Highest volume (379), with a high average resolution time (35.83 hours)
    * Feature Request: Second highest volume (316)
    * Training Requests: Lowest volume (45) but highest average resolution time (41.22 hours)
    * Different topics have different volumes and resolution times, which can guide where to focus resources.

3. Sources:
    * Email: Highest ticket volume (999) but highest average response time (44.92 minutes)
    * Chat: 549 tickets, with the quickest average response time (2.58 minutes)
    * Phone: 161 tickets, with a moderate response time (7.52 minutes)
#### Chat appears to be the most efficient communication channel in terms of response time.

### Time and Trends
1. Ticket Volume by Time of Week:
    * Weekday: 1,606 tickets, average resolution time 32.81 hours
    * Weekend: 294 tickets, average resolution time 33.62 hours
#### There are higher ticket volume during weekdays with slightly faster resolution.

2. Ticket Volume by Country:
    * Highest ticket volume:  Germany
    * Also significant volumes: Italy and Poland
   #### This Indicates geographical distribution of support requests.

3. Ticket Volume Trend:
   * Peaks in January, March, May, and November
   * Lower volumes in February, April, July, and August
#### Seasonality and periodic spikes in ticket volumes throughout the year.

4. Peak Ticket Creation Time (24-hour period):
    * Highest peak at 15 hours (3 PM)
    * Other notable peaks at 7 AM, 9 AM, and 11 AM
    * Helps in identifying busiest times of the day for support requests.

## Summary
  * The majority of tickets are low or medium priority.
  * SLAs are generally well-adhered to, but there is a noticeable number of violations, especially in resolution times.
  * Email is the most common but also the slowest communication channel for response.
  * Ready to use software and pricing/licensing issues generate the most support tickets.
  * Support demand is higher on weekdays and peaks in the afternoon.
