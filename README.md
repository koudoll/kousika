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
     



(df.groupby("call_type")["target"].mean()*100).sort_values().plot(kind="barh",color="orange")
     



(df.groupby("prev_outcome")["target"].mean()*100).sort_values().plot(kind="barh",color="red")
     



(df.groupby("marital")["target"].mean()*100).sort_values().plot(kind="barh",color="pink")
     


Interpretation

Based on the above graph:

% of single people buy more insurance than married
It is in linear and ordered fashion

(df.groupby("mon")["target"].mean()*100).sort_values().plot(kind="barh",color="yellow")
     


Interpretation

Based on the above graph:

% of people in mar buy insurance than in other months
During mar month,the insurance agents can many more calls and pitch the claim




