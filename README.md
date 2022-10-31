# FreeCycle

Sample Demo URL: http://159.122.177.104:31363

A basic GitHub repository example for new [Call for Code](https://developer.ibm.com/callforcode/) projects and those that join the Call for Code with The Linux Foundation deployment initiative. Not all sections or files are required. You can make this as simple or as in-depth as you need. And don't forget to [join the Call for Code community](https://developer.ibm.com/callforcode/solutions/projects/get-started/).

> If you're new to open source, please consider taking the [free "Introduction to Open Source" class](https://cognitiveclass.ai/courses/introduction-to-open-source).
> 
> [![Open Source Foundations](images/open-source-foundations.png)](https://cognitiveclass.ai/courses/introduction-to-open-source)

_Read this in other languages: [English](README.md), [한국어](./docs/README.ko.md), [português](./docs/README.pt_br.md), [中文](./docs/README.zh.md)._ 

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

[![Watch the video](https://raw.githubusercontent.com/Liquid-Prep/Liquid-Prep/main/images/readme/IBM-interview-video-image.png)](https://drive.google.com/file/d/1Y0iowbwrD11fTDCJ6Ds8r9pfU6YF3MTV/view?usp=share_link)

## The architecture


1. The user navigates to the site and uploads a video file.
2. Watson Speech to Text processes the audio and extracts the text.
3. Watson Translation (optionally) can translate the text to the desired language.
4. The app stores the translated text as a document within Object Storage.

## Long description

[More detail is available here](./docs/DESCRIPTION.md)

## Project roadmap

The project currently does the following things.

- Feature 1
- Feature 2
- Feature 3

It's in a free tier IBM Cloud Kubernetes cluster. In the future we plan to run on Red Hat OpenShift, for example.

See below for our proposed schedule on next steps after Call for Code 2021 submission.

![Roadmap](./images/roadmap.jpg)

## Getting started

In this section you add the instructions to run your project on your local machine for development and testing purposes. You can also add instructions on how to deploy the project in production.

- [sample-react-app](./sample-react-app/)
- [sample-angular-app](./sample-angular-app/)
- [Explore other projects](https://github.com/upkarlidder/ibmhacks)

## Live demo

You can find a running system to test at [callforcode.mybluemix.net](http://callforcode.mybluemix.net/).

See the "long description" field in our submission (not in this repo) for the log-in credentials.

## Built with

- [IBM Cloudant](https://cloud.ibm.com/catalog?search=cloudant#search_results) - The NoSQL database used
- [IBM Cloud Functions](https://cloud.ibm.com/catalog?search=cloud%20functions#search_results) - The compute platform for handing logic
- [IBM API Connect](https://cloud.ibm.com/catalog?search=api%20connect#search_results) - The web framework used
- [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
- [Maven](https://maven.apache.org/) - Dependency management
- [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags).

## Authors

<a href="https://github.com/Call-for-Code/Project-Sample/graphs/contributors">
  <img src="https://contributors-img.web.app/image?repo=Call-for-Code/Project-Sample" />
</a>

- **Billie Thompson** - _Initial work_ - [PurpleBooth](https://github.com/PurpleBooth)

## License

This project is licensed under the Apache 2 License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Based on [Billie Thompson's README template](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2).
