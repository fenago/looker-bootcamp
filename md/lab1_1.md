---

# **Lab 1.1: Setting Up and Visualizing Data in Looker Using FAA Airport Data**

---

### **Objective:**
In this lab, you will set up a sandbox Looker environment, learn how to visualize data using Looker’s Explore feature, and work with Dimensions and Measures to create and customize dashboards.

---
[![Watch Video](https://go.screenpal.com/api/thumbnail?url=cZQjr3VRpCY)](https://go.screenpal.com/watch/cZQjr3VRpCY)

Click the link or the image above to watch the video demonstration: [https://go.screenpal.com/watch/cZQjr3VRpCY](https://go.screenpal.com/watch/cZQjr3VRpCY)

### **Steps:**

---

### **Step 1: Visualize Your First Measure**

In this step, you'll calculate the average elevation across all airport facilities and visualize it as a single value.

1. Log into your Looker instance using the credentials from the Quick Labs page.
2. In the Looker navigation menu, click **Explore**.
3. Under **FAA**, click **Airports**.
4. Under **Airports > Measures**, click **Average elevation**.
5. Click **Run**.
6. Click the arrow next to **Visualization** to expand the window.
7. Hover your cursor over the icons to see the available visualization options.
8. Click the **Single value** icon.
9. Click the settings gear icon for **Visualization**.
10. Click **Edit > Style**.
11. Under **Style**, change the **Value color** to your preferred color.
12. Enable **Show title**, and provide a title in the **Title override** box.
13. Save the visualization by clicking the settings gear icon next to **Run**, then select **Save > To an existing dashboard**.
14. Enter a title for the visualization: **Average elevation**.
15. Create a new dashboard titled **Airports/Flights**.
16. Click **OK**, then **Save to Dashboard**.

---

### **Step 2: Visualize Dimensions and Measures**

In this step, you will create a bar chart showing the top 5 facility types with the highest average elevation.

1. In the Looker navigation menu, click **Explore**.
2. Under **FAA**, click **Airports**.
3. Under **Airports > Dimensions**, click **Facility type**.
4. Under **Airports > Measures**, click **Average Elevation**.
5. Under **Airports > Measures**, click **Count**.
6. Set the **Row limit** to 5.
7. Click **Run**.
8. Click the arrow next to **Visualization** to expand the window.
9. Click the **Bar** icon to display the results as a bar chart.
10. Click the settings gear icon for **Visualization** and enable **Value labels** under **Values**.
11. Drag **Airports** under **Top Axes**, while **Average elevation** stays under **Bottom Axes**.
12. Under **Configure axes > Bottom 1**, enter **Count** as the axis name.
13. Save the visualization with the title **Average elevation by facility type** to your **Airports/Flights** dashboard.

---

### **Step 3: Visualize a New Measure and Dimension**

In this step, you will explore a new Measure and Dimension to add to your analysis.

1. From the **Explore** menu, click **Airports** under **FAA**.
2. Under **Airports > Dimensions**, select **City**.
3. Under **Airports > Measures**, select **Total Number of Facilities**.
4. Click **Run** to generate the query.
5. Expand the **Visualization** tab and choose the **Pie chart** icon.
6. Customize the visualization:
   - Click the settings gear icon for **Visualization**.
   - Enable **Legend** under **Series** to display the names of the cities.
   - Enable **Show percentages** under **Values** to display percentage breakdowns.
7. Save this visualization as **Facilities by City** and add it to the **Airports/Flights** dashboard.

---

### **Step 4: Load a New External Spreadsheet**

In this step, you will load an external spreadsheet into Looker to analyze new data.

1. Download or prepare a CSV file with additional data that you want to analyze (e.g., a new airport dataset with updated attributes).
2. In Looker, navigate to the **Admin** panel from the **Settings** gear icon.
3. Click on **Connections** and ensure you have access to upload new files or connect to external data sources.
4. Go back to the **Explore** menu and click **Upload Data**.
5. Select the **CSV** file from your local machine.
6. Configure the data import by mapping the file columns to the dimensions and measures in Looker.
7. After importing the file, go to **Explore** and find the newly loaded data source under **FAA**.
8. Create a visualization similar to the previous steps, using **Dimensions** and **Measures** from the newly loaded dataset.
9. Save the visualization to your existing **Airports/Flights** dashboard.

---

### **Conclusion:**
By completing these four steps, you have set up a Looker environment, created and customized visualizations using existing FAA data, explored new measures and dimensions, and successfully loaded external data to analyze. This provides a foundational understanding of Looker’s data visualization and exploration capabilities.

---
