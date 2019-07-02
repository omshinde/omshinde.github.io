---
layout: post
title:  "Google Summer of Earth Engine 2019 with Nature Conservation Foundation"
---

.center {
  text-align: center;
}

## Building an App for Robust Visualization of Ecological Status and Change in a Region

The ecological status plays an important role in defining the functioning of an ecosystem pertaining to a region. The variation in the structure of ecosystem could be a result of subsequent events happening over a time-period or due to a particular phenomenon at a time instant. There are methods in practice to understand these variations based on **remote-sensing observations**, **in-situ measurements** and **manual surveys**. When it comes to in-situ measurements or manual surveys, a lot of resources and manual labor is required to complete the procedure. On the other hand, understanding variations in parameters affecting a regional ecosystem via remote-sensing based datasets such as satellite images, airborne sensor images requires relatively lesser amount of manual labor and could provide better insights over a large geographical scale.

But, the questions which arises in front of us are - *What are the parameters which directly affect the ecological status of a region?* *What are the physical factors which influences the ecosystem?* *Does these factors have same effect for different types of ecosystem?* *How can we make use of the large database of spatial and temporal data to generate insights about the ecological status of a region?*

[Google Summer of Earth Engine](https://sites.google.com/view/summerofearthengine/home) is an amazing initiative started by Google for supporting research along with leading Indian research organizations working in **environment**, **conservation**, **water resources** and **agricultural domains**. In Google Summer of Earth Engine 2019, I have been selected to work with [Nature Conservation Foundation](http://ncf-india.org/) under the mentorship of [Dr M D Madhusudan](https://en.wikipedia.org/wiki/Mysore_Doreswamy_Madhusudan). Dr Madhusudan is an Indian wildlife biologist and ecologist and the Co-founder and Director of Nature Conservation Foundation. The NCF is actively working towards conservation of India’s unique wildlife heritage with innovative technological research and imaginative solutions. 

Now, addressing the questions raised above, it has been observed that satellite images provide us with a lot of information which could be used to understand the ecological status in a region. In the recent research, a lot of improvements has been done in defining the proxies on the satellite images which plays a significant role in defining the variation in real-world. One such example is of urbanisation. The satellite derived products and indices can show the existing settlement and built-up areas in a region. It is worth noting here that this information would provide spatial context. We can use the archives of such products to understand the temporal context over a period of years. 

{:.center}
![Google Earth Engine App]({{site.baseurl}}/assets/images/earthEngine.jpg)

Google Earth Engine provides an end-to-end platform comprising of an inventory of datasets, algorithms for processing the datasets for specific applications and several other functionalities. The most important part is that Google Earth Engine provides the implementation of algorithms even for large geographical regions which corresponds to huge computation. Moreover, with the availability of UI features, it is also possible to wrap the implementation in the form of Earth Engine Apps.

In our app, we are making complete use of the above-mentioned superb facilities provided by the Google Earth Engine platform. The app comprises of 2 modules - Frontend module and Backend module. The frontend module would comprise of the UI features and would pass the input options selected by the user to the backend module. The backend module would complete the processing and generate results. These results would again be passed to the frontend module to display on the app. The fun lies in the fact that all of these steps would be happening in the Google Earth Engine platform. 

{:.center}
![Workflow of Google Earth Engine App]({{site.baseurl}}/assets/images/soee_workflow.png)
Workflow of Google Earth Engine App

Currently, we are approaching towards the completion of the project. In the following posts, I would be adding more details about the Google Earth Engine platform, my experience of working in Summer of Earth Engine 2019 and obviously, the application which we are developing. 

Till then, Keep reading! 😊

-*Rajat*


