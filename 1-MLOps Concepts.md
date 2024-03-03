# Data Camp - MLOps Track

# MLOps Concepts

## Introduction to MLOps

### What is MLOps?

![Untitled](Data%20Camp%20-%20MLOps%20Track%2060d56cc128f643149ad91041c454de14/Untitled.png)

### Why MLOps?

- MLOps aims to structure the process and mitigate the risks that are involved in machine learning development, deployment, and maintenance.

![Untitled](Data%20Camp%20-%20MLOps%20Track%2060d56cc128f643149ad91041c454de14/Untitled%201.png)

### What is the origin of MLOps?

- **MLOps** originates from **Development Operations**, also called DevOps.
- **DevOps** describes a set of practices and tools that can be applied to software development to ensure that software is developed continuously, reliably, and efficiently.
- Traditional software development used to be slow because of the separation of Development and Operations teams. The development team consists of the people who write the code, who were separated from the operations team, the people who deploy and support the code.
- This is why **DevOps** is an integration of both teams. Similar to how DevOps is applied to software development, MLOps is applied to machine learning development.

![Untitled](Data%20Camp%20-%20MLOps%20Track%2060d56cc128f643149ad91041c454de14/Untitled%202.png)

![Untitled](Data%20Camp%20-%20MLOps%20Track%2060d56cc128f643149ad91041c454de14/Untitled%203.png)

### What is the Benefits of MLOps?

- Improve the overall speed of developing and delivering machine learning models.
- Processes also become more reliable and secure because of MLOps.
- It aims to bridge the gap between machine learning and operations teams, which enhances collaboration.

### What is the MLOps life cycle?

![Untitled](Data%20Camp%20-%20MLOps%20Track%2060d56cc128f643149ad91041c454de14/Untitled%204.png)

- The machine learning lifecycle is important because it gives a high-level overview of how a machine learning project should be structured in order to deliver real, practical value. It also defines the roles that are required at each step to make the project into a success.

![Untitled](Data%20Camp%20-%20MLOps%20Track%2060d56cc128f643149ad91041c454de14/Untitled%205.png)

- In the **design** phase, we focus on the **design** of the machine learning project.
- We define the context of the problem and determine the added value of using machine learning.
- We also gather **business requirements**, as well as establish **key metrics** through which we can track the progress of the machine learning lifecycle.
- Additionally, we need to gather data and make sure the data quality is sufficient for developing a machine learning model.

![Untitled](Data%20Camp%20-%20MLOps%20Track%2060d56cc128f643149ad91041c454de14/Untitled%206.png)

- In the **development phase**, we focus on developing the machine learning model.
- We do this by experimenting with a combination of data, algorithms, and hyperparameters in line with the implementation design.
- During the experiment, we train and evaluate one or more models in order to find the most suitable one.
- The goal of the development phase is to end up with the most suitable machine learning model that is ready for deployment.

![Untitled](Data%20Camp%20-%20MLOps%20Track%2060d56cc128f643149ad91041c454de14/Untitled%207.png)

- In the **deployment** phase, we **integrate** the machine learning model we developed earlier into the business process.
- This might involve building a **microservice** from the machine learning model.
- A **microservice** is a small application that includes the machine learning model such that we can easily integrate it into the business process.
- We also aim to set up **monitoring** of the machine learning model. We can set up alerts when we encounter **data drift** or when our model does not output a prediction anymore.
- **Data drift** occurs when our data changes, which impacts the machine learning model.

![Untitled](Data%20Camp%20-%20MLOps%20Track%2060d56cc128f643149ad91041c454de14/Untitled%208.png)

- There are different roles that are involved within the machine learning lifecycle.
- There are two categories of roles: **Business roles** and **technical roles**.

![Untitled](Data%20Camp%20-%20MLOps%20Track%2060d56cc128f643149ad91041c454de14/Untitled%209.png)

- The **business stakeholder** is sometimes also referred to as the **product owner**.
- They are a managerial staff making budget decisions, and they make sure the machine learning project is aligned with the high-level vision of the company.
- They are involved throughout the lifecycle. First, they define the business requirements during the design phase. In the development phase, they also see whether the initial results from the experiments are satisfactory. Later in the deployment phase, they again examine whether the outcome of the lifecycle is as expected.

![Untitled](Data%20Camp%20-%20MLOps%20Track%2060d56cc128f643149ad91041c454de14/Untitled%2010.png)

- The **business subject matter expert**, who has domain knowledge about the problem that we are trying to solve.
- In retail, this could, for instance, be someone from the sales team that knows the variables that influence sales.
- The **subject matter expert** is involved throughout the lifecycle because they can assist the more technical roles with interpreting the data and results at each step.

![Untitled](Data%20Camp%20-%20MLOps%20Track%2060d56cc128f643149ad91041c454de14/Untitled%2011.png)

- The **data engineer** is responsible for the collecting, storing, and processing of data.
- This also means that the **data engineer** should check the **data quality** and include tests such that the quality is maintained throughout the process.
- Therefore, the **data engineer** is mostly involved with tasks that have to do with data before training the model, during the model training, and once the model is used in production.

![Untitled](Data%20Camp%20-%20MLOps%20Track%2060d56cc128f643149ad91041c454de14/Untitled%2012.png)

- The **data scientist** is responsible for **data analysis** and **model training** and **evaluation**.
- The **evaluation** includes monitoring the model once it has been deployed to ensure that the model predictions are valid. We can find the data scientist in all phases of the lifecycle, but mostly during the **development** phase.

![Untitled](Data%20Camp%20-%20MLOps%20Track%2060d56cc128f643149ad91041c454de14/Untitled%2013.png)

- The **software engineer** is mainly involved in the **deployment** phase, where they write software to **run** the **model**, **deploy** the **model**, and **monitor** whether the **model** is and stays online once it is deployed.
- They also make sure that code is written in accordance with **common** guidelines. Since the deployment is an important part of the machine learning lifecycle, the software engineer should also be included in the design phase.

![Untitled](Data%20Camp%20-%20MLOps%20Track%2060d56cc128f643149ad91041c454de14/Untitled%2014.png)

- The **machine learning engineer** is a relatively new role that is quite versatile and designed specifically to have expertise over the entire machine learning lifecycle.
- It is a cross-functional role that overlaps with the other technical roles. As such, the **machine learning engineer** is involved in all phases.
- They know, for instance, how to extract and store data and develop or deploy a machine learning model.

![Untitled](Data%20Camp%20-%20MLOps%20Track%2060d56cc128f643149ad91041c454de14/Untitled%2015.png)

- The **backend engineer** is someone that is mostly involved with setting up the **cloud** infrastructure to enable development and deployment of machine learning models.
- This could be a database for storing the data, but also the computers that run the machine learning model.

![Untitled](Data%20Camp%20-%20MLOps%20Track%2060d56cc128f643149ad91041c454de14/Untitled%2016.png)

## MLOps Design Phase

### Added Value

- The **machine learning design lifecycle** starts with determining the **added value** of building and running the machine learning model.
- This is often expressed in terms of money or time. It is wise to estimate the potential a certain project has.

![Untitled](Data%20Camp%20-%20MLOps%20Track%2060d56cc128f643149ad91041c454de14/Untitled%2017.png)

![Untitled](Data%20Camp%20-%20MLOps%20Track%2060d56cc128f643149ad91041c454de14/Untitled%2018.png)

### Business Requirements

- Identifying **business requirements** is crucial for machine learning lifecycle design phase.
- It is critical to think about the **end user** of the machine learning model.
- You must consider the **frequency** of the predictions and how **fast** we need them.
- We must also **evaluate** the **model's accuracy** and whether its results are **explainable** to non-experts.
- **Transparency** enables us to find why the model makes its predictions, why it is wrong, and how we can improve the model. These requirements all have an impact on what algorithm we will use.
- A machine learning model's **predictions** should be **explainable** since it is difficult to improve a model if we don't know why it makes its **predictions.**
- Depending on the problem we are trying to solve, there could also be **compliance** and **regulatory requirements** to the usage of machine learning.

![Untitled](Data%20Camp%20-%20MLOps%20Track%2060d56cc128f643149ad91041c454de14/Untitled%2019.png)

### Key Metrics

- In order for **machine learning lifecycle** to progress as expected, it is wise to track the performance of the model.
- We’ve seen that roles involved in **MLOps** processes are **multidisciplinary** and thus also have their own way of tracking performance.
- The **data scientist** looks at the accuracy of a model, how many times the algorithm is correct.
- The **subject matter expert** is interested in the model's impact on the business, for instance, how their work improves due to the use of machine learning. They are primarily interested in **domain-specific metrics**.
- The **business stakeholder** is more interested in the monetary value of the model, in how many cases do we actually generate revenue. This is often expressed in money or time.
- To get the most out of machine learning, we must align the different metrics to make sure everyone is on the same page.

![Untitled](Data%20Camp%20-%20MLOps%20Track%2060d56cc128f643149ad91041c454de14/Untitled%2020.png)

### Data Quality and Ingestion

- **Gathering data** is part of the design **phase**. During this phase, we investigate the **data quality** and how we **extract** the required data.
- What is **Data** **Quality**?
- The **quality** of a **machine learning model** is highly **dependent** on the **quality** of the **data**.
- **Data** sits at the core of the **machine learning model**. Therefore, having a clear view of the **data quality** is crucial for the success of the **machine learning lifecycle**.
- Having **poor data quality** is detrimental for the performance of the machine learning model. Improving the data quality is often the first step to improving the model's performance.

![Untitled](Data%20Camp%20-%20MLOps%20Track%2060d56cc128f643149ad91041c454de14/Untitled%2021.png)

- **Data quality** can be defined along four main **dimensions**, namely **accuracy**, **completeness**, **consistency**, and **timeliness**.
- **Accuracy** describes the extent to which data is accurate or correct for the task at hand.
- **Completeness** is about to what extent the data fully describes the problem at hand.
- **Timeliness** is about in what time frame the data will be readily available.

![Untitled](Data%20Camp%20-%20MLOps%20Track%2060d56cc128f643149ad91041c454de14/Untitled%2022.png)

![Untitled](Data%20Camp%20-%20MLOps%20Track%2060d56cc128f643149ad91041c454de14/Untitled%2023.png)

- There are multiple things we can do to tackle **low data quality**, such as collecting more data or filling missing data with other sources.
- In the design phase, we also look into how to **extract** and **process** data. This is done by using an **automated data pipeline.**
- A **data pipeline** is often a part within the **machine learning lifecycle** through which data is automatically processed.
- A common type of **data ingestion** process is **ETL**, which stands for **extract**, **transform**, and **load**.
- It describes the three steps gone through in an **ETL pipeline**. The data is **extracted** from the source, **transformed** to the required format, and **loaded** into some internal or proprietary database.
- In an **ETL pipeline**, we can also include **automated checks**, such as expectations we have about certain data columns.
- Including these **automated checks** in a data pipeline helps **speed** up the **development** and **deployment** phase of the lifecycle, since faulty or low-quality data will affect the machine learning model.

![Untitled](Data%20Camp%20-%20MLOps%20Track%2060d56cc128f643149ad91041c454de14/Untitled%2024.png)