## Managing Security in Google Cloud
- Day 1, [Managing Security in Google Cloud](https://www.cloudskillsboost.google/course_templates/382). This has the labs throughout and downloadable lecture notes at the bottom.
## Security Best Practices in Google Cloud
- Day 2, [Security Best Practices in Google Cloud](https://www.cloudskillsboost.google/course_templates/87). This has the labs throughout and downloadable lecture notes at the bottom.
## Mitigating Security Vulnerabilities on Google Cloud
- Day 3, [Mitigating Security Vulnerabilities in Google Cloud](https://www.cloudskillsboost.google/course_templates/88). This has the labs throughout and downloadable lecture notes at the bottom. [Choosing API tooling in GC](https://cloud.google.com/blog/products/application-modernization/choosing-between-apigee-api-gateway-and-cloud-endpoints) is a helpful blog post.
#### Follow-on learning links
- You can try the [Cloud Logging on Kubernetes Engine](https://www.cloudskillsboost.google/focuses/10910?parent=catalog) lab, which will use up some of your Cloud Skills Boost credits but might be relevant. I unfortunately can't point you to anything with Cloud IDS and GKE, but we can discuss bespoke training content if that's something you decide to pursue. :) I also think this quest might be useful, [Google Cloud's Operations Suite on GKE](https://www.cloudskillsboost.google/quests/133). 
#### Misc other links
- [Error budget template from Google's SRE workbook](https://sre.google/workbook/error-budget-policy/)
- [Chronicle, SIEM/SOAR from Google](https://chronicle.security/) is newer and doesn't have much documentation or training material; happy to put you in touch with Appsbroker for them to offer some bespoke training content on using it.
#### Deprecations
- So annoying, I know! :) But inevitable in the world of tech. [Cloud Debugger](https://cloud.google.com/debugger/docs/deprecations) is disappearing, and Snapshot Debugger (the suggested replacement) too. I'll update when a good final choice emerges. For GKE, [PodSecurityPolicies](https://cloud.google.com/kubernetes-engine/docs/deprecations/podsecuritypolicy) are being deprecated and there are a few different alternatives linked there. We tend to go Gatekeeper/Autopilot but there's no firm best practise so it's down to what works for your business.
#### Stay in touch :)
- [My LinkedIn](https://www.linkedin.com/in/virginiaeroberts/) is here for anyone wanting to stay in touch, or if you come up with any questions!



