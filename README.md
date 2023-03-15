# major project
# customer conversion prediction
# Exploratory Data Analysis
(df.groupby("job")["target"].mean()*100).sort_values().plot(kind="barh")

![image](https://user-images.githubusercontent.com/117351889/225285382-dc216030-a65b-47a2-8f1d-903d86214050.png)


Interpretation

According to the above graph:

% of student claim more insurance loan than other working class
It is an ordered and linear relationship

(df.groupby("education_qual")["target"].mean()*100).sort_values().plot(kind="barh",color="green")
![image](https://user-images.githubusercontent.com/117351889/225285803-9b0bc546-bf88-4f7d-97cf-7f1dc1d232c1.png)




(df.groupby("call_type")["target"].mean()*100).sort_values().plot(kind="barh",color="orange")
 ![image](https://user-images.githubusercontent.com/117351889/225286029-90ce4f07-a471-4442-a007-1d168a94d96f.png)




(df.groupby("prev_outcome")["target"].mean()*100).sort_values().plot(kind="barh",color="red")
 ![image](https://user-images.githubusercontent.com/117351889/225286103-4d855945-a1cf-40ef-a4e9-2a8ef6ca922c.png)
   



(df.groupby("marital")["target"].mean()*100).sort_values().plot(kind="barh",color="pink")
 ![image](https://user-images.githubusercontent.com/117351889/225286249-bab982a1-f2a8-4f84-8eda-3c248cd1e4b2.png)
   


Interpretation

Based on the above graph:

% of single people buy more insurance than married
It is in linear and ordered fashion

(df.groupby("mon")["target"].mean()*100).sort_values().plot(kind="barh",color="yellow")
![image](https://user-images.githubusercontent.com/117351889/225286430-510d7533-3617-45bd-9582-fa51b5b59036.png)
  


Interpretation

Based on the above graph:

% of people in mar buy insurance than in other months
During mar month,the insurance agents can many more calls and pitch the claim




