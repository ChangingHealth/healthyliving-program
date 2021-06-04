# Healthy Living for people with type 2 diabetes
Welcome to Healthy Living for people with type 2 diabetes.
You can learn more about the program at https://www.healthyliving.nhs.uk/

Healthy Living is an online self-management support programme and accompanying structured education pathway for adults with type 2 diabetes, which NHS England has licensed and is currently redeveloping for release in early 2020. Healthy Living was originally developed by a team at University College London (UCL), and provides information about type 2 diabetes and its treatments, offers emotional support, and helps with adopting and maintaining healthy behaviours (e.g. diet, exercise). Healthy Living offers an alternative means of accessing support alongside more traditional group-based structured education programmes, which is intended to increase access to these services.

Healthy Living has a strong evidence base proving its effectiveness. A randomised control trial (RCT), funded by the National Institute of Health Research (NIHR) demonstrated modest but significant improvements amongst the group using the Healthy Living diabetes tool in HbA1c levels. In addition to this, the UCL team also designed an implementation study demonstrating the feasibility of rolling Healthy Living out at scale.

## Program source code
We have open-sourced part of the program. Here you can find the different parts:

* [Healthy living Landing page](https://github.com/ChangingHealth/healthyliving-landing) - Created specifically for Healthy Living. Its primary function is to refer users onto the service by taking user information from this page and sending it to our platform system via an API.

* [Blood Glucose Tracker Plugin](https://github.com/ChangingHealth/vue-ctk-date-time-picker) - Unlike other tracker plugins within the platform (food, weight, steps), the Blood Glucose tracker was built specifically for Healthy Living. It enables users to track HbA1c percentage or mg/dl of blood glucose. 

* [Static Dashboard](https://github.com/ChangingHealth/healthyliving-program/tree/main/dashboard-hl) - As a result of user research feedback, we changed the navigation of the program to include a dashboard. This displays to users the progress of their learning. It also includes widgets for notifications, support, finding answers and easier access to trackers.

* [Program Metadata](https://github.com/ChangingHealth/healthyliving-program/tree/main/program-metadata) - The platform uses a program object to build the program that the users see. As this is unique to the service, we will make it open source.
