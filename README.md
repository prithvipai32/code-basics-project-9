
# Project-9 Analyzing Promotion and festive sales for AtliQ Mart

# FMCG domain

## PROBLEM STATEMENT

 ![atliq_image](https://github.com/prithvipai32/Code-Basics-project-9-FMCG-Domain/assets/160827333/99eea682-0bf7-4d1e-9297-d38f48285964)


This dashboard is designed to help AtliQ Mart analyze the promotion sales that was held during the festive periods of diwali and sankranthi on their branded products.

         It helps the company to know if their promotional offers had shown rise in their revenue and which promotions did well and which did not work well so that they can make informed decisions for their next promotional period.
         The following .csv ans .sql files were given as a dataset.
        * dim_campaigns.csv
        * dim_products.csv
        * dim_stores.csv
        * fact_events.csv
        * retail_events_db.sql

### STEPS FOLLOWED 

Step 1 : Load data into Power BI Desktop, dataset is a csv file.

Step 2 : Check and make necessary data cleaning for the given data.

Step 3 : Created custom coloumns using power query in fact_events such as revenue_before_promotion,discount and revenue_after_promotion.

Step 4 :Created measures to find Incremental revenue(IR), Incremental sold quantity (ISU), IR%, ISU%, top_bottom_stores by IR.

 Snap of created measures:

 ![image-2](https://github.com/prithvipai32/Code-Basics-project-9-FMCG-Domain/assets/160827333/5636babc-5490-4414-962e-2fc60e5619b6)

 ![image-3](https://github.com/prithvipai32/Code-Basics-project-9-FMCG-Domain/assets/160827333/fc8ae36e-e958-4137-8333-aebf2d7af7f6)

![image4](https://github.com/prithvipai32/Code-Basics-project-9-FMCG-Domain/assets/160827333/fe91aa48-baac-4f9f-8586-1ad8b2e2fc8a)

 ![image5](https://github.com/prithvipai32/Code-Basics-project-9-FMCG-Domain/assets/160827333/6a2b5627-a2bf-493e-84c2-095ea436544f)

 ![image-5](https://github.com/prithvipai32/Code-Basics-project-9-FMCG-Domain/assets/160827333/8eb6bddc-1ffd-4125-8ba4-cb40ebe698b6)

Step 5 : In the report view, under the view tab, theme was selected.Background was set.

 Step 6 : Reports were categorized into 4 pages to segregate the analysis based on factors such as Home page, Store analysis, Promo type analysis, Product and category analysis 

 ![image-6](https://github.com/prithvipai32/Code-Basics-project-9-FMCG-Domain/assets/160827333/92e40ea7-c487-4226-8fe3-f6117bc1bafe)


 Step 8 : Visual filters (Slicers) for diwali and sankranthi campaign, top/bottom choice, value filters, KPI's were added.

snapshot:
 ![1](https://github.com/prithvipai32/code-basics-project-9/assets/160827333/7ca73f9a-c424-44f5-b68e-c02515428f54)
Step 9 : Formatting was performed on visuals. Appropriate graphical representation was choosen. necessary legends, filters, Dynamic title were applied.

 Step 10 : Tool tips, bookmarks,reset button, sliders,info page, Q/A section were added for easily analyzing the data.
 
 # Report Snapshot (Power BI DESKTOP)

 1)Home page

![home_page](https://github.com/prithvipai32/Code-Basics-project-9-FMCG-Domain/assets/160827333/78d6107e-7581-45ff-9df4-9f478ea3940d)

 2)Store performance analysis

![2](https://github.com/prithvipai32/code-basics-project-9/assets/160827333/18938729-e7b7-40b8-985d-aedc9fbb165a)

3)Promotion type analysis

![3](https://github.com/prithvipai32/code-basics-project-9/assets/160827333/8596f40b-3215-4834-8487-fa0eda9aae4c)

4)Product & category analysis

![4](https://github.com/prithvipai32/code-basics-project-9/assets/160827333/4de922d9-3413-4b83-abc2-c49b5bdd03ea)

# Insights

The following inferences can be drawn from the dashboard:

Including both diwali and sankranthi campaigns:

## KPI

### [1] Total Revenue generated after promotions = 247.98 millions
### [2] Incremental revenue (IR) = 107.28 millions
### [3] Incremental sold units (ISU) = 0.23 millions
### [4] IR% = 76.3 %
### [5] ISU% = 108.31 %

## Stores
           
### [6] Store located in Mysore with Store Id STMYS-1 has generated the Highest Incremental revenue with 3.63 M

### [7] Store located in Mangalore with Store Id STMLR-0 has generated Least Incremental revenue with 0.78 M

### [8] Bangalore  city has generated High Incremental revenue of 26.74M

### [9] Trivandrum city has generated Least incremental revenue of 2.35M

## Promotion type

### [10] Promotype of 500 Cashback has generated highest IR of 91.05 M and promo type BOGOF showed increase in sales quantity by 157k units.

### [11] Percentage offers generated least revenue when compared to sales with cashback and BOGOF offers. 

### [12] Promo type  with 25% off showed decrease in its sales quantity by 6k units

## Product & Category

### [13] Product Atliq_home_essential_8_product_combo  under category Combo 1 has been the product with high IR due to 500 cash back promo during festive sales period. (Bangalore being the top performing city)


### [14] Atliq_Sonamasuri_rice(10kg) with 33% off  under category grocery & staples has been the product with least  incremental revenue post festive sales when compared with revenue before promo.
