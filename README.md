# Pareto-Analysis
#
# This is a report that I began years ago, trying to determine the top 20% of the equipment causing 80% of our downtime, also known as Pareto Analysis.
#
# After I installed the Electronic Delay Log onboard all vessels between 2015 and 2016, the Site Engineers would upload the database to the company server.  I retrieved all of the databases on a periodic basis for analysis. After combining and cleaning the database, I created a macro that sorted the databases by division, and run a formula for determining the Delay Duration, since only the Start and Finish Date/Times were given. 
#
# I then created each of these spreadsheets for the Divisions, since each dredge division/vessel was different and had different categories/subcategories, but we did also want to know the categories to determine if there were asset level failures.
#
# The EDL tab on the bottom of the spreadsheet is the data after being cleaned and macros run are placed into these spreadsheets. Each vessel has 4 tabs, to help keep track of any errors that may arise, consisting of analysis by Mechanical Delay – by Count and by Hours; and Operational Delay – by Count and by Hour. The reasoning for this is that even though the large long mechanical delays were important on an operational level of production, the small and frequent delays do add up, and sometimes surpass the long delays. 
#
# For example, from my analysis one year, I saw a specific vessel continue to blow the same fuse that caused the vessel to stop production, typically 2-3x a week for up to 15 minutes of delay each time. This resulted in over 24 hours and a count of over 125 entries. During my cross-functional team incident investigation, we determined the maintenance group was so used to this fuse blowing, they started ordering it in bulk vice finding the root cause because the company was focused on production and limiting time down. The actual troubleshooting found the issue and was repaired within 5 hours. 
#
# Back to the spreadsheets, I created the 4 vessel tabs of maintenance/operations and count/hours to compare/contrast the different vessels and across the division with other similar vessels.  In the Mech Summary and Ops Summary tabs I was able to show management the results of each vessel and division for each Calendar Year. Since people like visuals, I was able to create a Pareto chart for each and compared the count/hours to see any anomalies or correlations between them.
#
# These reports were very time-consuming and in the beginning of the process before macros and semi-automated steps that I used to further refine my work, it would take more than a month to produce these. Management pushed for more frequent reports for, at the beginning it was quarterly and annually. Eventually I was asked for the data monthly and eventually wanted to view the reports between projects and specific dates. 
#
# On the Mech Summary, I was able to create a user-entered Date-Range for Start and Stop, and I semi-automated this spreadsheet to only data-mine the data between those dates for more specific analysis that management was asking for. I also submitted my analysis results in a PowerPoint to the appropriate divisional leadership. This changed the way that upper leaders viewed maintenance, and started to use these reports for the better.
#
