## Managing Modern Software: An Overview of Container Management [presentation]

[PPT](https://drive.google.com/drive/folders/0BzVVFi4AfziiMHVZdFVTMHpzSk0)

In accelerating software delivery at your organization, you've likely done a lot of work with DevOps, and in the process may have had interaction with containers in some way, whether it's using them locally to build or try something, or deploying software in them into the cloud, or hearing your IT executives pushing for cost savings via containerizing things. Containers are an exciting technology that allows DevOps practices to make software delivery even more efficient in many ways, from cost savings to more frequent delivery.

As you get deeper into containers, you'll get deeper into container management needs. As soon as you have a set of containers deployed in production, you quickly find the need to manage things, everything from how the containers will find each other out in the wild, to what happens when they crash.

* Scheduling - deploying containers on the right infrastructure depending on capacity, etc.
* Container-to-container communication & service discovery 
* Scaling
* Load balancing
* Self-healing (automatic restarts)
* Rolling updates
* Service/App management (organizing containers that comprise an application; managing deployments)
* Storage management

You probably have heard buzz words like Kubernetes, which provides functionality like these and much more, but the ecosystem overall is daunting at first. This presentation will summarize the ecosystem, giving an overview of what container management and orchestration is, and will look at some tools, including Kubernetes, Swarm and Mesos.

Attendees should come away with a clearer understanding of container management, why you need it, and what tools are out there. Additionally they will come out with actionable next steps in container management.

Comments: I am a seasoned speaker with technical depth and experience in these hot container topics, and I have helped clarify the container management ecosystem for clients and co-workers. This is a hot topic I am excited to help people understand better.

+AZURE
Kubernetes on Azure Container Service has reached general availability. When you deploy your next generation application to Azure, whether on a PaaS or deployed directly onto Kubernetes itself (or both) you can deploy it onto a managed, supported Kubernetes cluster.
Furthermore, because we know that the world of PaaS and software development in general is a hybrid one, we’re excited to announce the preview availability of Windows clusters in Azure Container Service. We’re also working on hybrid clusters in ACS-Engine and expect to roll those out to general availability in the coming months.
https://kubernetes.io/blog/2017/02/caas-the-foundation-for-next-gen-paas/


## Business Case for Microservices

The microservices approach has been taking the software industry by storm, promising to make organizations more competitive and faster at delivering software. It doesn’t only have to be for the most complex systems like those at Netflix. The benefits hit many common pain points of so many software projects. Microservices can give organizations more agility with business decisions as the software can respond faster to constant change which is inevitable in the business world. A successfully implemented microservices approach can speed up software delivery, but it is daunting to get into and filled with uncertainty. This presentation will go into more detail to paint the big picture around microservices and where they fit. It will demystify the ecosystem and provide actionable next steps for determining if microservices fit into your strategy.

Audience: CxOs, IT executives, DevOps, software architects and developers needing to make decisions around cloud, containers, microservices and how to deliver software.

Benefits: Microservices, containers and cloud change paradigms for how software is created and delivered. The shifts are huge, so it's daunting for organizations to break into the approaches and technology, but it's critical to stay competitive. Decision-makers need the right information to make the right decisions in this new era of software, and this presentation attempts to provide it.

## Cloud, containers and microservices, oh my! An overview of cloud infrastructure

All of us in the IT industry are hearing words like containers, cloud, microservices, serverless and more. For IT decision makers who aren't able to get into the weeds of these things on a regular basis may have some trouble sorting out what all of these things are and how they relate. This talk will illustrate the big picture of cloud, and key moderm compoents fit including containers, microservices and serverless computing. This will help defog the ecosystem which is changing so drastically, creating new standards and paradigms for software delivery.

- Enterprise-grade security is highly correlated with
commercial container solutions and tools that tightly
link containers with microservices development.
Commercial container solutions are highly
correlated with DevTest tools and tools that link
microservices. These solutions are the bridge
between DevOps and a microservices-based
application architecture. 
- Companies seeking to leverage AI within
containerized apps will be seeking container
consulting services and support for non-x86
architectures (e.g., GPUs).
- Of utmost importance and
interest is enterprise-grade security for containers. However
only a quarter of respondents consider it widely
available today. 

## CaaS Services 

Helps companies containerize applications, create best-practice development workflows, and build robust microservice architectures:
Deployable Docker and development Subject Matter Experts
Enterprise container Assessment
Boot Camp training for Docker
Architecture development for containers and microservices
Deployable Jenkins and Docker development Subject Matter Experts
Blue/Green & Canary Deployment
Jenkins Pipelining; Bamboo, UCD
Gitflow experts and implementers
Continuous Delivery automation that works:
     Microservice versioning manifests
     Rollback capabilities
     Canary Deploys
Deployable Kubernetes and Swarm Subject Matter Experts
Production Readiness Audits
Container Monitoring solutions including CoScale and Prometheus
Managed services for Orchestration and Cloud
OpenShift, Docker EE, Rancher installation and management

## Docker Technical/Sales Professional Training

### Business initiatives

Interesting tidbits I learned from a docker tech sales video:

Common CIO Priorities:
- Modernization - moving monolithic applications on static hardware to service-based architecture and microservices. 
- Cloud adoption at scale, Cloud strategy - easy migrations but portable across clouds
- DevOps practices - CI, moving to Continuous Delivery

Docker offers:
- The myth of bi-modal IT: analysts are says organizations should have 2 IT practices, 1 for managing traditional apps, and one for modern service-based (microservices, etc) since different types of infrastructure
  - Docker wants all types of application on any type of hardware to be managed with their tooling
  - Tries to make them all fast, easily deployable, automatable. Important b/c orgs have such diverse infrastructure b/t mainframes, physical servers, linux and windows servers, mix of old and new applications. 
  - Developers want to to deliver fast, and Ops is responsible for standardizing and securing running applications
  - Docker offers a secure, software supply chain to try to tackle these things

According to them also, companies plan to spend more on Docker than any other infrastructural software, though Docker has less market penetration than the other big ones, Red Hat, VMWare, Microsoft, SAP, Oracle. So they think a lot of Docker Enterprise licenses are going to be sold


### Vendors most supporting microservices

Semi-related in other vendor news, according to some Docker Technical Sales Training, the vendors companies are planning to spend the most on in 2018 to support their microservices initiatives are Splunk, GitHub, Docker far ahead, then Atlassian, MongoDB, Puppet Labs, AWS Lambda, Chef, Ansible, MuleSoft, AppDynamics, Apogee, Elastic, New Relic, Confluent, Ceph



## Containers & Cloud Architecture Make You More Agile

Containers have been talked about a lot the last few years, and they are becoming a staple of big modernization projects and cloud architectures. In what ways can they make your team more agile and able to deliver software faster? When software is built using containers, on one end they can quickly give a jolt to developer productivity in standardizing their development platform and getting things running quickly. Eventually, on the other end, when your cloud architecture can fully support well-managed containers in production, ops can more easily manage the software since its standardized in containers, and it significantly clarifies the DevOps interaction. 

We'll go into the details of why containers and its surrounding cloud technology is being asked about by so many executives to stay competitive, and what the short and long term benefits are across an organization.

* Overview of cloud architecture and containers
* What managing software with containers entails
* Benefits to agile software delivery from container-based cloud architecture
* Pitfalls to watch out for
* How to get started

People should come away with an overall understanding of the cloud and container ecosystem, and what to think about and what questions to ask next in determining next steps to adopting cloud architecture.

## Getting Started with Container Deployment Workshop

Many of us have come into interaction with containers, otherwise know it is inevitable. Many may have also noticed that things get complicated when you start to explore deployment options for containers. Getting your hands dirty as soon as possible by deploying a containerized application will demystify a lot of things quickly and allow you to move forward faster. 

In this 2-hour workshop, we will take an existing simple app that is running in Docker, and go through steps to deploy it to Kubernetes. 

Audience Skill Level: practical hands-on experience and understanding of Docker (we won't have time to go over Docker concepts)

Benefits: Many know the need of containerization in order to take advantage of the benefits of modern software delivery approaches. Container-based software is relatively new to most organizations, and the ecosystem seems daunting when first entering it. One of the best ways to understand how to move forward is trying it out or seeing it in action. This tutorial will take you through how to get started with container management, by setting up a container management system such as Kubernetes, and deploying a containerized application into it.

[Instructor Bio](https://wyntuition.github.io/bio/)

## Getting Started with Docker (Docker for Development) Workshop

This is a 2-hour workshop - hands-on - on getting started with Docker for software development.

Audience Skill Level: Those of all skill levels new to Docker

Requirements: attendees must bring laptops, charged (may not be enough plugs), and with Docker installed & working (shouldn't take more than 5-10 mins):

• Install & set up for Windows (https://store.docker.com/editions/community/docker-ce-desktop-windows?tab=description)

• Install & set up for Mac (https://store.docker.com/editions/community/docker-ce-desktop-mac?tab=description)

Why Docker?

Using Docker during the development process has several advantages. We can use or create a container that has the libraries and tools we need for our app - we don’t have them on our host computer. We can spin up an environment with multiple services (including a database) in minutes, with one command. We can then share this environment with our teammates so we can ensure they have the same versions of things installed and can get up and running quickly.

Agenda Details

• Basics of Docker and containers

• Run an existing image

• Create an image, and tweak it in order to get the dependencies we need to start a container for developing

• Use Compose to spin up a development environment with a database

### Verbose abstract

#### Part I

Join us for part 1 of 2 of our Getting Into Docker Workshop Series. The workshop will begin with a 20-minute overview of the concepts of Docker before we jump into Dockerizing an app, then using Compose to build and run it. 

// Set up before the Event //
Docker installed in working (5-10 minutes)

// Requirements //
Open to all skill levels. Attendees must bring laptops, charged (may not be enough plugs), and with Docker installed & working (shouldn't take more than 5-10 mins)

// Why Docker? //
Using Docker during the development process has several advantages. We can use or create a container that has the libraries and tools we need for our app - we don’t have them on our host computer. We can spin up an environment with multiple services (including a database) in minutes, with one command. We can then share this environment with our teammates so we can ensure they have the same versions of things installed and can get up and running quickly.

// About Wyn //
Wyn is currently a managing consultant & senior developer with Excella. He has extensive experience in various industries with the analysis, design and implementation of software, largely with web-based applications on open source and .NET technologies. He also works heavily with DevOps, cloud and container-based approaches. He strives to be a good software craftsman by using XP practices.

He enjoys being involved in the community and has spoken at various events around the region, conducted hands-on workshops and contributed to open source. He is a co-coordinator of the Tech Talk DC User Group and a former coordinator of the ALT.NET DC user group.

Lately, Wyn has been deep diving into ASP.NET Core, Docker and DevOps. For fun Wyn likes playing music, skiing and conversation.

https://wyntuition.github.io/bio/

// Agenda //
6:00: Socializing and Food
6:10: Introductions and Announcements
6:15:  Workshop Kickoff
8:16: Wrap up

// Parking and Metro //
Parking at 2100 - 2300 Clarendon Blvd is free after 6:00. Enter the garage at 2100 Clarendon Blvd and turn right for gated parking in the garage or turn left for metered parking. The ATX is located at Courthouse Metro on the Orange and Silver lines.

#### Part II

Join us for part 2 of 2  of the Getting Into Docker Workshop Series, where we will take the containerized app from our first workshop session and deploy it.

// Set up before the Event //
Docker installed & working

// Requirements //
Practical hands-on experience and understanding of Docker (we won’t have time to go over Docker concepts). The Getting Started with Docker Workshop is a great prerequisite. 

Attendees must bring laptops, charged (may not be enough plugs), and with Docker installed & working (shouldn't take more than 5-10 mins)

// Container Deployment //
Many of us have come into interaction with container, otherwise know it is inevitable. Many may have also noticed that things get complicated when you start to explore deployment options for containers. Getting your hands dirty as soon as possible by deploying a containerized application will demystify a lot of things quickly and allow you to move forward faster.
In this 2-hour workshop, we will take an existing simple app that is running in Docker, and go through steps to deploy it to Kubernetes.
Audience Skill Level: practical hands-on experience and understanding of Docker (we won’t have time to go over Docker concepts)

// About Wyn //
Wyn is currently a managing consultant & senior developer with Excella. He has extensive experience in various industries with the analysis, design and implementation of software, largely with web-based applications on open source and .NET technologies. He also works heavily with DevOps, cloud and container-based approaches. He strives to be a good software craftsman by using XP practices.

He enjoys being involved in the community and has spoken at various events around the region, conducted hands-on workshops and contributed to open source. He is a co-coordinator of the Tech Talk DC User Group and a former coordinator of the ALT.NET DC user group.

Lately, Wyn has been deep diving into ASP.NET Core, Docker and DevOps. For fun Wyn likes playing music, skiing and conversation.

https://wyntuition.github.io/bio/

// Agenda //
6:00: Socializing and Food
6:10: Introductions and Announcements
6:15:  Workshop Kickoff
8:15: Wrap up

// Parking and Metro //
Parking at 2100 - 2300 Clarendon Blvd is free after 6:00. Enter the garage at 2100 Clarendon Blvd and turn right for gated parking in the garage or turn left for metered parking. The ATX is located at Courthouse Metro on the Orange and Silver lines.

