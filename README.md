# JNUC 2021 - Dashboards with PowerBI
 
 This is the repo for the JNUC 2021 talk regarding building and customizing beautiful dashboards with PowerBI. It includes code examples and extra slides. The JNUC session has been posted to YouTube [https://www.youtube.com/watch?v=ZfuVAqUmIEw](https://www.youtube.com/watch?v=ZfuVAqUmIEw)

 [![Watch the video](https://img.youtube.com/vi/ZfuVAqUmIEw/0.jpg)](https://www.youtube.com/watch?v=ZfuVAqUmIEw)

 Power BI Desktop app is free to use and is Windows only :(  If you want to publish or share your dashboard you may need additional licensing. See the links below for more details.

 The focus of the JNUC talk was focused around Macs, but many of the same principles can be applied for Mobile Devices like iOS and AppleTV devices.

# Important Notes for Jamf Pro 11.5 and later
Jamf has disabled basic authentication for all Jamf Pro instances automatically upon upgrade starting with Jamf Pro 11.5

[Jamf Pro 11.5 Important Notices](https://learn.jamf.com/en-US/bundle/jamf-pro-release-notes-11.5.0/page/Important_Notices.html)

You will need to enable Basic Authentication in Jamf Pro in order to use the PowerBI Jamf connector, both in the PowerBI app as well as if you use the data refresh feature in PowerBI. 

If Basic Auth is not enabled in Jamf, PowerBI will report "The credentials provided for the JamfPro source are invalid".

To re-enable basic authentication in Jamf Pro:
1. Go to Settings -> Users accounts and groups
2. Click Password Policy (in upper right)
3. Check the box 'Allow Basic authentication in addition to Bearer Token authentication'

Please consider voting up this feature idea for Microsoft to support API tokens. https://ideas.fabric.microsoft.com/ideas/idea/?ideaid=1d1acbef-5e21-ef11-8ee8-000d3a7c8d70

# Extra Slides
These slides includes extra information that didn't make the cut for the JNUC 2021 time limit. 

This includes a large section on how to transform the Extension Attributes query. Using those steps make it much easier to use Extension Attributes in visualizations and measures.

Depending on the feeback from JNUC 2021, some of this material may be folded into future presentation.

# Jamf Power BI Documentation
- [Jamf Power BI Integration](https://marketplace.jamf.com/details/power-bi/jamf.com/support/)
- [Show off your Reporting Dashboard](https://www.jamf.com/jamf-nation/discussions/35614/show-off-your-reporting-dashboard)
- [Jamf Training Module 1](https://www.youtube.com/watch?v=PBsP84G-vtg&list=PLlxHm_Px-Ie2qKoYo3pGxi8F6WSjNeG87&index=10)
- [Jamf Training Module 2](https://www.youtube.com/watch?v=PD5wTxHKCu8&list=PLlxHm_Px-Ie2qKoYo3pGxi8F6WSjNeG87&index=10)

# Microsoft Power BI Documentation
- [Download Power BI](https://www.microsoft.com/en-us/p/power-bi-desktop/9ntxr16hnw1t?activetab=pivot:overviewtab)
- [Microsoft PowerBI Documentation](https://powerbi.microsoft.com/en-us/desktop/)
- [Publish an app in Power BI](https://docs.microsoft.com/en-us/power-bi/collaborate-share/service-create-distribute-apps)
- [Power BI Feature List](https://docs.microsoft.com/en-us/power-bi/consumer/end-user-features)

# Power BI Tools
- [Power BI Measures for Jamf](https://www.slingpine.com/page/5/)
- [Creating Measure Tables in Power BI](https://www.biinsight.com/define-measure-table-power-bi-desktop/)

# Visualization Examples
Here's a few example visualizations I made with for our Jamf environment.  

![Summary](/Visualizations/PowerBI-Summary.png)

![Big Dashboard](/Visualizations/PowerBI-Big-Dashboard.png)

![Enrollments](/Visualizations/PowerBI-Enrollments.png)

![Mac Models](/Visualizations/PowerBI-Mac-Models.png)

![Application Search](/Visualizations/PowerBI-Application-Search.png)