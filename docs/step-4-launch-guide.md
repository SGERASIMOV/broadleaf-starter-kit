#### Previous Step: [Get the Broadleaf Starter Kit](step-3-get-starter-kit.md)

#Step 4. Launch the Application

## Launching Broadleaf Starter Kit

To launch Broadleaf Starter Kit, navigate to **Applications > Modules**.

![Installed module](images/installed-module.png)

Select the **Launch** drop-down button and choose **default** to launch the instance or **Advanced Launch...** to change the default instance parameters (e.g. image AMI, instance size, cookbooks location on S3, and destroy time, which should be at least 2 hours).

![Launch Starter Kit 1](images/launch-sk-1.png)

Select the **Launch** button. The instance will take about an hour to reach a running state.

![Starter Kit Advanced Launch](images/launch-advanced-launch.png)

The status bar displays the current status (1). To obtain more information, click the **Jobs** menu (2).

![Launching instance](images/launch-instance-screen-1.png)

**Jobs** displays current running workflows, along with their start times, current duration, name, user and status.

![Launching status](images/launch-instance-screen-2.png)

When the launch workflow (and sub-workflows) "*Finish*," the instance has reached its "Running State" and is ready to use.

![Instance running](images/instance-running.png)

Select the "**demosite **" button to open the demo store. You will see CRS with the Solr search box. Feel free to test it by searching for an item like "salsa."

![CRS search](images/launch-browse-crs-search.png)

Your search results will appear shortly. For filter search results, use right Filter panel.

![Search results](images/launch-crs-search-results.png)

You can select another language (spain for example) and search automaticaly refresh search results according to your language selection

![Search results spain]images/launch-crs-search-results-spain.png)

![Instance running](images/instance-running.png)

Select the "**admin_url**" button to open Administartion Panel. Use admin\admin for login

![Admin login page](images/crs-admin-login.png)

![Admin Panel](images/crs-admin-panel.png)
