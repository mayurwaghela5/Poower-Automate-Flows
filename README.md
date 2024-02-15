# Power Automate Flows Repository

Welcome to the Power Automate Flows Repository! This repository is dedicated to storing and sharing various Power Automate flows created to automate tasks, streamline processes, and improve productivity. Whether you're a beginner or an experienced user, you'll find a variety of flows here to inspire and assist you in your automation journey.
What is Power Automate?

Power Automate (formerly known as Microsoft Flow) is a cloud-based service that allows users to create automated workflows across a multitude of apps and services, without the need for extensive coding knowledge. With Power Automate, you can automate repetitive tasks, synchronize files, collect data, and more, all with minimal effort.

------------------------------------------------------------------------------------------------------------------------

These are the flows:

1. Title: Job Referral Reminder Flow

Description:

The Job Referral Reminder Flow is a workflow designed to assist active job seekers in keeping track of their job referral requests and follow-ups. This workflow utilizes Google Sheets and Gmail connections to automate reminders for job referral requests that have not been acted upon after a specified time period.

Functionality:

    Trigger: The flow is triggered to run every day at 9pm CST time.

    Data Management:
        Google Sheets: The workflow accesses a Google Sheet where job referral requests are logged. The sheet contains columns for the company name, job application link, job title, status of the application, and the date when the referral request was made.

    Condition Check:
        The workflow checks the status of the job application in the Google Sheet. It specifically looks for entries where the status is marked as "PENDING."

    Time Check:
        The workflow calculates the time elapsed since the referral request was made. If it has been 2 days since the request was made and the application status is still "PENDING," the workflow proceeds.

    Action:
        If the conditions are met, the workflow sends an email reminder to the person who was asked for the job referral. The email includes details such as the company name, job application link, and job title. Also, it updates the "Update" column in the sheet mentioning on what date was the reminder sent.

How to Use

To use any of the flows available in this repository, follow these steps:

    Clone or Download: Clone or download the repository to your local machine.

    Import Flow: Import the desired flow into your Power Automate environment by uploading the .zip file provided in the repository.

    Configure Connections: Configure the necessary connections and permissions required for the flow to function properly. This may include connecting to email accounts, cloud storage services, or other applications.

    Customize: Customize the flow to suit your specific needs by adjusting triggers, actions, and conditions as necessary.

    Test: Test the flow thoroughly to ensure it behaves as expected and meets your requirements.

    Deploy: Once satisfied, deploy the flow to your production environment for ongoing use.

Benefits:

    Helps job seekers stay organized and proactive in their job search efforts.
    Automates the follow-up process for job referral requests, saving time and effort.
    Ensures timely communication with referrers, increasing the likelihood of successful referrals.


------------------------------------------------------------------------------------------------------------------------

Contributions

Contributions to this repository are welcome! If you have created a Power Automate flow that you believe would benefit others, feel free to submit a pull request to have it included in the repository.