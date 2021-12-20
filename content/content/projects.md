---
title: "Projects"
date: 2021-12-15T14:40:17+01:00 
draft: false
---

Here there is a glimpse of my works over the years

### Reliability analysis tool
Java - SpringBoot - Javascript - React - Docker - Python

In the scope of a european project ([Reclaim](https://www.reclaim-project.eu/ "Reclaim")) I had to build a tool, the 
reliability analysis tool, that help the production line management in estimating failures of components by estimating
the reliability of them. In addition, the tool supports the formalization of the FMEA analysis and the modelling of a 
reliability block diagram thant helps in estimating the whole system reliability.   

The backbone of this platform is a Java + Spring application, in addition to that I build an estimation service in Python
that through a REST API made available a set of probability distributions that fitted with the component failure events
can estimate the probability of failure over a period of time. Meanwhile, the user interface is build with Javascript and 
React. All the services are containerized and deployed together.

{{< figure src="/projects/rat.png" link="/projects/rat.png" width="100%" target="_blank">}}

### iDA Platform
Java - SpringBoot - Javascript - React - Docker

In the context of an InnoSuisse project, in which the main implementation partner was InterrollSA, I have developed a 
data gathering platform. The data are gathered from various machines in the quality department. I had to develop a Java
service that managed all the operations including the communication with the machines, for the seek of this we have adopted
the OPC-UA protocol, thus I have used Eclipse Milo as interface.   

The data are collected into an InfluxDatabase and made available through the platform and a Grafana dashboard, which has
been integrated into the platform itself. The front-end has been built using Javascript combined with React, and all the
application has been containerized with docker.

{{< figure src="/projects/ida.png" link="/projects/ida.png" width="100%" target="_blank">}}

### Sketch your pain

Java - SpringBoot - Javascript - React - Docker

The sketch your pain research platform allows to sample the pain-drawings of patients. Process them and extract some
useful information such as a pain frequency map. This project is composed by different services, I personally developed
the Java backend with a spring application that orchestrate the whole system as well as the users interfaces: web
dashboard and a tablet. The tablet application that enable the patients to draw a body chart directly on a tablet. The gui's are
developed using Javascript and React.  

All the services are containerized, and I deployed the whole application on an Ubuntu server using docker.

{{< figure src="/projects/syp.png" link="/projects/syp.png" width="100%" target="_blank">}}

### Centralized access map

Java - SpringBoot - Javascript - Bootstrap

In the context of my Bachelor thesis, I had to develop a platform able to manage the users access right on the legacy
services. I thus developed a Java REST service using Spring, the database of choice was MongoDB. The frontend has been
developed using plain Javascript and Bootstrap framework for the graphical components.

Each service has been integrated developing a plugin architecture, thus a system integrator only had to develop a jar to
integrate its system into the CAM. More details on this can be found on the Bachelor thesis document (in italian)
attached under the image.

{{< figure src="/projects/cam.png" link="/projects/cam.png" width="100%" target="_blank">}}

[Download documentation](/projects/thesis.pdf "Thesis")

### Legolab
Java - SpringBoot - Javascript - React - Docker

The Legolab is a didactic platform which digitalizes a production environment, it supports both kanban and assembly to
order methodologies. The main objective is to teach how a real-world factory works by implementing a small assembly
line that build a lego forklift.

The application is build with Java and spring behind the curtains, meanwhile the user interface is built with Javascript
and React. The whole architecture is containerized and deployed on an Ubuntu server.

{{< figure src="/projects/legolab.png" link="/projects/legolab.png" width="100%" target="_blank">}}


#### Navigation

[About]({{< ref "/about" >}} "About")
[Education]({{< ref "/education" >}} "Education")
[Experience]({{< ref "/experience" >}} "Experience")
Projects
[Research]({{< ref "/research" >}} "Research")
[Contacts]({{< ref "/contacts" >}} "Contacts")