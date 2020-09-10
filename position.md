# Position paper of Satoru Takagi

## Papers as My presentation
First, I have prepared two short papers for this workshop to replace my presentation in the ["Native map viewer for the Web platform" session on Day 3](https://www.w3.org/2020/maps/agenda#day-3). These papers are based on the content of my position paper, which will follow in the next chapter.


* **[Decentralized Web Mapping](https://satakagi.github.io/mapsForWebWS2020-docs/De-centralizedWebMapping.html)**
* **[Quad Tree Composite Tiling and the standardization of tiling](https://satakagi.github.io/mapsForWebWS2020-docs/QuadTreeCompositeTilingAndVectorTileStandard.html)**

## Bio:

My ID on gitHub is satakagi.
I have been working on Web GIS and Web Mapping for more than a quarter of a century as a programmer/architect. And I am an employee of KDDI, a mobile communications operator in Japan. Also I am KDDI's AC Rep. at W3C.

Social infrastructure operators like KDDI have a strong interest in WebGIS and WebMapping. It has a huge demand inherently. That's why I'm in charge of KDDI's enterprise WebGIS and its basic frame work. It's called SVGMap, which is backed by a number of patented technologies. Meanwhile, I am publishing it as open source at following pages. *1,*2

* *1: GitHub repository: [https://github.com/svgmap](https://github.com/svgmap)
* *2: Home Page: [https://svgmap.org](https://svgmap.org)

And SVGMap has been standardized as a Japanese industrial standard. Its identification number is [JIS X.7197](https://webdesk.jsa.or.jp/books/W11M0090/index/?bunsyo_id=JIS+X+7197%3A2012).


## My Goals:

As the name SVGMap suggests, KDDI already made a proposal *3 for standardization of SVGMap in 2011 as one of the W3C member companies.

*3: [https://www.w3.org/Submission/2011/04/](https://www.w3.org/Submission/2011/04/)

Despite its long history, SVGMap is almost unknown to the Geo industry .
One reason is that we are focused on using it ourselves rather than selling it outside the company. Another reason is that the standardization proposals are moving towards the W3C and not the Geo industry. One of my goals this time is to make the geo industry aware of the SVGMap.

Second, I think there are many problems with the WebMap standards built by the Geo industry, such as raster and vector tiles specifications. And at SVGMap we are implementing methods that we think is better. We want to make that method known to the Geo industry.

And finally, I would like to inform the Geo industry of the philosophy of decentralized information systems, which is an essential goal of the WWW and is also partly being implemented by SVGMap. Building an aggregation site that layers data from multiple domains is not enough. This is because the function itself called aggregation is centralized.

By the way, the reason we are driven by this thought is that we are essentially Web Mapping users not a vendor.

## Desired Workshop Goals:

### Decentralized Web Mapping Task Force:

As far as W3C is concerned, Mapping simply by using web browsers is not creative. I consider existing Web Mapping services and platforms to be highly centralized. And I think it is creative to contribute to Web Mapping in W3C by launching a standardization activity with implementations for applying "decentralization", which is an important philosophy of WWW, to Mapping.

## Other Thoughts:

Based on our experience with the W3C, we find that standardizing the implementation of Web Mapping functionality as native code by browser vendors is neither realistic nor creative. Today's web browsers are establishing an framework called Extensible Web that extends the functionality of the browser as if it were native. Therefore, I think it is preferable that the decentralized Web Mapping standard is not natively implemented but is standardly implemented by such extensions.

We will register the position paper posted to the W3C in 2011 *3 as part of our position statement.