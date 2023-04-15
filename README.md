# Azure Savings Dashboard
I have created this dashboard to display the savings made due to the purchase of Reservations (RI) and Savings Plans (SP) and by signing the agreement with Microsoft to get Azure Commitment Discounts (ACD).

This dashboard is helpful for Customers who 
* Purchased Reservations or
* Purchased Savings Plan or
* Signed Monthly Azure Consumption Commitment (MACC) and got a special discounted price

Customers can view their savings by uploading the Amortized files into this Power BI file. For details on setting up this dashboard, check the attached setup.doc file.

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

##Total Savings View<a name="totalsavingsview"></a>
This section provides a high-level summary of savings made due to RI, SP, and ACD.

For RIs
* Savings used/utilized - Savings made due to the purchase of RIs.
* Savings unused/underutilized - Cost for the number of hours reservation wasn't used in a day and the monetary value of the waste.
* Savings - Sum of Savings used and unused.
	
For SP
* Savings used/utilized - Savings made due to the purchase of the SP
* Savings unused/underutilized - Cost for the number of hours SP wasn't used in a day and the monetary value of the waste.
* Savings - Sum of Savings used and unused.

For ACD
* PayG Cost - Public listing cost.
* ACD Cost - Azure commitment discount applied cost (This is applicable only for EA customers)
* ACD Savings over PayG - Public listing cost minus ACD cost, i.e., instead of paying the public listing amount customer paid discounted amount.

![image](https://user-images.githubusercontent.com/130760607/232172006-12d5b92d-c852-4024-8608-ac8d735058f3.png)

## Savings by Month <a name="savingsbymonth"></a>
Savings made due to RI, SP, and ACD for selected months from filters.
![image](https://user-images.githubusercontent.com/130760607/232172038-d9a715d6-7599-413c-9b8c-923c724471eb.png)

## Savings Utilized <a name="savingsutilized"></a>
Realized RI and SP savings
![image](https://user-images.githubusercontent.com/130760607/232172042-20fdc289-63bd-42d6-ab5f-0dc6de2dd09e.png)

## Savings Underutilized <a name="savingsunderutilized"></a>
Unused cost due to commitment not met for SP and RI
![image](https://user-images.githubusercontent.com/130760607/232172420-d7fe1b1b-cc25-4834-afa7-dcfd9e1964e9.png)

# Reservation Savings Page <a name="ripage"></a>
Granular drill-down view to check the subscription name, resource location, resource group, and resource name for Reservation savings utilized.

![image](https://user-images.githubusercontent.com/130760607/232173015-199ff40f-2be9-4778-ba34-9762562c9146.png)

![image](https://user-images.githubusercontent.com/130760607/232173010-952bb506-b5c2-4a13-81d2-83b8301dedc9.png)

# Savings Plan Savings Page <a name="sppage"></a>
Granular drill-down view to check the subscription name, resource location, resource group, and resource name for Savings Plan savings utilized.

![image](https://user-images.githubusercontent.com/130760607/232173297-fb8b3d0f-5eba-407b-b25d-ad50c47d7bda.png)

# ACD Savings Page <a name="acdpage"></a>
Service wise, no.of units and savings made along with an option to drill-down view to check the subscription name, resource location, resource group, and resource name for Savings made due to ACD.

![image](https://user-images.githubusercontent.com/130760607/232173680-adc62ecf-4f69-4da9-a102-bb41cf481683.png)

### Feedback and Suggestions
I welcome any feedback or suggestions on this dashboard! If you find any bugs or have ideas for improvements, please create an issue on this repository and I'll get back to you as soon as I can.

To create an issue, click on the "Issues" tab at the top of this page and then click the green "New Issue" button. Please provide as much detail as possible about the issue or suggestion you have, including any steps to reproduce the problem or implement the suggestion.

I appreciate your help in making this dashboard better for everyone!

### Disclaimer
The sample power bi template is not supported under any Microsoft standard support program or service. The sample power bi template is provided AS IS without warranty of any kind. Microsoft further disclaims all implied warranties including, without limitation, any implied warranties of merchantability or of fitness for a particular purpose. The entire risk arising out of the use or performance of the sample power bi template and documentation remains with you. In no event shall Microsoft, its authors, or anyone else involved in the creation, production, or delivery of the power bi template be liable for any damages whatsoever (including, without limitation, damages for loss of business profits, business interruption, loss of business information, or other pecuniary loss) arising out of the use of or inability to use the sample power bi template or documentation, even if Microsoft has been advised of the possibility of such damages.


