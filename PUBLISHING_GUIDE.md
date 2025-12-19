# Publishing Power BI Dashboard to Power BI Service

## Overview
This guide will walk you through the process of publishing your Power BI dashboard from Power BI Desktop to the Power BI Service (online).

## Prerequisites
- Power BI Desktop installed on your computer
- A Power BI Pro or Premium license (required for publishing)
- Microsoft work or school account
- Completed Power BI dashboard (.pbix file)

## Step-by-Step Publishing Guide

### 1. Prepare Your Dashboard
- Ensure all visualizations are working correctly
- Check that all data sources are accessible
- Verify filters and slicers function as expected
- Test all interactions between visuals

### 2. Save Your Work
- Save your .pbix file locally: File > Save
- Use a descriptive name for your dashboard
- Keep a backup copy in a secure location

### 3. Sign In to Power BI Service
- Open Power BI Desktop
- Click on "Sign in" in the top right corner
- Enter your Microsoft work or school account credentials

### 4. Publish to Power BI Service
1. Click on **"File"** menu in Power BI Desktop
2. Select **"Publish"** > **"Publish to Power BI"**
3. Choose your destination workspace:
   - **My Workspace**: Personal workspace (default)
   - **Shared Workspace**: Team workspace (if you have access)
4. Click **"Select"**
5. Wait for the publishing process to complete

### 5. Access Your Published Dashboard
- Once published, you'll see a success message
- Click **"Open [YourDashboardName] in Power BI"** to view online
- Alternatively, go to [app.powerbi.com](https://app.powerbi.com)

## Working with Power BI Service

### View Your Report
1. Log in to [Power BI Service](https://app.powerbi.com)
2. Navigate to your workspace
3. Find your report in the list
4. Click to open and interact with it

### Create a Dashboard (Optional)
1. Open your published report
2. Hover over a visual and click the **pin icon**
3. Create a new dashboard or add to existing
4. Name your dashboard and click "Pin"

### Share Your Dashboard
1. Open the dashboard or report
2. Click **"Share"** button at the top
3. Enter email addresses of people to share with
4. Set permissions (view only or allow recipients to share)
5. Click **"Grant access"**

### Schedule Data Refresh (if applicable)
1. Go to workspace and find your dataset
2. Click the **"More options (...)"** menu
3. Select **"Settings"**
4. Navigate to **"Scheduled refresh"**
5. Set up refresh schedule and credentials

## Best Practices

### Before Publishing
- Remove unnecessary data columns to reduce file size
- Optimize data model for performance
- Test with sample users before wide distribution
- Document data sources and refresh requirements

### Security
- Use Row-Level Security (RLS) for sensitive data
- Regularly review sharing permissions
- Use workspace roles appropriately
- Enable audit logs for compliance

### Performance
- Use Power BI Premium for large datasets
- Implement incremental refresh for big tables
- Optimize DAX measures
- Use aggregations where possible

## Troubleshooting

### Publishing Fails
- Check your internet connection
- Verify your Power BI license is active
- Ensure data sources are accessible
- Try publishing to a different workspace

### Data Refresh Issues
- Verify data source credentials
- Check gateway connection (for on-premises data)
- Review error messages in refresh history
- Ensure data source is accessible from Power BI Service

### Visuals Not Displaying
- Check if custom visuals are certified
- Verify browser compatibility
- Clear browser cache
- Try different browser

## Additional Resources

- [Power BI Documentation](https://docs.microsoft.com/power-bi/)
- [Power BI Community](https://community.powerbi.com/)
- [Power BI Blog](https://powerbi.microsoft.com/blog/)
- [Power BI Learn](https://learn.microsoft.com/training/powerplatform/power-bi)

## Repository Structure

```
PowerBI-Dashboard-Project/
├── README.md                 # Project overview
├── PUBLISHING_GUIDE.md      # This file
├── dashboards/              # Power BI .pbix files
├── data/                    # Sample data files
├── images/                  # Screenshots and documentation images
└── scripts/                 # Data preparation scripts
```

## License
This project is intended for educational and professional development purposes.

## Contact
For questions or support, please open an issue in this repository.
