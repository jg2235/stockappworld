Module 0: Introduction &  Lab Environment Orientation
=====================================================

This module kicks off our AppWorld *Code, Secure, Repeat - From AI Coding to Complete App Security Lab* and
is designed to get you oriented and comfortable in our hands-on lab environment.

Throughout this course we dive into essential technologies like:

* F5 Distributed Cloud (including vK8s, WAAP, and WAS)
* VSCode Server enhanced by the Cline extension
* GitLab CE for CI/CD
* Terraform with the volterraedge provider
* Python


In this module, you'll verify access to key tools: starting with VSCode Server for coding, GitLab for version control, and your F5 Distributed Cloud tenant for security.
We'll also confirm pre-built objects like namespaces and clusters, capture your unique namespace, and generate an API token to streamline automation.

Follow the steps closely—images are provided for guidance—and let's ensure everything's set up smoothly so you're ready to build and secure apps in the modules ahead. 



+----------------------------------------------------------------------------------------------+
| **Beginning of Lab:**  Let's get started!  Ask questions as needed.                          |
+----------------------------------------------------------------------------------------------+
| |labbgn|                                                                                     |
+----------------------------------------------------------------------------------------------+



**Expected Lab Time: 20 minutes**

Task 1: Verify Lab Component Access
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

For this task we will explore and verify access Visual Studio Code, in later modules we will work within
VSCode and use AI to vibe code our application.

+----------------------------------------------------------------------------------------------+
| 1. First up locate  the **Jump Host** resource and click **Access**  then **VSCODE**         |
|                                                                                              |
| |task1-01|                                                                                   |
+----------------------------------------------------------------------------------------------+
|                                                                                              |
| 2. Now enter the password *AppWorld2026!* and Click **Submit**  to login to VSCode           |
|                                                                                              |
| |task1-02|                                                                                   |
+----------------------------------------------------------------------------------------------+

+----------------------------------------------------------------------------------------------+
|                                                                                              |
| 3. This brings us to the VSCode walkthrough screen, to your left is the Cline extenstion, on |
|                                                                                              |
|    the right a AI assisted build agent.  Center screen is where you can adjust color         |
|                                                                                              |
|    preference, pick a color scheme and click **Mark Done** when your customizations are      |
|                                                                                              |
|    complete.                                                                                 |
| |task1-03|                                                                                   |
+----------------------------------------------------------------------------------------------+

.. note::
   *Students may see a this pop-up below, if you do simply click Allow*

+----------------------------------------------------------------------------------------------+
| |task1-13|                                                                                   |
+----------------------------------------------------------------------------------------------+

+----------------------------------------------------------------------------------------------+
| 4. Lets close the VSCode AI code assistant by clicking the "X" in the upper right hand corner|
|                                                                                              |
| |task1-04|                                                                                   | 
|                                                                                              |
+----------------------------------------------------------------------------------------------+
| 5.  Finally lets close the walkthrough screen by click on the "X"                            |
|                                                                                              |
| |task1-14|                                                                                   |
+----------------------------------------------------------------------------------------------+

+----------------------------------------------------------------------------------------------+
|                                                                                              |
| 6. Placed Holder for Gitlab Server Access (browser based)                                    |
| |task1-xx|                                                                                   |
|                                                                                              |
+----------------------------------------------------------------------------------------------+

For now we are finsihed working with VSCode and we can turn our attention to getting F5 Distributed Cloud tenant access verified

The following steps will guide you through the initial setup to access the Distributed Cloud Console and complete user access
customizations.  We will then verify pre-configured objects such as Namespaces, CE's, Virtual Sites and the vk8's clusters.  These
objects have been automatically created.  Namespaces are individual to each lab student and contain specific configuration objects.  
CE's know as customer edges nodes enable Distributed Cloud to extend to any edge location and provide the same SaaS services as within 
the global platform.  Virtual Sites are logically grouped sites across any edge location's and vk8's are virtual kubernetes services 
for app deployment.  Distributed Cloud Credential API Tokens are used to make API calls to the platform, these need to be manually generated.


You should have received an email with an invitation to access a F5 Distributed Cloud Tenant. The email will come 
from **no-reply@cloud.f5.com**.  Please check the email address used for course registration and its associated spam 
folders to see if the invitation email has been received. If you have not received an email, please contact a
memberof the lab team.


.. note::
     *F5 Distributed Cloud Console: https://f5-xc-lab-app.console.ves.volterra.io/*

 

+----------------------------------------------------------------------------------------------+
| 1. Lets grab that email and click **Accept Invitation**                                      |
|                                                                                              |
+----------------------------------------------------------------------------------------------+
| |task1-05|                                                                                   |
|                                                                                              |
+----------------------------------------------------------------------------------------------+
| 2. This should bring you to the sign-in screen below, Click **Sign in with Okta**            |
|                                                                                              |
+----------------------------------------------------------------------------------------------+
| |task1-06|                                                                                   |
|                                                                                              |
+----------------------------------------------------------------------------------------------+
| 3.  When you first login, accept the Lab tenant EULA. Click the check box and then click     |
|                                                                                              |
|     **Accept and Agree**.                                                                    |
+----------------------------------------------------------------------------------------------+
| |task1-07|                                                                                   |
|                                                                                              |
+----------------------------------------------------------------------------------------------+
| 4. Select **Super User** domain role and click **Next** to see various configuration options.|
|                                                                                              |
|    Roles can be changed any time later if desired.                                           |
|                                                                                              |
+----------------------------------------------------------------------------------------------+
|                                                                                              |
| |task1-08|                                                                                   |
|                                                                                              |
+----------------------------------------------------------------------------------------------+
| 5. Click the **Advanced** skill level to expose more menu options and then click **Get**     |
|                                                                                              |
|    **Started** to begin. You can change this setting after logging in as well.               |
+----------------------------------------------------------------------------------------------+
|                                                                                              |
| |task1-09|                                                                                   |
|                                                                                              |
+----------------------------------------------------------------------------------------------+
| 6. Namespaces, which provide an environment for isolating configured applications or         |
|                                                                                              |
|    enforcing role-based access controls, are leveraged within the F5 Distributed Cloud       |
|                                                                                              |
|    Console.  For the purposes of this lab, each lab attendee has been provided a unique      |
|                                                                                              |
|    **namespace** which you will be defaulted to (in terms of GUI navigation) for all tasks   |
|                                                                                              |
|    performed through the course of this lab.  To locate your specific namespace on the main  |
|                                                                                              |
|    screen below click the **profile**  icon in the upper right hand corner then select       |
|                                                                                              |
|    **Account Settings**                                                                      |
+----------------------------------------------------------------------------------------------+
|                                                                                              |
| |task1-10|                                                                                   |
|                                                                                              |
+----------------------------------------------------------------------------------------------+
| 7. Under personal management now click **My Namespaces**                                     |
|                                                                                              |
+----------------------------------------------------------------------------------------------+
|                                                                                              |
| |task1-11|                                                                                   |
|                                                                                              |
+----------------------------------------------------------------------------------------------+
| 8. To the the right you will see a unique **Namespace** assigned specifically to you, keep   |
|                                                                                              |
|    note of this as you will use this throught the remaining labs                             |
+----------------------------------------------------------------------------------------------+
|                                                                                              |
| |task1-12|                                                                                   |
|                                                                                              |
+----------------------------------------------------------------------------------------------+


+----------------------------------------------------------------------------------------------+
| 9. Generating a API Token is under your profile begin by click the **profile**  icon in the  | 
|                                                                                              |
|    upper right hand corner then select **Account Settings**                                  |
|                                                                                              |
| |task1-10|                                                                                   |
|                                                                                              |
+----------------------------------------------------------------------------------------------+
| 10. Under **Personal Management** Click **Credentials** then **Add Credentials**              | 
|                                                                                              |
| |task2-05|                                                                                   |
|                                                                                              |
+----------------------------------------------------------------------------------------------+
| 11. Use the following values:                                                                 | 
|                                                                                              |
|    **Credential Name:** *your-namespace-token*                                               |
|                                                                                              |
|    **Credential Type:** *API Token                                                           |
|                                                                                              |
|    **Expiry Date:** *Any Future Date*                                                        |
|                                                                                              |
|                                                                                              |
| |task2-06|                                                                                   |
|                                                                                              |
+----------------------------------------------------------------------------------------------+

+----------------------------------------------------------------------------------------------+
| 12. Click **Generate** at the bottom of the window and take note of the API Token value.      | 
|                                                                                              |
|    This will only appear once so copy and store otherwise you will need to either delete and |
|                                                                                              |
|    create a new API Token if you lose this key.                                              |
|                                                                                              |
| |task2-07|                                                                                   |
+----------------------------------------------------------------------------------------------+





Great! Now that we have taken care of some of the inital configurations lets finish up the rest in Task 2.

Task 2: Configure Cline Extension and GITLAB environment 
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

In this task we will finish setting up the Cline Extension and GITLAB environments so we can start
our  AI-assisted and Vibe coding journey.

+----------------------------------------------------------------------------------------------+
| 1. Locate  the **Jump Host** resource and click **Access**  then **VSCODE**                  |
|                                                                                              |
| |task1-01|                                                                                   |
+----------------------------------------------------------------------------------------------+
| 2. Look to the leftmost side and locate the Cline icon as indicated below                    |
|                                                                                              |
|  |task2-01|                                                                                  |
|                                                                                              |
+----------------------------------------------------------------------------------------------+
| 3. Select **Bring my own API Key** and Click Continue                                        |
|                                                                                              |
| |task2-02|                                                                                   |
+----------------------------------------------------------------------------------------------+
| 4. Configure the Provider with the following values then click **Continue**                  |
|                                                                                              |
|    **API Provider:** *GCP Vertex AI*                                                         |
|                                                                                              |
|    **Google Cloud Project ID:** *vscode-xxxxxx*                                              |
|                                                                                              |
|    **Google Cloud Region:** *us-central1*                                                    |
|                                                                                              |
|    **Model:** *gemini-2.5-flash*                                                             |
|                                                                                              |
| |task2-03|                                                                                   |
+----------------------------------------------------------------------------------------------+
| 5. When successfully configured you should see the following                                 |
|                                                                                              |
| |task2-04|                                                                                   |
|                                                                                              |
+----------------------------------------------------------------------------------------------+





+----------------------------------------------------------------------------------------------+
| **End of Lab:** Nice Job! Its time to move on to the next module!                            |
+----------------------------------------------------------------------------------------------+
| |labend|                                                                                     |
+----------------------------------------------------------------------------------------------+


.. |task1-01| image:: ../_static/task1-01.png
   :width: 800px
.. |task1-02| image:: ../_static/task1-02.png
   :width: 800px
.. |task1-03| image:: ../_static/task1-03.png
   :width: 800px
.. |task1-04| image:: ../_static/task1-04.png
   :width: 400px
.. |task1-05| image:: ../_static/task1-05.png
   :width: 800px
.. |task1-06| image:: ../_static/task1-06.png
   :width: 800px
.. |task1-07| image:: ../_static/task1-07.png
   :width: 800px
.. |task1-08| image:: ../_static/task1-08.png
   :width: 800px
.. |task1-09| image:: ../_static/task1-09.png
   :width: 800px
.. |task1-10| image:: ../_static/task1-10.png
   :width: 800px
.. |task1-11| image:: ../_static/task1-11.png
   :width: 800px
.. |task1-12| image:: ../_static/task1-12.png
   :width: 800px
.. |task1-13| image:: ../_static/task1-13.png
   :width: 400px
.. |task1-14| image:: ../_static/task1-14.png
   :width: 400px
.. |task2-01| image:: ../_static/task2-01.png
   :width: 300px
.. |task2-02| image:: ../_static/task2-02.png
   :width: 800px
.. |task2-03| image:: ../_static/task2-03.png
   :width: 800px
.. |task2-04| image:: ../_static/task2-04.png
   :width: 800px
.. |task2-05| image:: ../_static/task2-05.png
   :width: 800px
.. |task2-06| image:: ../_static/task2-06.png
   :width: 600px
.. |task2-07| image:: ../_static/task2-07.png
   :width: 600px
.. |labbgn| image:: ../_static/labbgn.png
   :width: 800px
.. |labend| image:: ../_static/labend.png
   :width: 800px
