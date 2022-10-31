# FreeCycle



A basic GitHub repository example for new [Call for Code](https://developer.ibm.com/callforcode/) projects and those that join the Call for Code with The Linux Foundation deployment initiative. Not all sections or files are required. You can make this as simple or as in-depth as you need. And don't forget to [join the Call for Code community](https://developer.ibm.com/callforcode/solutions/projects/get-started/).

> If you're new to open source, please consider taking the [free "Introduction to Open Source" class](https://cognitiveclass.ai/courses/introduction-to-open-source).
> 
> [![Open Source Foundations](images/open-source-foundations.png)](https://cognitiveclass.ai/courses/introduction-to-open-source)

## Contents

- [Submission or project name](#submission-or-project-name)
  - [Contents](#contents)
  - [Short description](#short-description)
    - [What's the problem?](#whats-the-problem)
    - [How can technology help?](#how-can-technology-help)
    - [The idea](#the-idea)
  - [Demo video](#demo-video)
  - [The architecture](#the-architecture)
  - [Long description](#long-description)
  - [Project roadmap](#project-roadmap)
  - [Getting started](#getting-started)
  - [Live demo](#live-demo)
  - [Built with](#built-with)
  - [Contributing](#contributing)
  - [Versioning](#versioning)
  - [Authors](#authors)
  - [License](#license)
  - [Acknowledgments](#acknowledgments)

## Short description

### What's the problem?

A lot of needs of underprivileged communities can be served by providing a platform of trust and openness that encourages general public to happily fulfil these needs through a culture of donation ans daily habit. Lack of a patform of trust and openness inhibits the helping culture even when people are willing to help.

### How can technology help?

End to end tracable digital platform where each donation can be traced to the ultimate recipient. Real time notification of events of interest so needs can be catered to real time. Internet scale so needs can be fulfilled from across the globe not just locally. Platform of trust and openness collaborating with Govt agencies, public data and APIs for authentication and economic segmentation, funding from corporates and part of ESG initiatives can create an ecosystem of trust and benevolence where people will feel happy to be able to help underprivileged with full confidence and visibility of transactions stored in blockchain and tracability end to end from donor to receiver. Platform can essentially help alleviate poverty and immediate needs by its global scale and real time functionality, including peer-to-peer real time money transfer, collaboration with delivery partners etc. Corporates woul;d be happy to be associated with such a platform for brand enhancement and social impact.

### The idea

The platform connects donors to need in real time. Users can publish and need or a donation offer and including basic details and location info. Platform provides features to browse needs in a city or within a geographic radius and fulfil those needs real time leveraging ecosystem of partners like delivery agencies, real time P2P money transfer etc. Users can also cater to any need in any part of the world. Users can also subscrive to events of inetersts e.g. they can tell the platform to notify them of needs arising within 20km of their home area for categories like food, clothes, medicines, electronics etc and get real time notifications of those events. Cloud Mongo DB NoSQL datastore curently used is highly efficient and scalable, front end is using AngularJS and backend APIs written in Node.js. WebSocket channels are maintained for real time notifications.

## Demo video

[![Watch the video][(https://drive.google.com/file/d/1tCwapobnB46xPG-VhDpfJCXAIWuNBcKd/view?usp=share_link)]

## The architecture


Users can list items of interest for donating or seek donations by listing their needs
Users can browse needs and choose to donate that item or browse donations and choose to accept an offer if the item is still available
Users can subscribe for events on items of interest, geographic location, vicinity within a geographic location, select from a category of items
Whenever a donation or need is created that satisfies the user’s criteria, he gets a notification real time
Users can query by item type, within a geographic radius or events of their interest as specified in the subscription model
User subscriptions, events for donation/needs are stored in Mongo DB as JSON schemas
The platform allows for requesting for generic household needs like food, clothing, furniture, mobile, electronics etc and can also be used for broadcasting emergency needs like blook, relief items etc.
<img width="1190" alt="image" src="https://github.com/sujoyghosal/Call_for_Code_FreeCycle/blob/main/images/FreeCycle%20Architecture.jpg">




## Project roadmap

The project currently does the following things.

- Blockchain transaction tracing
- Aadhar and Govt database authentications and user profiles
- Third party APIs and Ecosystem integration

It's in a free tier IBM Cloud Kubernetes cluster. In the future we plan to run on Red Hat OpenShift, for example.



## Live demo

You can find a running system to test at [http://159.122.177.104:31363](http://159.122.177.104:31363)



## Built with
App is running on IBM Cloud leveraging the following services:

- IBM Kubernetes Cluster
- Docker Containers
- IBM DevOPs Toolchain
- IBM Toolchain Slack Integration
- MongoDB


## Authors

<a href="[https://github.com/Call-for-Code/Project-Sample/graphs/contributors](https://github.com/sujoyghosal/Call_for_Code_FreeCycle)">
  <img src="[https://contributors-img.web.app/image?repo=Call-for-Code/Project-Sample](https://github.com/sujoyghosal/Call_for_Code_FreeCycle)" />
</a>

## License

This project is licensed under the Apache 2 License - see the [LICENSE](LICENSE) file for details.

