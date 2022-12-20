---
title: "The Demo"
chapter: true
weight: 60
---

## The Demo


### The first step of the demo is to log in to the GDemo Pointillist instance with your provided credentials. You can find the link to the GDemo Site HERE

Once inside the Pointillist solution, open up a new tab and go to the “dashboards” section. In the Dashboards section, we are going to showcase what has been generated within the Genesys Contact Center Health dashboard below.


![TheDemo](/images/Demo1.png)

On the left column of the user interface, you can toggle between several different customized views. For this demo use case we want to analyze the “Agent Escalation trends” tab. Inside this report I get detailed insights into exactly how, when and why customers are reaching agents. 

![TheDemo](/images/Demo2.png)

Our demo organization, GBank is using Pointillist to oversee all customer journeys relating to “Money Transfers.” An executive member from GBank is continuously monitoring the health of all Move My Money journeys to ensure time and costs stay consistent. 

Within Pointillist we can configure intuitive alerts to notify users when an expected threshold is exceeded. We just received an Alert from the Pointillist platform indicating there is a large spike in costs and as we explore more, we are brought directly to the corresponding dashboard via that custom alert.

As a business focused executive, I recognize that this is a critical aspect to both my customer’s experiences as well as my bottom line. I may not have the bandwidth to dive any further than the surface level insights from alerts, so I’m going to reach out through the Pointillist community and ask an Analyst to get to the bottom of it. Pointillist supports the needs of everyone from the financially focused executive to the data driven analyst. 


![TheDemo](/images/Demo3.png)

The next step for the Analyst is to Open the Alerts panel and explore the insights. 

![TheDemo](/images/Demo4.png)

The alerting system detected an anomaly inside the data and it is advising you to drill down deeper into these insights. As you can see in the alert, you have a reference to the dashboard. Click on it to go back to the dashboard where the alert occurred

![TheDemo](/images/Demo5.png)

Drill-down clicking the title of the widget and you will be redirected to the Add Payee sub journey. Our next step is to dive deeper into the journey interaction itself. You can see this Journey is the source of that chart we reviewed earlier, capturing the rate of agent transfers.

![TheDemo](/images/Demo6.png)

What we are finding is a list of customers from all communication channels that took this exact same customer path.  

- The customer received their bill,
- As advised for ease of use, went to the mobile app to pay the bill
- Needed to add a new payee, and then...
- Either successfully paid the bill, or in some cases, needed to talk to an agent first.  We had seen that spike in conversion, so I’d like the Pointillist AI to help me understand why.
 
Now, go to Insights (copy the journey in your workspace if you want to build your own insight) and select the insight trying to reduce the start an agent conversation. You will notice a pop up that provides at the moment insights to dive deeper into. 

![TheDemo](/images/Demo7.png)

At this point, Pointillist will begin looking at all of the interactions that proceed this one, all the attributes of the interactions and customer attributes, all through the lens of minimizing agent conversations. You can click on the chart insight.

What Pointillist found is not just an event it wants me to look at, but also the chart telling me why it thinks it's interesting...
- In this case, it’s saying the likelihood of starting an agent conversation is now dependent on my phone operating system. Essentially all the calls are coming from the iOS platform.
- Combining this information with the fact that we have a huge spike in calls, we know exactly what our problem is
Now that I’ve uncovered the root cause of the issue, I can quickly notify IT of the issue, so they can start working on fixing the iOS version of the app. 
- In the meantime, I need to orchestrate a real-time workaround for customers using the iOS version of the mobile app until the bug can be fixed.  
- I ask the chat channel manager to quickly create a new bot script that will take in the information needed to add a payee. The bot will appear when an iOS user tries to manually add a new payee. 

