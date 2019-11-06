Azone is an E-commerce website which sells a variety of products at its online platform. Azone records user behaviour of its customers and stores it as a log. However, most of the times, users do not buy the products instantly and there is a time gap during which the customer might surf the internet and maybe visit competitors websites

Now, to improve sales of products, Azone has hired Btech, an Adtech company which built a system such that ads are being shown for Azone's products on its partner website

If a user comes to Azone's website and searches for a product and then visits these partner websites or apps, his /her previously viewed items or their similar items are shown on as an ad. If the user clicks this ad, he/she will be redirected to the Azone's website and might buy the product

**Dataset Description**

1)
Train data contains the impression logs during 2018/11/15 - 2018/12/13 along with the label which specifies whether the ad is clicked or not

**train.csv**

Variable	           | Definition
--------------------|---------------------------------------------------
Impression_id	      | Ad impression id            
Impression_time	    | Time of impression at partner website
User_id	            | User_id
App_code	           | Appication code for a partner website where the ad was shown
Os_version	         | Version of the operating system
Is_4g	              | 1 using 4g, 0- no 4g
Is_click	           | (target) when user clicked the ad (1- click , 0 -no click)



2) 
View log of the users (2018/10/15- 2018/12/11) from Abay's website

view_log.csv


3)
item_data.csv

4)
test.csv- impressions to predict the click rate


 

