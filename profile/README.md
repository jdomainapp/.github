# Overview

JDA (previously known as `JDomainApp`) is a [multi-module Maven project](https://books.sonatype.com/mvnex-book/reference/multimodule.html) that implements Domain-Driven Design in Java. Key features of JDA include:

1. **Micro software architecture** (MOSA) which modularises the core domain model in micro-modules (one domain class per module). The architecture is also layered, MVC-enabled and service-ready (supports both RESTful and microservices).
2. MOSA consists in **3 main layers**: domain model (the core) layer, module layer and software layer. Each layer is described in a model.
3. **aDSL (annotation-based DSL)** is used to express the models directly in OOPLs
4. Language: Java
5. Deployed as a multi-module Maven project: each main feature is implemented in a separate module project, allowing them to be selectively imported into software projects

## Research and Development
JDA's development started in 2012 as a teaching tool in a software engineering subject at Hanoi University (Vietnam). It was first named jDomainApp, which means that it is a Java-based tool for domain-driven application development.

In 2014, the development of DomainAppTool, which is based on jDomainApp, began when a need was realised for a user-friendly tool that can be used to quickly and interactively
execute and test the domain model. 
We observe that the development of DomainAppTool and, more generally, that of the
jDomainApp framework continuously evolves. The tool is used not only to demonstrate the
framework’s capabilities but to quickly experiment with any new domain modelling ideas that
would eventually be incorporated into the framework. 

The 2016-2019 period played a crucial role in the framework's development. Three conference
papers were published with an aim to consolidate and formalise (to a certain extent)
the core theories that underlie the framework and tool. Two papers, in particular,
are the collaborative research works between the framework's author and Dr. Duc-Hanh Dang and Dr. Ha-Viet Nguyen from the Department of Software Engineering (VNU University of
Engineering and Technology). These works were later developed into two ISI journal papers.

Another major development of the framework started very recently in **2021** when the framework received a 2-year funding to develop the microservices capabilities. This project has just completed the first phase and is currently in the start of the second phase. Also starting with this project, jDomainApp is officially renamed to become **JDA**.

At this point, we feel that JDA is stable enough to be released  and thus decided to make the source code public. There are still issues to be resoved and untappeded potential to be explored. We hope that the framework would be received by the community, used in software development and be contributed to by developers.

# Contributors

# Reseachers
| Name | Date | Organisation | Description
| :--: | :--: | :--: | :--: |
| Le, Minh Duc | 2012-now | Swinburne Vietnam | JDA creator, designer (architecture, framework), project lead
| Dang, Duc Hanh | 2016-2023 | VNU, University of Engineering and Technology | aDSL language design 
| Vo, Dinh Hieu | 2012-2023 | VNU, University of Engineering and Technology | architecture design
| Nguyen, Viet Ha | 2016-2019 | VNU, University of Engineering and Technology | Software development methodology

| Name | Date | Description
| :--: | :--: | :--: |
| Le, Van Vinh | 2022-2023 | PhD Thesis, Faculty of IT, VNU University of Engineering and Technology
| Tran, Quang Linh | 2022-2023 | Masters Thesis, Faculty of IT, VNU University of Engineering and Technology
| Tong, Van Anh Hai | 2022-2023 | Masters Thesis, Faculty of IT, VNU University of Engineering and Technology
| Vu, Thanh Ha | 2018 | Masters Thesis, Faculty of IT, VNU University of Engineering and Technology
| Do, Hai Binh | 2019 | Graduation Thesis, Faculty of IT, Hanoi University 
