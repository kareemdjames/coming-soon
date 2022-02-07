# Let's Get Right Coming Soon


<!-- TODO: Insert the link in between the parenthesis -->
This is the repository for [Let's Get Right Coming Soon Website](https://coming-soon-340518.uc.r.appspot.com/). 

<br>

## The project

### Benefits of Google App Engine
Google App Engine in cloud computing is a PaaS, Platform as a Service model, i.e., it provides a platform for developers to build scalable applications on the Google cloud platform. The best thing about GAE is its ability to manage the built applications in Google’s data centers.

This way, organizations only have one job to master — building applications on the cloud. For the rest part — the App Engine provides the platform as well as manages the applications.

Google allows you to add your web application code to the platform while managing the infrastructure for you. The engine ensures that your web apps are secure and running and saves them from malware and threats by enabling the firewall.

1. All Time Availability<br>
When you develop and deploy your web applications on the cloud, you enable remote access for your applications. Considering the impact of COVID-19 on businesses, Google App Engine is the right choice that lets the developers develop applications remotely, while the cloud service manages the infrastructure needs.

2. Ensure Faster Time to Market<br>
For your web applications to succeed, ensuring faster time to market is imperative as the requirements are likely to change if the launch time is extended. Using Google App Engine is as easy as it can get for developers. The diverse tool repository and other functionalities ensure that the Google Cloud application development and testing time gets reduced, which, in turn, ensures faster launch time for MVP and consecutive launches.

3. Easy to Use Platform<br>
The developers only require to write code. With zero configuration and server management, you eliminate all the burden to manage and deploy the code. Google App Engine makes it easy to use the platform, which offers the flexibility to focus on other concurrent web applications and processes. The best part is that GAE automatically handles the traffic increase through patching, provisioning, and monitoring.

4. Diverse Set of APIs<br>
Google App Engine has several built-in APIs and services that allow developers to build robust and feature-rich apps. These features include:
Access to the application log
Blobstore, serve large data objects
Google App Engine Cloud Storage
SSL Support
Page Speed Services
Google Cloud Endpoint, for mobile application
URL Fetch API, User API, Memcache API, Channel API, XXMP API, File API
5. Increased Scalability<br>
Scalability is synonymous with growth — an essential factor that assures success and competitive advantage. The good news is that the Google App Engine cloud development platform is automatically scalable. Whenever the traffic to the web application increases, GAE automatically scales up the resources, and vice-versa.

6. Improved Savings<br>
With Google App Engine, you do not have to spend extra on server management of the app. The Google Cloud service is good at handling the backend process.
Also, Google App Engine pricing is flexible as the resources can scale up/down based on the app’s usage. The resources automatically scale up/down based on how the app performs in the market, thus ensuring honest pricing in the end.

7. Smart Pricing<br>
The major concern of organizations revolves around how much does Google App Engine cost? For your convenience, Google App Engine has a daily and a monthly billing cycle, i.e.,
Daily: You will be charged daily for the resources you use
Monthly: All the daily charges are calculated and added to the taxes (if applicable) and debited from your payment method
Also, the App Engine has a dedicated billing dashboard, “App Engine Dashboard” to view and manage your account and subsequent billings.

### Technologies used
I've used the following technologies:
- [Google App Engine](https://cloud.google.com/appengine/docs/overview)
- [Python](https://www.python.org/)
- [Google Cloud SDK](https://cloud.google.com/sdk/)

## The app
This app is a simple static coming soon website that I created to learn basic web concepts and hosting on Google App Engine. The app is deployed on Google App Engine. 

## Folder structure
- HTML files are located in `www/`
- CSS files are located in `www/css`
- Images are located in `www/img/`
- App engine configuration is located in `app.yaml` 

## Deployment
- To deploy this app **live**:
  - From a terminal, with Google Cloud SDK **OR** from the [Google's cloud shell](https://shell.cloud.google.com/):
      - `cd` into the `coming-soon` folder which contains the `app.yaml` config file (e.g.: `cd coming-soon`)
      - Deploy the web app: `gcloud app deploy`

- To test this app **locally**:
  - From **[Google's cloud shell](https://shell.cloud.google.com/)**:
    - `cd` into the `coming-soon` folder which contains the `app.yaml` config file
      -   e.g.: `cd coming-soon`
    - Run the following command to run the web server locally `dev_appserver.py app.yaml`
    - View the website by clicking on *preview on port 8080* (see image below) 
     ![image](https://user-images.githubusercontent.com/34327253/151443857-58edd60d-0731-4cc9-b963-48ba245fafde.png)


  - From your **local machine's terminal** (your computer), with Python installed:
    - Create a virtual environment:
      ```
      python3 -m venv env
      ```  
    - Activate the virtual environment:
        ```
        source env/bin/activate
        ```
    - Install dependencies:
        ```
        pip install -r requirements.txt
        ```
    - Run the app:
        ```
        python main.py
        ```
        The url for the app will be displayed in the terminal (e.g.  Running on http://127.0.0.1:5000/).