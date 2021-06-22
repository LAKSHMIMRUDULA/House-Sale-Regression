# House-Sale-Regression
content: 1.Loading and Checking data
2.Data preprocessing 
3.Creating Models

Linear Regression
polynomial Regression
SVR(Support Vector Regression)
Decision Tree
Random Forest
4.Conclusion
![image](https://user-images.githubusercontent.com/77747784/122896874-21608d00-d367-11eb-91b6-4c982162e113.png)
![image](https://user-images.githubusercontent.com/77747784/122896971-376e4d80-d367-11eb-888b-966e5f5fe51c.png)
![image](https://user-images.githubusercontent.com/77747784/122897044-435a0f80-d367-11eb-9e78-2214bef17d2f.png)
![image](https://user-images.githubusercontent.com/77747784/122897096-4ead3b00-d367-11eb-8a75-ca947aaf6183.png)
![image](https://user-images.githubusercontent.com/77747784/122897142-5a98fd00-d367-11eb-9470-68e58dad844a.png)
![image](https://user-images.githubusercontent.com/77747784/122897189-64bafb80-d367-11eb-924c-bd2737a215dd.png)
![image](https://user-images.githubusercontent.com/77747784/122897276-78666200-d367-11eb-8d3f-4899c98d08da.png)
![image](https://user-images.githubusercontent.com/77747784/122897348-8a480500-d367-11eb-8a96-996d18503b56.png)
![image](https://user-images.githubusercontent.com/77747784/122897448-a5b31000-d367-11eb-8134-72bd1af3d903.png)
![image](https://user-images.githubusercontent.com/77747784/122897512-b499c280-d367-11eb-97e0-46f09edcadb5.png)
![image](https://user-images.githubusercontent.com/77747784/122897678-d5faae80-d367-11eb-882e-396729bb946d.png)
![image](https://user-images.githubusercontent.com/77747784/122897733-e579f780-d367-11eb-9dbe-506634129588.png)
I split the date column into "year","month","day" columns.These columns are located on the far right.Then I dropped the date column
![image](https://user-images.githubusercontent.com/77747784/122897847-ffb3d580-d367-11eb-85a2-336fad57f558.png)
![image](https://user-images.githubusercontent.com/77747784/122897960-1c500d80-d368-11eb-8e44-18dd1af1be86.png)
![image](https://user-images.githubusercontent.com/77747784/122898126-43a6da80-d368-11eb-86d1-3ba150c0a4ad.png)
![image](https://user-images.githubusercontent.com/77747784/122898194-50c3c980-d368-11eb-9982-d6103a448e3d.png)
![image](https://user-images.githubusercontent.com/77747784/122898263-5d482200-d368-11eb-9ccb-acdf59d4a9f0.png)
![image](https://user-images.githubusercontent.com/77747784/122898326-6a651100-d368-11eb-9448-5f58f71a8c2f.png)
![image](https://user-images.githubusercontent.com/77747784/122898571-9e403680-d368-11eb-80f5-c208e0ccb880.png)
![image](https://user-images.githubusercontent.com/77747784/122898936-f2e3b180-d368-11eb-9b51-e797f6a6ea4b.png)
![image](https://user-images.githubusercontent.com/77747784/122898972-ff680a00-d368-11eb-8807-563ea5b377d7.png)
![image](https://user-images.githubusercontent.com/77747784/122899017-0bec6280-d369-11eb-8698-e6ad9e92198d.png)
![image](https://user-images.githubusercontent.com/77747784/122899071-1b6bab80-d369-11eb-811e-9b20699ed3ee.png)
![image](https://user-images.githubusercontent.com/77747784/122899144-2de5e500-d369-11eb-940a-d248af9bc217.png)
![image](https://user-images.githubusercontent.com/77747784/122899186-39d1a700-d369-11eb-93f6-4280ba370015.png)
![image](https://user-images.githubusercontent.com/77747784/122899231-4655ff80-d369-11eb-8bb8-48fb83e9d210.png)
![image](https://user-images.githubusercontent.com/77747784/122899286-5372ee80-d369-11eb-9e9c-8e7e90f2db6b.png)
![image](https://user-images.githubusercontent.com/77747784/122899348-61c10a80-d369-11eb-9fcd-bbbf423cf807.png)
![image](https://user-images.githubusercontent.com/77747784/122899439-73a2ad80-d369-11eb-93cb-aff20dfc5c3a.png)
![image](https://user-images.githubusercontent.com/77747784/122899521-85845080-d369-11eb-9c36-56789392dd8f.png)
![image](https://user-images.githubusercontent.com/77747784/122899611-992fb700-d369-11eb-8e4f-00872b2b8a5c.png)
![image](https://user-images.githubusercontent.com/77747784/122899677-a64ca600-d369-11eb-960d-32256db50738.png)
![image](https://user-images.githubusercontent.com/77747784/122899776-be242a00-d369-11eb-8088-726f12a9dd34.png)
![image](https://user-images.githubusercontent.com/77747784/122899821-caa88280-d369-11eb-9e66-c33b26414915.png)
comments on the results
Although Decision Tree has the highest R2 score(99.99),I think the most sussessful model for regression of this dataset is "Random Forest".Because 99.99 is such a perfect score it should not be,there may be some mistakes somewhere Also,the variable that affects the price the most is "sqft_living" with +0.70 correlation value.










