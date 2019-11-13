# Use Case Applicability: How to better integrate Continuous Improvement into Security Monitoring

![logo](FingerpointingLogo.png "Active Cyber Defenders")

## Description
This github hosts my project files towards more standard SOC reports. The goal is to define an open source reporting standard for Security Operation Center reports. 

It starts with the paper about Use Case Applicability, to create a standard measuring Security Monitoring capabilities. This repo also includes my presentations I held about my taxonomy.

Suggested KPIs, as presented at HACK.LU 2019 are:

 KPI | Explanation | Target Value 
 :-------------------------- |:----------------------------------------------------| :-----:
 Number of Log Management Rule Configuration Error events per month | This value reflects the rules configured in the SIEM by the SOC Analysts. A high number suspects bad quality of rules, more training or experience needed. | < 10 % 
 Number of Announced Administrative/User Action events per month | This value reflects suppressions that should be improved. | < 10 % 
 Number of Bad IOC/rule pattern value events per month | If too many events were created by bad IOCs or rule pattern values, the source or the trust in it should be questioned. | < 5 % 
 Number of Confirmed Attack attempt without IR actions (best matched with Log Source Category) | Number of events detected but prevented by measures in place or where the alert isn’t viewed as a high risk. | > 50 % 
 Number of Confirmed Attack attempt with IR actions (best matched with Log Source Category) | Very high numbers → Security Architecture should be updated <br> Very low numbers → The rules aren‘t detecting or you are safe | :) 


The full slides will be published end of November 2019, the Video recording already can be found here: https://www.youtube.com/watch?v=NifSKzogSrI

Before FIRST, there also was a podcast published where I could talk to Chris John Riley about this taxonomy and the thoughts behind. This recording can be found here: https://media.first.org/podcasts/FIRST2019-DesireeSacher.mp3

## Authors and acknowledgment
This paper was written by [Desiree Sacher](http://www.twitter.com/d3sre)

Thank you for initially trialing the idea:
Christoph Weber and Michael Kurth 

Thank you to everyone who proof read it before publication:
Raphaël Vinot, Corsin Camichel, Eireann Leverett, Florian Roth, Ian Amit, Meline Sieber, Frank Boldewin, Jochen Raymaekers, Francesco Picasso and Amanda Berlin 

## Licence
The paper was published under Creative Commons BY License: https://creativecommons.org/licenses/by/4.0/

