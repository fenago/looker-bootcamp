---

# **Lab 1_3: Loading Course Data into Your Looker Environment**

---

## **Overview:**
In this lab, you will learn how to import external data, specifically the **Element Rental Data**, into your Looker environment. This will ensure that everyone in the course, regardless of whether you are using the sandbox environment or your own Looker instance, is working with the same data throughout the course. Follow along with the steps carefully, as this is essential for the rest of the labs in this course.

---

### **Step 1: Log into Your Looker Environment**

1. If you're using the sandbox environment:
   - **Task**: Go ahead and start your sandbox environment by logging into Quick Labs and starting the Looker sandbox. 
   - **Task**: Log in with your temporary credentials as provided.

2. If you already have access to your own Looker instance:
   - **Task**: Log into your instance as you normally would.

3. **Reminder**: If you are using a sandbox environment, you'll need to complete this process each time your environment refreshes (which happens every hour). Be prepared to re-run these steps if needed.

---

### **Step 2: Enable Development Mode**

1. **Task**: In Looker, click on **Develop** from the left-hand menu.
   
2. **Task**: Turn on **Development Mode** (you should see an option to enable it at the top of the screen).
   - This is crucial, as you’ll be editing files in LookML, and development mode allows you to make and save changes without affecting other users.

---

### **Step 3: Open a Project**

1. **Task**: If you're using the sandbox environment, select the project labeled **Quick Labs Flights**. 
   - If you’re using your own Looker instance, select any available project from the **Develop** menu. 

2. **Task**: Once inside the project, you’ll see a list of files in the **File Browser** on the left side. You are looking for a file with a **.model** extension (it will likely be called **looker_basic.model** if you’re in the sandbox).

---

### **Step 4: Edit the Model File**

1. **Task**: Open the model file that you located in the previous step.
   
2. **Task**: Scroll to the bottom of the file and add a few lines of spacing. This will be the area where you paste the provided LookML for the **Element Rental Data**.

3. **Task**: Open the **Element Rental LookML** text file, which has been provided in the resources section of the course. This file contains the LookML code for the data you will be importing.
   
4. **Task**: Copy all the content from the **Element Rental LookML** file, starting with `new_product` and continuing to the end.

---

### **Step 5: Paste and Save the LookML Code**

1. **Task**: Paste the copied LookML code at the bottom of the **.model** file in Looker.
   
2. **Task**: After pasting the code, click **Save Changes**.

---

### **Step 6: Navigate Back to the Explore Menu**

1. **Task**: Once you’ve saved the changes, navigate back to the Looker homepage by clicking **Looker** in the top left corner of the screen.

2. **Task**: Click on **Explore** from the left-hand menu.

3. **Task**: You should now see a new category for **Element Rental Data** listed under the available Explores.

4. **Task**: Click on **Element Rental Data**. Inside, you should see multiple data categories, including **Sales** and **Inventory**.

---

### **Step 7: Verify the Data Import**

1. **Task**: Click on **Sales** and run a simple query (e.g., select **Product** and **Count**) to verify that the data has been successfully imported.
   
2. **Task**: Check if the correct data appears. You should see relevant results for products, sales, or inventory.

---

### **Step 8: Repeat After Refresh**

1. **Note**: If you’re using the sandbox environment, remember that your environment resets after one hour. After each reset, you will need to repeat these steps to re-import the data. 
   
2. **Task**: Practice this process at least twice so that you become comfortable with re-importing data efficiently.

---

### **Conclusion:**

By completing this lab, you’ve successfully imported external data into Looker and learned how to configure your instance with custom data sources. This process is essential as it allows you to follow along with the rest of the course using the same data set.

If you have any issues or questions, feel free to reach out for assistance.

---
