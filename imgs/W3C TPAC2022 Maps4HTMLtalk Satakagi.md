# W3C TPAC2022 Maps4HTML meeting talk
This is the speech transcript for **[this slide [PDF]](W3C%20TPAC2022%20Maps4HTMLtalk%20Satakagi.pdf)**.

## Page1 : front cover

**SVGMap in the Japanese Disaster Response Community**

## Page2 : Japanese WebGIS/Mapping user community involved in disaster response

There is a community in Japan consisting of infrastructure providers, government organizations, and the academies that support them, all of whom need to utilize Web GIS to address disaster response. It's called the [Tokyo Metropolitan Resilience Project](https://forr.bosai.go.jp/e/).([video](https://www.youtube.com/watch?v=WaDHFjUKcks)) KDDI is also a member of this community.

## Page3 : Comments from the Disaster Response Community

While this community sees Web Maps as an important role in disaster response, they also see the challenges noted here.
They are users rather than providers of information. KDDI, an operator of telecommunications infrastructure, is in the same position in the context of disaster response.
Numerous pieces of information that may be necessary for disaster response are already available individually on the Web.
However, since it is not possible to put them together, they are not very useful.
Besides, much of the information has already been put on separate web maps for each.
It would be very useful if it were possible to overlay the published map information as is.
Since we can't even do that now, we have to open two browser windows and compare them visually. How primitive we resort to only!

## Page4 : Reference Survey Results of Information Required for Disaster Response in Japan and its Availability to the Public By Tokyo Metropolitan Resilience Project

[This table shows the results of a survey](https://www.jstage.jst.go.jp/article/jdr/16/4/16_676/_pdf) of the data required for disaster response in Japan by its community. 
The table show that most of the information is published as individual web map services.

## Page5 : Current Situation of Disaster-Related Information - Silos

Government organizations and infrastructure operators publish their own information on the Web as individual Web pages that may be useful for disaster response.
For example, there are government organizations that publish hazard maps, government organizations that publish weather forecasts and earthquake bulletins, organizations that publish information on transportation system operations, electricity supply, telecommunication availability, and so on.
They all have individual websites, published as their own Web Map service. For the ordinary user, these are silos as they are.

## Page6 : Limitations of Web 2.0

It is easy to imagine that knowledge obtained by combining these diverse information sources is crucial to disaster response.
In the era of Web 2.0, a similar attempt has been made with a mechanism called "mashup service”.
But for such services, a business model, or monetization mechanism, was essential. This is one of the aspects that created the platform and promoted the centralization of the Web.
On the other hand, disaster response is basically hardly a monetization target. There is the aspect of public benefit.
Another aspect is that disasters are extremely diverse and difficult to predict, making it difficult to narrow down what information to mash up. Users want to mashup information from among all the information available on the Web, selecting what they need in a flexible manner. Therefore, the user should have the freedom to choose the source of the mashup. However, mashup services in Web 2.0 could only mashup sources for which the platformer could build a business model. As long as we rely on services, it will be difficult to exceed this limit.

## Page7 : OSINT：Open-source intelligence for disaster response

We are sure you all know the words [Open-source intelligence](https://en.wikipedia.org/wiki/Open-source_intelligence). It attracted a lot of attention in February of this year.
Open-source intelligence is a way of acquiring knowledge by collecting information that platforms have not been able to mash up, but that is available mainly on the Web, mostly by manually collecting it and comparing it with each other.
This is possible only by freely exploring and putting together every possible thing on the Web, which was not possible in the Web 2.0 mashup.
You can imagine that this concept is very important in disaster response as well. Namely, there is a need for open-source intelligence for disaster response.


## Page8 : Does Web3 say it all about the decentralized Web? No.

The centralized system of information distribution established in Web 2.0, in which platform services aggregate information and distribute it, seems to be seeking changes to de-centralize it, mainly from the aspect of monetization.　Well, that is Web3.
However, from the standpoint of users of information, it may not be of much interest. For the user, it may just be a change in where the money is paid after all.
Rather, it may be much more innovative for users to freely combine all kinds of information like open-source intelligence to obtain advanced knowledge. And this would be one of the values of becoming a decentralized Web.

## Page9 : Making existing stand-alone WebMap sites into an SVGMap layers

I responded to the community's need to be able to overlay existing stand-alone Web Map sites as much as possible with [SVG Map](https://svgmap.org/), which has a decentralized architecture.
First, the original Web Map site was analyzed. 
Using the findings from that, a micro web App based on SVG Map's Layers as Web App architecture was developed.
This sequence of prototyping has been done, and continues to be done, for as many layers as I deemed necessary.
[The webApp was insulated in layers](../De-centralizedWebMapping.md), and the small size of the application allowed for rapid development, so it could be expanded as much as needed. Also, thanks to its [highly flexible tiling architecture](../QuadTreeCompositeTilingAndVectorTileStandard.md), it was easy to implement content for sites with special tiling schemes.
Currently, the number of layers implemented is about to reach 800, which is probably the largest number in Japan, and is capable of covering all information necessary for disaster response.

## Page10 : De-centralized Disaster Management Web GIS Study Group

In recognition of this achievement, some core members of the disaster response community established a new study group
They focus on the use of world wide web for disaster response, but I consider it to include important world wide web issues and the search for its evolution that were not focused on in Web 2.0, nor even in Web 3.
One of the characteristics of this community is that users, not information providers, vendors, or platformers, are the stakeholders. This is a very different characteristic from Web3. In addition, several web professionals participate in this community.
I feel that this is one of the organizations that can contribute to the healthy progress of the World Wide Web.

