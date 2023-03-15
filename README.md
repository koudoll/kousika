# major project
# customer conversion prediction
# Exploratory Data Analysis
(df.groupby("job")["target"].mean()*100).sort_values().plot(kind="barh")
     
<AxesSubplot:ylabel='job'>

Interpretation

According to the above graph:

% of student claim more insurance loan than other working class
It is an ordered and linear relationship

(df.groupby("education_qual")["target"].mean()*100).sort_values().plot(kind="barh",color="green")
     
<AxesSubplot:ylabel='education_qual'>


(df.groupby("call_type")["target"].mean()*100).sort_values().plot(kind="barh",color="orange")
     
<AxesSubplot:ylabel='call_type'>


(df.groupby("prev_outcome")["target"].mean()*100).sort_values().plot(kind="barh",color="red")
     
<AxesSubplot:ylabel='prev_outcome'>


(df.groupby("marital")["target"].mean()*100).sort_values().plot(kind="barh",color="pink")
     
<AxesSubplot:ylabel='marital'>

Interpretation

Based on the above graph:

% of single people buy more insurance than married
It is in linear and ordered fashion

(df.groupby("mon")["target"].mean()*100).sort_values().plot(kind="barh",color="yellow")
     
<AxesSubplot:ylabel='mon'>

Interpretation

Based on the above graph:

% of people in mar buy insurance than in other months
During mar month,the insurance agents can many more calls and pitch the claim




