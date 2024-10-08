#### REMINDER
### Proyecto AWS_SAAC-003

Este repositorio contiene código y recursos relacionados con el curso **AWS Certified Solutions Architect - Associate (SAA-C03)** impartido por **Adrian Cantrill**. Todo el contenido de este repositorio ha sido creado siguiendo su curso y las instrucciones proporcionadas en el mismo.

### Autoría

El código y las ideas reflejadas en este repositorio pertenecen completamente a **Adrian Cantrill**, quien ha desarrollado el contenido de manera original a través de su curso.

### Curso de Adrian Cantrill en AWS Certified Solutions Architect - Associate (SAA-C03)

Para más información o para acceder al curso, puedes visitar los siguientes enlaces:

- [AWS Certified Solutions Architect - Associate (SAA-C03) en AdrianCantrill.com](https://learn.cantrill.io/p/aws-certified-solutions-architect-associate-saa-c03)
- [AWS Certified Solutions Architect - Associate (SAA-C03) en Udemy](https://www.udemy.com/course/aws-certified-solutions-architect-associate/)
- [Repositorio learn-cantrill-io-labs](https://github.com/acantril/learn-cantrill-io-labs/tree/master)

Agradecimientos especiales a Adrian Cantrill por compartir su conocimiento y contribuir al éxito de quienes buscan certificarse en AWS.

## Uso del Repositorio

Este repositorio se utiliza con fines educativos siguiendo las directrices del curso de **Adrian Cantrill**. Se recomienda no utilizar el contenido con fines comerciales ni distribuirlo sin la debida atribución.

---

### AWS_SAAC-003 Project

This repository contains code and resources related to the **AWS Certified Solutions Architect - Associate (SAA-C03)** course taught by **Adrian Cantrill**. All the content in this repository has been created following his course and instructions.

### Attribution

The code and ideas reflected in this repository fully belong to **Adrian Cantrill**, who originally developed the content through his course.

### Adrian Cantrill's AWS Certified Solutions Architect - Associate (SAA-C03) Course

For more information or to access the course, you can visit the following links:

- [AWS Certified Solutions Architect - Associate (SAA-C03) on AdrianCantrill.com](https://learn.cantrill.io/p/aws-certified-solutions-architect-associate-saa-c03)
- [AWS Certified Solutions Architect - Associate (SAA-C03) on Udemy](https://www.udemy.com/course/aws-certified-solutions-architect-associate/)
- [Learn-cantrill-io-labs repository](https://github.com/acantril/learn-cantrill-io-labs/tree/master)

Special thanks to Adrian Cantrill for sharing his knowledge and contributing to the success of those seeking AWS certification.

### Repository Usage

This repository is used for educational purposes following the guidelines of **Adrian Cantrill's** course. It is recommended not to use the content for commercial purposes or distribute it without proper attribution.

# Advanced Demo - Serverless App - Pet-Cuddle-O-Tron

In this advanced demo you are going to implement a simple serverless application using S3, API Gateway, Lambda, Step Functions, SNS & SES.  

The advanced demo consists of 6 stages :-

- STAGE 1 : Configure Simple Email service 
- STAGE 2 : Add a email lambda function to use SES to send emails for the serverless application 
- STAGE 3 : Implement and configure the state machine, the core of the application
- STAGE 4 : Implement the API Gateway, API and supporting lambda function
- STAGE 5 : Implement the static frontend application and test functionality
- STAGE 6 : Cleanup the account

**IF YOU HAVE ANY ISSUES WITH THE DEMO ... CHECK THE COMMON ISSUES PAGE BELOW**

[https://github.com/acantril/learn-cantrill-io-labs/blob/master/aws-serverless-pet-cuddle-o-tron/02_LABINSTRUCTIONS/CommonIssues.md](https://github.com/acantril/learn-cantrill-io-labs/blob/master/aws-serverless-pet-cuddle-o-tron/02_LABINSTRUCTIONS/CommonIssues.md)

![Architecture](https://github.com/acantril/learn-cantrill-io-labs/raw/master/aws-serverless-pet-cuddle-o-tron/ArchitectureEvolutionAll.png)

## Instructions

- [Stage1](https://github.com/acantril/learn-cantrill-io-labs/blob/master/aws-serverless-pet-cuddle-o-tron/02_LABINSTRUCTIONS/STAGE1%20-%20Configure%20SES.md)
- [Stage2](https://github.com/acantril/learn-cantrill-io-labs/blob/master/aws-serverless-pet-cuddle-o-tron/02_LABINSTRUCTIONS/STAGE2%20-%20Configure%20email_reminder_lambda.md)
- [Stage3](https://github.com/acantril/learn-cantrill-io-labs/blob/master/aws-serverless-pet-cuddle-o-tron/02_LABINSTRUCTIONS/STAGE3%20-%20Implement%20and%20Configure%20State%20Machine.md)
- [Stage4](https://github.com/acantril/learn-cantrill-io-labs/blob/master/aws-serverless-pet-cuddle-o-tron/02_LABINSTRUCTIONS/STAGE4%20-%20API%20Gateway%20and%20Application%20Lambda.md)
- [Stage5](https://github.com/acantril/learn-cantrill-io-labs/blob/master/aws-serverless-pet-cuddle-o-tron/02_LABINSTRUCTIONS/STAGE5%20-%20Serverless%20Application%20Frontend.md)
- [Stage6](https://github.com/acantril/learn-cantrill-io-labs/blob/master/aws-serverless-pet-cuddle-o-tron/02_LABINSTRUCTIONS/STAGE6%20-%20Cleanup.md)


## 1-Click Installs
No installs required for this Advanced Demo

## Video Guides

- [Stage1](https://youtu.be/ZSt1w_7sVvY)  
- [Stage2](https://youtu.be/KxOoBL_PkKQ)  
- [Stage3](https://youtu.be/lGlZ5d7MXys)  
- [Stage4](https://youtu.be/8BTUhDnRN0s)  
- [Stage5](https://youtu.be/TkydHW3UKUY)  
- [Stage6](https://youtu.be/iGTkY0EThBM)  

## Architecture Diagrams

- [Stage1 - PNG](https://github.com/acantril/learn-cantrill-io-labs/blob/master/aws-serverless-pet-cuddle-o-tron/02_LABINSTRUCTIONS/ARCHITECTURE-STAGE1.png)
- [Stage1 - PDF](https://github.com/acantril/learn-cantrill-io-labs/blob/master/aws-serverless-pet-cuddle-o-tron/02_LABINSTRUCTIONS/ARCHITECTURE-STAGE1.pdf)
- [Stage2 - PNG](https://github.com/acantril/learn-cantrill-io-labs/blob/master/aws-serverless-pet-cuddle-o-tron/02_LABINSTRUCTIONS/ARCHITECTURE-STAGE2.png)
- [Stage2 - PDF](https://github.com/acantril/learn-cantrill-io-labs/blob/master/aws-serverless-pet-cuddle-o-tron/02_LABINSTRUCTIONS/ARCHITECTURE-STAGE2.pdf)
- [Stage3 - PNG](https://github.com/acantril/learn-cantrill-io-labs/blob/master/aws-serverless-pet-cuddle-o-tron/02_LABINSTRUCTIONS/ARCHITECTURE-STAGE3.png)
- [Stage3 - PDF](https://github.com/acantril/learn-cantrill-io-labs/blob/master/aws-serverless-pet-cuddle-o-tron/02_LABINSTRUCTIONS/ARCHITECTURE-STAGE3.pdf)
- [Stage4 - PNG](https://github.com/acantril/learn-cantrill-io-labs/blob/master/aws-serverless-pet-cuddle-o-tron/02_LABINSTRUCTIONS/ARCHITECTURE-STAGE4.png)
- [Stage4 - PDF](https://github.com/acantril/learn-cantrill-io-labs/blob/master/aws-serverless-pet-cuddle-o-tron/02_LABINSTRUCTIONS/ARCHITECTURE-STAGE4.pdf)
- [Stage5 - PNG](https://github.com/acantril/learn-cantrill-io-labs/blob/master/aws-serverless-pet-cuddle-o-tron/02_LABINSTRUCTIONS/ARCHITECTURE-STAGE5.png)
- [Stage5 - PDF](https://github.com/acantril/learn-cantrill-io-labs/blob/master/aws-serverless-pet-cuddle-o-tron/02_LABINSTRUCTIONS/ARCHITECTURE-STAGE5.pdf)






