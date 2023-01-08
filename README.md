# Cloud Pricing Case

Investigating the appropriate price difference between On-Demand and Reserved consumption of cloud resources. 


The purpose of this paper is to compare pricing plans for two cloud computing services On-Demand service and Reserved service. On-Demand service suggests weekly payments for actual consumption of cloud resources while Reserved suggests payments in advance for a certain period of time, say a year. 

The main idea that consuming one instance of On-Demand service is equal to consuming $\alpha$ instances of Reserved services. The intuition behind this is quite simple - as customers goes into On-Demand contract, the provider will have to create additional reserves $(\alpha - 1$ instance) in order to be able to meet extra demand. Naturally, the provider will charge the client for maintaining this reserves and consequently buying one instance of On-Demand service will be the same for the customer as buying $\alpha$ instances of Reserved service

In this paper we will try to find $\alpha$ with Monte-Carlo approach, assuming we know interest rate $r$, period of time required to deploy new capacities $T$, standard deviation of users' consumption $\sigma$ and users' consumption correlation $\rho$.
