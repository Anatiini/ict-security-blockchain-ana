# h5 HelSec

## Jos Helmich - Industrial Cyber Security
Jos started with his history, 30+ years in software engineering.

Member of the ENISA Advisory group. ENISA is a multilayer framework for good cybersecurity practices for AI.

Talked about GDPR, how EU legislation regarding cybersecurity goes. And also about US cyber security regarding the legislation there and the presidential executive orders.

Made a "map" how the industry network should be setup. First there is the "Office Zone" which is connected to the internet, and then the information from the "Office Zone" gets sent to a "DMZ" (De-Militarized Zone) which is protected by 2 firewalls.
"Everything dies" in the DMZ. And then the data goes to the Industry side, which isn't itself connected to the internet. It is only connected through the DMZ.

The 622443 things went a bit over my head, especially since the mic was a bit quiet, so couldn't really understand that part.

Then he talked about EU's Artificial Intelligence Act, which is divided into three parts: Product safety requirements, GDPR, and cybersecurity resilience.

I would've liked for him to delve a bit more on how the industry network is setup, and the risks and benefits on it.

## Joona "Rinorragi" Immonen - My experiences on Defender External Attack Surface Management

Soccer dad, has been actively hobbying cyber security from the year 2000.

Went through Microsoft Cybersecurity Reference Architecture, basically how one should architect their companies IT.

The Defender External Attack Surface Management helps a company identify the leaks or publicly available data which could be used for attacking the company.
It tries to identify HTTP responses, Javascript components, TLS certificates, open ports, vulnerabilities and historical information about different CMS versions.

It also gives a brief overview of the different attack surfaces which could be used against a company. It lists common pain points, sensitive services, TLS and domain expirations and IP reputations.

The program costs 0.011€/day per asset of which the EASM finds.

Joona also compared the EASM to AMASS, which is a similar kind of tool.

EASM had a much faster setup, but enumeration took on average longer. Both give results when they are scanning, but EASM has excellent usability unlike AMASS.
Basically AMASS is a bit harder to use, but if you know your stuff, it is great for scripting and the source code is available.
AMASS good for long time investment or pentesting, EASM is for a cleaner overview and has a good ROI.

This presentation was better than the first I think. But this one had a lot more tech-savvy lingo, which I wasn't very familiar with. This made it more difficult to follow along, so I must have missed some key points, but I think I got the majority of the
talking points which were introduced.


