# Deploy a New Application Version

You've got a working Elastic Beanstalk sample app and have downloaded a new app with several versions. Now you're ready to deploy those new app versions to that environment.

## Step-by-Step

### Upload a New Application Version

Before you can deploy a new application version, you first have to upload it to Elastic Beanstalk.

1. Click the Deploy button on your application's dashboard page:

	![](img/en/step_click-deploy.png)

2. Click Upload, enter a Version Label, choose the first version release (v1.0.0) you downloaded previously, and click Upload:
	
	![](img/en/step_upload-new-version.png)

### Deploy New Version

Now that you've uploaded a new application version, you can deploy it to your environment.

1. Select the version you just uploaded, click Deploy, select your Environment, then click Deploy:

	![](img/en/step_deploy-new-version.png)

2. Go back to your application environment's dashboard:
	
	![](img/en/step_go-to-app-dashboard.png)
	
3. Your environment status will be Gray while the application is deployed to your environment:

	![](img/en/step_monitor-app-status.png)
	
4. Open your environment's URL when the status returns to Green

### Use New Version

Refer to the release notes for the app/version that you just deployed for details on what's new with that release and how to use it:

|         |   |
|:-------------:| ------------- 
| ![Node.js](img/node_logo.png) |  [Release Notes](http://github.com/awslabs/eb-node-express/releases) |
| ![Python](img/python-logo.png) | [Release Notes](http://github.com/awslabs/eb-python-flask/releases) |
	
### Repeat

Repeat the above steps to upload and deploy the additional (e.g., v1.1.0, v1.2.0, etc) application versions.

## Congratulations!

You've uploaded and deployed multiple application versions to your Elastic Beanstalk environment!

---

### [Where to Go From Here](where-to-go-from-here.md)

---
