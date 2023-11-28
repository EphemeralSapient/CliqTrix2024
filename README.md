# Zoho SalesIQ HR Application for Cliqtrix Contest

This application is designed for the Cliqtrix contest hosted by Zoho in 2024. It aims to streamline HR processes using Zoho SalesIQ and Zobot. The application is written in Deluge and offers a user-friendly GUI for job openings.

## Zobot Integration

This application leverages Zobot, Zoho SalesIQ's bot development platform, to automate customer interactions. Zobot chatbots can interact with visitors conversationally, automating the process of customer interactions and maintaining a presence even when all operators are engaged. This application uses Zobot to perform various tasks in the chat window, saving operator time.

## Hosted Application

The application is hosted and can be accessed at [https://salesiq.sempit.repl.co/](https://salesiq.sempit.repl.co/). Feel free to explore its features and functionalities.


## Features

- **Job Openings Display**: The application presents job openings in a concise and user-friendly manner.

- **Candidate Job Association**: The application can check if a candidate is associated with any job openings from previous enrollments and display them in a card format.

- **User Registration**: To register, the user must select a job opening and provide their email, a link to their resume, and a phone number. OTP verification is required for the phone number.

- **OTP Messaging**: Upon enrolling for a job opening, the user will receive an OTP message for verification. This process may take a few seconds as it uses the Spring Edge third-party service.

## Usage

To use this application, simply navigate to the job openings page and follow the prompts to register and enroll in job openings.

## Personal opinion

Honestly I've spent 4-5 days on wondering why tokens didn't work [newbie mistake] and looked for third party SMS service provider for free, maybe it has been tedious part but I believe presistence is the key; whomever viewing this repo, I don't think the website will stay up for long and please do note that source code is not optimizied and may find yourself harder to understand the logic since I haven't commented most of lines.

It was refreshing to script in Deluge as I learnt the workflow after attempting for a quite number of times.