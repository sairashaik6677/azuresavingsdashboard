# Azure Savings Dashboard
I have created this dashboard to display the savings made due to the purchase of Reservations (RI) or Savings Plans (SP) or by signing the agreement with Microsoft to get Azure Commitment Discounts (ACD).

This dashboard is helpful for Customers who 
* Purchased Reservations or
* Purchased Savings Plan or
* Signed Monthly Azure Consumption Commitment (MACC) and got a special discounted price

Customers can view their savings by uploading the Amortized files into this Power BI file. Check the attached setup pdf file for details on setting up this dashboard.

Please note that all the screenshots on this page are mock-up screens; hence each screen data will differ. These screens are captured to show you what the screen looks like based on the data you will be uploading.

# Table of Contents
* [Azure Savings Dashboard Overview](#overview)
  * [Filtering](#Filtering)
* [Savings Dashboard Page](#savingsdashboard)
  * [Total Savings View](#totalsavingsview)
  * [Savings by Month](#savingsbymonth)
  * [Savings Utilized](#savingsutilized)
  * [Savings Underutilized](#savingsunderutilized)
* [Savings Dashboard Page](#savingsdashboard)
* [Reservations Savings Page](#ripage)
* [Savings Plan Savings Page](#sppage)
* [ACD Savings Page](#acdpage)

# Azure Savings Dashboard Overview <a name="overview"></a>
The Savings dashboard provides an overview and details of Savings made from RI, SP, and ACD.

## Filtering <a name="Filtering"></a>
Customers can filter the Savings by Meter Category / Service, Meter Subcategory / Instance Type, Date, Subscription Name, Tags, Resource Location, Resource Group, and Resource Name. These filters can be helpful if you need to view Savings based on specific criteria.

For Example, Customers want to view the Savings made in specific subscriptions or based on particular tags or months.

![image](https://user-images.githubusercontent.com/130760607/232172097-25ec06da-9bbc-4729-b7c6-edc88ea0bd82.png)


# Savings Dashboard Page <a name="savingsdashboard"></a>
This page summarizes savings from RI, SP, and ACD, monthly Savings, and Utilized and Underutilized RI and SP costs.

## Total Savings View<a name="totalsavingsview"></a>
This section provides a high-level summary of savings made due to RI, SP, and ACD.

For RIs
* Savings used/utilized - Savings made due to the purchase of RIs.
* Savings unused/underutilized - Cost for the number of hours reservation wasn't used in a day and the monetary value of the waste.
* Savings - Sum of Savings used and unused.
	
For SP
* Savings used/utilized - Savings made due to the purchase of the SP
* Savings unused/underutilized - Cost for the number of hours SP wasn't used in an hour and the monetary value of the waste.
* Savings - Sum of Savings used and unused.

For ACD
* PayG Cost - Public listing cost.
* ACD Cost - Azure commitment discount applied cost (This is applicable only for MACC customers)
* ACD Savings over PayG - Public listing cost minus ACD cost, i.e., instead of paying the public listing amount customer paid discounted amount.

![image](https://user-images.githubusercontent.com/130760607/232178577-83ee7ff0-e6f4-400c-8aa3-f86ea740dc59.png)

## Savings by Month <a name="savingsbymonth"></a>
Savings made due to RI, SP, and ACD for selected months from filters.
![image](https://user-images.githubusercontent.com/130760607/232177123-05ddc4af-adea-41f7-996e-228332801e16.png)

## Savings Utilized <a name="savingsutilized"></a>
Realized RI and SP savings
![image](https://user-images.githubusercontent.com/130760607/232172042-20fdc289-63bd-42d6-ab5f-0dc6de2dd09e.png)

## Savings Underutilized <a name="savingsunderutilized"></a>
Unused cost due to commitment not met for SP and RI
![image](https://user-images.githubusercontent.com/130760607/232172420-d7fe1b1b-cc25-4834-afa7-dcfd9e1964e9.png)

# Reservation Savings Page <a name="ripage"></a>
Granular drill-down view to check the subscription name, resource location, resource group, and resource name for Reservation savings utilized.

![image](https://user-images.githubusercontent.com/130760607/232178344-e6a08e1b-cae4-4702-8a0b-5ec9e1254533.png)

![image](https://user-images.githubusercontent.com/130760607/232178354-3c4af8fb-2ca3-413a-aaa4-cf89effe1bc7.png)

![image](https://user-images.githubusercontent.com/130760607/232178364-68937592-5dec-4796-bd91-90251c06c22c.png)

![image](https://user-images.githubusercontent.com/130760607/232178376-b73b6134-fb23-447a-8edb-31c59d35af65.png)


# Savings Plan Savings Page <a name="sppage"></a>
Granular drill-down view to check the subscription name, resource location, resource group, and resource name for Savings Plan savings utilized.

![image](https://user-images.githubusercontent.com/130760607/232177865-042e7817-bc01-4d06-9908-e883b372630d.png)

![image](https://user-images.githubusercontent.com/130760607/232177924-f548e1c3-13ce-45cf-b51c-07a7f836ba17.png)

![image](https://user-images.githubusercontent.com/130760607/232177964-dd75d207-29a8-4a71-be9d-5c2069e46ebc.png)

![image](https://user-images.githubusercontent.com/130760607/232178014-4736807e-0df3-42a5-82d0-8f1416f57854.png)

![image](https://user-images.githubusercontent.com/130760607/232178036-265b793c-30bc-417f-ada9-4cd98e10f929.png)

# ACD Savings Page <a name="acdpage"></a>
Service wise, no.of units and savings made along with an option to drill-down view to check the subscription name, resource location, resource group, and resource name for Savings made due to ACD.

![image](https://user-images.githubusercontent.com/130760607/232178712-7615857a-d25e-485b-b85a-175886133695.png)

![image](https://user-images.githubusercontent.com/130760607/232178816-4803a53b-2b18-4a2b-acf0-f2f3d1013e10.png)

### Feedback and Suggestions
I welcome any feedback or suggestions on this dashboard! If you find any bugs or have ideas for improvements, please create an issue on this repository, and I'll get back to you as soon as possible.

To create an issue, click on the "Issues" tab at the top of this page and then click the green "New Issue" button. Please provide as much detail as possible about your issue or suggestion, including any steps to reproduce the problem or implement the recommendation.

I appreciate your help in the making this dashboard better for everyone!

