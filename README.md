## Table of Contents

| No. | Questions |
| --- | --------------------------- |
| 1   | [You significantly changed a complex Deployment Manager template and want to confirm that the dependencies of all defined resources are properly met before committing it to the project. You want the most rapid feedback on your changes. What should you do?](#you-significantly-changed-a-complex-deployment-manager-template-and-want-to-confirm-that-the-dependencies-of-all-defined-resources-are-properly-met-before-committing-it-to-the-project-you-want-the-most-rapid-feedback-on-your-changes-what-should-you-do) |
| 2   | [Your company has a 3-tier solution running on Compute Engine. The configuration of the current infrastructure is shown below. Each tier has a service account that is associated with all instances within it. You need to enable communication on TCP port 8080 between tiers as follows: Instances in tier #1 must communicate with tier #2. Instances in tier #2 must communicate with tier #3. What should you do?](#your-company-has-a-3-tier-solution-running-on-compute-engine-the-configuration-of-the-current-infrastructure-is-shown-below-each-tier-has-a-service-account-that-is-associated-with-all-instances-within-it-you-need-to-enable-communication-on-tcp-port-8080-between-tiers-as-follows-instances-in-tier-1-must-communicate-with-tier-2-instances-in-tier-2-must-communicate-with-tier-3-what-should-you-do) |
| 3   | [You are analyzing Google Cloud Platform service costs from three separate projects. You want to use this information to create service cost estimates by service type, daily and monthly, for the next six months using standard query syntax. What should you do?](#you-are-analyzing-google-cloud-platform-service-costs-from-three-separate-projects-you-want-to-use-this-information-to-create-service-cost-estimates-by-service-type-daily-and-monthly-for-the-next-six-months-using-standard-query-syntax-what-should-you-do) |
| 4   | [You want to send and consume Cloud Pub/Sub messages from your App Engine application. The Cloud Pub/Sub API is currently disabled. You will use a service account to authenticate your application to the API. You want to make sure your application can use Cloud Pub/Sub. What should you do?](#you-want-to-send-and-consume-cloud-pubsub-messages-from-your-app-engine-application-the-cloud-pubsub-api-is-currently-disabled-you-will-use-a-service-account-to-authenticate-your-application-to-the-api-you-want-to-make-sure-your-application-can-use-cloud-pubsub-what-should-you-do) |
| 5   | [You have a website hosted on App Engine standard environment. You want 1% of your users to see a new test version of the website. You want to minimize complexity.](#you-have-a-website-hosted-on-app-engine-standard-environment-you-want-1-of-your-users-to-see-a-new-test-version-of-the-website-you-want-to-minimize-complexity) |
| 6   | [Your organization is a financial company that needs to store audit log files for 3 years. Your organization has hundreds of Google Cloud projects. You need to implement a cost-effective approach for log file retention.](#your-organization-is-a-financial-company-that-needs-to-store-audit-log-files-for-3-years-your-organization-has-hundreds-of-google-cloud-projects-you-need-to-implement-a-cost-effective-approach-for-log-file-retention) |
| 7   | [You built an application on Google Cloud that uses Cloud Spanner. Your support team needs to monitor the environment but should not have access to table data. You need a streamlined solution to grant the correct permissions to your support team, and you want to follow Google-recommended practices. What should you do?](#you-built-an-application-on-google-cloud-that-uses-cloud-spanner-your-support-team-needs-to-monitor-the-environment-but-should-not-have-access-to-table-data-you-need-a-streamlined-solution-to-grant-the-correct-permissions-to-your-support-team-and-you-want-to-follow-google-recommended-practices-what-should-you-do) |
| 8   | [You want to run a single caching HTTP reverse proxy on GCP for a latency-sensitive website. This specific reverse proxy consumes almost no CPU. You want to have a 30-GB in-memory cache, and need an additional 2 GB of memory for the rest of the processes. You want to minimize cost. How should you run this reverse proxy?](#you-want-to-run-a-single-caching-http-reverse-proxy-on-gcp-for-a-latency-sensitive-website-this-specific-reverse-proxy-consumes-almost-no-cpu-you-want-to-have-a-30-gb-in-memory-cache-and-need-an-additional-2-gb-of-memory-for-the-rest-of-the-processes-you-want-to-minimize-cost-how-should-you-run-this-reverse-proxy) |
| 9   | [You have a single binary application that you want to run on Google Cloud Platform. You decided to automatically scale the application based on underlying infrastructure CPU usage. Your organizational policies require you to use Virtual Machines directly. You need to ensure that the application scaling is operationally efficient and completed as quickly as possible. What should you do?](#you-have-a-single-binary-application-that-you-want-to-run-on-google-cloud-platform-you-decided-to-automatically-scale-the-application-based-on-underlying-infrastructure-cpu-usage-your-organizational-policies-require-you-to-use-virtual-machines-directly-you-need-to-ensure-that-the-application-scaling-is-operationally-efficient-and-completed-as-quickly-as-possible-what-should-you-do) |
| 10   | [You need to set up permissions for a set of Compute Engine instances to enable them to write data into a particular Cloud Storage bucket. You want to follow Google-recommended practices. What should you do?](#you-need-to-set-up-permissions-for-a-set-of-compute-engine-instances-to-enable-them-to-write-data-into-a-particular-cloud-storage-bucket-you-want-to-follow-google-recommended-practices-what-should-you-do) |
| 11   | [You have an object in a Cloud Storage bucket that you want to share with an external company. The object contains sensitive data. You want access to the content to be removed after four hours. The external company does not have a Google account to which you can grant specific user-based access privileges. You want to use the most secure method that requires the fewest steps. What should you do?](#you-have-an-object-in-a-cloud-storage-bucket-that-you-want-to-share-with-an-external-company-the-object-contains-sensitive-data-you-want-access-to-the-content-to-be-removed-after-four-hours-the-external-company-does-not-have-a-google-account-to-which-you-can-grant-specific-user-based-access-privileges-you-want-to-use-the-most-secure-method-that-requires-the-fewest-steps-what-should-you-do) |
| 12   | [You need to create an autoscaling Managed Instance Group for an HTTPS web application. You want to make sure that unhealthy VMs are recreated. What should you do?](#you-need-to-create-an-autoscaling-managed-instance-group-for-an-https-web-application-you-want-to-make-sure-that-unhealthy-vms-are-recreated-what-should-you-do) |
| 13   | [You are deploying an application to a Compute Engine VM in a Managed Instance Group. The application must be running at all times, but only a single instance of the VM should run per GCP project. How should you configure the instance group?](#you-are-deploying-an-application-to-a-compute-engine-vm-in-a-managed-instance-group-the-application-must-be-running-at-all-times-but-only-a-single-instance-of-the-vm-should-run-per-gcp-project-how-should-you-configure-the-instance-group) |
| 14   | [You have production and test workloads that you want to deploy on Compute Engine. Production VMs need to be in a different subnet than the test VMs. All the VMs must be able to reach each other over internal IP without creating additional routes. You need to set up VPC and the 2 subnets. Which configuration meets these requirements?](#you-have-production-and-test-workloads-that-you-want-to-deploy-on-compute-engine-production-vms-need-to-be-in-a-different-subnet-than-the-test-vms-all-the-vms-must-be-able-to-reach-each-other-over-internal-ip-without-creating-additional-routes-you-need-to-set-up-vpc-and-the-2-subnets-which-configuration-meets-these-requirements) |
| 15   | [You have an instance group that you want to load balance. You want the load balancer to terminate the client SSL session. The instance group is used to serve a public web application over HTTPS. You want to follow Google-recommended practices. What should you do?](#you-have-an-instance-group-that-you-want-to-load-balance-you-want-the-load-balancer-to-terminate-the-client-ssl-session-the-instance-group-is-used-to-serve-a-public-web-application-over-https-you-want-to-follow-google-recommended-practices-what-should-you-do) |
| 16   | [You have a web application deployed as a Managed Instance Group. You have a new version of the application to gradually deploy. Your web application is currently receiving live web traffic. You want to ensure that the available capacity does not decrease during the deployment. What should you do?](#you-have-a-web-application-deployed-as-a-managed-instance-group-you-have-a-new-version-of-the-application-to-gradually-deploy-your-web-application-is-currently-receiving-live-web-traffic-you-want-to-ensure-that-the-available-capacity-does-not-decrease-during-the-deployment-what-should-you-do) |
| 17   | [You need to grant access for three users so that they can view and edit table data on a Cloud Spanner instance. What should you do?](#you-need-to-grant-access-for-three-users-so-that-they-can-view-and-edit-table-data-on-a-cloud-spanner-instance-what-should-you-do) |
| 18   | [You need to create a new billing account and then link it with an existing Google Cloud Platform project. What should you do?](#you-need-to-create-a-new-billing-account-and-then-link-it-with-an-existing-google-cloud-platform-project-what-should-you-do) |
| 19   | [You have sensitive data stored in three Cloud Storage buckets and have enabled data access logging. You want to verify activities for a particular user for these buckets, using the fewest possible steps. You need to verify the addition of metadata labels and which files have been viewed from those buckets. What should you do?](#you-have-sensitive-data-stored-in-three-cloud-storage-buckets-and-have-enabled-data-access-logging-you-want-to-verify-activities-for-a-particular-user-for-these-buckets-using-the-fewest-possible-steps-you-need-to-verify-the-addition-of-metadata-labels-and-which-files-have-been-viewed-from-those-buckets-what-should-you-do) |
| 20   | [You need to run an important query in BigQuery but expect it to return a lot of records. You want to find out how much it will cost to run the query. You are using on-demand pricing. What should you do?](#you-need-to-run-an-important-query-in-bigquery-but-expect-it-to-return-a-lot-of-records-you-want-to-find-out-how-much-it-will-cost-to-run-the-query-you-are-using-on-demand-pricing-what-should-you-do) |
| 21   | [You need to monitor resources that are distributed over different projects in Google Cloud Platform. You want to consolidate reporting under the same Stackdriver Monitoring dashboard. What should you do?](#you-need-to-monitor-resources-that-are-distributed-over-different-projects-in-google-cloud-platform-you-want-to-consolidate-reporting-under-the-same-stackdriver-monitoring-dashboard-what-should-you-do) |
| 22   | [You need a dynamic way of provisioning VMs on Compute Engine. The exact specifications will be in a dedicated configuration file. You want to follow Google's recommended practices. Which method should you use?](#you-need-a-dynamic-way-of-provisioning-vms-on-compute-engine-the-exact-specifications-will-be-in-a-dedicated-configuration-file-you-want-to-follow-googles-recommended-practices-which-method-should-you-use) |
| 23   | [You created an instance of SQL Server 2017 on Compute Engine to test features in the new version. You want to connect to this instance using the fewest number of steps. What should you do?](#you-created-an-instance-of-sql-server-2017-on-compute-engine-to-test-features-in-the-new-version-you-want-to-connect-to-this-instance-using-the-fewest-number-of-steps-what-should-you-do) |
| 24   | [You are the organization and billing administrator for your company. The engineering team has the Project Creator role on the organization. You do not want the engineering team to be able to link projects to the billing account. Only the finance team should be able to link a project to a billing account, but they should not be able to make any other changes to projects. What should you do?](#you-are-the-organization-and-billing-administrator-for-your-company-the-engineering-team-has-the-project-creator-role-on-the-organization-you-do-not-want-the-engineering-team-to-be-able-to-link-projects-to-the-billing-account-only-the-finance-team-should-be-able-to-link-a-project-to-a-billing-account-but-they-should-not-be-able-to-make-any-other-changes-to-projects-what-should-you-do) |
| 25   | [You are creating a Google Kubernetes Engine (GKE) cluster with a cluster autoscaler feature enabled. You need to make sure that each node of the cluster will run a monitoring pod that sends container metrics to a third-party monitoring solution. What should you do?](#you-are-creating-a-google-kubernetes-engine-gke-cluster-with-a-cluster-autoscaler-feature-enabled-you-need-to-make-sure-that-each-node-of-the-cluster-will-run-a-monitoring-pod-that-sends-container-metrics-to-a-third-party-monitoring-solution-what-should-you-do) |
| 26   | [You create a new Google Kubernetes Engine (GKE) cluster and want to make sure that it always runs a supported and stable version of Kubernetes. What should you do?](#you-create-a-new-google-kubernetes-engine-gke-cluster-and-want-to-make-sure-that-it-always-runs-a-supported-and-stable-version-of-kubernetes-what-should-you-do) |
| 27   | [Your company uses Cloud Storage to store application backup files for disaster recovery purposes. You want to follow Google's recommended practices. Which storage option should you use?](#your-company-uses-cloud-storage-to-store-application-backup-files-for-disaster-recovery-purposes-you-want-to-follow-googles-recommended-practices-which-storage-option-should-you-use) |
| 28   | [You need to set up a policy so that videos stored in a specific Cloud Storage Regional bucket are moved to Coldline after 90 days, and then deleted after one year from their creation. How should you set up the policy?](#you-need-to-set-up-a-policy-so-that-videos-stored-in-a-specific-cloud-storage-regional-bucket-are-moved-to-coldline-after-90-days-and-then-deleted-after-one-year-from-their-creation-how-should-you-set-up-the-policy) |
| 29   | [Your company has an existing GCP organization with hundreds of projects and a billing account. Your company recently acquired another company that also has hundreds of projects and its own billing account. You would like to consolidate all GCP costs of both GCP organizations onto a single invoice. You would like to consolidate all costs as of tomorrow. What should you do?](#your-company-has-an-existing-gcp-organization-with-hundreds-of-projects-and-a-billing-account-your-company-recently-acquired-another-company-that-also-has-hundreds-of-projects-and-its-own-billing-account-you-would-like-to-consolidate-all-gcp-costs-of-both-gcp-organizations-onto-a-single-invoice-you-would-like-to-consolidate-all-costs-as-of-tomorrow-what-should-you-do) |
| 30   | [You want to configure 10 Compute Engine instances for availability when maintenance occurs. Your requirements state that these instances should attempt to automatically restart if they crash. Also, the instances should be highly available including during system maintenance. What should you do?](#you-want-to-configure-10-compute-engine-instances-for-availability-when-maintenance-occurs-your-requirements-state-that-these-instances-should-attempt-to-automatically-restart-if-they-crash-also-the-instances-should-be-highly-available-including-during-system-maintenance-what-should-you-do) |
| 31   | [You have a development project with appropriate IAM roles defined. You are creating a production project and want to have the same IAM roles on the new project, using the fewest possible steps. What should you do?](#you-have-a-development-project-with-appropriate-iam-roles-defined-you-are-creating-a-production-project-and-want-to-have-the-same-iam-roles-on-the-new-project-using-the-fewest-possible-steps-what-should-you-do) |
| 32   | [You are using multiple configurations for gcloud. You want to review the configured Kubernetes Engine cluster of an inactive configuration using the fewest possible steps. What should you do?](#you-are-using-multiple-configurations-for-gcloud-you-want-to-review-the-configured-kubernetes-engine-cluster-of-an-inactive-configuration-using-the-fewest-possible-steps-what-should-you-do) |
| 33   | [You need to configure IAM access audit logging in BigQuery for external auditors. You want to follow Google-recommended practices. What should you do?](#you-need-to-configure-iam-access-audit-logging-in-bigquery-for-external-auditors-you-want-to-follow-google-recommended-practices-what-should-you-do) |
| 34   | [You need to create a custom VPC with a single subnet. The subnet's range must be as large as possible. Which range should you use?](#you-need-to-create-a-custom-vpc-with-a-single-subnet-the-subnets-range-must-be-as-large-as-possible-which-range-should-you-use) |
| 35   | [You recently deployed a new version of an application to App Engine and then discovered a bug in the release. You need to immediately revert to the prior version of the application. What should you do?](#you-recently-deployed-a-new-version-of-an-application-to-app-engine-and-then-discovered-a-bug-in-the-release-you-need-to-immediately-revert-to-the-prior-version-of-the-application-what-should-you-do) |
| 36   | [You want to configure Autohealing for network load balancing for a group of Compute Engine instances that run in multiple zones, using the fewest possible steps. You need to configure re-creation of VMs if they are unresponsive after 3 attempts of 10 seconds each. What should you do?](#you-want-to-configure-autohealing-for-network-load-balancing-for-a-group-of-compute-engine-instances-that-run-in-multiple-zones-using-the-fewest-possible-steps-you-need-to-configure-re-creation-of-vms-if-they-are-unresponsive-after-3-attempts-of-10-seconds-each-what-should-you-do) |
| 37   | [You have a Linux VM that must connect to Cloud SQL. You created a service account with the appropriate access rights. You want to make sure that the VM uses this service account instead of the default Compute Engine service account. What should you do?](#you-have-a-linux-vm-that-must-connect-to-cloud-sql-you-created-a-service-account-with-the-appropriate-access-rights-you-want-to-make-sure-that-the-vm-uses-this-service-account-instead-of-the-default-compute-engine-service-account-what-should-you-do) |
| 38   | [You have one project called proj-sa where you manage all your service accounts. You want to be able to use a service account from this project to take snapshots of VMs running in another project called proj-vm. What should you do?](#you-have-one-project-called-proj-sa-where-you-manage-all-your-service-accounts-you-want-to-be-able-to-use-a-service-account-from-this-project-to-take-snapshots-of-vms-running-in-another-project-called-proj-vm-what-should-you-do) |
| 39   | [You have one GCP account running in your default region and zone and another account running in a non-default region and zone. You want to start a new Compute Engine instance in these two Google Cloud Platform accounts using the command line interface. What should you do?](#you-have-one-gcp-account-running-in-your-default-region-and-zone-and-another-account-running-in-a-non-default-region-and-zone-you-want-to-start-a-new-compute-engine-instance-in-these-two-google-cloud-platform-accounts-using-the-command-line-interface-what-should-you-do) |
| 40   | [Every employee of your company has a Google account. Your operational team needs to manage a large number of instances on Compute Engine. Each member of this team needs only administrative access to the servers. Your security team wants to ensure that the deployment of credentials is operationally efficient and must be able to determine who accessed a given instance. What should you do?](#every-employee-of-your-company-has-a-google-account-your-operational-team-needs-to-manage-a-large-number-of-instances-on-compute-engine-each-member-of-this-team-needs-only-administrative-access-to-the-servers-your-security-team-wants-to-ensure-that-the-deployment-of-credentials-is-operationally-efficient-and-must-be-able-to-determine-who-accessed-a-given-instance-what-should-you-do) |
| 41   | [You need to deploy an application, which is packaged in a container image, in a new project. The application exposes an HTTP endpoint and receives very few requests per day. You want to minimize costs. What should you do?](#you-need-to-deploy-an-application-which-is-packaged-in-a-container-image-in-a-new-project-the-application-exposes-an-http-endpoint-and-receives-very-few-requests-per-day-you-want-to-minimize-costs-what-should-you-do) |
| 42   | [Your development team needs a new Jenkins server for their project. You need to deploy the server using the fewest steps possible. What should you do?](#your-development-team-needs-a-new-jenkins-server-for-their-project-you-need-to-deploy-the-server-using-the-fewest-steps-possible-what-should-you-do) |
| 43   | [You are building an application that stores relational data from users. Users across the globe will use this application. Your CTO is concerned about the scaling requirements because the size of the user base is unknown. You need to implement a database solution that can scale with your user growth with minimum configuration changes. Which storage solution should you use?](#you-are-building-an-application-that-stores-relational-data-from-users-users-across-the-globe-will-use-this-application-your-cto-is-concerned-about-the-scaling-requirements-because-the-size-of-the-user-base-is-unknown-you-need-to-implement-a-database-solution-that-can-scale-with-your-user-growth-with-minimum-configuration-changes-which-storage-solution-should-you-use) |
| 44   | [You are using Deployment Manager to create a Google Kubernetes Engine cluster. Using the same Deployment Manager deployment, you also want to create a DaemonSet in the kube-system namespace of the cluster. You want a solution that uses the fewest possible services.](#you-are-using-deployment-manager-to-create-a-google-kubernetes-engine-cluster-using-the-same-deployment-manager-deployment-you-also-want-to-create-a-daemonset-in-the-kube-system-namespace-of-the-cluster-you-want-a-solution-that-uses-the-fewest-possible-services) |
| 45   | [You have a Virtual Machine that is currently configured with 2 vCPUs and 4 GB of memory. It is running out of memory. You want to upgrade the Virtual Machine to have 8 GB of memory. What should you do?](#you-have-a-virtual-machine-that-is-currently-configured-with-2-vcpus-and-4-gb-of-memory-it-is-running-out-of-memory-you-want-to-upgrade-the-virtual-machine-to-have-8-gb-of-memory-what-should-you-do) |
| 46   | [You created a Google Cloud Platform project with an App Engine application inside the project. You initially configured the application to be served from the us-central region. Now you want the application to be served from the asia-northeast1 region. What should you do?](#you-created-a-google-cloud-platform-project-with-an-app-engine-application-inside-the-project-you-initially-configured-the-application-to-be-served-from-the-us-central-region-now-you-want-the-application-to-be-served-from-the-asia-northeast1-region-what-should-you-do) |
| 47   | [Several employees at your company have been creating projects with Cloud Platform and paying for it with their personal credit cards, which the company reimburses. The company wants to centralize all these projects under a single, new billing account. What should you do?](#several-employees-at-your-company-have-been-creating-projects-with-cloud-platform-and-paying-for-it-with-their-personal-credit-cards-which-the-company-reimburses-the-company-wants-to-centralize-all-these-projects-under-a-single-new-billing-account-what-should-you-do) |
| 48   | [You have a Dockerfile that you need to deploy on Kubernetes Engine. What should you do?](#you-have-a-dockerfile-that-you-need-to-deploy-on-kubernetes-engine-what-should-you-do) |
| 49   | [You have a project for your App Engine application that serves a development environment. The required testing has succeeded and you want to create a new project to serve as your production environment. What should you do?](#you-have-a-project-for-your-app-engine-application-that-serves-a-development-environment-the-required-testing-has-succeeded-and-you-want-to-create-a-new-project-to-serve-as-your-production-environment-what-should-you-do) |
| 50   | [You are building an application that will run in your data center. The application will use Google Cloud Platform (GCP) services like AutoML. You created a service account that has appropriate access to AutoML. You need to enable authentication to the APIs from your on-premises environment. What should you do?](#you-are-building-an-application-that-will-run-in-your-data-center-the-application-will-use-google-cloud-platform-gcp-services-like-automl-you-created-a-service-account-that-has-appropriate-access-to-automl-you-need-to-enable-authentication-to-the-apis-from-your-on-premises-environment-what-should-you-do) |
| 51   | [You host a static website on Cloud Storage. Recently, you began to include links to PDF files on this site. Currently, when users click on the links to these PDF files, their browsers prompt them to save the file onto their local system. Instead, you want the clicked PDF files to be displayed within the browser window directly, without prompting the user to save the file locally. What should you do?](#you-host-a-static-website-on-cloud-storage-recently-you-began-to-include-links-to-pdf-files-on-this-site-currently-when-users-click-on-the-links-to-these-pdf-files-their-browsers-prompt-them-to-save-the-file-onto-their-local-system-instead-you-want-the-clicked-pdf-files-to-be-displayed-within-the-browser-window-directly-without-prompting-the-user-to-save-the-file-locally-what-should-you-do) |
| 52   | [You have an application that looks for its licensing server on the IP 10.0.3.21. You need to deploy the licensing server on Compute Engine. You do not want to change the configuration of the application and want the application to be able to reach the licensing server. What should you do?](#you-have-an-application-that-looks-for-its-licensing-server-on-the-ip-100321-you-need-to-deploy-the-licensing-server-on-compute-engine-you-do-not-want-to-change-the-configuration-of-the-application-and-want-the-application-to-be-able-to-reach-the-licensing-server-what-should-you-do) |
| 53   | [You are deploying an application to App Engine. You want the number of instances to scale based on request rate. You need at least 3 unoccupied instances at all times. Which scaling type should you use?](#you-are-deploying-an-application-to-app-engine-you-want-the-number-of-instances-to-scale-based-on-request-rate-you-need-at-least-3-unoccupied-instances-at-all-times-which-scaling-type-should-you-use) |
| 54   | [You are the project owner of a GCP project and want to delegate control to colleagues to manage buckets and files in Cloud Storage. You want to follow Google-recommended practices. Which IAM roles should you grant your colleagues?](#you-are-the-project-owner-of-a-gcp-project-and-want-to-delegate-control-to-colleagues-to-manage-buckets-and-files-in-cloud-storage-you-want-to-follow-google-recommended-practices-which-iam-roles-should-you-grant-your-colleagues) |
| 55   | [You need to update a deployment in Deployment Manager without any resource downtime in the deployment. Which command should you use?](#you-need-to-update-a-deployment-in-deployment-manager-without-any-resource-downtime-in-the-deployment-which-command-should-you-use) |
| 56   | [You are running an application on multiple Virtual Machines within a Managed Instance Group and have autoscaling enabled. The autoscaling policy is configured so that additional instances are added to the group if the CPU utilization of instances goes above 80%. VMs are added until the instance group reaches its maximum limit of five VMs or until CPU utilization of instances lowers to 80%. The initial delay for HTTP health checks against the instances is set to 30 seconds. The Virtual Machine instances take around three minutes to become available for users. You observe that when the instance group autoscales, it adds more instances then necessary to support the levels of end-user traffic. You want to properly maintain instance group sizes when autoscaling. What should you do?](#you-are-running-an-application-on-multiple-virtual-machines-within-a-managed-instance-group-and-have-autoscaling-enabled-the-autoscaling-policy-is-configured-so-that-additional-instances-are-added-to-the-group-if-the-cpu-utilization-of-instances-goes-above-80-vms-are-added-until-the-instance-group-reaches-its-maximum-limit-of-five-vms-or-until-cpu-utilization-of-instances-lowers-to-80-the-initial-delay-for-http-health-checks-against-the-instances-is-set-to-30-seconds-the-virtual-machine-instances-take-around-three-minutes-to-become-available-for-users-you-observe-that-when-the-instance-group-autoscales-it-adds-more-instances-then-necessary-to-support-the-levels-of-end-user-traffic-you-want-to-properly-maintain-instance-group-sizes-when-autoscaling-what-should-you-do) |
| 57   | [You have 32 GB of data in a single file that you need to upload to a Nearline Storage bucket. The WAN connection you are using is rated at 1 Gbps, and you are the only one on the connection. You want to use as much of the rated 1 Gbps as possible to transfer the file rapidly. How should you upload the file?](#you-have-32-gb-of-data-in-a-single-file-that-you-need-to-upload-to-a-nearline-storage-bucket-the-wan-connection-you-are-using-is-rated-at-1-gbps-and-you-are-the-only-one-on-the-connection-you-want-to-use-as-much-of-the-rated-1-gbps-as-possible-to-transfer-the-file-rapidly-how-should-you-upload-the-file) |
| 58   | [You deployed an App Engine application using gcloud app deploy, but it did not deploy to the intended project. You want to find out why this happened and where the application deployed. What should you do?](#you-deployed-an-app-engine-application-using-gcloud-app-deploy-but-it-did-not-deploy-to-the-intended-project-you-want-to-find-out-why-this-happened-and-where-the-application-deployed-what-should-you-do) |
| 59   | [You want to verify the IAM users and roles assigned within a GCP project named my-project. What should you do?](#you-want-to-verify-the-iam-users-and-roles-assigned-within-a-gcp-project-named-my-project-what-should-you-do) |
| 60   | [You need to select and configure compute resources for a set of batch processing jobs. These jobs take around 2 hours to complete and are run nightly. You want to minimize service costs. What should you do?](#you-need-to-select-and-configure-compute-resources-for-a-set-of-batch-processing-jobs-these-jobs-take-around-2-hours-to-complete-and-are-run-nightly-you-want-to-minimize-service-costs-what-should-you-do) |
| 61   | [You want to select and configure a cost-effective solution for relational data on Google Cloud Platform. You are working with a small set of operational data in one geographic location. You need to support point-in-time recovery. What should you do?](#you-want-to-select-and-configure-a-cost-effective-solution-for-relational-data-on-google-cloud-platform-you-are-working-with-a-small-set-of-operational-data-in-one-geographic-location-you-need-to-support-point-in-time-recovery-what-should-you-do) |
| 62   | [You are hosting an application on bare-metal servers in your own data center. The application needs access to Cloud Storage. However, security policies prevent the servers hosting the application from having public IP addresses or access to the internet. You want to follow Google-recommended practices to provide the application with access to Cloud Storage. What should you do?](#you-are-hosting-an-application-on-bare-metal-servers-in-your-own-data-center-the-application-needs-access-to-cloud-storage-however-security-policies-prevent-the-servers-hosting-the-application-from-having-public-ip-addresses-or-access-to-the-internet-you-want-to-follow-google-recommended-practices-to-provide-the-application-with-access-to-cloud-storage-what-should-you-do) |
| 63   | [Your company has a Google Cloud Platform project that uses BigQuery for data warehousing. Your data science team changes frequently and has few members. You need to allow members of this team to perform queries. You want to follow Google-recommended practices. What should you do?](#your-company-has-a-google-cloud-platform-project-that-uses-bigquery-for-data-warehousing-your-data-science-team-changes-frequently-and-has-few-members-you-need-to-allow-members-of-this-team-to-perform-queries-you-want-to-follow-google-recommended-practices-what-should-you-do) |
| 64   | [You are given a project with a single Virtual Private Cloud (VPC) and a single subnetwork in the us-central1 region. There is a Compute Engine instance hosting an application in this subnetwork. You need to deploy a new instance in the same project in the europe-west1 region. This new instance needs access to the application. You want to follow Google-recommended practices. What should you do?](#you-are-given-a-project-with-a-single-virtual-private-cloud-vpc-and-a-single-subnetwork-in-the-us-central1-region-there-is-a-compute-engine-instance-hosting-an-application-in-this-subnetwork-you-need-to-deploy-a-new-instance-in-the-same-project-in-the-europe-west1-region-this-new-instance-needs-access-to-the-application-you-want-to-follow-google-recommended-practices-what-should-you-do) |
| 65   | [You are building a pipeline to process time-series data. Which Google Cloud Platform services should you put in boxes 1,2,3, and 4?](#you-are-building-a-pipeline-to-process-time-series-data-which-google-cloud-platform-services-should-you-put-in-boxes-123-and-4) |
| 66   | [For analysis purposes, you need to send all the logs from all of your Compute Engine instances to a BigQuery dataset called platform-logs. You have already installed the Cloud Logging agent on all the instances. You want to minimize cost. What should you do?](#for-analysis-purposes-you-need-to-send-all-the-logs-from-all-of-your-compute-engine-instances-to-a-bigquery-dataset-called-platform-logs-you-have-already-installed-the-cloud-logging-agent-on-all-the-instances-you-want-to-minimize-cost-what-should-you-do) |
| 67   | [You want to deploy an application on Cloud Run that processes messages from a Cloud Pub/Sub topic. You want to follow Google-recommended practices. What should you do?](#you-want-to-deploy-an-application-on-cloud-run-that-processes-messages-from-a-cloud-pubsub-topic-you-want-to-follow-google-recommended-practices-what-should-you-do) |
| 68   | [Your projects incurred more costs than you expected last month. Your research reveals that a development GKE container emitted a huge number of logs, which resulted in higher costs. You want to disable the logs quickly using the minimum number of steps. What should you do?](#your-projects-incurred-more-costs-than-you-expected-last-month-your-research-reveals-that-a-development-gke-container-emitted-a-huge-number-of-logs-which-resulted-in-higher-costs-you-want-to-disable-the-logs-quickly-using-the-minimum-number-of-steps-what-should-you-do) |
| 69   | [You've deployed a microservice called myapp1 to a Google Kubernetes Engine cluster using the YAML file specified below. You need to refactor this configuration so that the database password is not stored in plain text. You want to follow Google-recommended practices. What should you do?](#youve-deployed-a-microservice-called-myapp1-to-a-google-kubernetes-engine-cluster-using-the-yaml-file-specified-below-you-need-to-refactor-this-configuration-so-that-the-database-password-is-not-stored-in-plain-text-you-want-to-follow-google-recommended-practices-what-should-you-do) |
| 70   | [You have an application running in Google Kubernetes Engine (GKE) with cluster autoscaling enabled. The application exposes a TCP endpoint. There are several replicas of this application. You have a Compute Engine instance in the same region, but in another Virtual Private Cloud (VPC), called gce-network, that has no overlapping IP ranges with the first VPC. This instance needs to connect to the application on GKE. You want to minimize effort. What should you do?](#you-have-an-application-running-in-google-kubernetes-engine-gke-with-cluster-autoscaling-enabled-the-application-exposes-a-tcp-endpoint-there-are-several-replicas-of-this-application-you-have-a-compute-engine-instance-in-the-same-region-but-in-another-virtual-private-cloud-vpc-called-gce-network-that-has-no-overlapping-ip-ranges-with-the-first-vpc-this-instance-needs-to-connect-to-the-application-on-gke-you-want-to-minimize-effort-what-should-you-do) |
| 71   | [You are using Container Registry to centrally store your company's container images in a separate project. In another project, you want to create a Google Kubernetes Engine (GKE) cluster. You want to ensure that Kubernetes can download images from Container Registry. What should you do?](#you-are-using-container-registry-to-centrally-store-your-companys-container-images-in-a-separate-project-in-another-project-you-want-to-create-a-google-kubernetes-engine-gke-cluster-you-want-to-ensure-that-kubernetes-can-download-images-from-container-registry-what-should-you-do)
| 72   | [You deployed a new application inside your Google Kubernetes Engine cluster using the YAML file specified below. You check the status of the deployed pods and notice that one of them is still in PENDING status. You want to find out why the pod is stuck in pending status. What should you do?](#you-deployed-a-new-application-inside-your-google-kubernetes-engine-cluster-using-the-yaml-file-specified-below-you-check-the-status-of-the-deployed-pods-and-notice-that-one-of-them-is-still-in-pending-status-you-want-to-find-out-why-the-pod-is-stuck-in-pending-status-what-should-you-do)
| 73  | [You are setting up a Windows VM on Compute Engine and want to make sure you can log in to the VM via RDP. What should you do?](#you-are-setting-up-a-windows-vm-on-compute-engine-and-want-to-make-sure-you-can-log-in-to-the-vm-via-rdp-what-should-you-do)   |
| 74  | [You want to configure an SSH connection to a single Compute Engine instance for users in the dev1 group. This instance is the only resource in this particular Google Cloud Platform project that the dev1 users should be able to connect to. What should you do?](#you-want-to-configure-an-ssh-connection-to-a-single-compute-engine-instance-for-users-in-the-dev1-group-this-instance-is-the-only-resource-in-this-particular-google-cloud-platform-project-that-the-dev1-users-should-be-able-to-connect-to-what-should-you-do)   |
| 75  | [You need to produce a list of the enabled Google Cloud Platform APIs for a GCP project using the gcloud command line in the Cloud Shell. The project name is my-project. What should you do?](#you-need-to-produce-a-list-of-the-enabled-google-cloud-platform-apis-for-a-gcp-project-using-the-gcloud-command-line-in-the-cloud-shell-the-project-name-is-my-project-what-should-you-do)   |
| 76  | [You are building a new version of an application hosted in an App Engine environment. You want to test the new version with 1% of users before you completely switch your application over to the new version. What should you do?](#you-are-building-a-new-version-of-an-application-hosted-in-an-app-engine-environment-you-want-to-test-the-new-version-with-1-of-users-before-you-completely-switch-your-application-over-to-the-new-version-what-should-you-do)   |
| 77  | [You need to provide a cost estimate for a Kubernetes cluster using the GCP pricing calculator for Kubernetes. Your workload requires high IOPs, and you will also be using disk snapshots. You start by entering the number of nodes, average hours, and average days. What should you do next?](#you-need-to-provide-a-cost-estimate-for-a-kubernetes-cluster-using-the-gcp-pricing-calculator-for-kubernetes-your-workload-requires-high-iops-and-you-will-also-be-using-disk-snapshots-you-start-by-entering-the-number-of-nodes-average-hours-and-average-days-what-should-you-do-next)   |
| 78  | [You are using Google Kubernetes Engine with autoscaling enabled to host a new application. You want to expose this new application to the public, using HTTPS on a public IP address. What should you do?](#you-are-using-google-kubernetes-engine-with-autoscaling-enabled-to-host-a-new-application-you-want-to-expose-this-new-application-to-the-public-using-https-on-a-public-ip-address-what-should-you-do)   |
| 79  | [You need to enable traffic between multiple groups of Compute Engine instances that are currently running two different GCP projects. Each group of Compute Engine instances is running in its own VPC. What should you do?](#you-need-to-enable-traffic-between-multiple-groups-of-compute-engine-instances-that-are-currently-running-two-different-gcp-projects-each-group-of-compute-engine-instances-is-running-in-its-own-vpc-what-should-you-do)   |
| 80  | [You want to add a new auditor to a Google Cloud Platform project. The auditor should be allowed to read, but not modify, all project items. How should you configure the auditor's permissions?](#you-want-to-add-a-new-auditor-to-a-google-cloud-platform-project-the-auditor-should-be-allowed-to-read-but-not-modify-all-project-items-how-should-you-configure-the-auditors-permissions)   |
| 81  | [You are operating a Google Kubernetes Engine (GKE) cluster for your company where different teams can run non-production workloads. Your Machine Learning (ML) team needs access to Nvidia Tesla P100 GPUs to train their models. You want to minimize effort and cost. What should you do?](#you-are-operating-a-google-kubernetes-engine-gke-cluster-for-your-company-where-different-teams-can-run-non-production-workloads-your-machine-learning-ml-team-needs-access-to-nvidia-tesla-p100-gpus-to-train-their-models-you-want-to-minimize-effort-and-cost-what-should-you-do)   |
| 82  | [Your VMs are running in a subnet that has a subnet mask of 255.255.255.240. The current subnet has no more free IP addresses and you require an additional 10 IP addresses for new VMs. The existing and new VMs should all be able to reach each other without additional routes. What should you do?](#your-vms-are-running-in-a-subnet-that-has-a-subnet-mask-of-255255255240-the-current-subnet-has-no-more-free-ip-addresses-and-you-require-an-additional-10-ip-addresses-for-new-vms-the-existing-and-new-vms-should-all-be-able-to-reach-each-other-without-additional-routes-what-should-you-do)   |
| 83  | [Your organization uses G Suite for communication and collaboration. All users in your organization have a G Suite account. You want to grant some G Suite users access to your Cloud Platform project. What should you do?](#your-organization-uses-g-suite-for-communication-and-collaboration-all-users-in-your-organization-have-a-g-suite-account-you-want-to-grant-some-g-suite-users-access-to-your-cloud-platform-project-what-should-you-do)   |
| 84  | [You have a Google Cloud Platform account with access to both production and development projects. You need to create an automated process to list all compute instances in development and production projects on a daily basis. What should you do?](#you-have-a-google-cloud-platform-account-with-access-to-both-production-and-development-projects-you-need-to-create-an-automated-process-to-list-all-compute-instances-in-development-and-production-projects-on-a-daily-basis-what-should-you-do)   |
| 85  | [You have a large 5-TB AVRO file stored in a Cloud Storage bucket. Your analysts are proficient only in SQL and need access to the data stored in this file. You want to find a cost-effective way to complete their request as soon as possible. What should you do?](#you-have-a-large-5-tb-avro-file-stored-in-a-cloud-storage-bucket-your-analysts-are-proficient-only-in-sql-and-need-access-to-the-data-stored-in-this-file-you-want-to-find-a-cost-effective-way-to-complete-their-request-as-soon-as-possible-what-should-you-do)   |
| 86  | [You need to verify that a Google Cloud Platform service account was created at a particular time. What should you do?](#you-need-to-verify-that-a-google-cloud-platform-service-account-was-created-at-a-particular-time-what-should-you-do)   |
| 87  | [You deployed an LDAP server on Compute Engine that is reachable via TLS through port 636 using UDP. You want to make sure it is reachable by clients over that port. What should you do?](#you-deployed-an-ldap-server-on-compute-engine-that-is-reachable-via-tls-through-port-636-using-udp-you-want-to-make-sure-it-is-reachable-by-clients-over-that-port-what-should-you-do)   |
| 88  | [You need to set a budget alert for use of Compute Engine services on one of the three Google Cloud Platform projects that you manage. All three projects are linked to a single billing account. What should you do?](#you-need-to-set-a-budget-alert-for-use-of-compute-engine-services-on-one-of-the-three-google-cloud-platform-projects-that-you-manage-all-three-projects-are-linked-to-a-single-billing-account-what-should-you-do)   |
| 89  | [You are migrating a production-critical on-premises application that requires 96 vCPUs to perform its task. You want to make sure the application runs in a similar environment on GCP. What should you do?](#you-are-migrating-a-production-critical-on-premises-application-that-requires-96-vcpus-to-perform-its-task-you-want-to-make-sure-the-application-runs-in-a-similar-environment-on-gcp-what-should-you-do)   |
| 90  | [You want to configure a solution for archiving data in a Cloud Storage bucket. The solution must be cost-effective. Data with multiple versions should be archived after 30 days. Previous versions are accessed once a month for reporting. This archive data is also occasionally updated at month-end. What should you do?](#you-want-to-configure-a-solution-for-archiving-data-in-a-cloud-storage-bucket-the-solution-must-be-cost-effective-data-with-multiple-versions-should-be-archived-after-30-days-previous-versions-are-accessed-once-a-month-for-reporting-this-archive-data-is-also-occasionally-updated-at-month-end-what-should-you-do)   |
| 91  | [Your company's infrastructure is on-premises, but all machines are running at maximum capacity. You want to burst to Google Cloud. The workloads on Google Cloud must be able to directly communicate to the workloads on-premises using a private IP range. What should you do?](#your-companys-infrastructure-is-on-premises-but-all-machines-are-running-at-maximum-capacity-you-want-to-burst-to-google-cloud-the-workloads-on-google-cloud-must-be-able-to-directly-communicate-to-the-workloads-on-premises-using-a-private-ip-range-what-should-you-do)   |
| 92  | [You want to select and configure a solution for storing and archiving data on Google Cloud Platform. You need to support compliance objectives for data from one geographic location. This data is archived after 30 days and needs to be accessed annually. What should you do?](#you-want-to-select-and-configure-a-solution-for-storing-and-archiving-data-on-google-cloud-platform-you-need-to-support-compliance-objectives-for-data-from-one-geographic-location-this-data-is-archived-after-30-days-and-needs-to-be-accessed-annually-what-should-you-do)   |
| 93  | [Your company uses BigQuery for data warehousing. Over time, many different business units in your company have created 1000+ datasets across hundreds of projects. Your CIO wants you to examine all datasets to find tables that contain an employee_ssn column. You want to minimize effort in performing this task. What should you do?](#your-company-uses-bigquery-for-data-warehousing-over-time-many-different-business-units-in-your-company-have-created-1000-datasets-across-hundreds-of-projects-your-cio-wants-you-to-examine-all-datasets-to-find-tables-that-contain-an-employee_ssn-column-you-want-to-minimize-effort-in-performing-this-task-what-should-you-do)   |
| 94  | [You create a Deployment with 2 replicas in a Google Kubernetes Engine cluster that has a single preemptible node pool. After a few minutes, you use kubectl to examine the status of your Pod and observe that one of them is still in Pending status: What is the most likely cause?](#you-create-a-deployment-with-2-replicas-in-a-google-kubernetes-engine-cluster-that-has-a-single-preemptible-node-pool-after-a-few-minutes-you-use-kubectl-to-examine-the-status-of-your-pod-and-observe-that-one-of-them-is-still-in-pending-status-what-is-the-most-likely-cause)   |
| 95  | [You want to find out when users were added to Cloud Spanner Identity Access Management (IAM) roles on your Google Cloud Platform (GCP) project. What should you do in the GCP Console?](#you-want-to-find-out-when-users-were-added-to-cloud-spanner-identity-access-management-iam-roles-on-your-google-cloud-platform-gcp-project-what-should-you-do-in-the-gcp-console)   |
| 96  | [Your company implemented BigQuery as an enterprise data warehouse. Users from multiple business units run queries on this data warehouse. However, you notice that query costs for BigQuery are very high, and you need to control costs. Which two methods should you use? (Choose two.)](#your-company-implemented-bigquery-as-an-enterprise-data-warehouse-users-from-multiple-business-units-run-queries-on-this-data-warehouse-however-you-notice-that-query-costs-for-bigquery-are-very-high-and-you-need-to-control-costs-which-two-methods-should-you-use-choose-two)   |
| 97  | [You are building a product on top of Google Kubernetes Engine (GKE). You have a single GKE cluster. For each of your customers, a Pod is running in that cluster, and your customers can run arbitrary code inside their Pod. You want to maximize the isolation between your customers' Pods. What should you do?](#you-are-building-a-product-on-top-of-google-kubernetes-engine-gke-you-have-a-single-gke-cluster-for-each-of-your-customers-a-pod-is-running-in-that-cluster-and-your-customers-can-run-arbitrary-code-inside-their-pod-you-want-to-maximize-the-isolation-between-your-customers-pods-what-should-you-do)   |
| 98  | [Your customer has implemented a solution that uses Cloud Spanner and notices some read latency-related performance issues on one table. This table is accessed only by their users using a primary key. The table schema is shown below. You want to resolve the issue. What should you do?](#your-customer-has-implemented-a-solution-that-uses-cloud-spanner-and-notices-some-read-latency-related-performance-issues-on-one-table-this-table-is-accessed-only-by-their-users-using-a-primary-key-the-table-schema-is-shown-below-you-want-to-resolve-the-issue-what-should-you-do)   |
| 99  | [Your finance team wants to view the billing report for your projects. You want to make sure that the finance team does not get additional permissions to the project. What should you do?](#your-finance-team-wants-to-view-the-billing-report-for-your-projects-you-want-to-make-sure-that-the-finance-team-does-not-get-additional-permissions-to-the-project-what-should-you-do)   |
| 100 | [Your organization has strict requirements to control access to Google Cloud projects. You need to enable your Site Reliability Engineers (SREs) to approve requests from the Google Cloud support team when an SRE opens a support case. You want to follow Google-recommended practices. What should you do?](#your-organization-has-strict-requirements-to-control-access-to-google-cloud-projects-you-need-to-enable-your-site-reliability-engineers-sres-to-approve-requests-from-the-google-cloud-support-team-when-an-sre-opens-a-support-case-you-want-to-follow-google-recommended-practices-what-should-you-do) |
| 101 | [You need to host an application on a Compute Engine instance in a project shared with other teams. You want to prevent the other teams from accidentally causing downtime on that application. Which feature should you use?](#you-need-to-host-an-application-on-a-compute-engine-instance-in-a-project-shared-with-other-teams-you-want-to-prevent-the-other-teams-from-accidentally-causing-downtime-on-that-application-which-feature-should-you-use) |
| 102 | [Your organization needs to grant users access to query datasets in BigQuery but prevent them from accidentally deleting the datasets. You want a solution that follows Google-recommended practices. What should you do?](#your-organization-needs-to-grant-users-access-to-query-datasets-in-bigquery-but-prevent-them-from-accidentally-deleting-the-datasets-you-want-a-solution-that-follows-google-recommended-practices-what-should-you-do) |
| 103 | [You have a developer laptop with the Cloud SDK installed on Ubuntu. The Cloud SDK was installed from the Google Cloud Ubuntu package repository. You want to test your application locally on your laptop with Cloud Datastore. What should you do?](#you-have-a-developer-laptop-with-the-cloud-sdk-installed-on-ubuntu-the-cloud-sdk-was-installed-from-the-google-cloud-ubuntu-package-repository-you-want-to-test-your-application-locally-on-your-laptop-with-cloud-datastore-what-should-you-do) |
| 104 | [Your company set up a complex organizational structure on Google Cloud. The structure includes hundreds of folders and projects. Only a few team members should be able to view the hierarchical structure. You need to assign minimum permissions to these team members, and you want to follow Google-recommended practices. What should you do?](#your-company-set-up-a-complex-organizational-structure-on-google-cloud-the-structure-includes-hundreds-of-folders-and-projects-only-a-few-team-members-should-be-able-to-view-the-hierarchical-structure-you-need-to-assign-minimum-permissions-to-these-team-members-and-you-want-to-follow-google-recommended-practices-what-should-you-do) |
| 105 | [Your company has a single sign-on (SSO) identity provider that supports Security Assertion Markup Language (SAML) integration with service providers. Your company has users in Cloud Identity. You would like users to authenticate using your company's SSO provider. What should you do?](#your-company-has-a-single-sign-on-sso-identity-provider-that-supports-security-assertion-markup-language-saml-integration-with-service-providers-your-company-has-users-in-cloud-identity-you-would-like-users-to-authenticate-using-your-companys-sso-provider-what-should-you-do) |
| 106 | [Your organization has a dedicated person who creates and manages all service accounts for Google Cloud projects. You need to assign this person the minimum role for projects. What should you do?](#your-organization-has-a-dedicated-person-who-creates-and-manages-all-service-accounts-for-google-cloud-projects-you-need-to-assign-this-person-the-minimum-role-for-projects-what-should-you-do) |
| 107 | [You are building an archival solution for your data warehouse and have selected Cloud Storage to archive your data. Your users need to be able to access this archived data once a quarter for some regulatory requirements. You want to select a cost-efficient option. Which storage option should you use?](#you-are-building-an-archival-solution-for-your-data-warehouse-and-have-selected-cloud-storage-to-archive-your-data-your-users-need-to-be-able-to-access-this-archived-data-once-a-quarter-for-some-regulatory-requirements-you-want-to-select-a-cost-efficient-option-which-storage-option-should-you-use) |
| 108 | [A team of data scientists infrequently needs to use a Google Kubernetes Engine (GKE) cluster that you manage. They require GPUs for some long-running, nonrestartable jobs. You want to minimize cost. What should you do?](#a-team-of-data-scientists-infrequently-needs-to-use-a-google-kubernetes-engine-gke-cluster-that-you-manage-they-require-gpus-for-some-long-running-nonrestartable-jobs-you-want-to-minimize-cost-what-should-you-do) |
| 109 | [Your organization has user identities in Active Directory. Your organization wants to use Active Directory as their source of truth for identities. Your organization wants to have full control over the Google accounts used by employees for all Google services, including your Google Cloud Platform (GCP) organization. What should you do?](#your-organization-has-user-identities-in-active-directory-your-organization-wants-to-use-active-directory-as-their-source-of-truth-for-identities-your-organization-wants-to-have-full-control-over-the-google-accounts-used-by-employees-for-all-google-services-including-your-google-cloud-platform-gcp-organization-what-should-you-do) |
| 110 | [You have successfully created a development environment in a project for an application. This application uses Compute Engine and Cloud SQL. Now you need to create a production environment for this application. The security team has forbidden the existence of network routes between these 2 environments and has asked you to follow Google-recommended practices. What should you do?](#you-have-successfully-created-a-development-environment-in-a-project-for-an-application-this-application-uses-compute-engine-and-cloud-sql-now-you-need-to-create-a-production-environment-for-this-application-the-security-team-has-forbidden-the-existence-of-network-routes-between-these-2-environments-and-has-asked-you-to-follow-google-recommended-practices-what-should-you-do) |
| 111 | [Your management has asked an external auditor to review all the resources in a specific project. The security team has enabled the Organization Policy called Domain Restricted Sharing on the organization node by specifying only your Cloud Identity domain. You want the auditor to only be able to view, but not modify, the resources in that project. What should you do?](#your-management-has-asked-an-external-auditor-to-review-all-the-resources-in-a-specific-project-the-security-team-has-enabled-the-organization-policy-called-domain-restricted-sharing-on-the-organization-node-by-specifying-only-your-cloud-identity-domain-you-want-the-auditor-to-only-be-able-to-view-but-not-modify-the-resources-in-that-project-what-should-you-do) |
| 112 | [You have a workload running on Compute Engine that is critical to your business. You want to ensure that the data on the boot disk of this workload is backed up regularly. You need to be able to restore a backup as quickly as possible in case of disaster. You also want older backups to be cleaned automatically to save on cost. You want to follow Google-recommended practices. What should you do?](#you-have-a-workload-running-on-compute-engine-that-is-critical-to-your-business-you-want-to-ensure-that-the-data-on-the-boot-disk-of-this-workload-is-backed-up-regularly-you-need-to-be-able-to-restore-a-backup-as-quickly-as-possible-in-case-of-disaster-you-also-want-older-backups-to-be-cleaned-automatically-to-save-on-cost-you-want-to-follow-google-recommended-practices-what-should-you-do) |
| 113 | [You need to assign a Cloud Identity and Access Management (Cloud IAM) role to an external auditor. The auditor needs to have permissions to review your Google Cloud Platform (GCP) Audit Logs and also to review your Data Access logs. What should you do?](#you-need-to-assign-a-cloud-identity-and-access-management-cloud-iam-role-to-an-external-auditor-the-auditor-needs-to-have-permissions-to-review-your-google-cloud-platform-gcp-audit-logs-and-also-to-review-your-data-access-logs-what-should-you-do) |
| 114 | [You are managing several Google Cloud Platform (GCP) projects and need access to all logs for the past 60 days. You want to be able to explore and quickly analyze the log contents. You want to follow Google-recommended practices to obtain the combined logs for all projects. What should you do?](#you-are-managing-several-google-cloud-platform-gcp-projects-and-need-access-to-all-logs-for-the-past-60-days-you-want-to-be-able-to-explore-and-quickly-analyze-the-log-contents-you-want-to-follow-google-recommended-practices-to-obtain-the-combined-logs-for-all-projects-what-should-you-do) |
| 115 | [You need to reduce GCP service costs for a division of your company using the fewest possible steps. You need to turn off all configured services in an existing GCP project. What should you do?](#you-need-to-reduce-gcp-service-costs-for-a-division-of-your-company-using-the-fewest-possible-steps-you-need-to-turn-off-all-configured-services-in-an-existing-gcp-project-what-should-you-do) |
| 116 | [You are configuring service accounts for an application that spans multiple projects. Virtual Machines (VMs) running in the web-applications project need access to BigQuery datasets in crm-databases-proj. You want to follow Google-recommended practices to give access to the service account in the web-applications project. What should you do?](#you-are-configuring-service-accounts-for-an-application-that-spans-multiple-projects-virtual-machines-vms-running-in-the-web-applications-project-need-access-to-bigquery-datasets-in-crm-databases-proj-you-want-to-follow-google-recommended-practices-to-give-access-to-the-service-account-in-the-web-applications-project-what-should-you-do) |
| 117 | [An employee was terminated, but their access to Google Cloud Platform (GCP) was not removed until 2 weeks later. You need to find out this employee accessed any sensitive customer information after their termination. What should you do?](#an-employee-was-terminated-but-their-access-to-google-cloud-platform-gcp-was-not-removed-until-2-weeks-later-you-need-to-find-out-this-employee-accessed-any-sensitive-customer-information-after-their-termination-what-should-you-do) |
| 118 | [You need to create a custom IAM role for use with a GCP service. All permissions in the role must be suitable for production use. You also want to clearly share with your organization the status of the custom role. This will be the first version of the custom role. What should you do?](#you-need-to-create-a-custom-iam-role-for-use-with-a-gcp-service-all-permissions-in-the-role-must-be-suitable-for-production-use-you-also-want-to-clearly-share-with-your-organization-the-status-of-the-custom-role-this-will-be-the-first-version-of-the-custom-role-what-should-you-do) |
| 119 | [Your company has a large quantity of unstructured data in different file formats. You want to perform ETL transformations on the data. You need to make the data accessible on Google Cloud so it can be processed by a Dataflow job. What should you do?](#your-company-has-a-large-quantity-of-unstructured-data-in-different-file-formats-you-want-to-perform-etl-transformations-on-the-data-you-need-to-make-the-data-accessible-on-google-cloud-so-it-can-be-processed-by-a-dataflow-job-what-should-you-do) |
| 120 | [You need to manage multiple Google Cloud projects in the fewest steps possible. You want to configure the Google Cloud SDK command line interface (CLI) so that you can easily manage multiple projects. What should you do?](#you-need-to-manage-multiple-google-cloud-projects-in-the-fewest-steps-possible-you-want-to-configure-the-google-cloud-sdk-command-line-interface-cli-so-that-you-can-easily-manage-multiple-projects-what-should-you-do) |
| 121 | [Your Managed Instance Group raised an alert stating that new instance creation has failed to create new instances. You need to maintain the number of running instances specified by the template to be able to process expected application traffic. What should you do?](#your-managed-instance-group-raised-an-alert-stating-that-new-instance-creation-has-failed-to-create-new-instances-you-need-to-maintain-the-number-of-running-instances-specified-by-the-template-to-be-able-to-process-expected-application-traffic-what-should-you-do) |
| 122 | [Your company is moving from an on-premises environment to Google Cloud. You have multiple development teams that use Cassandra environments as backend databases. They all need a development environment that is isolated from other Cassandra instances. You want to move to Google Cloud quickly and with minimal support effort. What should you do?](#your-company-is-moving-from-an-on-premises-environment-to-google-cloud-you-have-multiple-development-teams-that-use-cassandra-environments-as-backend-databases-they-all-need-a-development-environment-that-is-isolated-from-other-cassandra-instances-you-want-to-move-to-google-cloud-quickly-and-with-minimal-support-effort-what-should-you-do) |
| 123 | [You have a Compute Engine instance hosting a production application. You want to receive an email if the instance consumes more than 90% of its CPU resources for more than 15 minutes. You want to use Google services. What should you do?](#you-have-a-compute-engine-instance-hosting-a-production-application-you-want-to-receive-an-email-if-the-instance-consumes-more-than-90-of-its-cpu-resources-for-more-than-15-minutes-you-want-to-use-google-services-what-should-you-do) |
| 124 | [You have an application that uses Cloud Spanner as a backend database. The application has a very predictable traffic pattern. You want to automatically scale up or down the number of Spanner nodes depending on traffic. What should you do?](#you-have-an-application-that-uses-cloud-spanner-as-a-backend-database-the-application-has-a-very-predictable-traffic-pattern-you-want-to-automatically-scale-up-or-down-the-number-of-spanner-nodes-depending-on-traffic-what-should-you-do) |
| 125 | [Your company publishes large files on an Apache web server that runs on a Compute Engine instance. The Apache web server is not the only application running in the project. You want to receive an email when the egress network costs for the server exceed 100 dollars for the current month as measured by Google Cloud. What should you do?](#your-company-publishes-large-files-on-an-apache-web-server-that-runs-on-a-compute-engine-instance-the-apache-web-server-is-not-the-only-application-running-in-the-project-you-want-to-receive-an-email-when-the-egress-network-costs-for-the-server-exceed-100-dollars-for-the-current-month-as-measured-by-google-cloud-what-should-you-do) |
| 126 | [You have designed a solution on Google Cloud that uses multiple Google Cloud products. Your company has asked you to estimate the costs of the solution. You need to provide estimates for the monthly total cost. What should you do?](#you-have-designed-a-solution-on-google-cloud-that-uses-multiple-google-cloud-products-your-company-has-asked-you-to-estimate-the-costs-of-the-solution-you-need-to-provide-estimates-for-the-monthly-total-cost-what-should-you-do) |
| 127 | [You have an application that receives SSL-encrypted TCP traffic on port 443. Clients for this application are located all over the world. You want to minimize latency for the clients. Which load balancing option should you use?](#you-have-an-application-that-receives-ssl-encrypted-tcp-traffic-on-port-443-clients-for-this-application-are-located-all-over-the-world-you-want-to-minimize-latency-for-the-clients-which-load-balancing-option-should-you-use) |
| 128 | [You have an application on a general-purpose Compute Engine instance that is experiencing excessive disk read throttling on its Zonal SSD Persistent Disk. The application primarily reads large files from disk. The disk size is currently 350 GB. You want to provide the maximum amount of throughput while minimizing costs. What should you do?](#you-have-an-application-on-a-general-purpose-compute-engine-instance-that-is-experiencing-excessive-disk-read-throttling-on-its-zonal-ssd-persistent-disk-the-application-primarily-reads-large-files-from-disk-the-disk-size-is-currently-350-gb-you-want-to-provide-the-maximum-amount-of-throughput-while-minimizing-costs-what-should-you-do) |
| 129 | [Your Dataproc cluster runs in a single Virtual Private Cloud (VPC) network in a single subnet with range 172.16.20.128/25. There are no private IP addresses available in the VPC network. You want to add new VMs to communicate with your cluster using the minimum number of steps. What should you do?](#your-dataproc-cluster-runs-in-a-single-virtual-private-cloud-vpc-network-in-a-single-subnet-with-range-172162012825-there-are-no-private-ip-addresses-available-in-the-vpc-network-you-want-to-add-new-vms-to-communicate-with-your-cluster-using-the-minimum-number-of-steps-what-should-you-do) |
| 130 | [You manage an App Engine Service that aggregates and visualizes data from BigQuery. The application is deployed with the default App Engine Service account. The data that needs to be visualized resides in a different project managed by another team. You do not have access to this project, but you want your application to be able to read data from the BigQuery dataset. What should you do?](#you-manage-an-app-engine-service-that-aggregates-and-visualizes-data-from-bigquery-the-application-is-deployed-with-the-default-app-engine-service-account-the-data-that-needs-to-be-visualized-resides-in-a-different-project-managed-by-another-team-you-do-not-have-access-to-this-project-but-you-want-your-application-to-be-able-to-read-data-from-the-bigquery-dataset-what-should-you-do) |
| 131 | [You need to create a copy of a custom Compute Engine Virtual Machine (VM) to facilitate an expected increase in application traffic due to a business acquisition. What should you do?](#you-need-to-create-a-copy-of-a-custom-compute-engine-virtual-machine-vm-to-facilitate-an-expected-increase-in-application-traffic-due-to-a-business-acquisition-what-should-you-do) |
| 132 | [You have deployed an application on a single Compute Engine instance. The application writes logs to disk. Users start reporting errors with the application. You want to diagnose the problem. What should you do?](#you-have-deployed-an-application-on-a-single-compute-engine-instance-the-application-writes-logs-to-disk-users-start-reporting-errors-with-the-application-you-want-to-diagnose-the-problem-what-should-you-do) |
| 133 | [An application generates daily reports in a Compute Engine Virtual Machine (VM). The VM is in the project corp-iot-insights. Your team operates only in the project corp-aggregate-reports and needs a copy of the daily exports in the bucket corp-aggregate-reports-storage. You want to configure access so that the daily reports from the VM are available in the bucket corp-aggregate-reports-storage and use as few steps as possible while following Google-recommended practices. What should you do?](#an-application-generates-daily-reports-in-a-compute-engine-virtual-machine-vm-the-vm-is-in-the-project-corp-iot-insights-your-team-operates-only-in-the-project-corp-aggregate-reports-and-needs-a-copy-of-the-daily-exports-in-the-bucket-corp-aggregate-reports-storage-you-want-to-configure-access-so-that-the-daily-reports-from-the-vm-are-available-in-the-bucket-corp-aggregate-reports-storage-and-use-as-few-steps-as-possible-while-following-google-recommended-practices-what-should-you-do) |
| 134 | [You built an application on your development laptop that uses Google Cloud services. Your application uses Application Default Credentials for authentication and works fine on your development laptop. You want to migrate this application to a Compute Engine Virtual Machine (VM) and set up authentication using Google-recommended practices and minimal changes. What should you do?](#you-built-an-application-on-your-development-laptop-that-uses-google-cloud-services-your-application-uses-application-default-credentials-for-authentication-and-works-fine-on-your-development-laptop-you-want-to-migrate-this-application-to-a-compute-engine-virtual-machine-vm-and-set-up-authentication-using-google-recommended-practices-and-minimal-changes-what-should-you-do) |
| 135 | [You need to create a Compute Engine instance in a new project that doesn't exist yet. What should you do?](#you-need-to-create-a-compute-engine-instance-in-a-new-project-that-doesnt-exist-yet-what-should-you-do) |
| 136 | [Your company runs one batch process in an on-premises server that takes around 30 hours to complete. The task runs monthly, can be performed offline, and must be restarted if interrupted. You want to migrate this workload to the cloud while minimizing cost. What should you do?](#your-company-runs-one-batch-process-in-an-on-premises-server-that-takes-around-30-hours-to-complete-the-task-runs-monthly-can-be-performed-offline-and-must-be-restarted-if-interrupted-you-want-to-migrate-this-workload-to-the-cloud-while-minimizing-cost-what-should-you-do) |
| 137 | [You are developing a new application and are looking for a Jenkins installation to build and deploy your source code. You want to automate the installation as quickly and easily as possible. What should you do?](#you-are-developing-a-new-application-and-are-looking-for-a-jenkins-installation-to-build-and-deploy-your-source-code-you-want-to-automate-the-installation-as-quickly-and-easily-as-possible-what-should-you-do) |
| 138 | [You have downloaded and installed the gcloud command line interface (CLI) and have authenticated with your Google Account. Most of your Compute Engine instances in your project run in the europe-west1-d zone. You want to avoid having to specify this zone with each CLI command when managing these instances. What should you do?](#you-have-downloaded-and-installed-the-gcloud-command-line-interface-cli-and-have-authenticated-with-your-google-account-most-of-your-compute-engine-instances-in-your-project-run-in-the-europe-west1-d-zone-you-want-to-avoid-having-to-specify-this-zone-with-each-cli-command-when-managing-these-instances-what-should-you-do) |
| 139 | [The core business of your company is to rent out construction equipment at large scale. All the equipment that is being rented out has been equipped with multiple sensors that send event information every few seconds. These signals can vary from engine status, distance traveled, fuel level, and more. Customers are billed based on the consumption monitored by these sensors. You expect high throughput - up to thousands of events per hour per device - and need to retrieve consistent data based on the time of the event. Storing and retrieving individual signals should be atomic. What should you do?](#the-core-business-of-your-company-is-to-rent-out-construction-equipment-at-large-scale-all-the-equipment-that-is-being-rented-out-has-been-equipped-with-multiple-sensors-that-send-event-information-every-few-seconds-these-signals-can-vary-from-engine-status-distance-traveled-fuel-level-and-more-customers-are-billed-based-on-the-consumption-monitored-by-these-sensors-you-expect-high-throughput---up-to-thousands-of-events-per-hour-per-device---and-need-to-retrieve-consistent-data-based-on-the-time-of-the-event-storing-and-retrieving-individual-signals-should-be-atomic-what-should-you-do) |
| 140 | [You are asked to set up application performance monitoring on Google Cloud projects A, B, and C as a single pane of glass. You want to monitor CPU, memory, and disk. What should you do?](#you-are-asked-to-set-up-application-performance-monitoring-on-google-cloud-projects-a-b-and-c-as-a-single-pane-of-glass-you-want-to-monitor-cpu-memory-and-disk-what-should-you-do) |
| 141 | [You created several resources in multiple Google Cloud projects. All projects are linked to different billing accounts. To better estimate future charges, you want to have a single visual representation of all costs incurred. You want to include new cost data as soon as possible. What should you do?](#you-created-several-resources-in-multiple-google-cloud-projects-all-projects-are-linked-to-different-billing-accounts-to-better-estimate-future-charges-you-want-to-have-a-single-visual-representation-of-all-costs-incurred-you-want-to-include-new-cost-data-as-soon-as-possible-what-should-you-do) |
| 142 | [Your company has workloads running on Compute Engine and on-premises. The Google Cloud Virtual Private Cloud (VPC) is connected to your WAN over a Virtual Private Network (VPN). You need to deploy a new Compute Engine instance and ensure that no public Internet traffic can be routed to it. What should you do?](#your-company-has-workloads-running-on-compute-engine-and-on-premises-the-google-cloud-virtual-private-cloud-vpc-is-connected-to-your-wan-over-a-virtual-private-network-vpn-you-need-to-deploy-a-new-compute-engine-instance-and-ensure-that-no-public-internet-traffic-can-be-routed-to-it-what-should-you-do) |
| 143 | [Your team maintains the infrastructure for your organization. The current infrastructure requires changes. You need to share your proposed changes with the rest of the team. You want to follow Google's recommended best practices. What should you do?](#your-team-maintains-the-infrastructure-for-your-organization-the-current-infrastructure-requires-changes-you-need-to-share-your-proposed-changes-with-the-rest-of-the-team-you-want-to-follow-googles-recommended-best-practices-what-should-you-do) |
| 144 | [You have a Compute Engine instance hosting an application used between 9 AM and 6 PM on weekdays. You want to back up this instance daily for disaster recovery purposes. You want to keep the backups for 30 days. You want the Google-recommended solution with the least management overhead and the least number of services. What should you do?](#you-have-a-compute-engine-instance-hosting-an-application-used-between-9-am-and-6-pm-on-weekdays-you-want-to-back-up-this-instance-daily-for-disaster-recovery-purposes-you-want-to-keep-the-backups-for-30-days-you-want-the-google-recommended-solution-with-the-least-management-overhead-and-the-least-number-of-services-what-should-you-do) |
| 145 | [Your existing application running in Google Kubernetes Engine (GKE) consists of multiple pods running on four GKE n1-standard-2 nodes. You need to deploy additional pods requiring n2-highmem-16 nodes without any downtime. What should you do?](#your-existing-application-running-in-google-kubernetes-engine-gke-consists-of-multiple-pods-running-on-four-gke-n1-standard-2-nodes-you-need-to-deploy-additional-pods-requiring-n2-highmem-16-nodes-without-any-downtime-what-should-you-do) |
| 146 | [You have an application that uses Cloud Spanner as a database backend to keep current state information about users. Cloud Bigtable logs all events triggered by users. You export Cloud Spanner data to Cloud Storage during daily backups. One of your analysts asks you to join data from Cloud Spanner and Cloud Bigtable for specific users. You want to complete this ad hoc request as efficiently as possible. What should you do?](#you-have-an-application-that-uses-cloud-spanner-as-a-database-backend-to-keep-current-state-information-about-users-cloud-bigtable-logs-all-events-triggered-by-users-you-export-cloud-spanner-data-to-cloud-storage-during-daily-backups-one-of-your-analysts-asks-you-to-join-data-from-cloud-spanner-and-cloud-bigtable-for-specific-users-you-want-to-complete-this-ad-hoc-request-as-efficiently-as-possible-what-should-you-do) |
| 147 | [You are hosting an application from Compute Engine Virtual Machines (VMs) in us-central1-a. You want to adjust your design to support the failure of a single Compute Engine zone, eliminate downtime, and minimize cost. What should you do?](#you-are-hosting-an-application-from-compute-engine-virtual-machines-vms-in-us-central1-a-you-want-to-adjust-your-design-to-support-the-failure-of-a-single-compute-engine-zone-eliminate-downtime-and-minimize-cost-what-should-you-do) |
| 148 | [A colleague handed over a Google Cloud Platform project for you to maintain. As part of a security checkup, you want to review who has been granted the Project Owner role. What should you do?](#a-colleague-handed-over-a-google-cloud-platform-project-for-you-to-maintain-as-part-of-a-security-checkup-you-want-to-review-who-has-been-granted-the-project-owner-role-what-should-you-do) |
| 149 | [You are running multiple VPC-native Google Kubernetes Engine clusters in the same subnet. The IPs available for the nodes are exhausted, and you want to ensure that the clusters can grow in nodes when needed. What should you do?](#you-are-running-multiple-vpc-native-google-kubernetes-engine-clusters-in-the-same-subnet-the-ips-available-for-the-nodes-are-exhausted-and-you-want-to-ensure-that-the-clusters-can-grow-in-nodes-when-needed-what-should-you-do) |
| 150 | [You have a batch workload that runs every night and uses a large number of Virtual Machines (VMs). It is fault-tolerant and can tolerate some of the VMs being terminated. The current cost of VMs is too high. What should you do?](#you-have-a-batch-workload-that-runs-every-night-and-uses-a-large-number-of-virtual-machines-vms-it-is-fault-tolerant-and-can-tolerate-some-of-the-vms-being-terminated-the-current-cost-of-vms-is-too-high-what-should-you-do) |
| 151 | [You are working with a user to set up an application in a new VPC behind a firewall. The user is concerned about data egress. You want to configure the fewest open egress ports. What should you do?](#you-are-working-with-a-user-to-set-up-an-application-in-a-new-vpc-behind-a-firewall-the-user-is-concerned-about-data-egress-you-want-to-configure-the-fewest-open-egress-ports-what-should-you-do) |
| 152 | [Your company runs its Linux workloads on Compute Engine instances. Your company will be working with a new operations partner that does not use Google Accounts. You need to grant access to the instances to your operations partner so they can maintain the installed tooling. What should you do?](#your-company-runs-its-linux-workloads-on-compute-engine-instances-your-company-will-be-working-with-a-new-operations-partner-that-does-not-use-google-accounts-you-need-to-grant-access-to-the-instances-to-your-operations-partner-so-they-can-maintain-the-installed-tooling-what-should-you-do) |
| 153 | [You have created a code snippet that should be triggered whenever a new file is uploaded to a Cloud Storage bucket. You want to deploy this code snippet. What should you do?](#you-have-created-a-code-snippet-that-should-be-triggered-whenever-a-new-file-is-uploaded-to-a-cloud-storage-bucket-you-want-to-deploy-this-code-snippet-what-should-you-do) |
| 154 | [You have been asked to set up Object Lifecycle Management for objects stored in storage buckets. The objects are written once and accessed frequently for 30 days. After 30 days, the objects are not read again unless there is a special need. The objects should be kept for three years, and you need to minimize cost. What should you do?](#you-have-been-asked-to-set-up-object-lifecycle-management-for-objects-stored-in-storage-buckets-the-objects-are-written-once-and-accessed-frequently-for-30-days-after-30-days-the-objects-are-not-read-again-unless-there-is-a-special-need-the-objects-should-be-kept-for-three-years-and-you-need-to-minimize-cost-what-should-you-do) |
| 155 | [You are storing sensitive information in a Cloud Storage bucket. For legal reasons, you need to be able to record all requests that read any of the stored data. You want to make sure you comply with these requirements. What should you do?](#you-are-storing-sensitive-information-in-a-cloud-storage-bucket-for-legal-reasons-you-need-to-be-able-to-record-all-requests-that-read-any-of-the-stored-data-you-want-to-make-sure-you-comply-with-these-requirements-what-should-you-do) |
| 156 | [You are the team lead of a group of 10 developers. You provided each developer with an individual Google Cloud Project that they can use as their personal sandbox to experiment with different Google Cloud solutions. You want to be notified if any of the developers are spending above $500 per month on their sandbox environment. What should you do?](#you-are-the-team-lead-of-a-group-of-10-developers-you-provided-each-developer-with-an-individual-google-cloud-project-that-they-can-use-as-their-personal-sandbox-to-experiment-with-different-google-cloud-solutions-you-want-to-be-notified-if-any-of-the-developers-are-spending-above-500-per-month-on-their-sandbox-environment-what-should-you-do) |
| 157 | [You are deploying a production application on Compute Engine. You want to prevent anyone from accidentally destroying the instance by clicking the wrong button. What should you do?](#you-are-deploying-a-production-application-on-compute-engine-you-want-to-prevent-anyone-from-accidentally-destroying-the-instance-by-clicking-the-wrong-button-what-should-you-do) |
| 158 | [Your company uses a large number of Google Cloud services centralized in a single project. All teams have specific projects for testing and development. The DevOps team needs access to all of the production services in order to perform their job. You want to prevent Google Cloud product changes from broadening their permissions in the future. You want to follow Google-recommended practices. What should you do?](#your-company-uses-a-large-number-of-google-cloud-services-centralized-in-a-single-project-all-teams-have-specific-projects-for-testing-and-development-the-devops-team-needs-access-to-all-of-the-production-services-in-order-to-perform-their-job-you-want-to-prevent-google-cloud-product-changes-from-broadening-their-permissions-in-the-future-you-want-to-follow-google-recommended-practices-what-should-you-do) |
| 159 | [You are building an application that processes data files uploaded from thousands of suppliers. Your primary goals for the application are data security and the expiration of aged data. You need to design the application to: Restrict access so that suppliers can access only their own data. Give suppliers write access to data only for 30 minutes. Delete data that is over 45 days old. You have a very short development cycle, and you need to make sure that the application requires minimal maintenance. Which two strategies should you use? (Choose two.)](#you-are-building-an-application-that-processes-data-files-uploaded-from-thousands-of-suppliers-your-primary-goals-for-the-application-are-data-security-and-the-expiration-of-aged-data-you-need-to-design-the-application-to-restrict-access-so-that-suppliers-can-access-only-their-own-data-give-suppliers-write-access-to-data-only-for-30-minutes-delete-data-that-is-over-45-days-old-you-have-a-very-short-development-cycle-and-you-need-to-make-sure-that-the-application-requires-minimal-maintenance-which-two-strategies-should-you-use-choose-two) |
| 160 | [Your company wants to standardize the creation and management of multiple Google Cloud resources using Infrastructure as Code. You want to minimize the amount of repetitive code needed to manage the environment. What should you do?](#your-company-wants-to-standardize-the-creation-and-management-of-multiple-google-cloud-resources-using-infrastructure-as-code-you-want-to-minimize-the-amount-of-repetitive-code-needed-to-manage-the-environment-what-should-you-do) |
| 161 | [You are performing a monthly security check of your Google Cloud environment and want to know who has access to view data stored in your Google Cloud Project. What should you?](#you-are-performing-a-monthly-security-check-of-your-google-cloud-environment-and-want-to-know-who-has-access-to-view-data-stored-in-your-google-cloud-project-what-should-you) |
| 162 | [Your company has embraced a hybrid cloud strategy where some of the applications are deployed on Google Cloud. A Virtual Private Network (VPN) tunnel connects your Virtual Private Cloud (VPC) in Google Cloud with your company's on-premises network. Multiple applications in Google Cloud need to connect to an on-premises database server, and you want to avoid having to change the IP configuration in all of your applications when the IP of the database changes. What should you do?](#your-company-has-embraced-a-hybrid-cloud-strategy-where-some-of-the-applications-are-deployed-on-google-cloud-a-virtual-private-network-vpn-tunnel-connects-your-virtual-private-cloud-vpc-in-google-cloud-with-your-companys-on-premises-network-multiple-applications-in-google-cloud-need-to-connect-to-an-on-premises-database-server-and-you-want-to-avoid-having-to-change-the-ip-configuration-in-all-of-your-applications-when-the-ip-of-the-database-changes-what-should-you-do) |
| 163 | [You have developed a containerized web application that will serve internal colleagues during business hours. You want to ensure that no costs are incurred outside of the hours the application is used. You have just created a new Google Cloud project and want to deploy the application. What should you do?](#you-have-developed-a-containerized-web-application-that-will-serve-internal-colleagues-during-business-hours-you-want-to-ensure-that-no-costs-are-incurred-outside-of-the-hours-the-application-is-used-you-have-just-created-a-new-google-cloud-project-and-want-to-deploy-the-application-what-should-you-do) |
| 164 | [You have experimented with Google Cloud using your own credit card and expensed the costs to your company. Your company wants to streamline the billing process and charge the costs of your projects to their monthly invoice. What should you do?](#you-have-experimented-with-google-cloud-using-your-own-credit-card-and-expensed-the-costs-to-your-company-your-company-wants-to-streamline-the-billing-process-and-charge-the-costs-of-your-projects-to-their-monthly-invoice-what-should-you-do) |
| 165 | [You are running a data warehouse on BigQuery. A partner company is offering a recommendation engine based on the data in your data warehouse. The partner company is also running their application on Google Cloud. They manage the resources in their own project, but they need access to the BigQuery dataset in your project. You want to provide the partner company with access to the dataset. What should you do?](#you-are-running-a-data-warehouse-on-bigquery-a-partner-company-is-offering-a-recommendation-engine-based-on-the-data-in-your-data-warehouse-the-partner-company-is-also-running-their-application-on-google-cloud-they-manage-the-resources-in-their-own-project-but-they-need-access-to-the-bigquery-dataset-in-your-project-you-want-to-provide-the-partner-company-with-access-to-the-dataset-what-should-you-do) |
| 166 | [Your web application has been running successfully on Cloud Run for Anthos. You want to evaluate an updated version of the application with a specific percentage of your production users (canary deployment). What should you do?](#your-web-application-has-been-running-successfully-on-cloud-run-for-anthos-you-want-to-evaluate-an-updated-version-of-the-application-with-a-specific-percentage-of-your-production-users-canary-deployment-what-should-you-do) |
| 167 | [Your company developed a mobile game that is deployed on Google Cloud. Gamers are connecting to the game with their personal phones over the Internet. The game sends UDP packets to update the servers about the gamers' actions while they are playing in multiplayer mode. Your game backend can scale over multiple Virtual Machines (VMs), and you want to expose the VMs over a single IP address. What should you do?](#your-company-developed-a-mobile-game-that-is-deployed-on-google-cloud-gamers-are-connecting-to-the-game-with-their-personal-phones-over-the-internet-the-game-sends-udp-packets-to-update-the-servers-about-the-gamers-actions-while-they-are-playing-in-multiplayer-mode-your-game-backend-can-scale-over-multiple-virtual-machines-vms-and-you-want-to-expose-the-vms-over-a-single-ip-address-what-should-you-do) |
| 168 | [You are working for a hospital that stores its medical images in an on-premises data room. The hospital wants to use Cloud Storage for archival storage of these images. The hospital wants an automated process to upload any new medical images to Cloud Storage. You need to design and implement a solution. What should you do?](#you-are-working-for-a-hospital-that-stores-its-medical-images-in-an-on-premises-data-room-the-hospital-wants-to-use-cloud-storage-for-archival-storage-of-these-images-the-hospital-wants-an-automated-process-to-upload-any-new-medical-images-to-cloud-storage-you-need-to-design-and-implement-a-solution-what-should-you-do) |
| 169 | [Your auditor wants to view your organization's use of data in Google Cloud. The auditor is most interested in auditing who accessed data in Cloud Storage buckets. You need to help the auditor access the data they need. What should you do?](#your-auditor-wants-to-view-your-organizations-use-of-data-in-google-cloud-the-auditor-is-most-interested-in-auditing-who-accessed-data-in-cloud-storage-buckets-you-need-to-help-the-auditor-access-the-data-they-need-what-should-you-do) |
| 170 | [You received a JSON file that contained a private key of a Service Account in order to get access to several resources in a Google Cloud project. You downloaded and installed the Cloud SDK and want to use this private key for authentication and authorization when performing gcloud commands. What should you do?](#you-received-a-json-file-that-contained-a-private-key-of-a-service-account-in-order-to-get-access-to-several-resources-in-a-google-cloud-project-you-downloaded-and-installed-the-cloud-sdk-and-want-to-use-this-private-key-for-authentication-and-authorization-when-performing-gcloud-commands-what-should-you-do) |
| 171 | [You are working with a Cloud SQL MySQL database at your company. You need to retain a month-end copy of the database for three years for audit purposes. What should you do?](#you-are-working-with-a-cloud-sql-mysql-database-at-your-company-you-need-to-retain-a-month-end-copy-of-the-database-for-three-years-for-audit-purposes-what-should-you-do) |
| 172 | [You are monitoring an application and receive user feedback that a specific error is spiking. You notice that the error is caused by a Service Account having insufficient permissions. You are able to solve the problem but want to be notified if the problem recurs. What should you do?](#you-are-monitoring-an-application-and-receive-user-feedback-that-a-specific-error-is-spiking-you-notice-that-the-error-is-caused-by-a-service-account-having-insufficient-permissions-you-are-able-to-solve-the-problem-but-want-to-be-notified-if-the-problem-recurs-what-should-you-do) |
| 173 | [You are developing a financial trading application that will be used globally. Data is stored and queried using a relational structure, and clients from all over the world should get the exact identical state of the data. The application will be deployed in multiple regions to provide the lowest latency to end users. You need to select a storage option for the application data while minimizing latency. What should you do?](#you-are-developing-a-financial-trading-application-that-will-be-used-globally-data-is-stored-and-queried-using-a-relational-structure-and-clients-from-all-over-the-world-should-get-the-exact-identical-state-of-the-data-the-application-will-be-deployed-in-multiple-regions-to-provide-the-lowest-latency-to-end-users-you-need-to-select-a-storage-option-for-the-application-data-while-minimizing-latency-what-should-you-do) |
| 174 | [You are about to deploy a new Enterprise Resource Planning (ERP) system on Google Cloud. The application holds the full database in-memory for fast data access, and you need to configure the most appropriate resources on Google Cloud for this application. What should you do?](#you-are-about-to-deploy-a-new-enterprise-resource-planning-erp-system-on-google-cloud-the-application-holds-the-full-database-in-memory-for-fast-data-access-and-you-need-to-configure-the-most-appropriate-resources-on-google-cloud-for-this-application-what-should-you-do) |
| 175 | [You have developed an application that consists of multiple microservices, with each microservice packaged in its own Docker container image. You want to deploy the entire application on Google Kubernetes Engine so that each microservice can be scaled individually. What should you do?](#you-have-developed-an-application-that-consists-of-multiple-microservices-with-each-microservice-packaged-in-its-own-docker-container-image-you-want-to-deploy-the-entire-application-on-google-kubernetes-engine-so-that-each-microservice-can-be-scaled-individually-what-should-you-do) |
| 176 | [You will have several applications running on different Compute Engine instances in the same project. You want to specify at a more granular level the service account each instance uses when calling Google Cloud APIs. What should you do?](#you-will-have-several-applications-running-on-different-compute-engine-instances-in-the-same-project-you-want-to-specify-at-a-more-granular-level-the-service-account-each-instance-uses-when-calling-google-cloud-apis-what-should-you-do) |
| 177 | [You are creating an application that will run on Google Kubernetes Engine. You have identified MongoDB as the most suitable database system for your application and want to deploy a managed MongoDB environment that provides a support SLA. What should you do?](#you-are-creating-an-application-that-will-run-on-google-kubernetes-engine-you-have-identified-mongodb-as-the-most-suitable-database-system-for-your-application-and-want-to-deploy-a-managed-mongodb-environment-that-provides-a-support-sla-what-should-you-do) |
| 178 | [You are managing a project for the Business Intelligence (BI) department in your company. A data pipeline ingests data into BigQuery via streaming. You want the users in the BI department to be able to run the custom SQL queries against the latest data in BigQuery. What should you do?](#you-are-managing-a-project-for-the-business-intelligence-bi-department-in-your-company-a-data-pipeline-ingests-data-into-bigquery-via-streaming-you-want-the-users-in-the-bi-department-to-be-able-to-run-the-custom-sql-queries-against-the-latest-data-in-bigquery-what-should-you-do) |
| 179 | [Your company is moving its entire workload to Compute Engine. Some servers should be accessible through the Internet, and other servers should only be accessible over the internal network. All servers need to be able to talk to each other over specific ports and protocols. The current on-premises network relies on a demilitarized zone (DMZ) for the public servers and a Local Area Network (LAN) for the private servers. You need to design the networking infrastructure on Google Cloud to match these requirements. What should you do?](#your-company-is-moving-its-entire-workload-to-compute-engine-some-servers-should-be-accessible-through-the-internet-and-other-servers-should-only-be-accessible-over-the-internal-network-all-servers-need-to-be-able-to-talk-to-each-other-over-specific-ports-and-protocols-the-current-on-premises-network-relies-on-a-demilitarized-zone-dmz-for-the-public-servers-and-a-local-area-network-lan-for-the-private-servers-you-need-to-design-the-networking-infrastructure-on-google-cloud-to-match-these-requirements-what-should-you-do) |

### You significantly changed a complex Deployment Manager template and want to confirm that the dependencies of all defined resources are properly met before committing it to the project. You want the most rapid feedback on your changes. What should you do?

- [ ] Use granular logging statements within a Deployment Manager template authored in Python.
- [ ] Monitor activity of the Deployment Manager execution on the Stackdriver Logging page of the GCP Console.
- [ ] Execute the Deployment Manager template against a separate project with the same configuration, and monitor for failures.
- [x] Execute the Deployment Manager template using the C-preview option in the same project, and observe the state of interdependent resources.

The correct answer is:

4. **Execute the Deployment Manager template using the `--preview` option in the same project, and observe the state of interdependent resources**.

### Explanation of why other options are less optimal:

1. **Use granular logging statements within a Deployment Manager template authored in Python**:
   - **Reason for being less optimal**: Granular logging can help understand the flow and catch specific errors, but it does not provide a high-level overview of the entire deployment's state or the dependencies between resources. It also requires going through potentially large amounts of log data, which is not the quickest method for confirming dependencies.

2. **Monitor activity of the Deployment Manager execution on the Stackdriver Logging page of the GCP Console**:
   - **Reason for being less optimal**: This method helps monitor deployments in real-time but only after the deployment has started. It doesn't provide a pre-deployment check to ensure that all dependencies are properly configured, meaning issues are only detected during or after the deployment process, not before.

3. **Execute the Deployment Manager template against a separate project with the same configuration, and monitor for failures**:
   - **Reason for being less optimal**: While testing in a separate project can help identify issues, it involves setting up and maintaining a duplicate project environment, which is time-consuming and complex. This approach also delays feedback compared to using the `--preview` option, which provides immediate insights within the same project environment without actual changes.

4. **Execute the Deployment Manager template using the `--preview` option in the same project, and observe the state of interdependent resources**:
   - **Reason for being optimal**: The `--preview` option is specifically designed to provide a dry-run of the deployment, showing what changes would be made and how resources would be affected without actually applying those changes. This allows for rapid feedback on the overall deployment plan and ensures that all resource dependencies are correctly defined and met before any actual deployment occurs.

In summary, the `--preview` option gives the fastest and most effective way to confirm resource dependencies and deployment outcomes without making any real changes to the project, making it the best choice for this scenario.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### Your company has a 3-tier solution running on Compute Engine. The configuration of the current infrastructure is shown below. Each tier has a service account that is associated with all instances within it. You need to enable communication on TCP port 8080 between tiers as follows: Instances in tier #1 must communicate with tier #2. Instances in tier #2 must communicate with tier #3. What should you do?

![3-tier solution running on Compute Engine](images/tier3.png)

- [ ] 1. Create an ingress firewall rule with the following settings: Targets: all instances. Source filter: IP ranges (with the range set to 10.0.2.0/24). Protocols: allow all. 2. Create an ingress firewall rule with the following settings: Targets: all instances. Source filter: IP ranges (with the range set to 10.0.1.0/24). Protocols: allow all.
- [x] 1. Create an ingress firewall rule with the following settings: Targets: all instances with tier #2 service account. Source filter: all instances with tier #1 service account. Protocols: allow TCP: 8080. 2. Create an ingress firewall rule with the following settings: Targets: all instances with tier #3 service account. Source filter: all instances with tier #2 service account. Protocols: allow TCP: 8080.
- [ ] 1. Create an ingress firewall rule with the following settings: Targets: all instances with tier #2 service account. Source filter: all instances with tier #1 service account. Protocols: allow all. 2. Create an ingress firewall rule with the following settings: Targets: all instances with tier #3 service account. Source filter: all instances with tier #2 service account. Protocols: allow all.
- [ ] 1. Create an egress firewall rule with the following settings: Targets: all instances. Source filter: IP ranges (with the range set to 10.0.2.0/24). Protocols: allow TCP: 8080. 2. Create an egress firewall rule with the following settings: Targets: all instances. Source filter: IP ranges (with the range set to 10.0.1.0/24). Protocols: allow TCP: 8080.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You are analyzing Google Cloud Platform service costs from three separate projects. You want to use this information to create service cost estimates by service type, daily and monthly, for the next six months using standard query syntax. What should you do?

- [ ] Export your bill to a Cloud Storage bucket, and then import into Cloud Bigtable for analysis.
- [ ] Export your bill to a Cloud Storage bucket, and then import into Google Sheets for analysis.
- [ ] Export your transactions to a local file, and perform analysis with a desktop tool.
- [x] Export your bill to a BigQuery dataset, and then write time window-based SQL queries for analysis.

The correct answer is:

4. **Export your bill to a BigQuery dataset, and then write time window-based SQL queries for analysis**.

### Explanation of why other options are less optimal:

1. **Export your bill to a Cloud Storage bucket, and then import into Cloud Bigtable for analysis**:
   - **Reason for being less optimal**: Cloud Bigtable is a NoSQL database that is designed for low-latency reads and writes. It is not optimized for the kind of analytical queries required for this task, such as aggregations and time window-based analysis. BigQuery, on the other hand, is specifically designed for such analytical queries and can handle large datasets efficiently.

2. **Export your bill to a Cloud Storage bucket, and then import into Google Sheets for analysis**:
   - **Reason for being less optimal**: Google Sheets is a spreadsheet tool and is not well-suited for handling large datasets or performing complex, time window-based SQL queries. While it is useful for basic analysis and small datasets, it lacks the scalability and performance needed for detailed cost analysis over multiple projects and long time periods.

3. **Export your transactions to a local file, and perform analysis with a desktop tool**:
   - **Reason for being less optimal**: Desktop tools may not handle large datasets efficiently and can be cumbersome for performing complex queries across multiple projects. Additionally, this approach lacks the scalability and automation capabilities provided by cloud-based solutions like BigQuery.

4. **Export your bill to a BigQuery dataset, and then write time window-based SQL queries for analysis**:
   - **Reason for being optimal**: BigQuery is a highly scalable, fully-managed data warehouse designed for large-scale data analysis. It supports complex SQL queries, including time window-based analysis, and can efficiently handle large datasets from multiple projects. Exporting billing data to BigQuery allows you to leverage its powerful querying capabilities to create detailed service cost estimates by service type, daily and monthly, for the next six months.

By using BigQuery, you can perform sophisticated analysis with high performance and scalability, making it the best choice for this task.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You want to send and consume Cloud Pub/Sub messages from your App Engine application. The Cloud Pub/Sub API is currently disabled. You will use a service account to authenticate your application to the API. You want to make sure your application can use Cloud Pub/Sub. What should you do?

- [x] Enable the Cloud Pub/Sub API in the API Library on the GCP Console.
- [ ] Rely on the automatic enablement of the Cloud Pub/Sub API when the Service Account accesses it.
- [ ] Use Deployment Manager to deploy your application. Rely on the automatic enablement of all APIs used by the application being deployed.
- [ ] Grant the App Engine Default service account the role of Cloud Pub/Sub Admin. Have your application enable the API on the first connection to Cloud Pub/Sub.

The correct answer is:

1. **Enable the Cloud Pub/Sub API in the API Library on the GCP Console**.

### Explanation of why other options are wrong:

2. **Rely on the automatic enablement of the Cloud Pub/Sub API when the Service Account accesses it**:
   - **Reason for being wrong**: APIs are not automatically enabled when a service account accesses them. Service accounts authenticate requests, but they do not enable APIs. You must manually enable the Cloud Pub/Sub API in the API Library.

3. **Use Deployment Manager to deploy your application. Rely on the automatic enablement of all APIs used by the application being deployed**:
   - **Reason for being wrong**: Deployment Manager can deploy resources and set up configurations, but it does not automatically enable APIs that are required by your application. You need to explicitly enable the Cloud Pub/Sub API regardless of how you deploy your application.

4. **Grant the App Engine Default service account the role of Cloud Pub/Sub Admin. Have your application enable the API on the first connection to Cloud Pub/Sub**:
   - **Reason for being wrong**: Granting the Cloud Pub/Sub Admin role to the service account is excessive privilege for enabling an API. Additionally, there is no mechanism for an application to dynamically enable an API upon its first connection. Enabling APIs is a manual administrative task that needs to be performed through the GCP Console or API.

### Why Option 1 is correct:

- **Enable the Cloud Pub/Sub API in the API Library on the GCP Console**: This is the correct action because enabling APIs must be done manually through the GCP Console or programmatically via API calls. Once the Cloud Pub/Sub API is enabled, your App Engine application, using the appropriate service account with the necessary IAM roles (such as Pub/Sub Publisher or Subscriber), can send and consume messages from Cloud Pub/Sub without issues.

  
--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You have a website hosted on App Engine standard environment. You want 1% of your users to see a new test version of the website. You want to minimize complexity.

- [ ] Deploy the new version in the same application and use the –-migrate option.
- [x] Deploy the new version in the same application and use the –-splits option to give a weight of 99 to the current version and a weight of 1 to the new version.
- [ ] Create a new App Engine application in the same project. Deploy the new version in that application. Use the App Engine library to proxy 1% of the requests to the new version.
- [ ] Create a new App Engine application in the same project. Deploy the new version in that application. Configure your network load balancer to send 1% of the traffic to that new application.

The correct answer is:

2. **Deploy the new version in the same application and use the `--split` option to give a weight of 99 to the current version and a weight of 1 to the new version**.

### Explanation of why other options are wrong:

1. **Deploy the new version in the same application and use the `--migrate` option**:
   - **Reason for being wrong**: The `--migrate` option in App Engine is used for performing traffic splitting during deployment, but it does not allow you to specify a precise percentage split. It typically migrates 100% of traffic to the new version, which is not suitable for directing only 1% of traffic to a test version.

3. **Create a new App Engine application in the same project. Deploy the new version in that application. Use the App Engine library to proxy 1% of the requests to the new version**:
   - **Reason for being wrong**: Creating a new App Engine application introduces unnecessary complexity. Proxying requests from one App Engine application to another using the App Engine library is not a standard approach for traffic splitting within the same application. It adds overhead and maintenance complexity without providing significant benefits compared to using built-in traffic splitting features.

4. **Create a new App Engine application in the same project. Deploy the new version in that application. Configure your network load balancer to send 1% of the traffic to that new application**:
   - **Reason for being wrong**: Configuring a network load balancer to split traffic between different App Engine applications in the same project is not a standard or recommended approach. App Engine provides built-in traffic splitting functionality (`--split` option) that is designed specifically for this purpose and integrates seamlessly with the platform's deployment capabilities.

### Why Option 2 is correct:

- **Deploy the new version in the same application and use the `--split` option to give a weight of 99 to the current version and a weight of 1 to the new version**: This option leverages App Engine's native traffic splitting feature (`--split` option during deployment). By specifying a 99:1 split, you ensure that only 1% of incoming traffic is routed to the new version, allowing you to test it without affecting the majority of users. This approach minimizes complexity by keeping both versions within the same App Engine application and using standard platform features for traffic management.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### Your organization is a financial company that needs to store audit log files for 3 years. Your organization has hundreds of Google Cloud projects. You need to implement a cost-effective approach for log file retention.

- [ ] Create an export to the sink that saves logs from Cloud Audit to BigQuery.
- [x] Create an export to the sink that saves logs from Cloud Audit to a Coldline Storage bucket.
- [ ] Write a custom script that uses logging API to copy the logs from Stackdriver logs to BigQuery.
- [ ] Export these logs to Cloud Pub/Sub and write a Cloud Dataflow pipeline to store logs to Cloud SQL.

The correct answer is:

2. **Create an export to the sink that saves logs from Cloud Audit to a Coldline Storage bucket**.

### Explanation of why other options are wrong:

1. **Create an export to the sink that saves logs from Cloud Audit to BigQuery**:
   - **Reason for being wrong**: While exporting logs to BigQuery allows for powerful querying and analysis capabilities, it is not the most cost-effective option for long-term storage of audit logs. BigQuery storage costs can be higher compared to storing data in Coldline Storage, especially when considering the retention period of 3 years.

3. **Write a custom script that uses logging API to copy the logs from Stackdriver logs to BigQuery**:
   - **Reason for being wrong**: Manually copying logs using a custom script adds complexity and maintenance overhead. It also doesn't address the cost-effectiveness of storage over a 3-year period, as storing logs directly in BigQuery for such a long retention period can be expensive.

4. **Export these logs to Cloud Pub/Sub and write a Cloud Dataflow pipeline to store logs to Cloud SQL**:
   - **Reason for being wrong**: Cloud Pub/Sub and Cloud Dataflow are not optimal for long-term storage of audit logs due to the need for continuous processing and transformation of data. Storing logs in Cloud SQL is also not suitable for large-scale log storage over a 3-year period due to scalability and cost considerations.

### Why Option 2 is correct:

- **Create an export to the sink that saves logs from Cloud Audit to a Coldline Storage bucket**: Coldline Storage (now called Archive Storage) is designed for long-term, infrequently accessed data storage at a lower cost compared to active storage options like BigQuery or standard Cloud Storage. Storing audit logs in Coldline Storage ensures cost-effectiveness while meeting the requirement of retaining logs for 3 years. This option is straightforward to implement and manages the storage costs efficiently over the retention period.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You built an application on Google Cloud that uses Cloud Spanner. Your support team needs to monitor the environment but should not have access to table data. You need a streamlined solution to grant the correct permissions to your support team, and you want to follow Google-recommended practices. What should you do?

- [x] Add the support team group to the roles/monitoring.viewer role.
- [ ] Add the support team group to the roles/spanner.databaseUser role.
- [ ] Add the support team group to the roles/spanner.databaseReader role.
- [ ] Add the support team group to the roles/stackdriver.accounts.viewer role.

The correct answer is:

3. **Add the support team group to the roles/spanner.databaseReader role**.

### Explanation of why other options are wrong:

1. **Add the support team group to the roles/monitoring.viewer role**:
   - **Reason for being wrong**: The `roles/monitoring.viewer` role provides permissions to view monitoring data (metrics, dashboards) in Stackdriver Monitoring. It does not provide access to Cloud Spanner resources or data. This role is not suitable for granting access to monitor Cloud Spanner environments.

2. **Add the support team group to the roles/spanner.databaseUser role**:
   - **Reason for being wrong**: The `roles/spanner.databaseUser` role grants permissions to read and write data in Cloud Spanner databases. While this role allows for interaction with the database (querying data), it does not align with the requirement to monitor the environment without access to table data. It provides more permissions than necessary for monitoring purposes.

4. **Add the support team group to the roles/stackdriver.accounts.viewer role**:
   - **Reason for being wrong**: The `roles/stackdriver.accounts.viewer` role provides permissions to view Stackdriver accounts and their configurations. It does not grant access to Cloud Spanner resources or data. This role is focused on Stackdriver monitoring and does not address the specific requirement to monitor Cloud Spanner without accessing table data.

### Why Option 3 is correct:

- **Add the support team group to the roles/spanner.databaseReader role**: The `roles/spanner.databaseReader` role is designed to provide read-only access to Cloud Spanner databases. Users with this role can view database schemas, read metadata, and monitor the health and performance of Cloud Spanner databases without accessing table data. This aligns perfectly with the requirement to monitor the environment while maintaining data confidentiality. It follows Google-recommended practices by granting the least privilege necessary for the support team to perform their monitoring tasks effectively without exposing sensitive data.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You want to run a single caching HTTP reverse proxy on GCP for a latency-sensitive website. This specific reverse proxy consumes almost no CPU. You want to have a 30-GB in-memory cache, and need an additional 2 GB of memory for the rest of the processes. You want to minimize cost. How should you run this reverse proxy?  -----------------Issue

- [x] Create a Cloud Memorystore for Redis instance with 32-GB capacity.
- [ ] Run it on Compute Engine, and choose a custom instance type with 6 vCPUs and 32 GB of memory.
- [ ] Package it in a container image, and run it on Kubernetes Engine, using n1-standard-32 instances as nodes.
- [ ] Run it on Compute Engine, choose the instance type n1-standard-1, and add an SSD persistent disk of 32 GB.

The correct answer is:

1. **Create a Cloud Memorystore for Redis instance with 32-GB capacity**.

### Explanation of why other options are wrong:

2. **Run it on Compute Engine, and choose a custom instance type with 6 vCPUs and 32 GB of memory**:
   - **Reason for being wrong**: This option provides more resources (6 vCPUs) than necessary for a caching HTTP reverse proxy that consumes almost no CPU. It also does not guarantee the same level of in-memory caching performance and reliability as a managed Redis service like Cloud Memorystore.

3. **Package it in a container image, and run it on Kubernetes Engine, using n1-standard-32 instances as nodes**:
   - **Reason for being wrong**: Using Kubernetes Engine with n1-standard-32 instances introduces unnecessary complexity and over-provisioning of resources. It's not cost-effective to use such large nodes for a low-CPU usage caching proxy, especially when considering Kubernetes orchestration overhead.

4. **Run it on Compute Engine, choose the instance type n1-standard-1, and add an SSD persistent disk of 32 GB**:
   - **Reason for being wrong**: While n1-standard-1 instances are smaller and cheaper, adding an SSD persistent disk for caching still requires management overhead for caching mechanisms and data persistence. It's not as straightforward or cost-effective as using a managed caching solution like Cloud Memorystore.

### Why Option 1 is correct:

- **Create a Cloud Memorystore for Redis instance with 32-GB capacity**: Cloud Memorystore for Redis is a fully managed Redis service on Google Cloud Platform. It provides a scalable and reliable in-memory caching solution with low latency access to data. By choosing a 32-GB instance, you can allocate 30 GB for the in-memory cache and have 2 GB for other processes, exactly meeting your requirements. This option minimizes management overhead, ensures optimal performance for caching, and is cost-effective compared to managing your own caching solution on Compute Engine or Kubernetes.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You have a single binary application that you want to run on Google Cloud Platform. You decided to automatically scale the application based on underlying infrastructure CPU usage. Your organizational policies require you to use Virtual Machines directly. You need to ensure that the application scaling is operationally efficient and completed as quickly as possible. What should you do?

- [ ] Create a Google Kubernetes Engine cluster, and use horizontal pod autoscaling to scale the application.
- [x] Create an instance template, and use the template in a Managed Instance Group with autoscaling configured.
- [ ] Create an instance template, and use the template in a Managed Instance Group that scales up and down based on the time of day.
- [ ] Use a set of third-party tools to build automation around scaling the application up and down, based on Stackdriver CPU usage monitoring.

The correct answer is:

2. **Create an instance template, and use the template in a Managed Instance Group with autoscaling configured**.

### Explanation of why other options are wrong:

1. **Create a Google Kubernetes Engine cluster, and use horizontal pod autoscaling to scale the application**:
   - **Reason for being wrong**: While Kubernetes Engine provides horizontal pod autoscaling, it is not aligned with the requirement to use Virtual Machines directly, as Kubernetes abstracts the underlying VMs. This option would introduce unnecessary complexity and doesn't adhere to the organizational policy of using VMs directly.

3. **Create an instance template, and use the template in a Managed Instance Group that scales up and down based on the time of day**:
   - **Reason for being wrong**: Scaling based on time of day is useful for predictable workload patterns but does not dynamically scale based on underlying infrastructure CPU usage, as required. This option may not efficiently utilize resources during unexpected workload spikes or changes in CPU usage.

4. **Use a set of third-party tools to build automation around scaling the application up and down, based on Stackdriver CPU usage monitoring**:
   - **Reason for being wrong**: While third-party tools can provide customization, they often require additional setup, management, and potential integration challenges. Using built-in GCP services like Managed Instance Groups with autoscaling is generally more operationally efficient and aligns better with managing resources directly on Google Cloud Platform.

### Why Option 2 is correct:

- **Create an instance template, and use the template in a Managed Instance Group with autoscaling configured**: This option leverages Managed Instance Groups (MIGs) which allow you to create a group of identical VM instances from a common instance template. Autoscaling configured on the MIGs ensures that the number of VM instances automatically scales based on CPU usage, which aligns with the requirement to scale based on underlying infrastructure CPU usage. It's operationally efficient because GCP manages the scaling process based on predefined policies, ensuring the application can quickly respond to changes in workload demand while adhering to organizational policies of using VMs directly.
  
--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You need to set up permissions for a set of Compute Engine instances to enable them to write data into a particular Cloud Storage bucket. You want to follow Google-recommended practices. What should you do?

- [ ] Create a service account with an access scope. Use the access scope 'https://www.googleapis.com/auth/devstorage.write_only'.
- [ ] Create a service account with an access scope. Use the access scope 'https://www.googleapis.com/auth/cloud-platform'.
- [x] Create a service account and add it to the IAM role 'storage.objectCreator' for that bucket.
- [ ] Create a service account and add it to the IAM role 'storage.objectAdmin' for that bucket.

The correct answer is:

4. **Create a service account and add it to the IAM role 'storage.objectAdmin' for that bucket**.

### Explanation of why other options are wrong:

1. **Create a service account with an access scope. Use the access scope 'https://www.googleapis.com/auth/devstorage.write_only'**:
   - **Reason for being wrong**: Access scopes are not used for defining permissions to specific resources like Cloud Storage buckets. Access scopes control what API actions are allowed when an instance uses the default service account. However, they do not grant fine-grained access to specific buckets or objects within Cloud Storage.

2. **Create a service account with an access scope. Use the access scope 'https://www.googleapis.com/auth/cloud-platform'**:
   - **Reason for being wrong**: The `cloud-platform` scope is broad and grants access to all Google Cloud services. While this would technically allow the instance to interact with Cloud Storage, it provides much broader permissions than necessary and does not follow the principle of least privilege, which is a Google-recommended practice.

3. **Create a service account and add it to the IAM role 'storage.objectCreator' for that bucket**:
   - **Reason for being wrong**: The `storage.objectCreator` role grants permission to create objects (write) in the specified bucket, but it does not provide broader access such as listing objects or modifying existing objects. Since the question specifies enabling instances to write data into the bucket, `storage.objectCreator` would allow creation of objects but does not cover other potential actions needed.

### Why Option 4 is correct:

- **Create a service account and add it to the IAM role 'storage.objectAdmin' for that bucket**: The `storage.objectAdmin` role provides full control over objects in the specified Cloud Storage bucket. This includes permissions to read, write, and manage objects within the bucket. By assigning the service account to this role, you ensure that the Compute Engine instances have all necessary permissions to write data into the bucket, adhering to Google-recommended practices by granting the least privilege necessary for the task.
  
--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You have an object in a Cloud Storage bucket that you want to share with an external company. The object contains sensitive data. You want access to the content to be removed after four hours. The external company does not have a Google account to which you can grant specific user-based access privileges. You want to use the most secure method that requires the fewest steps. What should you do?

- [x] Create a signed URL with a four-hour expiration and share the URL with the company.
- [ ] Set object access to 'public' and use object lifecycle management to remove the object after four hours.
- [ ] Configure the storage bucket as a static website and furnish the object's URL to the company. Delete the object from the storage bucket after four hours.
- [ ] Create a new Cloud Storage bucket specifically for the external company to access. Copy the object to that bucket. Delete the bucket after four hours have passed.

The correct answer is:

1. **Create a signed URL with a four-hour expiration and share the URL with the company**.

### Explanation of why other options are wrong:

2. **Set object access to 'public' and use object lifecycle management to remove the object after four hours**:
   - **Reason for being wrong**: Setting the object access to 'public' exposes the sensitive data to anyone with the object's URL, not just the intended external company. This approach violates the requirement to securely share the data and does not provide fine-grained access control. Object lifecycle management alone does not revoke public access after a specified time.

3. **Configure the storage bucket as a static website and furnish the object's URL to the company. Delete the object from the storage bucket after four hours**:
   - **Reason for being wrong**: Similar to option 2, configuring the bucket as a static website makes the object publicly accessible. Deleting the object after four hours does not prevent unauthorized access during the initial sharing period. This method does not ensure the secure sharing of sensitive data.

4. **Create a new Cloud Storage bucket specifically for the external company to access. Copy the object to that bucket. Delete the bucket after four hours have passed**:
   - **Reason for being wrong**: This option involves unnecessary steps and complexity. Creating a new bucket and copying the object introduces additional management overhead and does not guarantee secure sharing or automatic revocation of access after four hours. It's not the most straightforward or efficient method for temporary access to a single object.

### Why Option 1 is correct:

- **Create a signed URL with a four-hour expiration and share the URL with the company**: A signed URL is a secure method to grant time-limited access to individual objects in Cloud Storage without requiring the recipient to have a Google account. By creating a signed URL with a four-hour expiration, you ensure that the external company can access the object securely and only within the specified time frame. This method adheres to best practices for securely sharing sensitive data while minimizing administrative steps and ensuring access control.
  
--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You need to create an autoscaling Managed Instance Group for an HTTPS web application. You want to make sure that unhealthy VMs are recreated. What should you do?

- [x] Create a health check on port 443 and use that when creating the Managed Instance Group.
- [ ] Select Multi-Zone instead of Single-Zone when creating the Managed Instance Group.
- [ ] In the Instance Template, add the label 'health-check'.
- [ ] In the Instance Template, add a startup script that sends a heartbeat to the metadata server.

The correct answer is:

1. **Create a health check on port 443 and use that when creating the Managed Instance Group**.

### Explanation of why other options are wrong:

2. **Select Multi-Zone instead of Single-Zone when creating the Managed Instance Group**:
   - **Reason for being wrong**: Choosing Multi-Zone instead of Single-Zone affects the availability and distribution of instances across multiple zones, but it does not directly address the requirement to recreate unhealthy VMs. Multi-Zone configuration improves availability but does not ensure VM replacement or health monitoring directly.

3. **In the Instance Template, add the label 'health-check'**:
   - **Reason for being wrong**: Adding a label to the instance template does not configure health checks or provide mechanisms for monitoring instance health. Labels are metadata tags used for organizational purposes and do not influence autoscaling behavior or VM health monitoring directly.

4. **In the Instance Template, add a startup script that sends a heartbeat to the metadata server**:
   - **Reason for being wrong**: While a startup script could potentially be used to monitor instance health, it is not a recommended method for managing VM health checks and autoscaling. Google Cloud Platform provides dedicated health check mechanisms (such as HTTP/S health checks) that are specifically designed for monitoring the health of instances in Managed Instance Groups. Using custom scripts for health monitoring adds complexity and does not leverage built-in Google Cloud services effectively.

### Why Option 1 is correct:

- **Create a health check on port 443 and use that when creating the Managed Instance Group**: Google Cloud allows you to create HTTP or HTTPS health checks that periodically verify that instances are responding to requests correctly. When you associate such a health check with a Managed Instance Group, instances failing health checks are automatically detected as unhealthy. The Managed Instance Group then terminates unhealthy instances and creates new ones to maintain the desired number of healthy instances, ensuring the availability and reliability of the HTTPS web application. This approach is the recommended way to handle VM replacement for unhealthy instances in autoscaling Managed Instance Groups.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You are deploying an application to a Compute Engine VM in a Managed Instance Group. The application must be running at all times, but only a single instance of the VM should run per GCP project. How should you configure the instance group?

- [x] Set autoscaling to On, set the minimum number of instances to 1, and then set the maximum number of instances to 1.
- [ ] Set autoscaling to Off, set the minimum number of instances to 1, and then set the maximum number of instances to 1.
- [ ] Set autoscaling to On, set the minimum number of instances to 1, and then set the maximum number of instances to 2.
- [ ] Set autoscaling to Off, set the minimum number of instances to 1, and then set the maximum number of instances to 2.

**Option 1: Set autoscaling to On, set the minimum number of instances to 1, and then set the maximum number of instances to 1**
**Autoscaling Behavior:** Even though both the minimum and maximum instances are set to 1, having autoscaling enabled means that if the single instance in the Managed Instance Group fails (becomes unhealthy), Google Cloud Platform (GCP) will automatically detect this and replace the failed instance with a new one.

**Failure Recovery:** This configuration ensures that your application remains resilient to instance failures. The autoscaler continuously monitors the health of instances using health checks. If it detects that the instance has failed or is unhealthy based on the configured health checks, it terminates the failed instance and starts a new one to maintain the desired instance count.

**Operational Continuity:** By utilizing autoscaling in this way, you benefit from automated instance replacement without manual intervention. This helps in maintaining the application's availability and ensures that the instance group always runs the specified number of instances.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You have production and test workloads that you want to deploy on Compute Engine. Production VMs need to be in a different subnet than the test VMs. All the VMs must be able to reach each other over internal IP without creating additional routes. You need to set up VPC and the 2 subnets. Which configuration meets these requirements?

- [x] Create a single custom VPC with 2 subnets. Create each subnet in a different region and with a different CIDR range.
- [ ] Create a single custom VPC with 2 subnets. Create each subnet in the same region and with the same CIDR range.
- [ ] Create 2 custom VPCs, each with a single subnet. Create each subnet is a different region and with a different CIDR range.
- [ ] Create 2 custom VPCs, each with a single subnet. Create each subnet in the same region and with the same CIDR range.

The correct answer is:

1. **Create a single custom VPC with 2 subnets. Create each subnet in a different region and with a different CIDR range.**

### Explanation of why other options are wrong:

2. **Create a single custom VPC with 2 subnets. Create each subnet in the same region and with the same CIDR range**:
   - **Reason for being wrong**: Subnets within the same region must have unique CIDR ranges to avoid overlap. Having the same CIDR range for both subnets would result in an overlapping IP address space, which is not allowed within a single VPC.

3. **Create 2 custom VPCs, each with a single subnet. Create each subnet in a different region and with a different CIDR range**:
   - **Reason for being wrong**: This option unnecessarily creates two separate VPCs, which complicates network administration and does not meet the requirement of having all VMs (production and test) within the same network for internal communication. The requirement specifies using a single VPC.

4. **Create 2 custom VPCs, each with a single subnet. Create each subnet in the same region and with the same CIDR range**:
   - **Reason for being wrong**: Similar to option 2, having the same CIDR range for subnets in the same region would lead to overlapping IP address spaces, which is not allowed within a single VPC. This configuration does not satisfy the requirement of having distinct subnets for production and test workloads within the same VPC.

### Why Option 1 is correct:

- **Single VPC**: By creating a single custom VPC, you centralize network management and allow all VMs (both production and test) to communicate internally using internal IP addresses without additional routes.

- **Different Regions**: Placing each subnet in a different region ensures geographical separation, which might be necessary for disaster recovery or compliance reasons.

- **Different CIDR Ranges**: Assigning different CIDR ranges to each subnet within the VPC prevents IP address conflicts and ensures that each subnet has its own unique address space, meeting the requirement for separate subnets for production and test workloads.

### Conclusion:

Option 1 is the correct choice because it aligns with best practices for VPC design by using a single VPC with multiple subnets, each with unique CIDR ranges and potentially located in different regions. This setup facilitates internal communication between VMs while maintaining network isolation and addressing requirements for both production and test environments.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You have an instance group that you want to load balance. You want the load balancer to terminate the client SSL session. The instance group is used to serve a public web application over HTTPS. You want to follow Google-recommended practices. What should you do?   -----------------Issue

- [x] Configure an HTTP(S) load balancer.
- [ ] Configure an internal TCP load balancer.
- [ ] Configure an external SSL proxy load balancer.
- [ ] Configure an external TCP proxy load balancer.

The correct answer is:

3. **Configure an external SSL proxy load balancer.**

### Explanation of why other options are wrong:

1. **Configure an HTTP(S) load balancer**:
   - **Reason for being wrong**: While an HTTP(S) load balancer can terminate SSL/TLS connections, it terminates them at the load balancer level itself. If you specifically want the load balancer to terminate the SSL session and pass unencrypted traffic to the backend instances (often for performance or security inspection reasons), an external SSL proxy load balancer is more appropriate.

2. **Configure an internal TCP load balancer**:
   - **Reason for being wrong**: Internal TCP load balancers are used for internal, non-public facing applications where SSL termination is typically handled by the backend instances themselves. It doesn't terminate SSL sessions at the load balancer level.

4. **Configure an external TCP proxy load balancer**:
   - **Reason for being wrong**: TCP proxy load balancers do not terminate SSL sessions; they pass SSL traffic through without inspecting or modifying it. If SSL termination at the load balancer level is required, an SSL proxy load balancer is the correct choice.

### Why Option 3 is correct:

- **External SSL Proxy Load Balancer**: This type of load balancer is designed to terminate SSL/TLS sessions at the load balancer itself. It decrypts incoming HTTPS requests, inspects or modifies them if necessary, and then forwards the traffic to the backend instances over a separate, possibly unencrypted connection. This setup allows for central management of SSL certificates, offloading SSL processing from backend instances, and potentially improving performance by reducing the workload on the instances.

- **Google-recommended Practice**: Google Cloud Platform recommends using SSL proxy load balancers for terminating SSL/TLS sessions at the load balancer level, especially for public-facing web applications that require HTTPS. It provides enhanced security features and flexibility in managing SSL certificates and traffic.

### Conclusion:

Configuring an external SSL proxy load balancer ensures that SSL/TLS sessions are terminated at the load balancer, adhering to Google-recommended practices for managing SSL/TLS termination in a scalable and secure manner for public web applications served over HTTPS.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You have a web application deployed as a Managed Instance Group. You have a new version of the application to gradually deploy. Your web application is currently receiving live web traffic. You want to ensure that the available capacity does not decrease during the deployment. What should you do?

- [ ] Perform a rolling-action start-update with maxSurge set to 0 and maxUnavailable set to 1.
- [x] Perform a rolling-action start-update with maxSurge set to 1 and maxUnavailable set to 0.
- [ ] Create a new Managed Instance Group with an updated instance template. Add the group to the backend service for the load balancer. When all instances in the new Managed Instance Group are healthy, delete the old Managed Instance Group.
- [ ] Create a new instance template with the new application version. Update the existing Managed Instance Group with the new instance template. Delete the instances in the Managed Instance Group to allow the Managed Instance Group to recreate the instance using the new instance template.

The correct answer is:

2. **Perform a rolling-action start-update with maxSurge set to 1 and maxUnavailable set to 0.**

### Explanation of why other options are wrong:

1. **Perform a rolling-action start-update with maxSurge set to 0 and maxUnavailable set to 1**:
   - **Reason for being wrong**: Setting `maxSurge` to 0 means no additional instances can be created beyond the current capacity, which prevents scaling up to accommodate the new version. Additionally, setting `maxUnavailable` to 1 would allow one instance to be unavailable at a time, potentially reducing capacity during the deployment.

3. **Create a new Managed Instance Group with an updated instance template**:
   - **Reason for being wrong**: This approach involves creating a completely new Managed Instance Group and adding it to the backend service. It does not ensure that the available capacity remains constant during deployment, as the new group would need to scale up and the old group would likely be deleted after all instances are healthy in the new group, causing potential fluctuations in capacity.

4. **Create a new instance template and update the existing Managed Instance Group**:
   - **Reason for being wrong**: This option involves updating the instance template of the existing Managed Instance Group and deleting instances to recreate them with the new template. This process can lead to temporary decreases in available capacity during the deployment, which is contrary to the requirement of maintaining constant capacity.

### Why Option 2 is correct:

- **Rolling Update with `maxSurge` and `maxUnavailable` settings**: This approach allows for a controlled deployment of the new application version while ensuring that the available capacity does not decrease:
  - `maxSurge` set to 1 allows the Managed Instance Group to temporarily increase its size by one instance above the desired capacity, ensuring that there is room to deploy new instances with the updated application version.
  - `maxUnavailable` set to 0 ensures that no instances are taken offline at any time during the update process, maintaining the current capacity of the Managed Instance Group.

- **Gradual Deployment**: The rolling update strategy ensures that new instances with the updated application version are gradually rolled out, while old instances are gradually replaced. This minimizes disruption to the availability and capacity of the web application during the deployment process.

### Conclusion:

Performing a rolling-action start-update with `maxSurge` set to 1 and `maxUnavailable` set to 0 is the recommended approach to ensure a smooth deployment of a new application version in a Managed Instance Group while maintaining constant available capacity. This method adheres to best practices for minimizing downtime and ensuring service continuity during updates.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You need to grant access for three users so that they can view and edit table data on a Cloud Spanner instance. What should you do?

- [ ] Run gcloud iam roles describe roles/spanner.databaseUser. Add the users to the role.
- [x] Run gcloud iam roles describe roles/spanner.databaseUser. Add the users to a new group. Add the group to the role.
- [ ] Run gcloud iam roles describe roles/spanner.viewer –project my-project. Add the users to the role.
- [ ] Run gcloud iam roles describe roles/spanner.viewer –project my-project. Add the users to a new group. Add the group to the role.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You need to create a new billing account and then link it with an existing Google Cloud Platform project. What should you do?

- [ ] Verify that you are Project Billing Manager for the GCP project. Update the existing project to link it to the existing billing account.
- [x] Verify that you are Project Billing Manager for the GCP project. Create a new billing account and link the new billing account to the existing project.
- [ ] Verify that you are Billing Administrator for the billing account. Create a new project and link the new project to the existing billing account.
- [ ] Verify that you are Billing Administrator for the billing account. Update the existing project to link it to the existing billing account.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You have sensitive data stored in three Cloud Storage buckets and have enabled data access logging. You want to verify activities for a particular user for these buckets, using the fewest possible steps. You need to verify the addition of metadata labels and which files have been viewed from those buckets. What should you do?

- [x] Using the GCP Console, filter the Activity log to view the information.
- [ ] Using the GCP Console, filter the Stackdriver log to view the information.
- [ ] View the bucket in the Storage section of the GCP Console.
- [ ] Create a trace in Stackdriver to view the information.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You need to run an important query in BigQuery but expect it to return a lot of records. You want to find out how much it will cost to run the query. You are using on-demand pricing. What should you do?

- [ ] Arrange to switch to Flat-Rate pricing for this query, then move back to on-demand.
- [x] Use the command line to run a dry run query to estimate the number of bytes read. Then convert that bytes estimate to dollars using the Pricing Calculator.
- [ ] Use the command line to run a dry run query to estimate the number of bytes returned. Then convert that bytes estimate to dollars using the Pricing Calculator.
- [ ] Run a select count (*) to get an idea of how many records your query will look through. Then convert that number of rows to dollars using the Pricing Calculator.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You need to monitor resources that are distributed over different projects in Google Cloud Platform. You want to consolidate reporting under the same Stackdriver Monitoring dashboard. What should you do?

- [ ] Use Shared VPC to connect all projects, and link Stackdriver to one of the projects.
- [ ] For each project, create a Stackdriver account. In each project, create a service account for that project and grant it the role of Stackdriver Account Editor in all other projects.
- [x] Configure a single Stackdriver account, and link all projects to the same account.
- [ ] Configure a single Stackdriver account for one of the projects. In Stackdriver, create a Group and add the other project names as criteria for that Group.

To consolidate reporting under the same Stackdriver (now Google Cloud Monitoring) dashboard for resources distributed over different projects, you should:

- **[3] Configure a single Stackdriver account, and link all projects to the same account.**

### Explanation:
- **Single Stackdriver Account**: By configuring a single Stackdriver Monitoring account and linking all projects to this account, you can consolidate and view metrics from all projects in one place. This approach simplifies monitoring and management by centralizing the data.

### Why Other Options are Wrong:
- **[1] Use Shared VPC to connect all projects, and link Stackdriver to one of the projects.**
  - Shared VPC is used for sharing networks across projects, not for monitoring purposes. Linking Stackdriver to one project won't automatically include metrics from other projects.

- **[2] For each project, create a Stackdriver account. In each project, create a service account for that project and grant it the role of Stackdriver Account Editor in all other projects.**
  - This option is overly complex and unnecessary. It involves creating multiple Stackdriver accounts and managing service account permissions, which can be cumbersome and does not inherently consolidate the monitoring data into a single dashboard.

- **[4] Configure a single Stackdriver account for one of the projects. In Stackdriver, create a Group and add the other project names as criteria for that Group.**
  - While creating a group in Stackdriver might help organize resources, it doesn't inherently link multiple projects to a single Stackdriver account for consolidated reporting. Groups are more about organizing resources within a project rather than across multiple projects.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You need a dynamic way of provisioning VMs on Compute Engine. The exact specifications will be in a dedicated configuration file. You want to follow Google's recommended practices. Which method should you use?

- [x] Deployment Manager.
- [ ] Cloud Composer.
- [ ] Managed Instance Group.
- [ ] Unmanaged Instance Group.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You created an instance of SQL Server 2017 on Compute Engine to test features in the new version. You want to connect to this instance using the fewest number of steps. What should you do?

- [ ] Install a RDP client on your desktop. Verify that a firewall rule for port 3389 exists.
- [x] Install a RDP client in your desktop. Set a Windows username and password in the GCP Console. Use the credentials to log in to the instance.
- [ ] Set a Windows password in the GCP Console. Verify that a firewall rule for port 22 exists. Click the RDP button in the GCP Console and supply the credentials to log in.
- [ ] Set a Windows username and password in the GCP Console. Verify that a firewall rule for port 3389 exists. Click the RDP button in the GCP Console, and supply the credentials to log in.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You are the organization and billing administrator for your company. The engineering team has the Project Creator role on the organization. You do not want the engineering team to be able to link projects to the billing account. Only the finance team should be able to link a project to a billing account, but they should not be able to make any other changes to projects. What should you do?

- [x] Assign the finance team only the Billing Account User role on the billing account.
- [ ] Assign the engineering team only the Billing Account User role on the billing account.
- [ ] Assign the finance team the Billing Account User role on the billing account and the Project Billing Manager role on the organization.
- [ ] Assign the engineering team the Billing Account User role on the billing account and the Project Billing Manager role on the organization.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You are creating a Google Kubernetes Engine (GKE) cluster with a cluster autoscaler feature enabled. You need to make sure that each node of the cluster will run a monitoring pod that sends container metrics to a third-party monitoring solution. What should you do?

- [ ] Deploy the monitoring pod in a StatefulSet object.
- [x] Deploy the monitoring pod in a DaemonSet object.
- [ ] Reference the monitoring pod in a Deployment object.
- [ ] Reference the monitoring pod in a cluster initializer at the GKE cluster creation time.

To ensure that each node of the GKE cluster runs a monitoring pod that sends container metrics to a third-party monitoring solution, you should:

- **[2] Deploy the monitoring pod in a DaemonSet object.**

### Explanation:
- **DaemonSet**: A DaemonSet ensures that a copy of a pod runs on all (or some) nodes in the cluster. When you create a DaemonSet, it automatically adds the monitoring pod to each new node added to the cluster, which is ideal for running monitoring agents.

### Why Other Options are Wrong:
- **[1] Deploy the monitoring pod in a StatefulSet object.**
  - A StatefulSet is used for stateful applications, where each pod has a unique identity and stable storage. It's not intended for ensuring that each node runs a pod.

- **[3] Reference the monitoring pod in a Deployment object.**
  - A Deployment ensures that a specified number of replicas of a pod are running, but it doesn't ensure that one pod runs on each node. It distributes pods across the cluster based on available resources.

- **[4] Reference the monitoring pod in a cluster initializer at the GKE cluster creation time.**
  - While you can initialize certain settings at the cluster creation time, this option doesn't provide a way to ensure that a monitoring pod runs on each node. DaemonSets are specifically designed for this purpose and are the standard Kubernetes solution for running a pod on every node.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You create a new Google Kubernetes Engine (GKE) cluster and want to make sure that it always runs a supported and stable version of Kubernetes. What should you do?

- [ ] Enable the Node Auto-Repair feature for your GKE cluster.
- [x] Enable the Node Auto-Upgrades feature for your GKE cluster.
- [ ] Select the latest available cluster version for your GKE cluster.
- [ ] Select 'Container-Optimized OS (cos)' as a node image for your GKE cluster.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### Your company uses Cloud Storage to store application backup files for disaster recovery purposes. You want to follow Google's recommended practices. Which storage option should you use?

- [ ] Multi-Regional Storage.
- [ ] Regional Storage.
- [ ] Nearline Storage.
- [x] Coldline Storage.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You need to set up a policy so that videos stored in a specific Cloud Storage Regional bucket are moved to Coldline after 90 days, and then deleted after one year from their creation. How should you set up the policy?

- [ ] Use Cloud Storage Object Lifecycle Management using Age conditions with SetStorageClass and Delete actions. Set the SetStorageClass action to 90 days and the Delete action to 275 days (365-90).
- [x] Use Cloud Storage Object Lifecycle Management using Age conditions with SetStorageClass and Delete actions. Set the SetStorageClass action to 90 days and the Delete action to 365 days.
- [ ] Use gsutil rewrite and set the Delete action to 275 days (365-90).
- [ ] Use gsutil rewrite and set the Delete action to 365 days.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### Your company has an existing GCP organization with hundreds of projects and a billing account. Your company recently acquired another company that also has hundreds of projects and its own billing account. You would like to consolidate all GCP costs of both GCP organizations onto a single invoice. You would like to consolidate all costs as of tomorrow. What should you do?

- [x] Link the acquired company's projects to your company's billing account.
- [ ] Configure the acquired company's billing account and your company's billing account to export the billing data into the same BigQuery dataset.
- [ ] Migrate the acquired company's projects into your company's GCP organization. Link the migrated projects to your company's billing account.
- [ ] Create a new GCP organization and a new billing account. Migrate the acquired company's projects and your company's projects into the new GCP organization and link the projects to the new billing account.

To consolidate all GCP costs of both organizations onto a single invoice by tomorrow, the most straightforward and immediate action would be to:

- **[1] Link the acquired company's projects to your company's billing account.**

This approach allows you to quickly and efficiently consolidate billing under one account, ensuring that all costs are included in a single invoice. This option provides an immediate solution without the need for more complex reorganization or migration of projects, which would take more time and effort.

Options like migrating projects to a new organization or linking billing data to a shared BigQuery dataset are more involved and wouldn't provide an immediate consolidation of invoices by tomorrow.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You want to configure 10 Compute Engine instances for availability when maintenance occurs. Your requirements state that these instances should attempt to automatically restart if they crash. Also, the instances should be highly available including during system maintenance. What should you do?

- [x] Create an instance template for the instances. Set the 'Automatic Restart' to on. Set the 'On-host maintenance' to Migrate VM instance. Add the instance template to an instance group.
- [ ] Create an instance template for the instances. Set 'Automatic Restart' to off. Set 'On-host maintenance' to Terminate VM instances. Add the instance template to an instance group.
- [ ] Create an instance group for the instances. Set the 'Autohealing' health check to healthy (HTTP).
- [ ] Create an instance group for the instance. Verify that the 'Advanced creation options' setting for 'do not retry machine creation' is set to off.

The correct option for your scenario is:

**[1] Create an instance template for the instances. Set the 'Automatic Restart' to on. Set the 'On-host maintenance' to Migrate VM instance. Add the instance template to an instance group.**

Here’s why this option is correct:

- **Create an instance template for the instances:** Instance templates in Google Cloud allow you to define the machine type, boot disk image or container image, labels, and other instance properties. They provide a consistent way to create VM instances.

- **Set the 'Automatic Restart' to on:** This ensures that if an instance crashes due to a failure, the instance will attempt to restart automatically, helping to maintain availability.

- **Set the 'On-host maintenance' to Migrate VM instance:** This setting ensures that during maintenance events that require the underlying host to be updated or replaced, Google Cloud will migrate the VM instance to another host, maintaining its availability.

- **Add the instance template to an instance group:** Instance groups in Google Cloud manage groups of VM instances as a single entity, providing features such as autoscaling, load balancing, and autohealing.

Now, let's analyze why the other options are incorrect:

- **[2] Create an instance template for the instances. Set 'Automatic Restart' to off. Set 'On-host maintenance' to Terminate VM instances. Add the instance template to an instance group:**
  - Setting 'Automatic Restart' to off means instances won't attempt to restart automatically if they crash, which contradicts the requirement for automatic restart.
  - Setting 'On-host maintenance' to Terminate VM instances means instances would be terminated rather than migrated during maintenance, which does not ensure availability.

- **[3] Create an instance group for the instances. Set the 'Autohealing' health check to healthy (HTTP):**
  - While instance groups do support autohealing, configuring a health check alone without specifying the instance template's settings for automatic restart and maintenance behavior does not ensure that instances will automatically restart or be migrated during maintenance.

- **[4] Create an instance group for the instance. Verify that the 'Advanced creation options' setting for 'do not retry machine creation' is set to off:**
  - This setting is unrelated to ensuring instance availability during maintenance or automatic restart. It focuses on retry behavior for creating instances.

Therefore, option [1] is the correct choice as it directly addresses the requirements for instance availability during maintenance and automatic restart in Google Cloud Compute Engine instances.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You have a development project with appropriate IAM roles defined. You are creating a production project and want to have the same IAM roles on the new project, using the fewest possible steps. What should you do?

- [x] Use gcloud iam roles copy and specify the production project as the destination project.
- [ ] Use gcloud iam roles copy and specify your organization as the destination organization.
- [ ] In the Google Cloud Platform Console, use the 'create role from role' functionality.
- [ ] In the Google Cloud Platform Console, use the 'create role' functionality and select all applicable permissions.

The correct option for your scenario is:

**[1] Use gcloud iam roles copy and specify the production project as the destination project.**

Here’s why the other options are incorrect:

- **[2] Use gcloud iam roles copy and specify your organization as the destination organization:**
  This option is not necessary unless you need to copy roles across projects within the same organization. It's more specific to organizational-level IAM management rather than project-level.

- **[3] In the Google Cloud Platform Console, use the 'create role from role' functionality:**
  This option allows you to create a new role based on an existing role within the same project, but it doesn't copy roles between projects. It's useful for refining or customizing existing roles within a single project.

- **[4] In the Google Cloud Platform Console, use the 'create role' functionality and select all applicable permissions:**
  This option involves manually creating a new role and selecting permissions, which is not efficient if you want to replicate an existing role with the same permissions from another project. It's more suited for creating entirely new roles from scratch.

Therefore, using `gcloud iam roles copy` with the destination project specified is the most direct and efficient method to replicate IAM roles from one project to another. It ensures that all permissions and configurations associated with the roles are copied accurately to the new project.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You are using multiple configurations for gcloud. You want to review the configured Kubernetes Engine cluster of an inactive configuration using the fewest possible steps. What should you do?

- [ ] Use gcloud config configurations describe to review the output.
- [ ] Use gcloud config configurations activate and gcloud config list to review the output.
- [ ] Use kubectl config get-contexts to review the output.
- [x] Use kubectl config use-context and kubectl config view to review the output.

To review the configured Kubernetes Engine cluster of an inactive configuration using the fewest possible steps, you should use `kubectl config view`.

### Correct Answer:
**Use kubectl config use-context and kubectl config view to review the output.**

### Explanation:

- **kubectl config use-context:** This command switches the current context to the specified one.
- **kubectl config view:** This command displays the current configuration settings, including the active context, clusters, users, and other relevant information.

By using `kubectl config use-context` to switch to the desired context and then `kubectl config view` to display the details, you can review the configuration effectively.

### Why the Other Options Are Incorrect:

1. **Use gcloud config configurations describe to review the output.**
   - **Incorrect:** This command describes the gcloud configuration but does not directly show the Kubernetes Engine cluster information tied to it.

2. **Use gcloud config configurations activate and gcloud config list to review the output.**
   - **Inefficient:** This approach requires activating the configuration and listing the settings, which is more cumbersome and involves more steps.

3. **Use kubectl config get-contexts to review the output.**
   - **Incomplete:** This command shows the available contexts but does not provide detailed information about the specific configuration of an inactive context.

4. **Use kubectl config use-context and kubectl config view to review the output.**
   - **Correct:** This method switches to the specified context and then reviews the current configuration, providing a direct way to see the Kubernetes Engine cluster details.

### Conclusion:
Using `kubectl config use-context` to switch contexts and `kubectl config view` to display the current configuration settings is the most efficient and direct method to review the Kubernetes Engine cluster of an inactive configuration.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You need to configure IAM access audit logging in BigQuery for external auditors. You want to follow Google-recommended practices. What should you do?

- [x] Add the auditors group to the 'logging.viewer' and 'bigQuery.dataViewer' predefined IAM roles.
- [ ] Add the auditors group to two new custom IAM roles.
- [ ] Add the auditor user accounts to the 'logging.viewer' and 'bigQuery.dataViewer' predefined IAM roles.
- [ ] Add the auditor user accounts to two new custom IAM roles.

To configure IAM access audit logging in BigQuery for external auditors while following Google-recommended practices, you should add the auditors group to the 'logging.viewer' and 'bigQuery.dataViewer' predefined IAM roles.

### Correct Answer:
**Add the auditors group to the 'logging.viewer' and 'bigQuery.dataViewer' predefined IAM roles.**

### Explanation:

#### Why Option 1 is Correct:
- **Predefined Roles:** Using predefined roles (`logging.viewer` and `bigQuery.dataViewer`) is a best practice recommended by Google because these roles are designed to provide the necessary permissions without granting excessive access.
- **Group Management:** Assigning roles to a group rather than individual users simplifies management and ensures consistency in permissions. This way, any new auditor added to the group automatically inherits the necessary permissions.
- **Audit Logging:** The `logging.viewer` role allows auditors to view audit logs, and the `bigQuery.dataViewer` role allows them to read BigQuery data, which are typical requirements for auditing purposes.

### Why the Other Options Are Incorrect:

2. **Add the auditors group to two new custom IAM roles.**
   - **Unnecessary Custom Roles:** Creating custom roles for this purpose is unnecessary when predefined roles already exist to fulfill the requirements. Custom roles add complexity without providing additional benefits in this scenario.

3. **Add the auditor user accounts to the 'logging.viewer' and 'bigQuery.dataViewer' predefined IAM roles.**
   - **Individual User Management:** Assigning roles to individual user accounts is less efficient than assigning them to a group. It requires more administrative effort and increases the risk of inconsistencies.

4. **Add the auditor user accounts to two new custom IAM roles.**
   - **Individual Users and Custom Roles:** This option combines the drawbacks of options 2 and 3. It adds unnecessary complexity by creating custom roles and managing permissions at the individual user level instead of at the group level.

### Conclusion:
Option 1 follows Google-recommended practices by using predefined IAM roles to grant the necessary permissions and managing these permissions through a group, making it the most efficient and secure approach.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You need to create a custom VPC with a single subnet. The subnet's range must be as large as possible. Which range should you use?

- [ ] 0.0.0.0/0.
- [x] 10.0.0.0/8.
- [ ] 172.16.0.0/12.
- [ ] 192.168.0.0/16.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You recently deployed a new version of an application to App Engine and then discovered a bug in the release. You need to immediately revert to the prior version of the application. What should you do?

- [ ] Run gcloud app restore.
- [ ] On the App Engine page of the GCP Console, select the application that needs to be reverted and click Revert.
- [x] On the App Engine Versions page of the GCP Console, route 100% of the traffic to the previous version.
- [ ] Deploy the original version as a separate application. Then go to App Engine settings and split traffic between applications so that the original version serves 100% of the requests.

To revert to the prior version of your application in App Engine, you should route 100% of the traffic to the previous version.

### Correct Answer:
**On the App Engine Versions page of the GCP Console, route 100% of the traffic to the previous version.**

### Explanation:

#### Why Option 3 is Correct:
- **Traffic Splitting:** App Engine allows you to deploy multiple versions of your application and manage traffic between them. By routing 100% of the traffic to the previous version, you effectively revert to that version without needing to redeploy or modify the existing versions.
- **Immediate Reversion:** This method provides an immediate solution to revert traffic back to the stable version, ensuring that users no longer encounter the bug in the new release.

### Why the Other Options Are Incorrect:

1. **Run gcloud app restore.**
   - **Non-Existent Command:** There is no `gcloud app restore` command available in the Google Cloud SDK, making this option invalid.

2. **On the App Engine page of the GCP Console, select the application that needs to be reverted and click Revert.**
   - **No Revert Button:** There is no "Revert" button on the App Engine page of the GCP Console. Traffic management is done through the Versions page.

4. **Deploy the original version as a separate application. Then go to App Engine settings and split traffic between applications so that the original version serves 100% of the requests.**
   - **Unnecessary Steps:** This option is overly complex and unnecessary. You don't need to deploy the original version again. App Engine's traffic splitting feature allows you to route traffic to existing versions without redeploying.

### Conclusion:
Option 3 is the best answer because it leverages App Engine's built-in traffic management capabilities to revert to a previous version quickly and efficiently. This ensures minimal downtime and disruption for users while addressing the bug in the new release.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You want to configure Autohealing for network load balancing for a group of Compute Engine instances that run in multiple zones, using the fewest possible steps. You need to configure re-creation of VMs if they are unresponsive after 3 attempts of 10 seconds each. What should you do?

- [ ] Create an HTTP load balancer with a backend configuration that references an existing instance group. Set the health check to healthy (HTTP).
- [ ] Create an HTTP load balancer with a backend configuration that references an existing instance group. Define a balancing mode and set the maximum RPS to 10.
- [x] Create a Managed Instance Group. Set the Autohealing health check to healthy (HTTP).
- [ ] Create a Managed Instance Group. Verify that the autoscaling setting is on.

To configure Autohealing for network load balancing with the fewest steps, you should create a Managed Instance Group and set the Autohealing health check.

### Correct Answer:
**Create a Managed Instance Group. Set the Autohealing health check to healthy (HTTP).**

### Explanation:

#### Why Option 3 is Correct:
- **Managed Instance Group (MIG):** A Managed Instance Group is the primary way to set up autohealing for instances in Google Cloud. It manages identical instances based on a template and ensures they are healthy.
- **Autohealing Configuration:** Within the MIG, you can set up an autohealing policy that uses a health check to determine the health of the instances. If instances are deemed unhealthy, they are automatically recreated.
- **Health Check Configuration:** You can define an HTTP health check with specific parameters (like 3 attempts of 10 seconds each) to determine if an instance is healthy.

### Why the Other Options Are Incorrect:

1. **Create an HTTP load balancer with a backend configuration that references an existing instance group. Set the health check to healthy (HTTP).**
   - **Load Balancer Focus:** This option focuses on setting up a load balancer, not autohealing. While health checks are part of the load balancer, they do not directly configure autohealing for the instances.

2. **Create an HTTP load balancer with a backend configuration that references an existing instance group. Define a balancing mode and set the maximum RPS to 10.**
   - **Balancing Mode Configuration:** This option sets up a load balancer with specific request per second (RPS) limits, which is unrelated to the autohealing configuration needed for recreating unresponsive VMs.

4. **Create a Managed Instance Group. Verify that the autoscaling setting is on.**
   - **Autoscaling vs. Autohealing:** Autoscaling adjusts the number of instances based on load but does not ensure individual instance health or recreate unresponsive instances. Autohealing specifically recreates unhealthy instances based on health checks.

### Conclusion:
Option 3 is the best answer because it directly addresses the need to configure autohealing for the instances in a managed instance group with a specific HTTP health check. This approach ensures that instances are recreated if they become unresponsive according to the defined health check parameters.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You have a Linux VM that must connect to Cloud SQL. You created a service account with the appropriate access rights. You want to make sure that the VM uses this service account instead of the default Compute Engine service account. What should you do?

- [x] When creating the VM via the web console, specify the service account under the 'Identity and API Access' section.
- [ ] Download a JSON Private Key for the service account. On the Project Metadata, add that JSON as the value for the key compute-engine-service-account.
- [ ] Download a JSON Private Key for the service account. On the Custom Metadata of the VM, add that JSON as the value for the key compute-engine-service-account.
- [ ] Download a JSON Private Key for the service account. After creating the VM, ssh into the VM and save the JSON under ~/.gcloud/compute-engine-service-account.json.

To ensure that your Linux VM uses a specific service account instead of the default Compute Engine service account, you need to assign the desired service account during the VM creation process.

### Correct Answer:
**When creating the VM via the web console, specify the service account under the 'Identity and API Access' section.**

### Explanation:

#### Why Option 1 is Correct:
- **Service Account Selection:** During the VM creation process, you can specify a custom service account under the 'Identity and API Access' section. This assigns the specified service account to the VM, allowing it to access Cloud SQL and other Google Cloud resources according to the permissions granted to the service account.
- **No Need for Key Management:** Specifying the service account at creation time eliminates the need to manually handle and manage JSON private keys, which simplifies security and reduces the risk of key exposure.

### Why the Other Options Are Incorrect:

2. **Download a JSON Private Key for the service account. On the Project Metadata, add that JSON as the value for the key compute-engine-service-account.**
   - **Incorrect Metadata Use:** Project metadata is not intended for storing and distributing sensitive JSON private keys. This approach exposes the private key and does not ensure the VM uses the specified service account.

3. **Download a JSON Private Key for the service account. On the Custom Metadata of the VM, add that JSON as the value for the key compute-engine-service-account.**
   - **Incorrect Metadata Use:** Similar to project metadata, VM custom metadata is not meant for distributing JSON private keys. This method also exposes the private key and is not a secure practice.

4. **Download a JSON Private Key for the service account. After creating the VM, ssh into the VM and save the JSON under ~/.gcloud/compute-engine-service-account.json.**
   - **Manual and Insecure:** This approach requires manual intervention and handling of the private key, increasing the risk of exposure. It is not the recommended method for assigning a service account to a VM.

### Conclusion:
Option 1 is the correct approach because it securely assigns the specified service account to the VM during the creation process, leveraging built-in Google Cloud Platform features without exposing sensitive credentials.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You have one project called proj-sa where you manage all your service accounts. You want to be able to use a service account from this project to take snapshots of VMs running in another project called proj-vm. What should you do?

- [ ] Download the private key from the service account, and add it to each VMs custom metadata.
- [ ] Download the private key from the service account, and add the private key to each VM's SSH keys.
- [x] Grant the service account the IAM role of Compute Storage Admin in the project called proj-vm.
- [ ] When creating the VMs, set the service account's API scope for Compute Engine to read/write.

To allow a service account from one project (proj-sa) to take snapshots of VMs running in another project (proj-vm), you need to ensure that the service account has the necessary permissions to perform this task in the target project.

### Correct Answer:
**Grant the service account the IAM role of Compute Storage Admin in the project called proj-vm.**

### Explanation:

#### Why Option 3 is Correct:
- **Permissions:** The `Compute Storage Admin` role includes permissions to create snapshots of disks. By granting this role to the service account in the proj-vm project, you allow the service account to perform the necessary snapshot operations.
- **Cross-Project Permissions:** IAM roles can be assigned across projects, meaning you can grant a service account from one project permissions to resources in another project. This is a common practice in GCP to manage access and permissions efficiently.

### Why the Other Options Are Incorrect:

1. **Download the private key from the service account, and add it to each VM's custom metadata.**
   - **Incorrect Approach:** Adding the private key to VM metadata is not a secure or recommended practice. It doesn't grant the necessary permissions for taking snapshots and exposes the private key, which is a security risk.

2. **Download the private key from the service account, and add the private key to each VM's SSH keys.**
   - **Incorrect Use of SSH Keys:** SSH keys are used for secure access to VM instances, not for granting API permissions like taking snapshots. This method does not address the need for proper IAM roles.

4. **When creating the VMs, set the service account's API scope for Compute Engine to read/write.**
   - **Scopes vs. Roles:** API scopes define the level of access to GCP services for a particular instance, but they do not grant the necessary IAM permissions across projects. Scopes are limited to the instance level and cannot span multiple projects.

### Conclusion:
Option 3 is the correct approach because it properly uses IAM roles to grant the required permissions to the service account, ensuring it can take snapshots of VMs in the proj-vm project securely and efficiently.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You have one GCP account running in your default region and zone and another account running in a non-default region and zone. You want to start a new Compute Engine instance in these two Google Cloud Platform accounts using the command line interface. What should you do?

- [x] Create two configurations using gcloud config configurations create [NAME]. Run gcloud config configurations activate [NAME] to switch between accounts when running the commands to start the Compute Engine instances.
- [ ] Create two configurations using gcloud config configurations create [NAME]. Run gcloud configurations list to start the Compute Engine instances.
- [ ] Activate two configurations using gcloud configurations activate [NAME]. Run gcloud config list to start the Compute Engine instances.
- [ ] Activate two configurations using gcloud configurations activate [NAME]. Run gcloud configurations list to start the Compute Engine instances.

To manage multiple Google Cloud Platform (GCP) accounts and set different configurations for each, the appropriate steps involve creating and activating configurations. Here's the correct approach:

### Correct Answer:
**Create two configurations using `gcloud config configurations create [NAME]`. Run `gcloud config configurations activate [NAME]` to switch between accounts when running the commands to start the Compute Engine instances.**

### Explanation:

#### Why Option 1 is Correct:
- **Creating Configurations:** Using `gcloud config configurations create [NAME]`, you can create separate configurations for each account.
- **Activating Configurations:** The command `gcloud config configurations activate [NAME]` allows you to switch between these configurations, making it easy to manage and run commands in different accounts without having to reconfigure each time.
- **Running Commands:** After activating the desired configuration, you can run the necessary commands to start Compute Engine instances in the respective accounts.

### Why the Other Options Are Incorrect:

2. **Create two configurations using gcloud config configurations create [NAME]. Run gcloud configurations list to start the Compute Engine instances.**
   - **Incorrect Usage:** `gcloud configurations list` is used to list all available configurations, not to start instances. It doesn't switch between configurations or start Compute Engine instances.

3. **Activate two configurations using gcloud configurations activate [NAME]. Run gcloud config list to start the Compute Engine instances.**
   - **Incorrect Command:** `gcloud config list` lists the properties in the currently active configuration. It does not start Compute Engine instances or switch between configurations.

4. **Activate two configurations using gcloud configurations activate [NAME]. Run gcloud configurations list to start the Compute Engine instances.**
   - **Incorrect Combination:** `gcloud configurations list` lists all available configurations but does not start Compute Engine instances. It also does not switch between configurations.

### Conclusion:
Option 1 correctly outlines the steps to create and switch between configurations for different GCP accounts using the `gcloud` command-line tool. This method allows you to manage multiple accounts efficiently and execute commands in the appropriate account context.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### Every employee of your company has a Google account. Your operational team needs to manage a large number of instances on Compute Engine. Each member of this team needs only administrative access to the servers. Your security team wants to ensure that the deployment of credentials is operationally efficient and must be able to determine who accessed a given instance. What should you do?

- [ ] Generate a new SSH key pair. Give the private key to each member of your team. Configure the public key in the metadata of each instance.
- [ ] Ask each member of the team to generate a new SSH key pair and to send you their public key. Use a configuration management tool to deploy those keys on each instance.
- [x] Ask each member of the team to generate a new SSH key pair and to add the public key to their Google account. Grant the 'compute.osAdminLogin' role to the Google group corresponding to this team.
- [ ] Generate a new SSH key pair. Give the private key to each member of your team. Configure the public key as a project-wide public SSH key in your Cloud Platform project and allow project-wide public SSH keys on each instance.

### Correct Answer:
**Ask each member of the team to generate a new SSH key pair and to add the public key to their Google account. Grant the 'compute.osAdminLogin' role to the Google group corresponding to this team.**

### Explanation:

#### Why Option 3 is Correct:
- **Administrative Access:** By granting the `compute.osAdminLogin` role to a Google group, all team members in that group will have administrative access to the instances.
- **Operational Efficiency:** Each team member managing their own SSH key pair and adding it to their Google account streamlines the process and reduces the overhead of manual key distribution.
- **Auditing and Accountability:** Using individual Google accounts ensures that each access is tied to a specific user, enabling detailed auditing and accountability through Google Cloud's audit logs.

### Why the Other Options Are Incorrect:

1. **Generate a new SSH key pair. Give the private key to each member of your team. Configure the public key in the metadata of each instance.**
   - **Operational Efficiency:** Managing and distributing a single SSH key pair to all team members is inefficient and insecure. If the private key is compromised, it would be difficult to revoke access without disrupting all users.
   - **Auditing:** This method lacks the ability to track individual user access, as all team members would be using the same credentials.

2. **Ask each member of the team to generate a new SSH key pair and to send you their public key. Use a configuration management tool to deploy those keys on each instance.**
   - **Operational Efficiency:** While this method centralizes key deployment, it still involves significant manual effort in collecting and deploying individual keys.
   - **Auditing:** This approach can track individual access, but it is more complex and less efficient compared to using Google accounts with their associated audit logs.

4. **Generate a new SSH key pair. Give the private key to each member of your team. Configure the public key as a project-wide public SSH key in your Cloud Platform project and allow project-wide public SSH keys on each instance.**
   - **Operational Efficiency:** Similar to Option 1, distributing the same SSH key pair to all team members is inefficient and poses security risks.
   - **Auditing:** This method also lacks the ability to track individual user access, as all team members would be using the same credentials.

### Conclusion:
Option 3 provides a balanced solution that ensures operational efficiency, individual accountability, and robust security. By leveraging Google accounts and the `compute.osAdminLogin` role, you can manage access effectively and maintain detailed audit logs.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You need to deploy an application, which is packaged in a container image, in a new project. The application exposes an HTTP endpoint and receives very few requests per day. You want to minimize costs. What should you do?

- [x] Deploy the container on Cloud Run.
- [ ] Deploy the container on Cloud Run on GK.
- [ ] Deploy the container on App Engine Flexible.
- [ ] Deploy the container on Google Kubernetes Engine, with cluster autoscaling and horizontal pod autoscaling enabled.

To minimize costs while deploying an application that receives very few requests per day and is packaged in a container image, the most suitable option would be:

- [1] **Deploy the container on Cloud Run.**

### Here's why Cloud Run is the recommended choice:

- **Cost Efficiency:** Cloud Run offers a serverless platform where you pay only for the exact compute resources consumed by your application per request and the duration of each request. It scales down to zero when there are no requests, which can result in significant cost savings for applications with low traffic.

- **Ease of Deployment:** Deploying a container image on Cloud Run is straightforward. You simply deploy your container, and Cloud Run manages the rest, including scaling based on incoming requests.

- **Automatic Scaling:** Cloud Run automatically scales your containers up and down based on traffic, ensuring that you don't over-provision resources when traffic is low.

### Comparison with Other Options:

- **Option 2:** Deploying on Cloud Run on Google Kubernetes Engine (GKE) adds unnecessary complexity and overhead for an application with minimal traffic. GKE involves managing Kubernetes clusters, which is more suitable for applications with complex orchestration needs or higher traffic volumes.

- **Option 3:** App Engine Flexible environment offers scalability and automatic scaling, but it may be more expensive compared to Cloud Run for low-traffic applications because it requires maintaining instances running continuously.

- **Option 4:** Deploying on Google Kubernetes Engine (GKE) with cluster autoscaling and horizontal pod autoscaling enabled is overkill for an application with very few requests per day. It involves managing a Kubernetes cluster, which adds operational complexity and potentially higher costs due to maintaining cluster nodes even during low traffic periods.

### Conclusion:

Deploying your container on **Cloud Run (option 1)** is the most cost-effective and straightforward approach for an application that receives very few requests per day. It leverages serverless computing benefits, such as automatic scaling and pay-per-use pricing, while minimizing operational overhead and ensuring efficient resource utilization.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### Your development team needs a new Jenkins server for their project. You need to deploy the server using the fewest steps possible. What should you do?

- [ ] Download and deploy the Jenkins Java WAR to App Engine Standard.
- [ ] Create a new Compute Engine instance and install Jenkins through the command line interface.
- [ ] Create a Kubernetes cluster on Compute Engine and create a deployment with the Jenkins Docker image.
- [x] Use GCP Marketplace to launch the Jenkins solution.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You are building an application that stores relational data from users. Users across the globe will use this application. Your CTO is concerned about the scaling requirements because the size of the user base is unknown. You need to implement a database solution that can scale with your user growth with minimum configuration changes. Which storage solution should you use?

- [ ] Cloud SQL.
- [x] Cloud Spanner.
- [ ] Cloud Firestore.
- [ ] Cloud Datastore.

Based on the requirement to implement a database solution that can scale with user growth with minimum configuration changes, the most suitable option from the provided choices would be **Cloud Spanner** (option 2).

Here's why Cloud Spanner is appropriate:

- **Horizontal Scalability:** Cloud Spanner is a fully managed, horizontally scalable relational database service. It is designed to automatically handle sharding and distribution of data across multiple nodes, allowing it to scale out seamlessly as your application's workload grows.

- **Global Distribution:** It provides strong consistency and high availability across regions and continents. This is particularly beneficial for applications with users distributed globally, ensuring low-latency access to data.

- **ACID Transactions:** Cloud Spanner supports ACID (Atomicity, Consistency, Isolation, Durability) transactions, which are essential for applications that require strong data consistency guarantees.

- **Schema Flexibility:** While Cloud Spanner is a relational database, it offers some schema flexibility compared to traditional relational databases, making it easier to adapt to evolving application requirements without major schema changes.

- **Managed Service:** Like other Google Cloud services, Cloud Spanner is fully managed, meaning Google handles the underlying infrastructure, backups, patches, and updates. This reduces operational overhead and allows developers to focus on application development.

### Other Options Considered:

- **Cloud SQL (option 1):** While Cloud SQL is a good choice for traditional relational databases, it may require more manual effort to scale horizontally compared to Cloud Spanner. It's suitable for smaller-scale applications or when strict relational schema requirements are necessary but doesn't offer the same level of global scalability and automatic sharding.

- **Cloud Firestore (option 3) and Cloud Datastore (option 4):** These are NoSQL document databases. They are more suitable for semi-structured data and applications that benefit from flexibility in schema design. However, they may not provide the same level of relational data consistency and transactional support required for some applications storing relational data.

### Conclusion:

Given the requirement for global scalability, relational data consistency, and minimal configuration changes as the user base grows, **Cloud Spanner** is the best choice among the options provided. It provides a scalable and globally distributed relational database solution with strong consistency and transaction support, making it well-suited for modern applications with global user bases.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You are using Deployment Manager to create a Google Kubernetes Engine cluster. Using the same Deployment Manager deployment, you also want to create a DaemonSet in the kube-system namespace of the cluster. You want a solution that uses the fewest possible services.

- [x] Add the cluster's API as a new Type Provider in Deployment Manager, and use the new type to create the DaemonSet.
- [ ] Use the Deployment Manager Runtime Configurator to create a new Config resource that contains the DaemonSet definition.
- [ ] With Deployment Manager, create a Compute Engine instance with a startup script that uses kubectl to create the DaemonSet.
- [ ] In the cluster's definition in Deployment Manager, add a metadata that has kube-system as key and the DaemonSet manifest as value.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You have a Virtual Machine that is currently configured with 2 vCPUs and 4 GB of memory. It is running out of memory. You want to upgrade the Virtual Machine to have 8 GB of memory. What should you do?

- [ ] Rely on live migration to move the workload to a machine with more memory.
- [ ] Use gcloud to add metadata to the V. Set the key to required-memory-size and the value to 8 GB.
- [ ] Stop the VM, change the machine type to n1-standard-8, and start the VM.
- [x] Stop the VM, increase the memory to 8 GB, and start the VM.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You created a Google Cloud Platform project with an App Engine application inside the project. You initially configured the application to be served from the us-central region. Now you want the application to be served from the asia-northeast1 region. What should you do?

- [ ] Change the default region property setting in the existing GCP project to asia-northeast1.
- [ ] Change the region property setting in the existing App Engine application from us-central to asia-northeast1.
- [ ] Create a second App Engine application in the existing GCP project and specify asia-northeast1 as the region to serve your application.
- [x] Create a new GCP project and create an App Engine application inside this new project. Specify asia-northeast1 as the region to serve your application.

The correct answer is:

- [x] Create a new GCP project and create an App Engine application inside this new project. Specify asia-northeast1 as the region to serve your application.

Here's why the other options are not suitable:

1. **Change the default region property setting in the existing GCP project to asia-northeast1:**
   - This option changes the default region setting for the entire GCP project, which affects other resources as well, not just the App Engine application. It does not allow for specific regional configuration of individual App Engine services.

2. **Change the region property setting in the existing App Engine application from us-central to asia-northeast1:**
   - App Engine does not allow changing the region of an existing application once it has been set. Therefore, this option is not feasible because you cannot alter the region setting of an already deployed App Engine application.

3. **Create a second App Engine application in the existing GCP project and specify asia-northeast1 as the region to serve your application:**
   - You cannot change an app's region after you set it.

Therefore, the recommended approach is to create a new GCP project specifically for the App Engine application that needs to be served from the asia-northeast1 region. This keeps your deployments clean, separate, and aligned with Google Cloud's best practices for regional deployment management.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### Several employees at your company have been creating projects with Cloud Platform and paying for it with their personal credit cards, which the company reimburses. The company wants to centralize all these projects under a single, new billing account. What should you do?

- [ ] Contact [email protected] with your bank account details and request a corporate billing account for your company.
- [ ] Create a ticket with Google Support and wait for their call to share your credit card details over the phone.
- [ ] In the Google Platform Console, go to the Resource Manage and move all projects to the root Organization.
- [x] In the Google Cloud Platform Console, create a new billing account and set up a payment method.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You have a Dockerfile that you need to deploy on Kubernetes Engine. What should you do?

- [ ] Use kubectl app deploy `<dockerfilename>`.
- [ ] Use gcloud app deploy `<dockerfilename>`.
- [x] Create a docker image from the Dockerfile and upload it to Container Registry. Create a Deployment YAML file to point to that image. Use kubectl to create the deployment with that file.
- [ ] Create a docker image from the Dockerfile and upload it to Cloud Storage. Create a Deployment YAML file to point to that image. Use kubectl to create the deployment with that file.

The correct approach to deploy a Dockerfile on Kubernetes Engine is:

- [3] **Create a docker image from the Dockerfile and upload it to Container Registry. Create a Deployment YAML file to point to that image. Use kubectl to create the deployment with that file.**

Here's why this option is the correct choice:

- **Create a docker image:** You need to build a Docker image from your Dockerfile. This involves using the `docker build` command locally on your machine where the Dockerfile is located.

- **Upload it to Container Registry:** Once the Docker image is built, you should upload it to Google Container Registry (GCR). GCR is a managed Docker registry service provided by Google Cloud Platform where you can store and manage your Docker images.

- **Create a Deployment YAML file:** Kubernetes uses YAML configuration files to define resources such as Deployments, Services, and Pods. You need to create a Deployment YAML file that specifies the details of your application deployment, including the Docker image location in GCR.

- **Use kubectl to create the deployment:** Finally, you use `kubectl` (Kubernetes command-line tool) to apply the Deployment YAML file to your Kubernetes cluster. This command instructs Kubernetes to create the necessary resources (in this case, a Deployment) based on your configuration.

Now, let's briefly explain why the other options are incorrect:

- [1] **Use kubectl app deploy `<dockerfilename>`:**
  - There is no direct `kubectl` command like `kubectl app deploy` for deploying Dockerfiles. Kubernetes deployments are configured using YAML files that reference Docker images.

- [2] **Use gcloud app deploy `<dockerfilename>`:**
  - `gcloud app deploy` is used for deploying applications to Google App Engine, not Kubernetes Engine. It's not suitable for deploying Docker images to Kubernetes.

- [4] **Create a docker image from the Dockerfile and upload it to Cloud Storage. Create a Deployment YAML file to point to that image. Use kubectl to create the deployment with that file:**
  - Docker images are typically stored in a Docker registry like Google Container Registry (GCR), not in Cloud Storage. Kubernetes directly pulls Docker images from container registries, not Cloud Storage buckets.

Therefore, option [3] is the correct and recommended approach for deploying a Dockerfile on Kubernetes Engine.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You have a project for your App Engine application that serves a development environment. The required testing has succeeded and you want to create a new project to serve as your production environment. What should you do?

- [x] Use gcloud to create the new project, and then deploy your application to the new project.
- [ ] Use gcloud to create the new project and to copy the deployed application to the new project.
- [ ] Create a Deployment Manager configuration file that copies the current App Engine deployment into a new project.
- [ ] Deploy your application again using gcloud and specify the project parameter with the new project name to create the new project.

For creating a new project to serve as your App Engine production environment after successful testing in the development environment, the recommended approach is:

- [1] **Use gcloud to create the new project, and then deploy your application to the new project.**

Here’s why this option is the correct choice:

- **Creating the new project first:** Using `gcloud` to create a new project ensures that you have a dedicated environment separate from your development project, specifically tailored for production use.
  
- **Deploying your application:** Once the project is created, you can deploy your application using `gcloud app deploy` or similar commands. This allows you to specify the new project where the application should be deployed, ensuring that it is deployed correctly in the production environment.

Now, let's briefly explain why the other options are not the best choices:

- [2] **Use gcloud to create the new project and to copy the deployed application to the new project.**
  - While creating the project first is correct, "copying" the deployed application isn't a straightforward process via `gcloud`. You typically deploy applications to a new project rather than copying them between projects.

- [3] **Create a Deployment Manager configuration file that copies the current App Engine deployment into a new project.**
  - Deployment Manager is used for managing infrastructure deployments, templates, and configurations. It’s not typically used to copy or migrate entire applications between projects.

- [4] **Deploy your application again using gcloud and specify the project parameter with the new project name to create the new project.**
  - This option is confusing because deploying an application doesn't create a new project. Projects are created separately using `gcloud projects create` or through the GCP Console.

Therefore, option [1] is the correct choice as it aligns with best practices for creating a new production environment project and deploying your application to that project using `gcloud` commands.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You are building an application that will run in your data center. The application will use Google Cloud Platform (GCP) services like AutoML. You created a service account that has appropriate access to AutoML. You need to enable authentication to the APIs from your on-premises environment. What should you do?

- [ ] Use service account credentials in your on-premises application.
- [x] Use gcloud to create a key file for the service account that has appropriate permissions.
- [ ] Set up direct interconnect between your data center and Google Cloud Platform to enable authentication for your on-premises applications.
- [ ] Go to the IAM & admin console, grant a user account permissions similar to the service account permissions, and use this user account for authentication from your data center.

The correct approach to enable authentication to Google Cloud Platform (GCP) APIs from your on-premises environment, using a service account that has appropriate access to AutoML, is to **use `gcloud` to create a key file for the service account that has appropriate permissions**.

Here's why this approach is correct:

1. **Service Account Credentials**: Service accounts are a recommended way to authenticate applications and services when interacting with GCP APIs. They provide a mechanism to securely authenticate and authorize API requests.

2. **Creating a Key File**: When you create a service account key file using `gcloud`, you obtain a JSON file that contains the private key and other necessary information. This key file is used to authenticate API requests made from your application running in the on-premises environment.

3. **Using the Key File**: Your application can then use this key file to authenticate with GCP APIs, including AutoML. The key file is loaded by your application to obtain access tokens, which are then used to authenticate API requests.

Therefore, the correct step in this scenario is to use `gcloud` to generate a key file for your service account and then configure your on-premises application to use this key file for authentication when accessing AutoML or other GCP services.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You host a static website on Cloud Storage. Recently, you began to include links to PDF files on this site. Currently, when users click on the links to these PDF files, their browsers prompt them to save the file onto their local system. Instead, you want the clicked PDF files to be displayed within the browser window directly, without prompting the user to save the file locally. What should you do?

- [ ] Enable Cloud CDN on the website frontend.
- [ ] Enable 'Share publicly' on the PDF file objects.
- [x] Set Content-Type metadata to application/pdf on the PDF file objects.
- [ ] Add a label to the storage bucket with a key of Content-Type and value of application/pdf.

To ensure that PDF files hosted on your static website in Cloud Storage are displayed directly within the browser window instead of prompting the user to save them locally, you should:

**[3] Set Content-Type metadata to application/pdf on the PDF file objects.**

Here’s why this is the correct approach:

- **Content-Type Metadata**: When serving files from Cloud Storage, the browser uses the `Content-Type` header to determine how to handle the file. For PDF files, the correct `Content-Type` should be `application/pdf`. If this metadata is set correctly on your PDF file objects in Cloud Storage, the browser will interpret them as PDF documents and attempt to display them inline, rather than triggering a download prompt.

- **Cloud Storage Setup**: Ensure that each PDF file stored in your Cloud Storage bucket has its `Content-Type` metadata set to `application/pdf`. You can set this metadata during file upload or update it later using the Cloud Console, gsutil command-line tool, or Cloud Storage client libraries.

**Why the other options are incorrect:**

- **[1] Enable Cloud CDN on the website frontend**: Cloud CDN improves website performance by caching content closer to users. While it can speed up delivery, it does not control how files are displayed in the browser.

- **[2] Enable 'Share publicly' on the PDF file objects**: Enabling public access is necessary for users to view the files, but it doesn't influence how the browser handles the content-type or display behavior.

- **[4] Add a label to the storage bucket with a key of Content-Type and value of application/pdf**: Labels are used for organizational purposes and do not affect how files are served or displayed by the browser.

Therefore, by setting the `Content-Type` metadata to `application/pdf` on your PDF file objects in Cloud Storage, you ensure that users can view the PDF files directly in their browser windows when clicking on links from your static website.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You have an application that looks for its licensing server on the IP 10.0.3.21. You need to deploy the licensing server on Compute Engine. You do not want to change the configuration of the application and want the application to be able to reach the licensing server. What should you do?

- [x] Reserve the IP 10.0.3.21 as a static internal IP address using gcloud and assign it to the licensing server.
- [ ] Reserve the IP 10.0.3.21 as a static public IP address using gcloud and assign it to the licensing server.
- [ ] Use the IP 10.0.3.21 as a custom ephemeral IP address and assign it to the licensing server.
- [ ] Start the licensing server with an automatic ephemeral IP address, and then promote it to a static internal IP address.

To ensure that your application can reach the licensing server at the specific IP address (10.0.3.21) without changing the application's configuration, you should:

**[1] Reserve the IP 10.0.3.21 as a static internal IP address using gcloud and assign it to the licensing server.**

Here’s why this option is correct:

- **Static Internal IP Address**: By reserving 10.0.3.21 as a static internal IP address, you ensure that the IP address remains consistent and does not change over time. This is crucial because your application is configured to reach the licensing server at this specific IP address.

- **Using gcloud**: Google Cloud Platform (GCP) allows you to reserve static internal IP addresses for Compute Engine instances. You can do this using the `gcloud` command-line tool or through the Google Cloud Console.

- **No Configuration Change Needed**: Since your application expects to find the licensing server at 10.0.3.21, using a static internal IP address ensures that the application can reliably communicate with the server without needing any configuration changes.

**Why the other options are incorrect:**

- **[2] Reserve the IP 10.0.3.21 as a static public IP address using gcloud and assign it to the licensing server**: This is incorrect because the IP address 10.0.3.21 is an internal IP address, not a public one. Assigning it as a static public IP address would not align with its intended use within an internal network.

- **[3] Use the IP 10.0.3.21 as a custom ephemeral IP address and assign it to the licensing server**: Ephemeral IP addresses are not suitable for this scenario because they can change over time, which would cause connectivity issues for your application expecting a fixed IP address.

- **[4] Start the licensing server with an automatic ephemeral IP address, and then promote it to a static internal IP address**: This option involves starting with an ephemeral IP address and then promoting it to static, but it doesn't ensure that the specific IP address 10.0.3.21 is reserved. Moreover, promoting from ephemeral to static IP address is a different process and doesn't directly address the requirement of maintaining the specific IP address.

Therefore, **reserving 10.0.3.21 as a static internal IP address** is the correct approach to ensure that your application can reliably reach the licensing server without requiring any changes to the application's existing configuration.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You are deploying an application to App Engine. You want the number of instances to scale based on request rate. You need at least 3 unoccupied instances at all times. Which scaling type should you use?

- [ ] Manual Scaling with 3 instances.
- [ ] Basic Scaling with min_instances set to 3.
- [ ] Basic Scaling with max_instances set to 3.
- [x] Automatic Scaling with min_idle_instances set to 3.

To deploy an application to App Engine with the number of instances scaling based on request rate and ensuring at least 3 unoccupied instances at all times, you should use:

**[4] Automatic Scaling with min_idle_instances set to 3.**

Here's why this option is the most suitable:

- **Automatic Scaling with min_idle_instances set to 3**: This setting ensures that there are always at least 3 idle instances available to handle incoming requests. This allows the system to quickly respond to spikes in traffic by keeping a buffer of unoccupied instances, while also scaling up and down based on the actual request rate.

The reasons why the other options are less suitable:

**[1] Manual Scaling with 3 instances**:
- Manual scaling with a fixed number of instances does not provide the flexibility to scale based on the request rate. It keeps a constant number of instances running regardless of the traffic, which can be inefficient.

**[2] Basic Scaling with min_instances set to 3**:
- Basic scaling is designed to start and stop instances based on the request rate, but it does not maintain idle instances. Setting `min_instances` to 3 would ensure at least 3 instances are running, but they may not be unoccupied.

**[3] Basic Scaling with max_instances set to 3**:
- Setting `max_instances` to 3 in basic scaling would limit the number of instances to 3, which can lead to inadequate handling of high traffic if more than 3 instances are needed. This does not ensure the presence of idle instances.

Therefore, **Automatic Scaling with min_idle_instances set to 3** is the best choice to meet your requirements of scaling based on request rate and maintaining at least 3 unoccupied instances at all times.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You are the project owner of a GCP project and want to delegate control to colleagues to manage buckets and files in Cloud Storage. You want to follow Google-recommended practices. Which IAM roles should you grant your colleagues?

- [ ] Project Editor.
- [x] Storage Admin.
- [ ] Storage Object Admin.
- [ ] Storage Object Creator.

To delegate control to your colleagues to manage buckets and files in Cloud Storage while following Google-recommended practices, you should grant them the:

**[2] Storage Admin** role.

Here's why this option is the most suitable:

- **Storage Admin**: This role allows full control over Cloud Storage resources. It grants permissions to create, update, and delete buckets and objects, effectively allowing comprehensive management of both buckets and files. This aligns with your requirement to delegate control over buckets and files.

The reasons why the other options are less suitable:

**[1] Project Editor**:
- This role provides broad permissions across many resources in the project, not just Cloud Storage. It’s more than what’s needed for managing Cloud Storage and could be too permissive.

**[3] Storage Object Admin**:
- This role allows full control over objects within Cloud Storage buckets, but does not provide permissions to manage the buckets themselves (e.g., creating or deleting buckets).

**[4] Storage Object Creator**:
- This role allows users to create new objects in buckets, but does not allow them to read, update, or delete existing objects, nor does it allow them to manage buckets.

Therefore, granting the **Storage Admin** role to your colleagues will provide them with the necessary permissions to manage both Cloud Storage buckets and the files within them, aligning with Google-recommended practices.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You need to update a deployment in Deployment Manager without any resource downtime in the deployment. Which command should you use?

- [ ] gcloud deployment-manager deployments create –config <deployment-config-path>.
- [x] gcloud deployment-manager deployments update –config <deployment-config-path>.
- [ ] gcloud deployment-manager resources create –config <deployment-config-path>.
- [ ] gcloud deployment-manager resources update –config <deployment-config-path>.

To update a deployment in Deployment Manager without any resource downtime, you should use the command:

**[2] gcloud deployment-manager deployments update --config <deployment-config-path>.**

Here's why this option is the most appropriate:

- **`gcloud deployment-manager deployments update`**: This command updates an existing deployment based on the specified configuration file. The `update` operation in Deployment Manager is designed to handle updates to your resources without causing downtime, following the best practices for resource updates and managing dependencies.

The reasons why the other options are less suitable:

**[1] gcloud deployment-manager deployments create --config <deployment-config-path>.**
- This command is used to create a new deployment, not update an existing one. It cannot be used to make changes to an already deployed set of resources.

**[3] gcloud deployment-manager resources create --config <deployment-config-path>.**
- This command does not exist in the context of Deployment Manager. Resources are managed within deployments, and individual resource creation is not typically handled this way.

**[4] gcloud deployment-manager resources update --config <deployment-config-path>.**
- This command does not exist either. Updates are managed at the deployment level, not the individual resource level, within Deployment Manager.

Therefore, the correct command to use for updating a deployment without causing any resource downtime is:

**[2] gcloud deployment-manager deployments update --config <deployment-config-path>.**

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You are running an application on multiple Virtual Machines within a Managed Instance Group and have autoscaling enabled. The autoscaling policy is configured so that additional instances are added to the group if the CPU utilization of instances goes above 80%. VMs are added until the instance group reaches its maximum limit of five VMs or until CPU utilization of instances lowers to 80%. The initial delay for HTTP health checks against the instances is set to 30 seconds. The Virtual Machine instances take around three minutes to become available for users. You observe that when the instance group autoscales, it adds more instances then necessary to support the levels of end-user traffic. You want to properly maintain instance group sizes when autoscaling. What should you do?

- [ ] Set the maximum number of instances to 1.
- [ ] Decrease the maximum number of instances to 3.
- [ ] Use a TCP health check instead of an HTTP health check.
- [x] Increase the initial delay of the HTTP health check to 200 seconds.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You have 32 GB of data in a single file that you need to upload to a Nearline Storage bucket. The WAN connection you are using is rated at 1 Gbps, and you are the only one on the connection. You want to use as much of the rated 1 Gbps as possible to transfer the file rapidly. How should you upload the file?

- [ ] Use the GCP Console to transfer the file instead of gsutil.
- [x] Enable parallel composite uploads using gsutil on the file transfer.
- [ ] Decrease the TCP window size on the machine initiating the transfer.
- [ ] Change the storage class of the bucket from Nearline to Multi-Regional.

The best option to maximize the use of your 1 Gbps connection and transfer the 32 GB file rapidly is:

**[2] Enable parallel composite uploads using gsutil on the file transfer.**

Here's why this option is the most suitable:

- **Parallel Composite Uploads**: gsutil supports parallel composite uploads, which allows you to split a large file into smaller, more manageable chunks and upload them simultaneously. This can significantly increase the upload speed, especially when using a high-bandwidth connection like your 1 Gbps WAN connection.

The reasons why the other options are less suitable:

**[1] Use the GCP Console to transfer the file instead of gsutil.**
- While the GCP Console is user-friendly, it does not offer the same level of control and optimization for large file transfers as gsutil, especially with parallel uploads.

**[3] Decrease the TCP window size on the machine initiating the transfer.**
- Decreasing the TCP window size would likely reduce the throughput, not increase it. Larger TCP window sizes are generally better for high-bandwidth, high-latency connections, as they allow more data to be in transit before requiring an acknowledgment.

**[4] Change the storage class of the bucket from Nearline to Multi-Regional.**
- Changing the storage class of the bucket will not impact the upload speed. Storage classes are primarily about the cost and availability characteristics of the data once it is stored, not the speed of data transfer to the bucket.

Therefore, enabling parallel composite uploads with gsutil is the best method to utilize your 1 Gbps connection effectively and transfer your 32 GB file quickly.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You deployed an App Engine application using gcloud app deploy, but it did not deploy to the intended project. You want to find out why this happened and where the application deployed. What should you do?

- [ ] Check the app.yaml file for your application and check project settings.
- [ ] Check the web-application.xml file for your application and check project settings.
- [ ] Go to Deployment Manager and review settings for deployment of applications.
- [x] Go to Cloud Shell and run gcloud config list to review the Google Cloud configuration used for deployment.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You want to verify the IAM users and roles assigned within a GCP project named my-project. What should you do?

- [ ] Run gcloud iam roles list. Review the output section.
- [ ] Run gcloud iam service-accounts list. Review the output section.
- [x] Navigate to the project and then to the IAM section in the GCP Console. Review the members and roles.
- [ ] Navigate to the project and then to the Roles section in the GCP Console. Review the roles and status.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You need to select and configure compute resources for a set of batch processing jobs. These jobs take around 2 hours to complete and are run nightly. You want to minimize service costs. What should you do?

- [ ] Select Google Kubernetes Engine. Use a single-node cluster with a small instance type.
- [ ] Select Google Kubernetes Engine. Use a three-node cluster with micro instance types.
- [x] Select Compute Engine. Use preemptible VM instances of the appropriate standard machine type.
- [ ] Select Compute Engine. Use VM instance types that support micro bursting.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You want to select and configure a cost-effective solution for relational data on Google Cloud Platform. You are working with a small set of operational data in one geographic location. You need to support point-in-time recovery. What should you do?

- [x] Select Cloud SQL (MySQL). Verify that the enable binary logging option is selected.
- [ ] Select Cloud SQL (MySQL). Select the create failover replicas option.
- [ ] Select Cloud Spanner. Set up your instance with 2 nodes.
- [ ] Select Cloud Spanner. Set up your instance as multi-regional.

Given your requirements—a small set of operational data, a single geographic location, and the need for point-in-time recovery—the best option would be:

**[1] Select Cloud SQL (MySQL). Verify that the enable binary logging option is selected.**

Here's why this option is the best fit:

- **Cloud SQL (MySQL)**: Cloud SQL is a fully-managed relational database service for MySQL, PostgreSQL, and SQL Server. It is cost-effective and well-suited for smaller datasets and operational workloads.
- **Enable Binary Logging**: Enabling binary logging in MySQL is crucial for point-in-time recovery. Binary logs contain a record of all changes to the database, allowing you to restore the database to a specific point in time.

The reasons why the other options are less suitable:

**[2] Select Cloud SQL (MySQL). Select the create failover replicas option.**
- While creating failover replicas increases availability and reliability, it does not directly address point-in-time recovery, which is your primary requirement.

**[3] Select Cloud Spanner. Set up your instance with 2 nodes.**
- Cloud Spanner is a powerful, fully managed, horizontally scalable database service. However, it is designed for high-availability and high-throughput applications, making it more complex and expensive than necessary for a small set of operational data.

**[4] Select Cloud Spanner. Set up your instance as multi-regional.**
- Setting up a Cloud Spanner instance as multi-regional further increases complexity and cost. It is intended for applications requiring global availability and consistency, which exceeds your current needs.

Therefore, **option [1]** is the most cost-effective and suitable solution for your requirements.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You are hosting an application on bare-metal servers in your own data center. The application needs access to Cloud Storage. However, security policies prevent the servers hosting the application from having public IP addresses or access to the internet. You want to follow Google-recommended practices to provide the application with access to Cloud Storage. What should you do?

- [ ] 1. Use nslookup to get the IP address for storage.googleapis.com. 2. Negotiate with the security team to be able to give a public IP address to the servers. 3. Only allow egress traffic from those servers to the IP addresses for storage.googleapis.com.
- [ ] 1. Using Cloud VPN, create a VPN tunnel to a Virtual Private Cloud (VPC) in Google Cloud. 2. In this VPC, create a Compute Engine instance and install the Squid proxy server on this instance. 3. Configure your servers to use that instance as a proxy to access Cloud Storage.
- [ ] 1. Use Migrate for Compute Engine (formerly known as Velostrata) to migrate those servers to Compute Engine. 2. Create an internal load balancer (ILB) that uses storage.googleapis.com as backend. 3. Configure your new instances to use this ILB as proxy.
- [x] 1. Using Cloud VPN or Interconnect, create a tunnel to a VPC in Google Cloud. 2. Use Cloud Router to create a custom route advertisement for 199.36.153.4/30. Announce that network to your on-premises network through the VPN tunnel. 3. In your on-premises network, configure your DNS server to resolve *.googleapis.com as a CNAME to restricted.googleapis.com.

To provide your application with access to Cloud Storage while following Google-recommended practices and adhering to your security policies, you should choose:

**[4] 1. Using Cloud VPN or Interconnect, create a tunnel to a VPC in Google Cloud. 2. Use Cloud Router to create a custom route advertisement for 199.36.153.4/30. Announce that network to your on-premises network through the VPN tunnel. 3. In your on-premises network, configure your DNS server to resolve *.googleapis.com as a CNAME to restricted.googleapis.com.**

Here's why this option is correct:

- **Cloud VPN or Interconnect**: Establishing a VPN or Interconnect tunnel provides a secure connection between your on-premises network and Google Cloud, allowing private communication without exposing your servers to the public internet.
- **Custom Route Advertisement**: By creating a custom route advertisement for 199.36.153.4/30, you can direct traffic destined for Google's restricted VIP range for private access to Google APIs, which includes Cloud Storage.
- **DNS Configuration**: Configuring your DNS server to resolve `*.googleapis.com` as a CNAME to `restricted.googleapis.com` ensures that requests to Google Cloud APIs, including Cloud Storage, are directed through the restricted VIP range, maintaining security and compliance with your no-public-IP policy.

The reasons why the other options are incorrect:

**[1] 1. Use nslookup to get the IP address for storage.googleapis.com. 2. Negotiate with the security team to be able to give a public IP address to the servers. 3. Only allow egress traffic from those servers to the IP addresses for storage.googleapis.com.**
- This option involves giving your servers public IP addresses, which violates your security policy.

**[2] 1. Using Cloud VPN, create a VPN tunnel to a Virtual Private Cloud (VPC) in Google Cloud. 2. In this VPC, create a Compute Engine instance and install the Squid proxy server on this instance. 3. Configure your servers to use that instance as a proxy to access Cloud Storage.**
- While this solution avoids public IP addresses, it adds unnecessary complexity by introducing a proxy server, which is not the recommended approach by Google for accessing Cloud Storage.

**[3] 1. Use Migrate for Compute Engine (formerly known as Velostrata) to migrate those servers to Compute Engine. 2. Create an internal load balancer (ILB) that uses storage.googleapis.com as backend. 3. Configure your new instances to use this ILB as proxy.**
- Migrating your servers to Compute Engine is an extensive change and may not be feasible or necessary. Additionally, using an internal load balancer in this way is not a standard approach for accessing Cloud Storage.

Therefore, **option [4]** provides a secure, compliant, and efficient way to access Cloud Storage from your on-premises servers without public IP addresses.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### Your company has a Google Cloud Platform project that uses BigQuery for data warehousing. Your data science team changes frequently and has few members. You need to allow members of this team to perform queries. You want to follow Google-recommended practices. What should you do?

- [ ] 1. Create an IAM entry for each data scientist's user account. 2. Assign the BigQuery jobUser role to the group.
- [ ] 1. Create an IAM entry for each data scientist's user account. 2. Assign the BigQuery dataViewer user role to the group.
- [x] 1. Create a dedicated Google group in Cloud Identity. 2. Add each data scientist's user account to the group. 3. Assign the BigQuery jobUser role to the group.
- [ ] 1. Create a dedicated Google group in Cloud Identity. 2. Add each data scientist's user account to the group. 3. Assign the BigQuery dataViewer user role to the group.

To allow members of the data science team to perform queries in BigQuery following Google-recommended practices, the best approach is:

**[3] 1. Create a dedicated Google group in Cloud Identity. 2. Add each data scientist's user account to the group. 3. Assign the BigQuery jobUser role to the group.**

Here’s why this option is correct:

- **Dedicated Google Group**: Creating a Google group in Cloud Identity simplifies the management of user permissions, especially when team membership changes frequently. You only need to update the group membership instead of updating IAM roles individually.
- **BigQuery jobUser Role**: The BigQuery jobUser role grants permissions to run jobs (queries) in BigQuery, which is precisely what the data science team needs to perform their work.
- **Assigning Roles to the Group**: Assigning the BigQuery jobUser role to the group ensures that all current and future members of the group automatically inherit the necessary permissions to run queries in BigQuery.

The reasons why the other options are incorrect:

**[1] 1. Create an IAM entry for each data scientist's user account. 2. Assign the BigQuery jobUser role to the group.**
- This option doesn’t make use of a Google group for managing permissions, which adds administrative overhead. Updating IAM entries for each user individually is less efficient than managing a single group.

**[2] 1. Create an IAM entry for each data scientist's user account. 2. Assign the BigQuery dataViewer user role to the group.**
- The BigQuery dataViewer role only grants permissions to view datasets and tables, not to run queries. Data scientists need to run queries, so this role is insufficient.

**[4] 1. Create a dedicated Google group in Cloud Identity. 2. Add each data scientist's user account to the group. 3. Assign the BigQuery dataViewer user role to the group.**
- Similar to option [2], the BigQuery dataViewer role is insufficient because it does not grant permissions to run queries, which is the primary requirement for the data science team.

Therefore, **option [3]** is the most efficient and recommended approach to allow data scientists to perform queries in BigQuery while minimizing administrative overhead and ensuring proper permission management.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You are given a project with a single Virtual Private Cloud (VPC) and a single subnetwork in the us-central1 region. There is a Compute Engine instance hosting an application in this subnetwork. You need to deploy a new instance in the same project in the europe-west1 region. This new instance needs access to the application. You want to follow Google-recommended practices. What should you do?

- [x] 1. Create a subnetwork in the same VPC, in europe-west1. 2. Create the new instance in the new subnetwork and use the first instance's private address as the endpoint.
- [ ] 1. Create a VPC and a subnetwork in europe-west1. 2. Expose the application with an internal load balancer. 3. Create the new instance in the new subnetwork and use the load balancer's address as the endpoint.
- [ ] 1. Create a subnetwork in the same VPC, in europe-west1. 2. Use Cloud VPN to connect the two subnetworks. 3. Create the new instance in the new subnetwork and use the first instance's private address as the endpoint.
- [ ] 1. Create a VPC and a subnetwork in europe-west1. 2. Peer the 2 VPCs. 3. Create the new instance in the new subnetwork and use the first instance's private address as the endpoint.

To deploy a new instance in the europe-west1 region and allow it to access the application on an existing instance in the us-central1 region, while following Google-recommended practices, you should choose:

**[1] 1. Create a subnetwork in the same VPC, in europe-west1. 2. Create the new instance in the new subnetwork and use the first instance's private address as the endpoint.**

Here's why this option is correct:

- **Same VPC, Different Subnetwork**: By creating a new subnetwork in the same VPC, you ensure that both instances (in different regions) are part of the same VPC. This simplifies networking and security management, as they can communicate with each other using their internal IP addresses.
- **Regional Subnetworks**: Google Cloud allows creating regional subnetworks, which means you can have a subnetwork in us-central1 and another in europe-west1 within the same VPC. Instances in different regions but the same VPC can communicate internally without requiring VPN or VPC peering.

The reasons why the other options are incorrect:

**[2] 1. Create a VPC and a subnetwork in europe-west1. 2. Expose the application with an internal load balancer. 3. Create the new instance in the new subnetwork and use the load balancer's address as the endpoint.**
- Creating a new VPC is unnecessary and adds complexity. Exposing the application with an internal load balancer is also more complex than needed for simple internal communication.

**[3] 1. Create a subnetwork in the same VPC, in europe-west1. 2. Use Cloud VPN to connect the two subnetworks. 3. Create the new instance in the new subnetwork and use the first instance's private address as the endpoint.**
- Using Cloud VPN to connect subnetworks within the same VPC is unnecessary. Subnetworks within the same VPC can communicate directly without a VPN.

**[4] 1. Create a VPC and a subnetwork in europe-west1. 2. Peer the 2 VPCs. 3. Create the new instance in the new subnetwork and use the first instance's private address as the endpoint.**
- Creating and peering two VPCs adds unnecessary complexity. It's simpler and more efficient to use the same VPC with different subnetworks in different regions.

Therefore, **option [1]** is the simplest and most efficient approach that follows Google-recommended practices for deploying a new instance in a different region while allowing it to access an application on an existing instance.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You are building a pipeline to process time-series data. Which Google Cloud Platform services should you put in boxes 1,2,3, and 4?

![Google Cloud Platform services](images/pipeline.jpeg)

- [ ] Cloud Pub/Sub, Cloud Dataflow, Cloud Datastore, BigQuery.
- [ ] Firebase Messages, Cloud Pub/Sub, Cloud Spanner, BigQuery.
- [ ] Cloud Pub/Sub, Cloud Storage, BigQuery, Cloud Bigtable.
- [x] Cloud Pub/Sub, Cloud Dataflow, Cloud Bigtable, BigQuery.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### For analysis purposes, you need to send all the logs from all of your Compute Engine instances to a BigQuery dataset called platform-logs. You have already installed the Cloud Logging agent on all the instances. You want to minimize cost. What should you do?

- [ ] 1. Give the BigQuery Data Editor role on the platform-logs dataset to the service accounts used by your instances. 2. Update your instances' metadata to add the following value: logs-destination: bq://platform-logs.
- [ ] 1. In Cloud Logging, create a logs export with a Cloud Pub/Sub topic called logs as a sink. 2. Create a Cloud Function that is triggered by messages in the logs topic. 3. Configure that Cloud Function to drop logs that are not from Compute Engine and to insert Compute Engine logs in the platform-logs dataset.
- [x] 1. In Cloud Logging, create a filter to view only Compute Engine logs. 2. Click Create Export. 3. Choose BigQuery as Sink Service, and the platform-logs dataset as Sink Destination.
- [ ] 1. Create a Cloud Function that has the BigQuery User role on the platform-logs dataset. 2. Configure this Cloud Function to create a BigQuery Job that executes this query: INSERT INTO dataset.platform-logs (timestamp, log) SELECT timestamp, log FROM compute.logs WHERE timestamp > DATE_SUB(CURRENT_DATE(), INTERVAL 1 DAY) 3. Use Cloud Scheduler to trigger this Cloud Function once a day.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You want to deploy an application on Cloud Run that processes messages from a Cloud Pub/Sub topic. You want to follow Google-recommended practices. What should you do?

- [ ] 1. Create a Cloud Function that uses a Cloud Pub/Sub trigger on that topic. 2. Call your application on Cloud Run from the Cloud Function for every message.
- [ ] 1. Grant the Pub/Sub Subscriber role to the service account used by Cloud Run. 2. Create a Cloud Pub/Sub subscription for that topic. 3. Make your application pull messages from that subscription.
- [x] 1. Create a service account. 2. Give the Cloud Run Invoker role to that service account for your Cloud Run application. 3. Create a Cloud Pub/Sub subscription that uses that service account and uses your Cloud Run application as the push endpoint.
- [ ] 1. Deploy your application on Cloud Run on GKE with the connectivity set to Internal. 2. Create a Cloud Pub/Sub subscription for that topic. 3. In the same Google Kubernetes Engine cluster as your application, deploy a container that takes the messages and sends them to your application.

To deploy an application on Cloud Run that processes messages from a Cloud Pub/Sub topic, following Google-recommended practices, the best approach is:

**[3] 1. Create a service account. 2. Give the Cloud Run Invoker role to that service account for your Cloud Run application. 3. Create a Cloud Pub/Sub subscription that uses that service account and uses your Cloud Run application as the push endpoint.**

Here's why this option is correct:

- **Service Account and Cloud Run Invoker Role**: Creating a service account and giving it the Cloud Run Invoker role ensures that only authorized services can invoke your Cloud Run application.
- **Cloud Pub/Sub Subscription with Push Endpoint**: Configuring a Cloud Pub/Sub subscription to use your Cloud Run application as a push endpoint allows Pub/Sub to push messages directly to your application. This is a standard and efficient method for integrating Pub/Sub with Cloud Run.

The reasons why the other options are incorrect:

**[1] 1. Create a Cloud Function that uses a Cloud Pub/Sub trigger on that topic. 2. Call your application on Cloud Run from the Cloud Function for every message.**
- This adds unnecessary complexity by introducing an additional Cloud Function. It's more straightforward and efficient to use a direct Pub/Sub to Cloud Run integration.

**[2] 1. Grant the Pub/Sub Subscriber role to the service account used by Cloud Run. 2. Create a Cloud Pub/Sub subscription for that topic. 3. Make your application pull messages from that subscription.**
- This approach involves pulling messages from Pub/Sub, which is less efficient than using a push subscription. Cloud Run applications are better suited to handle push-based message delivery.

**[4] 1. Deploy your application on Cloud Run on GKE with the connectivity set to Internal. 2. Create a Cloud Pub/Sub subscription for that topic. 3. In the same Google Kubernetes Engine cluster as your application, deploy a container that takes the messages and sends them to your application.**
- This approach is overly complex, involving additional infrastructure and configuration that is unnecessary for simply processing Pub/Sub messages with a Cloud Run application.

Therefore, **option [3]** is the recommended practice for deploying a Cloud Run application that processes messages from a Cloud Pub/Sub topic efficiently and securely.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### Your projects incurred more costs than you expected last month. Your research reveals that a development GKE container emitted a huge number of logs, which resulted in higher costs. You want to disable the logs quickly using the minimum number of steps. What should you do?

- [x] 1. Go to the Logs ingestion window in Stackdriver Logging, and disable the log source for the GKE container resource.
- [ ] 1. Go to the Logs ingestion window in Stackdriver Logging, and disable the log source for the GKE Cluster Operations resource.
- [ ] 1. Go to the GKE console, and delete existing clusters. 2. Recreate a new cluster. 3. Clear the option to enable legacy Stackdriver Logging.
- [ ] 1. Go to the GKE console, and delete existing clusters. 2. Recreate a new cluster. 3. Clear the option to enable legacy Stackdriver Monitoring.

To quickly disable logs for a GKE container using the minimum number of steps, the correct option is:

**[1] Go to the Logs ingestion window in Stackdriver Logging, and disable the log source for the GKE container resource.**

Here’s why this option is correct:

- **Logs ingestion window in Stackdriver Logging**: This is where you manage which log sources are enabled for ingestion into Stackdriver Logging.
- **Disable the log source for the GKE container resource**: By disabling the log source specifically for the GKE container emitting the huge number of logs, you stop the logs from being ingested and therefore reduce the associated costs quickly and directly.

The reasons why the other options are incorrect:

**[2] Go to the Logs ingestion window in Stackdriver Logging, and disable the log source for the GKE Cluster Operations resource.**
- This option targets GKE Cluster Operations logs, which are different from application or container logs. Disabling these logs would not address the issue caused by the GKE container emitting excessive logs.

**[3] Go to the GKE console, and delete existing clusters. Recreate a new cluster. Clear the option to enable legacy Stackdriver Logging.**
- Deleting and recreating the entire GKE cluster is an extreme and unnecessary step for simply disabling logs for a specific container. It involves significant downtime and operational overhead.

**[4] Go to the GKE console, and delete existing clusters. Recreate a new cluster. Clear the option to enable legacy Stackdriver Monitoring.**
- Similar to option [3], this involves deleting and recreating the GKE cluster, which is not needed to disable logs for a specific container. It also mentions Stackdriver Monitoring, which is different from Stackdriver Logging.

Therefore, **option [1]** is the correct and efficient choice to quickly address the issue of excessive logging costs from a specific GKE container.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You've deployed a microservice called myapp1 to a Google Kubernetes Engine cluster using the YAML file specified below. You need to refactor this configuration so that the database password is not stored in plain text. You want to follow Google-recommended practices. What should you do?

![YAML of microservice myapp1](images/yaml.jpg)

- [ ] Store the database password inside the Docker image of the container, not in the YAML file.
- [x] Store the database password inside a Secret object. Modify the YAML file to populate the DB_PASSWORD environment variable from the Secret.
- [ ] Store the database password inside a ConfigMap object. Modify the YAML file to populate the DB_PASSWORD environment variable from the ConfigMap.
- [ ] Store the database password in a file inside a Kubernetes persistent volume, and use a persistent volume claim to mount the volume to the container.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You have an application running in Google Kubernetes Engine (GKE) with cluster autoscaling enabled. The application exposes a TCP endpoint. There are several replicas of this application. You have a Compute Engine instance in the same region, but in another Virtual Private Cloud (VPC), called gce-network, that has no overlapping IP ranges with the first VPC. This instance needs to connect to the application on GKE. You want to minimize effort. What should you do?

- [x] 1. In GKE, create a Service of type LoadBalancer that uses the application's Pods as backend. 2. Set the service's externalTrafficPolicy to Cluster. 3. Configure the Compute Engine instance to use the address of the load balancer that has been created.
- [ ] 1. In GKE, create a Service of type NodePort that uses the application's Pods as backend. 2. Create a Compute Engine instance called proxy with 2 network interfaces, one in each VPC. 3. Use iptables on this instance to forward traffic from gce-network to the GKE nodes. 4. Configure the Compute Engine instance to use the address of proxy in gce-network as endpoint.
- [ ] 1. In GKE, create a Service of type LoadBalancer that uses the application's Pods as backend. 2. Add an annotation to this service: cloud.google.com/load-balancer-type: Internal 3. Peer the two VPCs together. 4. Configure the Compute Engine instance to use the address of the load balancer that has been created.
- [ ] 1. In GKE, create a Service of type LoadBalancer that uses the application's Pods as backend. 2. Add a Cloud Armor Security Policy to the load balancer that whitelists the internal IPs of the MIG's instances. 3. Configure the Compute Engine instance to use the address of the load balancer that has been created.

To minimize effort and allow a Compute Engine instance from a different VPC to connect to an application running in Google Kubernetes Engine (GKE), where the application exposes a TCP endpoint and has cluster autoscaling enabled, the best approach is:

**[1]**
1. In GKE, create a Service of type LoadBalancer that uses the application's Pods as backend.
2. Set the service's externalTrafficPolicy to Cluster.
3. Configure the Compute Engine instance to use the address of the load balancer that has been created.

Here’s why this option is correct:

- **LoadBalancer Service**: Creating a Service of type LoadBalancer in GKE automatically provisions a Google Cloud Load Balancer (either internal or external, depending on your configuration).
- **externalTrafficPolicy: Cluster**: This setting ensures that the source IP address of incoming traffic to the LoadBalancer is preserved, which is important for your scenario where the Compute Engine instance needs to connect and maintain the source IP integrity.
- **Compute Engine Instance Configuration**: By configuring the Compute Engine instance to use the address of the LoadBalancer, you ensure that traffic from the instance is correctly directed to the application running in GKE, regardless of the backend Pod's location (even with autoscaling).

The reasons why the other options are incorrect:

**[2]**
- Creating a Compute Engine instance with two network interfaces in different VPCs and using iptables for traffic forwarding adds unnecessary complexity and management overhead. It's not the minimal effort approach.

**[3]**
- Peering the two VPCs together and creating an Internal Load Balancer would require additional networking setup and configuration, which is more complex and not directly related to minimizing effort in this scenario.

**[4]**
- Adding a Cloud Armor Security Policy to whitelist internal IPs of Managed Instance Groups (MIGs) is focused on security rather than simplifying connectivity between a Compute Engine instance and a GKE application. It's not directly addressing the connectivity requirements stated in the scenario.

Therefore, **option [1]** is the most straightforward and efficient approach to enable connectivity from a Compute Engine instance in a separate VPC to an application running in GKE with cluster autoscaling enabled.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You are using Container Registry to centrally store your company's container images in a separate project. In another project, you want to create a Google Kubernetes Engine (GKE) cluster. You want to ensure that Kubernetes can download images from Container Registry. What should you do?

- [x] In the project where the images are stored, grant the Storage Object Viewer IAM role to the service account used by the Kubernetes nodes.
- [ ] When you create the GKE cluster, choose the Allow full access to all Cloud APIs option under 'Access scopes'.
- [ ] Create a service account, and give it access to Cloud Storage. Create a P12 key for this service account and use it as an imagePullSecrets in Kubernetes.
- [ ] Configure the ACLs on each image in Cloud Storage to give read-only access to the default Compute Engine service account.

To ensure that Google Kubernetes Engine (GKE) can download container images from Container Registry in a separate project, the correct approach is:

**[1] In the project where the images are stored, grant the Storage Object Viewer IAM role to the service account used by the Kubernetes nodes.**

Here’s why this option is correct:

- **Storage Object Viewer IAM role**: This role grants read access to objects (in this case, container images stored in Container Registry) in Cloud Storage buckets. Container Registry uses Cloud Storage buckets to store container images.
- By granting the Storage Object Viewer role to the service account used by the GKE nodes (usually the Compute Engine default service account), you allow the Kubernetes nodes to fetch container images stored in Container Registry.

The reasons why the other options are incorrect:

**[2] When you create the GKE cluster, choose the Allow full access to all Cloud APIs option under 'Access scopes'.**
- This option grants wide-ranging access to all Cloud APIs but does not specifically grant access to Container Registry images stored in a separate project. It's not the recommended approach for securing access to Container Registry.

**[3] Create a service account, and give it access to Cloud Storage. Create a P12 key for this service account and use it as an imagePullSecrets in Kubernetes.**
- While you can create a service account and generate a key, using a P12 key as an imagePullSecret in Kubernetes is not the standard way to authenticate to Container Registry. Kubernetes typically uses Docker configuration file-based secrets (`docker-registry`) to authenticate to private registries like Container Registry.

**[4] Configure the ACLs on each image in Cloud Storage to give read-only access to the default Compute Engine service account.**
- Manually configuring ACLs on each image in Cloud Storage is not scalable and not necessary when using IAM roles to manage access. Granting the Storage Object Viewer role to the service account is a more efficient and manageable approach.

Therefore, to ensure that Kubernetes can download images from Container Registry in another project, you should implement **option [1]** by granting the Storage Object Viewer IAM role to the appropriate service account in the project where Container Registry is located.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You deployed a new application inside your Google Kubernetes Engine cluster using the YAML file specified below. You check the status of the deployed pods and notice that one of them is still in PENDING status. You want to find out why the pod is stuck in pending status. What should you do?

![YAML of Google Kubernetes Engine](images/yaml2.png)

![Deployed pods status](images/pods.png)

- [ ] Review details of the myapp-service Service object and check for error messages.
- [ ] Review details of the myapp-deployment Deployment object and check for error messages.
- [x] Review details of myapp-deployment-58ddbbb995-lp86m Pod and check for warning messages.
- [ ] View logs of the container in myapp-deployment-58ddbbb995-lp86m pod and check for warning messages.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You are setting up a Windows VM on Compute Engine and want to make sure you can log in to the VM via RDP. What should you do?

- [ ] After the VM has been created, use your Google Account credentials to log in into the VM.
- [x] After the VM has been created, use gcloud compute reset-windows-password to retrieve the login credentials for the VM.
- [ ] When creating the VM, add metadata to the instance using 'windows-password' as the key and a password as the value.
- [ ] After the VM has been created, download the JSON Private Key for the default Compute Engine service account. Use the credentials in the JSON file to log in to the VM.

To ensure you can log in to a Windows VM on Compute Engine via RDP, the correct approach is:

**[2] After the VM has been created, use gcloud compute reset-windows-password to retrieve the login credentials for the VM.**

Here’s why this option is correct:

- **gcloud compute reset-windows-password**: This command allows you to reset the password for the specified Windows VM instance and retrieve the new password. This is necessary because Compute Engine does not display or store the initial Windows password after VM creation for security reasons.

The reasons why the other options are incorrect:

**[1] After the VM has been created, use your Google Account credentials to log in into the VM.**
- Google Account credentials are not used to log in to a Windows VM via RDP. You need a specific Windows password.

**[3] When creating the VM, add metadata to the instance using 'windows-password' as the key and a password as the value.**
- This metadata option does not exist. Compute Engine does not support adding 'windows-password' metadata to set the password for a Windows VM during creation.

**[4] After the VM has been created, download the JSON Private Key for the default Compute Engine service account. Use the credentials in the JSON file to log in to the VM.**
- The JSON private key for the Compute Engine service account is used for accessing Google Cloud APIs programmatically, not for logging in to a Windows VM via RDP. RDP requires a specific Windows username and password.

Therefore, to log in to your Windows VM via RDP after creation, you should use option **[2]** and run the `gcloud compute reset-windows-password` command to obtain the necessary credentials.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You want to configure an SSH connection to a single Compute Engine instance for users in the dev1 group. This instance is the only resource in this particular Google Cloud Platform project that the dev1 users should be able to connect to. What should you do?

- [x] Set metadata to enable-oslogin=true for the instance. Grant the dev1 group the compute.osLogin role. Direct them to use the Cloud Shell to ssh to that instance.
- [ ] Set metadata to enable-oslogin=true for the instance. Set the service account to no service account for that instance. Direct them to use the Cloud Shell to ssh to that instance.
- [ ] Enable block project wide keys for the instance. Generate an SSH key for each user in the dev1 group. Distribute the keys to dev1 users and direct them to use their third-party tools to connect.
- [ ] Enable block project wide keys for the instance. Generate an SSH key and associate the key with that instance. Distribute the key to dev1 users and direct them to use their third-party tools to connect.

To configure an SSH connection to a single Compute Engine instance for users in the dev1 group, where this instance is the only resource they should connect to, the best approach is:

**[1] Set metadata to enable-oslogin=true for the instance. Grant the dev1 group the compute.osLogin role. Direct them to use the Cloud Shell to ssh to that instance.**

Here's why this option is correct:

- **enable-oslogin=true**: This metadata setting enables OS Login, which allows users to authenticate using their Google Cloud credentials rather than traditional SSH keys. This simplifies SSH access management.
- **Grant compute.osLogin role to dev1 group**: This role allows members of the dev1 group to use OS Login to authenticate to the instance.
- **Use Cloud Shell**: Users can use the Cloud Shell environment, which automatically handles authentication and connection to the instance using OS Login.

The reasons why the other options are incorrect:

**[2] Set metadata to enable-oslogin=true for the instance. Set the service account to no service account for that instance. Direct them to use the Cloud Shell to ssh to that instance.**
- Setting the service account to no service account would disable any service account access, which is not necessary for SSH access by users. This option does not provide a mechanism for user authentication via OS Login.

**[3] Enable block project wide keys for the instance. Generate an SSH key for each user in the dev1 group. Distribute the keys to dev1 users and direct them to use their third-party tools to connect.**
- Using block project wide keys is a legacy method and is not suitable when OS Login is available. It involves managing SSH keys manually, which is less secure and more complex compared to OS Login.

**[4] Enable block project wide keys for the instance. Generate an SSH key and associate the key with that instance. Distribute the key to dev1 users and direct them to use their third-party tools to connect.**
- Similar to option [3], this involves managing SSH keys manually, which is less preferable when OS Login can be used for more secure and manageable access control.

Therefore, **option [1]** is the correct and recommended approach to configure SSH access for users in the dev1 group to the specified Compute Engine instance.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You need to produce a list of the enabled Google Cloud Platform APIs for a GCP project using the gcloud command line in the Cloud Shell. The project name is my-project. What should you do?

- [x] Run gcloud projects list to get the project ID, and then run gcloud services list --project <project ID>.
- [ ] Run gcloud init to set the current project to my-project, and then run gcloud services list --available.
- [ ] Run gcloud info to view the account value, and then run gcloud services list --account <Account>.
- [ ] Run gcloud projects describe <project ID> to verify the project value, and then run gcloud services list --available.

To produce a list of the enabled Google Cloud Platform APIs for a GCP project using the gcloud command line in the Cloud Shell, the best option is:

**[1] Run gcloud projects list to get the project ID, and then run gcloud services list --project <project ID>.**

This is the correct choice because:
- **`gcloud projects list`**: This command helps you retrieve the project ID of your project named "my-project".
- **`gcloud services list --project <project ID>`**: This command lists all the enabled APIs for the specified project.

The reasons why the other options are incorrect:

**[2] Run gcloud init to set the current project to my-project, and then run gcloud services list --available.**
- The `gcloud services list --available` command lists all available APIs that you can enable, not the ones currently enabled.

**[3] Run gcloud info to view the account value, and then run gcloud services list --account <Account>.**
- The account value is not relevant to listing the enabled APIs for a specific project. This option does not correctly target the project-specific enabled services.

**[4] Run gcloud projects describe <project ID> to verify the project value, and then run gcloud services list --available.**
- `gcloud services list --available` lists all available APIs, not the enabled ones. The `gcloud projects describe` command is useful for getting project details but unnecessary for listing enabled APIs when you already know the project ID.

Therefore, the correct command sequence is:

1. **Get the project ID**:
   ```bash
   gcloud projects list
   ```
2. **List the enabled APIs**:
   ```bash
   gcloud services list --project <project ID>
   ```

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You are building a new version of an application hosted in an App Engine environment. You want to test the new version with 1% of users before you completely switch your application over to the new version. What should you do?

- [ ] Deploy a new version of your application in Google Kubernetes Engine instead of App Engine and then use GCP Console to split traffic.
- [ ] Deploy a new version of your application in a Compute Engine instance instead of App Engine and then use GCP Console to split traffic.
- [ ] Deploy a new version as a separate app in App Engine. Then configure App Engine using GCP Console to split traffic between the two apps.
- [x] Deploy a new version of your application in App Engine. Then go to App Engine settings in GCP Console and split traffic between the current version and newly deployed versions accordingly.

To test the new version of your application with 1% of users before completely switching over, the best option is:

**[4] Deploy a new version of your application in App Engine. Then go to App Engine settings in GCP Console and split traffic between the current version and newly deployed versions accordingly.**

This option is correct because:
- App Engine provides built-in traffic splitting capabilities, allowing you to gradually roll out new versions by directing a percentage of traffic to the new version.
- You can configure traffic splitting in the GCP Console, specifying the percentage of traffic to be directed to each version of your application.

The reasons why the other options are incorrect:

**[1] Deploy a new version of your application in Google Kubernetes Engine instead of App Engine and then use GCP Console to split traffic.**
- This option involves moving your application to a completely different environment (Kubernetes Engine) which is unnecessary and more complex for the task of testing a new version with a subset of users.

**[2] Deploy a new version of your application in a Compute Engine instance instead of App Engine and then use GCP Console to split traffic.**
- Similar to option [1], this involves unnecessary complexity by moving your application to Compute Engine. App Engine has built-in traffic splitting capabilities that are more suitable.

**[3] Deploy a new version as a separate app in App Engine. Then configure App Engine using GCP Console to split traffic between the two apps.**
- Deploying the new version as a separate app is not necessary. You can deploy it as a new version within the same app and use App Engine’s traffic splitting features directly.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You need to provide a cost estimate for a Kubernetes cluster using the GCP pricing calculator for Kubernetes. Your workload requires high IOPs, and you will also be using disk snapshots. You start by entering the number of nodes, average hours, and average days. What should you do next?

- [x] Fill in local SSD. Fill in persistent disk storage and snapshot storage.
- [ ] Fill in local SSD. Add estimated cost for cluster management.
- [ ] Select Add GPUs. Fill in persistent disk storage and snapshot storage.
- [ ] Select Add GPUs. Add estimated cost for cluster management.

Given the requirements of high IOPs and the use of disk snapshots, the next step in the GCP pricing calculator for Kubernetes would be:

**[1] Fill in local SSD. Fill in persistent disk storage and snapshot storage.**

This option is correct because:
- **Local SSD**: High IOPs can be achieved using local SSDs, which provide low-latency, high-throughput storage directly attached to the virtual machine instances in your Kubernetes cluster.
- **Persistent Disk Storage and Snapshot Storage**: Since you will be using disk snapshots, it is essential to include the cost of persistent disk storage and the additional cost of snapshot storage.

The reasons why the other options are incorrect:

**[2] Fill in local SSD. Add estimated cost for cluster management.**
- While local SSD is necessary for high IOPs, this option ignores the need to account for persistent disk storage and snapshot storage costs, which are essential given your requirements.

**[3] Select Add GPUs. Fill in persistent disk storage and snapshot storage.**
- GPUs are not mentioned as a requirement for your workload. This option is irrelevant unless your application specifically requires GPU resources.

**[4] Select Add GPUs. Add estimated cost for cluster management.**
- Similar to option [3], this option is irrelevant unless your workload requires GPUs. Additionally, it does not account for the need for persistent disk storage and snapshot storage.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You are using Google Kubernetes Engine with autoscaling enabled to host a new application. You want to expose this new application to the public, using HTTPS on a public IP address. What should you do?

- [x] Create a Kubernetes Service of type NodePort for your application, and a Kubernetes Ingress to expose this Service via a Cloud Load Balancer.
- [ ] Create a Kubernetes Service of type ClusterIP for your application. Configure the public DNS name of your application using the IP of this Service.
- [ ] Create a Kubernetes Service of type NodePort to expose the application on port 443 of each node of the Kubernetes cluster. Configure the public DNS name of your application with the IP of every node of the cluster to achieve load-balancing.
- [ ] Create a HAProxy pod in the cluster to load-balance the traffic to all the pods of the application. Forward the public traffic to HAProxy with an iptable rule. Configure the DNS name of your application using the public IP of the node HAProxy is running on.

To expose your new application to the public using HTTPS on a public IP address in Google Kubernetes Engine (GKE) with autoscaling enabled, the best option is:

**[1] Create a Kubernetes Service of type NodePort for your application, and a Kubernetes Ingress to expose this Service via a Cloud Load Balancer.**

This is the correct choice because:
- **Kubernetes Service of type NodePort**: This service type exposes the application on a port on each node in your cluster, which is necessary for the Ingress resource to route traffic to the correct pods.
- **Kubernetes Ingress**: Ingress allows you to define rules for routing external HTTP and HTTPS traffic to your services. It can be used to configure a Cloud Load Balancer, which will handle HTTPS termination and provide a public IP address for your application.

The reasons why the other options are incorrect:

**[2] Create a Kubernetes Service of type ClusterIP for your application. Configure the public DNS name of your application using the IP of this Service.**
- A ClusterIP service is only accessible within the cluster and does not have a public IP address. This type of service cannot be used to expose your application to the public.

**[3] Create a Kubernetes Service of type NodePort to expose the application on port 443 of each node of the Kubernetes cluster. Configure the public DNS name of your application with the IP of every node of the cluster to achieve load-balancing.**
- While this exposes the application on each node, it does not provide HTTPS termination or a single public IP address. Manually configuring DNS with the IPs of each node is not efficient and does not scale well.

**[4] Create a HAProxy pod in the cluster to load-balance the traffic to all the pods of the application. Forward the public traffic to HAProxy with an iptable rule. Configure the DNS name of your application using the public IP of the node HAProxy is running on.**
- This approach is complex and involves managing HAProxy and iptable rules manually. It does not leverage the built-in capabilities of Kubernetes Ingress and Cloud Load Balancers, which are designed for this purpose and provide easier management and scalability.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You need to enable traffic between multiple groups of Compute Engine instances that are currently running two different GCP projects. Each group of Compute Engine instances is running in its own VPC. What should you do?

- [ ] Verify that both projects are in a GCP Organization. Create a new VPC and add all instances.
- [x] Verify that both projects are in a GCP Organization. Share the VPC from one project and request that the Compute Engine instances in the other project use this shared VPC.
- [ ] Verify that you are the Project Administrator of both projects. Create two new VPCs and add all instances.
- [ ] Verify that you are the Project Administrator of both projects. Create a new VPC and add all instances.

To enable traffic between multiple groups of Compute Engine instances running in two different GCP projects, each with its own VPC, the best option is:

**[2] Verify that both projects are in a GCP Organization. Share the VPC from one project and request that the Compute Engine instances in the other project use this shared VPC.**

This option is correct because:
- **Shared VPC** allows you to connect multiple projects within the same organization to a common VPC network. This facilitates communication between instances in different projects without needing to create additional VPCs or move instances.
- By sharing the VPC, you can manage network policies and configurations centrally, which simplifies network administration and enhances security.

The reasons why the other options are incorrect:

**[1] Verify that both projects are in a GCP Organization. Create a new VPC and add all instances.**
- Creating a new VPC and adding all instances would require migrating existing instances, which is complex and potentially disruptive. It's also unnecessary when Shared VPC can achieve the same goal without moving instances.

**[3] Verify that you are the Project Administrator of both projects. Create two new VPCs and add all instances.**
- Creating two new VPCs and adding instances would duplicate effort and resources, leading to increased complexity in network management. It's not efficient when Shared VPC provides a simpler solution.

**[4] Verify that you are the Project Administrator of both projects. Create a new VPC and add all instances.**
- Similar to option [1], this would require migrating instances, which is not necessary. Shared VPC offers a more efficient and less disruptive solution.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You want to add a new auditor to a Google Cloud Platform project. The auditor should be allowed to read, but not modify, all project items. How should you configure the auditor's permissions?

- [ ] Create a custom role with view-only project permissions. Add the user's account to the custom role.
- [ ] Create a custom role with view-only service permissions. Add the user's account to the custom role.
- [x] Select the built-in IAM project Viewer role. Add the user's account to this role.
- [ ] Select the built-in IAM service Viewer role. Add the user's account to this role. 

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You are operating a Google Kubernetes Engine (GKE) cluster for your company where different teams can run non-production workloads. Your Machine Learning (ML) team needs access to Nvidia Tesla P100 GPUs to train their models. You want to minimize effort and cost. What should you do?

- [ ] Ask your ML team to add the accelerator: gpu annotation to their pod specification.
- [ ] Recreate all the nodes of the GKE cluster to enable GPUs on all of them.
- [ ] Create your own Kubernetes cluster on top of Compute Engine with nodes that have GPUs. Dedicate this cluster to your ML team.
- [x] Add a new, GPU-enabled, node pool to the GKE cluster. Ask your ML team to add the cloud.google.com/gke -accelerator: nvidia-tesla-p100 nodeSelector to their pod specification.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### Your VMs are running in a subnet that has a subnet mask of 255.255.255.240. The current subnet has no more free IP addresses and you require an additional 10 IP addresses for new VMs. The existing and new VMs should all be able to reach each other without additional routes. What should you do?

- [x] Use gcloud to expand the IP range of the current subnet.
- [ ] Delete the subnet, and recreate it using a wider range of IP addresses.
- [ ] Create a new project. Use Shared VPC to share the current network with the new project.
- [ ] Create a new subnet with the same starting IP but a wider range to overwrite the current subnet.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### Your organization uses G Suite for communication and collaboration. All users in your organization have a G Suite account. You want to grant some G Suite users access to your Cloud Platform project. What should you do?

- [ ] Enable Cloud Identity in the GCP Console for your domain.
- [x] Grant them the required IAM roles using their G Suite email address.
- [ ] Create a CSV sheet with all users' email addresses. Use the gcloud command line tool to convert them into Google Cloud Platform accounts.
- [ ] In the G Suite console, add the users to a special group called cloud-console-users@yourdomain.com. Rely on the default behavior of the Cloud Platform to grant users access if they are members of this group.

To grant G Suite users access to your Google Cloud Platform (GCP) project, you should follow these steps:

- [2] **Grant them the required IAM roles using their G Suite email address.**

Here’s why this option is correct:

- **IAM Roles and G Suite Users:** In GCP, you can grant IAM (Identity and Access Management) roles directly to G Suite users by using their G Suite email addresses. This allows you to specify exactly which permissions and access levels these users should have within your GCP project.

- **Integration with G Suite:** G Suite accounts are automatically linked to Google Cloud Platform, so you can manage access to GCP resources using the same identity and credentials that users use for G Suite services.

The other options are not appropriate or do not align with best practices for granting G Suite users access to GCP:

- **Option 1:** Enabling Cloud Identity in the GCP Console for your domain is not necessary to grant access to G Suite users. Cloud Identity is more relevant for managing identities and access across Google Cloud services, but G Suite accounts already provide integration for access.

- **Option 3:** Converting G Suite accounts into Google Cloud Platform accounts via a CSV sheet and gcloud command line tool is not the standard or recommended approach for managing access to GCP resources for G Suite users.

- **Option 4:** Adding users to a special group in the G Suite console (`cloud-console-users@yourdomain.com`) and relying on default behaviors for access is not the preferred method for managing precise access control in GCP. IAM roles provide more granular control over permissions.

Therefore, **Option 2** is the correct approach to grant G Suite users access to your Cloud Platform project by assigning them the required IAM roles using their G Suite email addresses. This method leverages G Suite's integration with Google Cloud Platform to manage access efficiently and securely.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You have a Google Cloud Platform account with access to both production and development projects. You need to create an automated process to list all compute instances in development and production projects on a daily basis. What should you do?

- [x] Create two configurations using gcloud config. Write a script that sets configurations as active, individually. For each configuration, use gcloud compute instances list to get a list of compute resources.
- [ ] Create two configurations using gsutil config. Write a script that sets configurations as active, individually. For each configuration, use gsutil compute instances list to get a list of compute resources.
- [ ] Go to Cloud Shell and export this information to Cloud Storage on a daily basis.
- [ ] Go to GCP Console and export this information to Cloud SQL on a daily basis.

The best option for creating an automated process to list all compute instances in both development and production projects on a daily basis is:

**[x] Create two configurations using gcloud config. Write a script that sets configurations as active, individually. For each configuration, use gcloud compute instances list to get a list of compute resources.**

This option is correct because:
- Using `gcloud config`, you can create separate configurations for each project (development and production).
- Writing a script to switch between these configurations and list the compute instances ensures that you are correctly accessing and listing resources from the intended project.
- `gcloud compute instances list` is the appropriate command for listing compute instances.

The reasons why the other options are incorrect:

**[ ] Create two configurations using gsutil config. Write a script that sets configurations as active, individually. For each configuration, use gsutil compute instances list to get a list of compute resources.**
- `gsutil` is a command-line tool for interacting with Google Cloud Storage, not for managing compute resources. You should use `gcloud` for compute instances.

**[ ] Go to Cloud Shell and export this information to Cloud Storage on a daily basis.**
- While you could manually do this, it does not automate the process. Additionally, this option does not specify how to handle the project configurations or the actual listing of compute instances.

**[ ] Go to GCP Console and export this information to Cloud SQL on a daily basis.**
- This option involves manual steps and does not automate the process. It also does not address the need to list compute instances from multiple projects.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You have a large 5-TB AVRO file stored in a Cloud Storage bucket. Your analysts are proficient only in SQL and need access to the data stored in this file. You want to find a cost-effective way to complete their request as soon as possible. What should you do?

- [ ] Load data in Cloud Datastore and run a SQL query against it.
- [ ] Create a BigQuery table and load data in BigQuery. Run a SQL query on this table and drop this table after you complete your request.
- [x] Create external tables in BigQuery that point to Cloud Storage buckets and run a SQL query on these external tables to complete your request.
- [ ] Create a Hadoop cluster and copy the AVRO file to NDFS by compressing it. Load the file in a hive table and provide access to your analysts so that they can run SQL queries.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You need to verify that a Google Cloud Platform service account was created at a particular time. What should you do?

- [x] Filter the Activity log to view the Configuration category. Filter the Resource type to Service Account.
- [ ] Filter the Activity log to view the Configuration category. Filter the Resource type to Google Project.
- [ ] Filter the Activity log to view the Data Access category. Filter the Resource type to Service Account.
- [ ] Filter the Activity log to view the Data Access category. Filter the Resource type to Google Project.

To verify that a Google Cloud Platform service account was created at a particular time, you should follow these steps:

- **[1] Filter the Activity log to view the Configuration category. Filter the Resource type to Service Account.**

Here’s why this option is correct:

- **Configuration Category:** The Configuration category in the Google Cloud Console Activity logs includes events related to creating, updating, and deleting resources like service accounts.
  
- **Resource Type to Service Account:** By filtering the Activity log to show events related specifically to the Service Account resource type, you can narrow down the logs to those directly related to the creation of service accounts.

- **Verification:** This approach allows you to see when the service account was created, providing details such as the timestamp of the creation event and any associated metadata.

The other options are less appropriate for verifying the creation time of a service account:

- **Option 2:** Filtering the Activity log for Google Project in the Configuration category doesn't specifically target service account creation events.

- **Option 3:** The Data Access category typically includes events related to accessing data rather than creating service accounts.

- **Option 4:** Filtering for Google Project in the Data Access category is unrelated to service account creation events.

Therefore, **Option 1** is the correct and recommended approach to verify the creation time of a Google Cloud Platform service account.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You deployed an LDAP server on Compute Engine that is reachable via TLS through port 636 using UDP. You want to make sure it is reachable by clients over that port. What should you do?

- [ ] Add the network tag allow-udp-636 to the VM instance running the LDAP server.
- [ ] Create a route called allow-udp-636 and set the next hop to be the VM instance running the LDAP server.
- [x] Add a network tag of your choice to the instance. Create a firewall rule to allow ingress on UDP port 636 for that network tag.
- [ ] Add a network tag of your choice to the instance running the LDAP server. Create a firewall rule to allow egress on UDP port 636 for that network tag.

To ensure that your LDAP server deployed on Compute Engine is reachable by clients over port 636 using UDP, you should follow these steps:

- **[3] Add a network tag of your choice to the instance. Create a firewall rule to allow ingress on UDP port 636 for that network tag.**

Here’s why this option is correct:

- **Network Tag:** Adding a network tag to the instance allows you to target specific instances for firewall rules.
  
- **Firewall Rule for Ingress:** By creating a firewall rule that allows ingress traffic on UDP port 636 for the network tag assigned to your LDAP server instance, you permit incoming traffic from clients trying to connect to the LDAP server.

- **UDP Port 636:** LDAP typically uses TCP port 636 for LDAPS (LDAP over SSL/TLS), but if you specifically need UDP for any reason (such as specific client requirements or configurations), this rule ensures UDP traffic on port 636 is allowed.

The other options are less appropriate or incorrect for enabling UDP traffic on port 636:

- **Option 1:** Adding a network tag alone without creating a corresponding firewall rule will not allow traffic on UDP port 636. Tags are used to identify instances but do not directly control traffic flow.

- **Option 2:** Creating a route is used for directing traffic within the network, not for allowing specific ports or protocols like UDP 636.

- **Option 4:** Allowing egress (outgoing) traffic on UDP port 636 does not address the requirement for inbound traffic from clients to reach the LDAP server over UDP.

Therefore, **Option 3** is the correct approach to ensure that your LDAP server on Compute Engine is reachable by clients over UDP port 636.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You need to set a budget alert for use of Compute Engine services on one of the three Google Cloud Platform projects that you manage. All three projects are linked to a single billing account. What should you do?

- [x] Verify that you are the project billing administrator. Select the associated billing account and create a budget and alert for the appropriate project.
- [ ] Verify that you are the project billing administrator. Select the associated billing account and create a budget and a custom alert.
- [ ] Verify that you are the project administrator. Select the associated billing account and create a budget for the appropriate project.
- [ ] Verify that you are project administrator. Select the associated billing account and create a budget and a custom alert.

The best option for setting a budget alert for the use of Compute Engine services on one of the Google Cloud Platform projects is:

**[1] Verify that you are the project billing administrator. Select the associated billing account and create a budget and alert for the appropriate project.**

This is the correct choice because:
- You need to be the project billing administrator to manage budgets and alerts related to billing.
- Once you have verified your role, you can select the associated billing account and create a budget and alert specifically for the appropriate project.

The reasons why the other options are incorrect:

**[2] Verify that you are the project billing administrator. Select the associated billing account and create a budget and a custom alert.**
- This option is almost correct, but it includes the term "custom alert," which is unnecessary. The standard budget alert will suffice for monitoring the Compute Engine services' costs.

**[3] Verify that you are the project administrator. Select the associated billing account and create a budget for the appropriate project.**
- Being a project administrator does not necessarily grant permissions to manage billing settings. You need to be the project billing administrator to create budgets and alerts.

**[4] Verify that you are the project administrator. Select the associated billing account and create a budget and a custom alert.**
- Similar to option [3], being a project administrator is not sufficient for managing billing. Additionally, "custom alert" is unnecessary in this context. The correct role is the project billing administrator.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You are migrating a production-critical on-premises application that requires 96 vCPUs to perform its task. You want to make sure the application runs in a similar environment on GCP. What should you do?

- [x] When creating the VM, use machine type n1-standard-96.
- [ ] When creating the VM, use Intel Skylake as the CPU platform.
- [ ] Create the VM using Compute Engine default settings. Use gcloud to modify the running instance to have 96 vCPUs.
- [ ] Start the VM using Compute Engine default settings, and adjust as you go based on Rightsizing Recommendations.

To ensure the application runs in a similar environment on GCP, the best option is:

**[1] When creating the VM, use machine type n1-standard-96.**

This is the correct choice because:
- The n1-standard-96 machine type directly provides 96 vCPUs, matching the required specifications of your on-premises application.
- This machine type is designed for high-performance tasks and should provide the computational resources needed for your application.

The reasons why the other options are incorrect:

**[2] When creating the VM, use Intel Skylake as the CPU platform.**
- While selecting a specific CPU platform like Intel Skylake can optimize performance for some applications, it does not guarantee that the VM will have 96 vCPUs. The machine type must be specified to ensure the correct number of vCPUs.

**[3] Create the VM using Compute Engine default settings. Use gcloud to modify the running instance to have 96 vCPUs.**
- Compute Engine default settings do not provision a VM with 96 vCPUs. Modifying the instance after creation is more complex and not a best practice for a production-critical application, as it can lead to downtime or configuration errors.

**[4] Start the VM using Compute Engine default settings, and adjust as you go based on Rightsizing Recommendations.**
- Starting with default settings means the VM will not have the required 96 vCPUs initially. Rightsizing Recommendations are more suitable for optimizing resource usage after monitoring the application’s performance. This approach is not suitable for a production-critical application that requires specific resources from the start.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You want to configure a solution for archiving data in a Cloud Storage bucket. The solution must be cost-effective. Data with multiple versions should be archived after 30 days. Previous versions are accessed once a month for reporting. This archive data is also occasionally updated at month-end. What should you do?

- [ ] Add a bucket lifecycle rule that archives data with newer versions after 30 days to Coldline Storage.
- [x] Add a bucket lifecycle rule that archives data with newer versions after 30 days to Nearline Storage.
- [ ] Add a bucket lifecycle rule that archives data from regional storage after 30 days to Coldline Storage.
- [ ] Add a bucket lifecycle rule that archives data from regional storage after 30 days to Nearline Storage.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### Your company's infrastructure is on-premises, but all machines are running at maximum capacity. You want to burst to Google Cloud. The workloads on Google Cloud must be able to directly communicate to the workloads on-premises using a private IP range. What should you do?

- [ ] In Google Cloud, configure the VPC as a host for Shared VP.
- [ ] In Google Cloud, configure the VPC for VPC Network Peering.
- [ ] Create bastion hosts both in your on-premises environment and on Google Cloud. Configure both as proxy servers using their public IP addresses.
- [x] Set up Cloud VPN between the infrastructure on-premises and Google Cloud.

To enable your workloads on Google Cloud to communicate directly with workloads on-premises using a private IP range, while allowing for bursting from on-premises infrastructure to Google Cloud, the most appropriate solution is:

- [4] Set up Cloud VPN between the infrastructure on-premises and Google Cloud.

Here’s why this option is correct:

- **Cloud VPN**: Google Cloud VPN allows you to securely connect your on-premises network to your Google Cloud Virtual Private Cloud (VPC) network using IPsec VPN tunnels. This setup enables private IP communication between on-premises machines and Google Cloud workloads.

- **Private IP Range**: With Cloud VPN, you can configure IP ranges that are part of your on-premises network to be reachable from Google Cloud workloads. This ensures that your applications can communicate securely using private IP addresses, maintaining network isolation and security.

The other options are less suitable for achieving private IP communication between on-premises and Google Cloud:

- **Option 1 (Shared VPC)**: Shared VPC allows resources from multiple projects to connect to a common VPC network, but it does not directly address the need for private IP communication with on-premises infrastructure.

- **Option 2 (VPC Network Peering)**: VPC Network Peering allows VPC networks to be interconnected, but it does not establish a secure, private communication channel between on-premises and Google Cloud networks.

- **Option 3 (Bastion hosts with public IP addresses)**: Using bastion hosts as proxy servers with public IP addresses introduces security risks and does not provide direct private IP communication between on-premises and Google Cloud networks.

Therefore, **Option 4 (Cloud VPN)** is the recommended solution for establishing secure and private IP communication between your on-premises infrastructure and Google Cloud, allowing for bursting workloads to the cloud while maintaining network isolation and compliance with your company's infrastructure requirements.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You want to select and configure a solution for storing and archiving data on Google Cloud Platform. You need to support compliance objectives for data from one geographic location. This data is archived after 30 days and needs to be accessed annually. What should you do?

- [ ] Select Multi-Regional Storage. Add a bucket lifecycle rule that archives data after 30 days to Coldline Storage.
- [ ] Select Multi-Regional Storage. Add a bucket lifecycle rule that archives data after 30 days to Nearline Storage.
- [ ] Select Regional Storage. Add a bucket lifecycle rule that archives data after 30 days to Nearline Storage.
- [x] Select Regional Storage. Add a bucket lifecycle rule that archives data after 30 days to Coldline Storage.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### Your company uses BigQuery for data warehousing. Over time, many different business units in your company have created 1000+ datasets across hundreds of projects. Your CIO wants you to examine all datasets to find tables that contain an employee_ssn column. You want to minimize effort in performing this task. What should you do?

- [x] Go to Data Catalog and search for employee_ssn in the search box.
- [ ] Write a shell script that uses the bq command line tool to loop through all the projects in your organization.
- [ ] Write a script that loops through all the projects in your organization and runs a query on INFORMATION_SCHEMA.COLUMNS view to find the employee_ssn column.
- [ ] Write a Cloud Dataflow job that loops through all the projects in your organization and runs a query on INFORMATION_SCHEMA.COLUMNS view to find employee_ssn column.

To efficiently find tables across all datasets in your company's BigQuery environment that contain an `employee_ssn` column while minimizing effort, the most appropriate approach is:

- [1] Go to Data Catalog and search for `employee_ssn` in the search box.

Here’s why this option is the best choice:

- **Data Catalog**: Google Cloud's Data Catalog is designed to provide a unified and searchable metadata catalog for all your data assets across Google Cloud services, including BigQuery datasets and tables.
  
- **Searching for `employee_ssn`**: Data Catalog allows you to search for specific columns like `employee_ssn` across all datasets within your organization's Google Cloud environment. This search capability is efficient and leverages metadata indexing to quickly locate relevant information without needing to manually query each dataset.

The other options involve scripting or using Cloud Dataflow, which can be more complex and time-consuming:

- **Option 2 (Shell script with `bq` command)**: While feasible, scripting with `bq` would require looping through all projects and datasets, querying each table's schema to find the `employee_ssn` column. This approach could be labor-intensive and may not scale well for large numbers of datasets.

- **Option 3 (Script using INFORMATION_SCHEMA.COLUMNS)**: This involves scripting to query the `INFORMATION_SCHEMA.COLUMNS` view across all projects. While this is more automated than using `bq` manually, it still requires scripting effort and potentially large amounts of API calls depending on the number of projects and datasets.

- **Option 4 (Cloud Dataflow job)**: Writing a Cloud Dataflow job for this task would be over-engineering unless there are specific requirements for data processing or transformation beyond simple metadata search.

Therefore, **Option 1** is the most efficient and straightforward approach to achieve the task of identifying tables with an `employee_ssn` column across all datasets in your BigQuery environment using Google Cloud's Data Catalog.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You create a Deployment with 2 replicas in a Google Kubernetes Engine cluster that has a single preemptible node pool. After a few minutes, you use kubectl to examine the status of your Pod and observe that one of them is still in Pending status. What is the most likely cause?

![Deployed pods status](images/pods.png)

- [ ] The pending Pod's resource requests are too large to fit on a single node of the cluster.
- [ ] Too many Pods are already running in the cluster, and there are not enough resources left to schedule the pending Pod.
- [ ] The node pool is configured with a service account that does not have permission to pull the container image used by the pending Pod.
- [x] The pending Pod was originally scheduled on a node that has been preempted between the creation of the Deployment and your verification of the Pods' status. It is currently being rescheduled on a new node.

Based on the information provided and the observation that one of your Pods in a Deployment with 2 replicas is still in Pending status on a Google Kubernetes Engine cluster with a single preemptible node pool, the most likely cause is:

- [4] The pending Pod was originally scheduled on a node that has been preempted between the creation of the Deployment and your verification of the Pods' status. It is currently being rescheduled on a new node.

Here’s why this is the most likely cause:

- **Preemptible Node**: In Google Kubernetes Engine (GKE), preemptible VMs (nodes) can be terminated by Google Cloud with short notice (up to 24 hours). When a preemptible node is terminated (preempted), any Pods running on that node are also terminated.

- **Pod Rescheduling**: When a preemptible node is preempted, Kubernetes detects this and attempts to reschedule the Pods that were running on that node onto other available nodes in the cluster. This rescheduling process can lead to some Pods, particularly if the cluster is under resource pressure or the node pool has limited capacity, remaining in Pending status until suitable resources are found.

- **Deployment ReplicaSet**: In your case, with a Deployment having 2 replicas, Kubernetes ensures that at least 2 Pods are running based on the desired state defined in the Deployment’s ReplicaSet. If one Pod is Pending, it suggests that Kubernetes is in the process of rescheduling that Pod onto another node after the original node (where it was scheduled) was preempted.

The other options are less likely to be the cause:

- **Option 1 (Resource requests too large)**: While this can sometimes cause Pending status if nodes cannot satisfy resource requests, preemptible nodes are typically the cause in this scenario.

- **Option 2 (Too many Pods running)**: GKE manages node scaling based on resource requirements, and Kubernetes should handle scheduling based on available resources unless the node pool is severely overutilized.

- **Option 3 (Service account permission issue)**: This would typically result in a different error related to pulling the container image rather than leaving the Pod in Pending status.

Therefore, **Option 4** is the most likely cause for the pending Pod in your scenario, where it was originally scheduled on a preemptible node that has been preempted, and Kubernetes is in the process of rescheduling it onto a new node.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You want to find out when users were added to Cloud Spanner Identity Access Management (IAM) roles on your Google Cloud Platform (GCP) project. What should you do in the GCP Console?

- [ ] Open the Cloud Spanner console to review configurations.
- [ ] Open the IAM &amp; admin console to review IAM policies for Cloud Spanner roles.
- [ ] Go to the Stackdriver Monitoring console and review information for Cloud Spanner.
- [x] Go to the Stackdriver Logging console, review admin activity logs, and filter them for Cloud Spanner IAM roles.

To find out when users were added to Cloud Spanner Identity Access Management (IAM) roles on your Google Cloud Platform (GCP) project, you should:

- [4] Go to the Stackdriver Logging console, review admin activity logs, and filter them for Cloud Spanner IAM roles.

Here’s why this option is correct:

- **Stackdriver Logging**: Stackdriver Logging captures admin activity logs, which include events related to changes in IAM roles and permissions within your GCP project.
  
- **Reviewing Admin Activity Logs**: Within Stackdriver Logging, you can filter logs specifically for changes related to Cloud Spanner IAM roles. This allows you to see when users were added or removed from IAM roles associated with Cloud Spanner.

- **Other Options Explained**:
  - **Option 1 (Cloud Spanner Console)**: This console is primarily for managing Cloud Spanner databases and instances, not for reviewing IAM role changes.
  - **Option 2 (IAM & admin console)**: While the IAM & admin console allows you to manage IAM policies, it does not provide a direct view of when changes were made historically.
  - **Option 3 (Stackdriver Monitoring)**: Stackdriver Monitoring is focused on monitoring and alerting for system performance, not for reviewing historical IAM changes.

Therefore, **Option 4** is the correct choice for reviewing when users were added to Cloud Spanner IAM roles by accessing admin activity logs through Stackdriver Logging.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### Your company implemented BigQuery as an enterprise data warehouse. Users from multiple business units run queries on this data warehouse. However, you notice that query costs for BigQuery are very high, and you need to control costs. Which two methods should you use? (Choose two.)

- [ ] Split the users from business units to multiple projects.
- [x] Apply a user- or project-level custom query quota for BigQuery data warehouse.
- [ ] Create separate copies of your BigQuery data warehouse for each business unit.
- [ ] Split your BigQuery data warehouse into multiple data warehouses for each business unit.
- [x] Change your BigQuery query model from on-demand to flat rate. Apply the appropriate number of slots to each Project.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You are building a product on top of Google Kubernetes Engine (GKE). You have a single GKE cluster. For each of your customers, a Pod is running in that cluster, and your customers can run arbitrary code inside their Pod. You want to maximize the isolation between your customers' Pods. What should you do?

- [ ] Use Binary Authorization and whitelist only the container images used by your customers' Pods.
- [ ] Use the Container Analysis API to detect vulnerabilities in the containers used by your customers' Pods.
- [x] Create a GKE node pool with a sandbox type configured to gvisor. Add the parameter runtimeClassName: gvisor to the specification of your customers' Pods.
- [ ] Use the cos_containerd image for your GKE nodes. Add a nodeSelector with the value cloud.google.com/gke-os-distribution: cos_containerd to the specification of your customers' Pods.

To maximize isolation between your customers' Pods running in a single Google Kubernetes Engine (GKE) cluster, the most suitable option from those provided is:

- [3] Create a GKE node pool with a sandbox type configured to gvisor. Add the parameter runtimeClassName: gvisor to the specification of your customers' Pods.

Here’s why this option is appropriate:

- **gVisor Sandbox**: Google gVisor provides an additional layer of isolation and security by running each container in a lightweight sandboxed environment. This helps prevent one customer's workload from accessing another customer's data or resources directly.

- **Node Pool Configuration**: By creating a dedicated GKE node pool configured to use gVisor as the sandbox type (`gvisor`), you isolate the Pods of your customers within this specific node pool. Each customer's Pod can then be configured to use the `gvisor` runtimeClassName, ensuring that their containers run in gVisor sandboxes.

The other options are less focused on maximizing isolation between customers' Pods:

- **Option 1 (Binary Authorization)**: While Binary Authorization helps in enforcing policies for container images, it does not directly maximize isolation between Pods running in the same cluster.

- **Option 2 (Container Analysis API)**: This API is used for vulnerability scanning of container images and does not impact runtime isolation between Pods.

- **Option 4 (cos_containerd image and nodeSelector)**: Using a specific containerd-based image for nodes and nodeSelectors does not provide the same level of isolation as gVisor’s sandboxing mechanism.

Therefore, **Option 3** is the most effective choice to ensure maximum isolation between your customers' Pods within a GKE cluster, leveraging gVisor's sandboxing capabilities at the node pool level and specifying `runtimeClassName: gvisor` in the Pod specifications.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### Your customer has implemented a solution that uses Cloud Spanner and notices some read latency-related performance issues on one table. This table is accessed only by their users using a primary key. The table schema is shown below. You want to resolve the issue. What should you do?

![Database table](images/db_table.png)

- [ ] Remove the profile_picture field from the table.
- [ ] Add a secondary index on the person_id column.
- [x] Change the primary key to not have monotonically increasing values.
- [ ] Create a secondary index using the following Data Definition Language (DDL):

![DDL](images/ddl.png)

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### Your finance team wants to view the billing report for your projects. You want to make sure that the finance team does not get additional permissions to the project. What should you do?

- [ ] Add the group for the finance team to roles/billing user role.
- [ ] Add the group for the finance team to roles/billing admin role.
- [x] Add the group for the finance team to roles/billing viewer role.
- [ ] Add the group for the finance team to roles/billing project/Manager role.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### Your organization has strict requirements to control access to Google Cloud projects. You need to enable your Site Reliability Engineers (SREs) to approve requests from the Google Cloud support team when an SRE opens a support case. You want to follow Google-recommended practices. What should you do?

- [ ] Add your SREs to roles/iam.roleAdmin role.
- [ ] Add your SREs to roles/accessapproval.approver role.
- [ ] Add your SREs to a group and then add this group to roles/iam.roleAdmin.role.
- [x] Add your SREs to a group and then add this group to roles/accessapproval.approver role.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You need to host an application on a Compute Engine instance in a project shared with other teams. You want to prevent the other teams from accidentally causing downtime on that application. Which feature should you use?

- [ ] Use a Shielded VM.
- [ ] Use a Preemptible VM.
- [ ] Use a sole-tenant node.
- [x] Enable deletion protection on the instance.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### Your organization needs to grant users access to query datasets in BigQuery but prevent them from accidentally deleting the datasets. You want a solution that follows Google-recommended practices. What should you do?

- [ ] Add users to roles/bigquery user role only, instead of roles/bigquery dataOwner.
- [ ] Add users to roles/bigquery dataEditor role only, instead of roles/bigquery dataOwner.
- [ ] Create a custom role by removing delete permissions, and add users to that role only.
- [x] Create a custom role by removing delete permissions. Add users to the group, and then add the group to the custom role.

      To grant users access to query datasets in BigQuery while preventing them from accidentally deleting the datasets, and to follow Google-recommended practices, the best approach is:

- **Option 4: Create a custom role by removing delete permissions. Add users to the group, and then add the group to the custom role.**

Here’s why this option is suitable:

- **Option 1 (roles/bigquery.user role only)**: This role grants only querying permissions but does not explicitly prevent users from deleting datasets.

- **Option 2 (roles/bigquery.dataEditor role only)**: This role allows users to edit data within datasets, which includes deleting data and tables. It grants more permissions than necessary if your goal is to prevent dataset deletions.

- **Option 3 (Create a custom role by removing delete permissions, and add users to that role only)**: This option is similar to Option 4 but directly assigns users to the custom role without using a group. It's straightforward but may become cumbersome to manage if you have many users.

- **Option 4 (Create a custom role by removing delete permissions. Add users to the group, and then add the group to the custom role)**: This option combines the flexibility of custom roles with the ease of group management. By creating a custom role that explicitly removes delete permissions (`bigquery.datasets.delete`), you ensure users cannot delete datasets. Adding users to a group and then assigning that group to the custom role allows for easier management and scalability. It also follows best practices by using groups for role assignments, which can streamline access management across your organization.

Therefore, **Option 4** is the recommended approach to grant users the necessary querying permissions in BigQuery while preventing accidental dataset deletions and maintaining manageability according to Google-recommended practices.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You have a developer laptop with the Cloud SDK installed on Ubuntu. The Cloud SDK was installed from the Google Cloud Ubuntu package repository. You want to test your application locally on your laptop with Cloud Datastore. What should you do? --------------Issue

- [ ] Export Cloud Datastore data using gcloud datastore export.
- [ ] Create a Cloud Datastore index using gcloud datastore indexes create.
- [ ] Install the google-cloud-sdk-datastore-emulator component using the apt get install command.
- [x] Install the cloud-datastore-emulator component using the gcloud components install command.

To test your application locally with Cloud Datastore on your developer laptop that runs Ubuntu and has the Cloud SDK installed from the Google Cloud Ubuntu package repository, you should follow these steps:

- **[4] Install the cloud-datastore-emulator component using the gcloud components install command.**

Here's why this is the correct option:

- **Option 4**: Installing the `cloud-datastore-emulator` component using the `gcloud components install` command is the appropriate step to set up the Cloud Datastore emulator locally. The Cloud Datastore emulator allows you to emulate Google Cloud Datastore on your local machine, enabling you to develop and test applications without interacting with the actual Cloud Datastore service.

- **Option 1**: Exporting Cloud Datastore data using `gcloud datastore export` is used for exporting data from the actual Cloud Datastore service, not for setting up the emulator.

- **Option 2**: Creating a Cloud Datastore index using `gcloud datastore indexes create` is a command used to manage indexes in the Cloud Datastore service, not for setting up the emulator.

- **Option 3**: Installing the `google-cloud-sdk-datastore-emulator` component using the `apt-get install` command is not the correct method because the emulator component for Cloud Datastore is installed via the Cloud SDK (`gcloud`), not through the system package manager (`apt-get`).

Therefore, **Option 4** is the correct choice for installing and setting up the Cloud Datastore emulator on your developer laptop.
--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### Your company set up a complex organizational structure on Google Cloud. The structure includes hundreds of folders and projects. Only a few team members should be able to view the hierarchical structure. You need to assign minimum permissions to these team members, and you want to follow Google-recommended practices. What should you do?

- [ ] Add the users to roles/browser role.
- [ ] Add the users to roles/iam.roleViewer role.
- [x] Add the users to a group, and add this group to roles/browser.
- [ ] Add the users to a group, and add this group to roles/iam.roleViewer role.

To allow a few team members to view the hierarchical structure of your Google Cloud organization while following Google-recommended practices, you should:

### Correct Answer:
- **[3] Add the users to a group, and add this group to roles/browser.**

### Explanation:
- **[1] Add the users to roles/browser role**: Assigning roles directly to individual users is not a best practice because it becomes hard to manage as the number of users grows.
- **[2] Add the users to roles/iam.roleViewer role**: The `roles/iam.roleViewer` role is not the appropriate role for viewing the hierarchical structure of folders and projects.
- **[3] Add the users to a group, and add this group to roles/browser**: This is the recommended practice. By adding users to a group and then assigning the role to the group, you can easily manage permissions at scale. The `roles/browser` role provides the necessary permissions to view the organization’s structure.
- **[4] Add the users to a group, and add this group to roles/iam.roleViewer role**: Again, the `roles/iam.roleViewer` role is not intended for viewing the organizational structure. The `roles/browser` role is more suitable.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### Your company has a single sign-on (SSO) identity provider that supports Security Assertion Markup Language (SAML) integration with service providers. Your company has users in Cloud Identity. You would like users to authenticate using your company's SSO provider. What should you do?

- [ ] In Cloud Identity, set up SSO with Google as an identity provider to access custom SAML apps.
- [x] In Cloud Identity, set up SSO with a third-party identity provider with Google as a service provider.
- [ ] Obtain OAuth 2.0 credentials, configure the user consent screen, and set up OAuth 2.0 for Mobile &amp; Desktop Apps.
- [ ] Obtain OAuth 2.0 credentials, configure the user consent screen, and set up OAuth 2.0 for Web Server Applications.

To integrate your company's SSO provider that supports SAML with Cloud Identity, you need to set up single sign-on (SSO) with a third-party identity provider, with Google acting as the service provider.

### Correct Answer:
- **[2] In Cloud Identity, set up SSO with a third-party identity provider with Google as a service provider.**

### Explanation:
- **[1] In Cloud Identity, set up SSO with Google as an identity provider to access custom SAML apps**: This sets up Google as the identity provider, but in your case, you want your company's SSO provider to be the identity provider.
- **[2] In Cloud Identity, set up SSO with a third-party identity provider with Google as a service provider**: This correctly configures Cloud Identity to use your company's SSO provider as the identity provider, with Google acting as the service provider.
- **[3] Obtain OAuth 2.0 credentials, configure the user consent screen, and set up OAuth 2.0 for Mobile & Desktop Apps**: OAuth 2.0 is not used for SAML SSO integrations.
- **[4] Obtain OAuth 2.0 credentials, configure the user consent screen, and set up OAuth 2.0 for Web Server Applications**: Again, OAuth 2.0 is not the appropriate protocol for this SAML SSO scenario.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### Your organization has a dedicated person who creates and manages all service accounts for Google Cloud projects. You need to assign this person the minimum role for projects. What should you do?

- [ ] Add the user to roles/iam.roleAdmin role.
- [ ] Add the user to roles/iam.securityAdmin role.
- [ ] Add the user to roles/iam.serviceAccountUser role.
- [x] Add the user to roles/iam.serviceAccountAdmin role.

To manage all service accounts, including creating and managing them, the appropriate role to assign is the **Service Account Admin** role. This role provides permissions to create, update, delete, and manage service accounts.

### Correct Answer:
- **[4] Add the user to roles/iam.serviceAccountAdmin role.**

### Explanation:
- **roles/iam.roleAdmin**: This role is for managing IAM roles, not service accounts.
- **roles/iam.securityAdmin**: This role is for managing IAM policies and security configurations, not specifically service accounts.
- **roles/iam.serviceAccountUser**: This role allows using service accounts but not creating or managing them.
- **roles/iam.serviceAccountAdmin**: This role has the necessary permissions to create, update, delete, and manage service accounts, which fits the requirement.
--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You are building an archival solution for your data warehouse and have selected Cloud Storage to archive your data. Your users need to be able to access this archived data once a quarter for some regulatory requirements. You want to select a cost-efficient option. Which storage option should you use?

- [ ] Cold Storage.
- [x] Nearline Storage.
- [ ] Regional Storage.
- [ ] Multi-Regional Storage.

Given the requirements of accessing the archived data once a quarter (every 90 days), the most cost-efficient option for this access pattern would be **Coldline Storage**. Coldline Storage is specifically designed for data that is accessed infrequently, typically less than once a year, making it more cost-effective for quarterly access compared to other options.

### Correct Answer:
- **[1] Cold Storage.**

### Explanation:
- **Coldline Storage (Cold Storage)**: This is suitable for data accessed less than once a year. Since your data is accessed once every quarter, this fits well with the usage pattern and provides a cost-efficient solution.
- **Nearline Storage**: More suitable for data accessed less than once a month but more frequently than Coldline. It would be less cost-efficient for quarterly access compared to Coldline Storage.
- **Regional Storage**: This is designed for data that needs to be accessed frequently and stored in a specific region. It would be more expensive and unnecessary for infrequent, quarterly access.
- **Multi-Regional Storage**: This is for data that needs to be accessed frequently across multiple regions. It is the most expensive option and not suitable for infrequent, quarterly access.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### A team of data scientists infrequently needs to use a Google Kubernetes Engine (GKE) cluster that you manage. They require GPUs for some long-running, nonrestartable jobs. You want to minimize cost. What should you do?  ---------------Issue

- [ ] Enable node auto-provisioning on the GKE cluster.
- [ ] Create a VerticalPodAutscaler for those workloads.
- [ ] Create a node pool with preemptible VMs and GPUs attached to those VMs.
- [x] Create a node pool of instances with GPUs, and enable autoscaling on this node pool with a minimum size of 1.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### Your organization has user identities in Active Directory. Your organization wants to use Active Directory as their source of truth for identities. Your organization wants to have full control over the Google accounts used by employees for all Google services, including your Google Cloud Platform (GCP) organization. What should you do?

- [x] Use Google Cloud Directory Sync (GCDS) to synchronize users into Cloud Identity.
- [ ] Use the cloud Identity APIs and write a script to synchronize users to Cloud Identity.
- [ ] Export users from Active Directory as a CSV and import them to Cloud Identity via the Admin Console.
- [ ] Ask each employee to create a Google account using self signup. Require that each employee use their company email address and password.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You have successfully created a development environment in a project for an application. This application uses Compute Engine and Cloud SQL. Now you need to create a production environment for this application. The security team has forbidden the existence of network routes between these 2 environments and has asked you to follow Google-recommended practices. What should you do?

- [x] Create a new project, enable the Compute Engine and Cloud SQL APIs in that project, and replicate the setup you have created in the development environment.
- [ ] Create a new production subnet in the existing VPC and a new production Cloud SQL instance in your existing project, and deploy your application using those resources.
- [ ] Create a new project, modify your existing VPC to be a Shared VPC, share that VPC with your new project, and replicate the setup you have in the development environment in that new project in the Shared VP.
- [ ] Ask the security team to grant you the Project Editor role in an existing production project used by another division of your company. Once they grant you that role, replicate the setup you have in the development environment in that project.

The correct option is:

- **[x] Create a new project, enable the Compute Engine and Cloud SQL APIs in that project, and replicate the setup you have created in the development environment.**

### Explanation:

Creating a new project for the production environment is the recommended approach for several reasons:

1. **Isolation:** A new project ensures complete isolation between the development and production environments, which is crucial for maintaining security and avoiding potential conflicts or leaks. This aligns with the security team's requirement of no network routes between environments.

2. **Granular Control:** By creating a new project, you can manage IAM roles, permissions, and billing separately for the production environment, providing more granular control and enhancing security.

3. **Best Practices:** Google Cloud recommends using separate projects for different environments (development, staging, production) to streamline management, improve security, and simplify billing and resource tracking.

### Why other options are not suitable:

- **[ ] Create a new production subnet in the existing VPC and a new production Cloud SQL instance in your existing project, and deploy your application using those resources:**
  - While creating a new subnet does provide some level of isolation, it does not fully separate the environments at the project level. This option would still allow potential network routes and does not meet the requirement for complete separation.

- **[ ] Create a new project, modify your existing VPC to be a Shared VPC, share that VPC with your new project, and replicate the setup you have in the development environment in that new project in the Shared VPC:**
  - Using a Shared VPC can complicate the network configuration and does not necessarily provide the complete isolation that creating a new project does. Shared VPCs are more suitable for organizations with specific requirements for shared resources across multiple projects.

- **[ ] Ask the security team to grant you the Project Editor role in an existing production project used by another division of your company. Once they grant you that role, replicate the setup you have in the development environment in that project:**
  - This option mixes environments and roles, which can lead to security and management issues. It also violates the principle of least privilege by potentially granting unnecessary access.

By creating a new project and replicating the setup, you can ensure a clean, isolated production environment that adheres to best practices and security requirements.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### Your management has asked an external auditor to review all the resources in a specific project. The security team has enabled the Organization Policy called Domain Restricted Sharing on the organization node by specifying only your Cloud Identity domain. You want the auditor to only be able to view, but not modify, the resources in that project. What should you do?

- [ ] Ask the auditor for their Google account, and give them the Viewer role on the project.
- [ ] Ask the auditor for their Google account, and give them the Security Reviewer role on the project.
- [x] Create a temporary account for the auditor in Cloud Identity, and give that account the Viewer role on the project.
- [ ] Create a temporary account for the auditor in Cloud Identity, and give that account the Security Reviewer role on the project.

To ensure that the external auditor can view, but not modify, resources in a specific project while adhering to your organization's Domain Restricted Sharing policy, the recommended approach is:

- [x] **Create a temporary account for the auditor in Cloud Identity, and give that account the Viewer role on the project.**

### Explanation:

- **Viewer role:** This role grants read-only access to view resources within a project. Users with the Viewer role can see all resources and configurations but cannot make any modifications or perform actions that could alter the state of the project.

- **Domain Restricted Sharing policy:** This policy restricts sharing to only users within your organization's specified Cloud Identity domain. By creating a temporary account for the auditor within this domain, you ensure compliance with the policy while allowing the auditor to access the necessary resources.

### Why the other options are not the best choices:

- **Ask the auditor for their Google account, and give them the Viewer role on the project:**
  - While this option may seem straightforward, it assumes the auditor already has a Google account within your domain. Creating a temporary account ensures that you have full control over the access and can revoke it as needed after the audit.

- **Ask the auditor for their Google account, and give them the Security Reviewer role on the project:**
  - The Security Reviewer role includes permissions that are more extensive than just viewing. It allows actions related to security assessments and configurations, which may not be appropriate or necessary for the auditor's role.

- **Create a temporary account for the auditor in Cloud Identity, and give that account the Security Reviewer role on the project:**
  - Similar to the previous option, this provides unnecessary permissions that exceed the scope of what the auditor requires (viewing resources only).

### Additional considerations:

- Ensure that the temporary account created for the auditor is only active for the duration of the audit and is disabled or removed afterward to maintain security and compliance.
- Monitor the auditor's activities to ensure they adhere to the scope of their role (viewing only) and do not perform any unauthorized actions.

By creating a temporary Cloud Identity account and assigning the Viewer role to it, you provide the auditor with the necessary access to perform their audit while maintaining strict control over permissions and adherence to organizational policies.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You have a workload running on Compute Engine that is critical to your business. You want to ensure that the data on the boot disk of this workload is backed up regularly. You need to be able to restore a backup as quickly as possible in case of disaster. You also want older backups to be cleaned automatically to save on cost. You want to follow Google-recommended practices. What should you do?

- [ ] Create a Cloud Function to create an instance template.
- [x] Create a snapshot schedule for the disk using the desired interval.
- [ ] Create a cron job to create a new disk from the disk using gcloud.
- [ ] Create a Cloud Task to create an image and export it to Cloud Storage.

To ensure that the data on the boot disk of your critical Compute Engine workload is backed up regularly and following Google-recommended practices, the best approach would be:

- [2] **Create a snapshot schedule for the disk using the desired interval.**

### Explanation:

- **Create a snapshot schedule for the disk:** Compute Engine allows you to create snapshot schedules that automatically capture incremental backups of persistent disks at specified intervals. This method is efficient because it only captures changes since the last snapshot, reducing both storage costs and the time required to create backups.

### Why the other options are not the best choice:

- **Create a Cloud Function to create an instance template:**
  - This option does not directly address the backup requirements for the disk's data. Instance templates are used for creating new virtual machine instances with pre-configured settings, not for backing up data.

- **Create a cron job to create a new disk from the disk using gcloud:**
  - This approach suggests creating new disks rather than creating backups. It does not ensure that the backups are incremental or managed automatically over time.

- **Create a Cloud Task to create an image and export it to Cloud Storage:**
  - While exporting images to Cloud Storage is useful for certain scenarios, it doesn't provide automated backup capabilities for the boot disk's data. It also doesn't manage snapshots over time, including cleanup of older backups to optimize costs.

### Benefits of using snapshot schedules:

- **Automated backups:** Once configured, snapshot schedules automatically create backups at defined intervals, ensuring that your data is backed up regularly without manual intervention.

- **Incremental backups:** Snapshots capture only incremental changes since the last snapshot, reducing storage costs and the time required to perform backups.

- **Disaster recovery:** Snapshots allow you to quickly restore the boot disk in case of data loss or disaster, providing resilience to critical workloads.

- **Cost efficiency:** By managing snapshot schedules, you can define retention policies to automatically delete older snapshots, optimizing storage costs.

Therefore, creating a snapshot schedule for the disk ensures that your critical Compute Engine workload's data is backed up regularly, can be restored quickly in case of disaster, and adheres to Google-recommended practices for backup and disaster recovery.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You need to assign a Cloud Identity and Access Management (Cloud IAM) role to an external auditor. The auditor needs to have permissions to review your Google Cloud Platform (GCP) Audit Logs and also to review your Data Access logs. What should you do?

- [ ] Assign the auditor the IAM role roles/logging.privateLogViewer. Perform the export of logs to Cloud Storage.
- [x] Assign the auditor the IAM role roles/logging.privateLogViewer. Direct the auditor to also review the logs for changes to Cloud IAM policy.
- [ ] Assign the auditor's IAM user to a custom role that has logging.privateLogEntries.list permission. Perform the export of logs to Cloud Storage.
- [ ] Assign the auditor's IAM user to a custom role that has logging.privateLogEntries.list permission. Direct the auditor to also review the logs for changes to Cloud IAM policy.

Based on the provided options and the requirement that the auditor needs permissions to review both GCP Audit Logs and Data Access logs, the most suitable choice is:

- [x] Assign the auditor the IAM role roles/logging.privateLogViewer. Direct the auditor to also review the logs for changes to Cloud IAM policy.

### Explanation:

- **roles/logging.privateLogViewer:** This predefined role grants the auditor permission to view private logs, including Audit Logs and Data Access logs. It allows the auditor to access and review these logs directly within the Google Cloud Console or through API calls.

- **Direct the auditor to also review the logs for changes to Cloud IAM policy:** This additional guidance ensures that the auditor understands the scope of their access and can review relevant logs related to changes in IAM policies, which might be important for auditing purposes.

### Why the other options are not the best choice:

- **Assign the auditor the IAM role roles/logging.privateLogViewer. Perform the export of logs to Cloud Storage:**
  - This option only focuses on exporting logs to Cloud Storage and does not specify the necessary permissions for the auditor to directly review Audit Logs and Data Access logs.

- **Assign the auditor's IAM user to a custom role that has logging.privateLogEntries.list permission. Perform the export of logs to Cloud Storage:**
  - Creating a custom role with `logging.privateLogEntries.list` permission is unnecessary when there is already a predefined role (`roles/logging.privateLogViewer`) that provides the required access.

- **Assign the auditor's IAM user to a custom role that has logging.privateLogEntries.list permission. Direct the auditor to also review the logs for changes to Cloud IAM policy:**
  - Similar to the first incorrect option, this suggests using a custom role unnecessarily and also adds the requirement to review IAM policy changes, which might not be directly related to the primary task of reviewing Audit Logs and Data Access logs.

Therefore, the correct approach is to assign the predefined role `roles/logging.privateLogViewer` to the auditor and instruct them to also review logs related to changes in Cloud IAM policies to ensure comprehensive auditing and oversight.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You are managing several Google Cloud Platform (GCP) projects and need access to all logs for the past 60 days. You want to be able to explore and quickly analyze the log contents. You want to follow Google-recommended practices to obtain the combined logs for all projects. What should you do?

- [ ] Navigate to Stackdriver Logging and select resource.labels.project_id="*".
- [x] Create a Stackdriver Logging Export with a Sink destination to a BigQuery dataset. Configure the table expiration to 60 days.
- [ ] Create a Stackdriver Logging Export with a Sink destination to Cloud Storage. Create a lifecycle rule to delete objects after 60 days.
- [ ] Configure a Cloud Scheduler job to read from Stackdriver and store the logs in BigQuery. Configure the table expiration to 60 days.

To obtain combined logs for all projects over the past 60 days and follow Google-recommended practices, the best approach is:

- [2] Create a Stackdriver Logging Export with a Sink destination to a BigQuery dataset. Configure the table expiration to 60 days.

### Explanation:

- **Stackdriver Logging Export:** By setting up a logging export, you can aggregate logs from multiple projects into a single location.
- **Sink destination to BigQuery:** Exporting logs to BigQuery allows for efficient storage and querying of log data over time.
- **Table expiration:** Configuring the table expiration to 60 days ensures that logs older than the specified period are automatically deleted, aligning with data retention best practices.

### Why the other options are not the best choice:

- **Option 1:** Navigating to Stackdriver Logging and selecting `resource.labels.project_id="*"` would only allow you to view logs interactively filtered by project IDs. It doesn't provide aggregation across all projects or storage beyond what's visible in the console.
  
- **Option 3:** Exporting logs to Cloud Storage with a lifecycle rule to delete objects after 60 days is feasible but doesn't facilitate easy querying and analysis of log data as effectively as BigQuery.

- **Option 4:** Using Cloud Scheduler to periodically read from Stackdriver and store logs in BigQuery is a manual and potentially complex setup compared to using a Stackdriver Export directly to BigQuery, which is simpler and aligns more closely with Google-recommended practices for log management and analysis.

Therefore, **Option 2** is the most appropriate choice for aggregating logs across multiple GCP projects, storing them in BigQuery for efficient querying and analysis, and ensuring logs are retained for up to 60 days as per your requirement.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You need to reduce GCP service costs for a division of your company using the fewest possible steps. You need to turn off all configured services in an existing GCP project. What should you do?  -----------Issue   A 

- [x] 1. Verify that you are assigned the Project Owners IAM role for this project. 2. Locate the project in the GCP console, click Shut down and then enter the project I.
- [ ] 1. Verify that you are assigned the Project Owners IAM role for this project. 2. Switch to the project in the GCP console, locate the resources and delete them.
- [ ] 1. Verify that you are assigned the Organizational Administrator IAM role for this project. 2. Locate the project in the GCP console, enter the project ID and then click Shut down.
- [ ] 1. Verify that you are assigned the Organizational Administrators IAM role for this project. 2. Switch to the project in the GCP console, locate the resources and delete them.

For turning off all configured services in an existing GCP project to reduce costs, the correct approach is:

- [x] 1. Verify that you are assigned the Project Owners IAM role for this project. 2. Locate the project in the GCP console, click Shut down and then enter the project ID.

### Reasoning 1 is correct:

- **Project Owners IAM role:** This role provides full access to manage all resources within the project, including the ability to shut down the project.
- **Shut down the project:** This action suspends billing and stops all services within the project, effectively reducing costs.

### Why the other options are not correct:

- **Option 2:**
  - Deleting resources individually is more labor-intensive and doesn't guarantee that all services are properly shut down or that costs are minimized efficiently.

- **Option 3:**
  - Entering the project ID and clicking "Shut down" without verifying permissions and context (Project Owners role) can lead to unintended consequences if critical services are inadvertently shut down.

- **Option 4:**
  - Similar to Option 2, deleting resources individually is not as efficient as shutting down the entire project to reduce costs comprehensively.

Therefore, the recommended and correct approach is to ensure you have the Project Owners IAM role, locate the project in the GCP console, and then initiate the shutdown process for the entire project to halt all services and reduce costs effectively.
--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You are configuring service accounts for an application that spans multiple projects. Virtual Machines (VMs) running in the web-applications project need access to BigQuery datasets in crm-databases-proj. You want to follow Google-recommended practices to give access to the service account in the web-applications project. What should you do?

- [ ] Give project owner for web-applications appropriate roles to crm-databases-proj.
- [ ] Give project owner role to crm-databases-proj and the web-applications project.
- [ ] Give project owner role to crm-databases-proj and bigquery.dataViewer role to web-applications.
- [x] Give bigquery.dataViewer role to crm-databases-proj and appropriate roles to web-applications.

To follow Google-recommended practices for giving access to BigQuery datasets in `crm-databases-proj` to a service account in the `web-applications` project, you should:

**Option 4: Give `bigquery.dataViewer` role to `crm-databases-proj` and appropriate roles to `web-applications`.**

### Reasoning:

- **bigquery.dataViewer role:** This role provides read access to BigQuery datasets. It allows the service account in the `web-applications` project to view data in datasets within `crm-databases-proj` without having unnecessary permissions.

- **Appropriate roles to web-applications:** You should grant roles to the service account in `web-applications` that are necessary for its operations but strictly follow the principle of least privilege. Typically, roles like `roles/bigquery.jobUser` or `roles/bigquery.metadataViewer` might be appropriate depending on the specific tasks the service account needs to perform.

### Why the other options are not correct:

- **Option 1: Give project owner for `web-applications` appropriate roles to `crm-databases-proj`.**
  - Granting project owner roles across projects is overly permissive and violates the principle of least privilege. It gives too much control and access that might not be necessary for the service account.

- **Option 2: Give project owner role to `crm-databases-proj` and the `web-applications` project.**
  - Similar to Option 1, granting project owner roles across projects is excessive and should be avoided due to security and governance concerns.

- **Option 3: Give project owner role to `crm-databases-proj` and `bigquery.dataViewer` role to `web-applications`.**
  - This option grants too much access to `web-applications` by giving it project owner role, which is unnecessary and risky. It's better to keep roles scoped appropriately to the specific needs of each project and service account.

Therefore, **Option 4** is the correct choice as it aligns with Google-recommended practices by granting minimal necessary permissions (`bigquery.dataViewer`) to `crm-databases-proj` and ensuring appropriate roles are assigned to `web-applications` without over-provisioning privileges.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### An employee was terminated, but their access to Google Cloud Platform (GCP) was not removed until 2 weeks later. You need to find out this employee accessed any sensitive customer information after their termination. What should you do?

- [ ] View System Event Logs in Stackdriver. Search for the user's email as the principal.
- [ ] View System Event Logs in Stackdriver. Search for the service account associated with the user.
- [x] View Data Access audit logs in Stackdriver. Search for the user's email as the principal.
- [ ] View the Admin Activity log in Stackdriver. Search for the service account associated with the user.

To determine if the terminated employee accessed any sensitive customer information after their termination, you should:

**Option 3: View Data Access audit logs in Stackdriver. Search for the user's email as the principal.**

### Reasoning:

- **Data Access audit logs:** These logs provide detailed information about who accessed what data and when in Google Cloud Platform (GCP). They are crucial for auditing and compliance purposes, especially in scenarios involving access to sensitive information.

- **Search by user's email as the principal:** This approach allows you to specifically track actions performed by the terminated employee, even after their official termination date. You can search for any access or operations related to sensitive customer information during the two weeks after termination.

### Why the other options are not correct:

- **Option 1: View System Event Logs in Stackdriver. Search for the user's email as the principal.**
  - System Event Logs in Stackdriver primarily track changes to GCP resources, not user actions related to data access. They won't provide detailed information about data access events by users.

- **Option 2: View System Event Logs in Stackdriver. Search for the service account associated with the user.**
  - Service accounts are typically used for automated processes or services, not individual user access. Monitoring service account activities won't necessarily reveal actions taken by the terminated employee's personal account.

- **Option 4: View the Admin Activity log in Stackdriver. Search for the service account associated with the user.**
  - The Admin Activity log records actions related to administrative activities in GCP, such as IAM changes or resource modifications. It doesn't directly capture data access events by individual users, especially after their termination.

Therefore, **Option 3** is the most appropriate choice as it focuses on auditing data access, allows specific search by user's email (principal), and aligns with the need to track potential unauthorized access to sensitive customer information post-termination.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You need to create a custom IAM role for use with a GCP service. All permissions in the role must be suitable for production use. You also want to clearly share with your organization the status of the custom role. This will be the first version of the custom role. What should you do? -------------Issue

- [x] Use permissions in your role that use the 'supported' support level for role permissions. Set the role stage to ALPHA while testing the role permissions.
- [ ] Use permissions in your role that use the 'supported' support level for role permissions. Set the role stage to BETA while testing the role permissions.
- [ ] Use permissions in your role that use the 'testing' support level for role permissions. Set the role stage to ALPHA while testing the role permissions.
- [ ] Use permissions in your role that use the 'testing' support level for role permissions. Set the role stage to BETA while testing the role permissions.

All diff ans

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### Your company has a large quantity of unstructured data in different file formats. You want to perform ETL transformations on the data. You need to make the data accessible on Google Cloud so it can be processed by a Dataflow job. What should you do?

- [ ] Upload the data to BigQuery using the bq command line tool.
- [x] Upload the data to Cloud Storage using the gsutil command line tool.
- [ ] Upload the data into Cloud SQL using the import function in the console.
- [ ] Upload the data into Cloud Spanner using the import function in the console.

To make unstructured data accessible on Google Cloud for processing by a Dataflow job, the most appropriate solution is:

**Option 2: Upload the data to Cloud Storage using the gsutil command line tool.**

### Why Option 2 is correct:

- **Cloud Storage for Unstructured Data:** Cloud Storage is designed to store and manage unstructured data, including large files and various file formats. It provides high availability, scalability, and ease of access for data processing.

- **Data Accessibility:** Dataflow jobs can directly read data from Cloud Storage, making it a suitable staging area for data before processing with Dataflow.

- **ETL Process:** Before performing ETL (Extract, Transform, Load) transformations with Dataflow, you typically stage your data in Cloud Storage. This allows Dataflow to efficiently process and transform data from various sources.

### Why the other options are incorrect:

- **Option 1: Upload the data to BigQuery using the bq command line tool:**
  - BigQuery is not typically used for storing unstructured data directly. It is a data warehouse for structured data optimized for fast SQL queries, not for unstructured file storage.
  
- **Option 3: Upload the data into Cloud SQL using the import function in the console:**
  - Cloud SQL is a fully managed relational database service. It is not suitable for handling unstructured data and is optimized for structured data storage and SQL queries.
  
- **Option 4: Upload the data into Cloud Spanner using the import function in the console:**
  - Cloud Spanner is a horizontally scalable, strongly consistent database service. Like Cloud SQL, it is not designed for storing unstructured data or serving as a staging area for ETL processes.

Therefore, **Option 2** (Upload the data to Cloud Storage using the gsutil command line tool) is the correct choice as it aligns with best practices for handling unstructured data and preparing it for processing with Dataflow on Google Cloud.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You need to manage multiple Google Cloud projects in the fewest steps possible. You want to configure the Google Cloud SDK command line interface (CLI) so that you can easily manage multiple projects. What should you do?

- [x] 1. Create a configuration for each project you need to manage. 2. Activate the appropriate configuration when you work with each of your assigned Google Cloud projects.
- [ ] 1. Create a configuration for each project you need to manage. 2. Use gcloud init to update the configuration values when you need to work with a non-default project.
- [ ] 1. Use the default configuration for one project you need to manage. 2. Activate the appropriate configuration when you work with each of your assigned Google Cloud projects.
- [ ] 1. Use the default configuration for one project you need to manage. 2. Use gcloud init to update the configuration values when you need to work with a non-default project.

To manage multiple Google Cloud projects efficiently using the Google Cloud SDK command line interface (CLI), the recommended approach is:

**Option 1:** 
1. **Create a configuration for each project you need to manage.**
2. **Activate the appropriate configuration when you work with each of your assigned Google Cloud projects.**

### Why Option 1 is correct:

- **Creating a configuration for each project:** This step involves setting up separate configurations in your Google Cloud SDK for each project you want to manage. This allows you to define specific settings (like project ID, region, etc.) for each project independently.
  
- **Activating the appropriate configuration:** Once configurations are set up, you can easily switch between them using the `gcloud config configurations activate` command. This ensures that when you execute commands using the CLI, they apply to the correct project context.

### Why the other options are incorrect:

- **Option 2:** Using `gcloud init` to update configuration values when needed does not explicitly encourage the creation of separate configurations for each project. It may lead to confusion and potential errors when switching between projects.

- **Option 3:** Using the default configuration for one project and activating configurations manually is less efficient and could lead to mistakes if commands are run in the wrong project context.

- **Option 4:** Similar to Option 2, relying solely on `gcloud init` to update configurations for non-default projects may not provide clear separation between different project contexts.

Therefore, **Option 1** is the best choice as it promotes a clear and organized approach to managing multiple Google Cloud projects with the CLI.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### Your Managed Instance Group raised an alert stating that new instance creation has failed to create new instances. You need to maintain the number of running instances specified by the template to be able to process expected application traffic. What should you do?     ----------------Issue Big Issue

- [x] Create an instance template that contains valid syntax which will be used by the instance group. Delete any persistent disks with the same name as instance names.
- [ ] Create an instance template that contains valid syntax that will be used by the instance group. Verify that the instance name and persistent disk name values are not the same in the template.
- [ ] Verify that the instance template being used by the instance group contains valid syntax. Delete any persistent disks with the same name as instance names. Set the disks.autoDelete property to true in the instance template.
- [ ] Delete the current instance template and replace it with a new instance template. Verify that the instance name and persistent disk name values are not the same in the template. Set the disks.autoDelete property to true in the instance template.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### Your company is moving from an on-premises environment to Google Cloud. You have multiple development teams that use Cassandra environments as backend databases. They all need a development environment that is isolated from other Cassandra instances. You want to move to Google Cloud quickly and with minimal support effort. What should you do?

- [ ] 1. Build an instruction guide to install Cassandra on Google Cloud. 2. Make the instruction guide accessible to your developers.
- [x] 1. Advise your developers to go to Cloud Marketplace. 2. Ask the developers to launch a Cassandra image for their development work.
- [ ] 1. Build a Cassandra Compute Engine instance and take a snapshot of it. 2. Use the snapshot to create instances for your developers.
- [ ] 1. Build a Cassandra Compute Engine instance and take a snapshot of it. 2. Upload the snapshot to Cloud Storage and make it accessible to your developers. 3. Build instructions to create a Compute Engine instance from the snapshot so that developers can do it themselves.

The correct answer is **Option 2**:

1. Advise your developers to go to Cloud Marketplace.
2. Ask the developers to launch a Cassandra image for their development work.

**Explanation:**

- **Option 1:** Building an instruction guide to install Cassandra on Google Cloud and making it accessible to developers would require each team to set up and manage their own Cassandra environment, which could lead to inconsistencies and higher support efforts.
  
- **Option 3:** Creating a Cassandra Compute Engine instance and taking a snapshot of it limits flexibility and scalability. Each team would still need to manage their own instance based on this snapshot, which increases administrative overhead.

- **Option 4:** Taking a snapshot of a Cassandra Compute Engine instance and uploading it to Cloud Storage for developers to use still requires developers to manually create instances from the snapshot. This process lacks the simplicity and automation needed for a quick deployment.

**Why Option 2 is the best choice:**

- **Cloud Marketplace:** Google Cloud Marketplace provides pre-configured solutions, including Cassandra images, that developers can launch with minimal setup effort.
- **Isolation:** Each development team can launch their own isolated Cassandra instance without affecting others, ensuring development environments are separate and independent.
- **Ease of Deployment:** By using a pre-configured image from Cloud Marketplace, teams can quickly deploy Cassandra environments without needing detailed infrastructure setup knowledge.

This approach minimizes support efforts by leveraging Google Cloud's managed services and ensures consistent environments across development teams.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You have a Compute Engine instance hosting a production application. You want to receive an email if the instance consumes more than 90% of its CPU resources for more than 15 minutes. You want to use Google services. What should you do?   --------------Issue    2 or 4        All says 2

- [ ] 1. Create a consumer Gmail account. 2. Write a script that monitors the CPU usage. 3. When the CPU usage exceeds the threshold, have that script send an email using the Gmail account and smtp.gmail.com on port 25 as SMTP server.
- [x] 1. Create a Stackdriver Workspace, and associate your Google Cloud Platform (GCP) project with it. 2. Create an Alerting Policy in Stackdriver that uses the threshold as a trigger condition. 3. Configure your email address in the notification channel.
- [ ] 1. Create a Stackdriver Workspace, and associate your GCP project with it. 2. Write a script that monitors the CPU usage and sends it as a custom metric to Stackdriver. 3. Create an uptime check for the instance in Stackdriver.
- [ ] 1. In Stackdriver Logging, create a logs-based metric to extract the CPU usage by using this regular expression: CPU Usage: ([0-9] {1,3})% 2. In Stackdriver Monitoring, create an Alerting Policy based on this metric. 3. Configure your email address in the notification channel.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You have an application that uses Cloud Spanner as a backend database. The application has a very predictable traffic pattern. You want to automatically scale up or down the number of Spanner nodes depending on traffic. What should you do?

- [ ] Create a cron job that runs on a scheduled basis to review Cloud Monitoring metrics, and then resize the Spanner instance accordingly.
- [ ] Create a Cloud Monitoring alerting policy to send an alert to oncall SRE emails when Cloud Spanner CPU exceeds the threshold. SREs would scale resources up or down accordingly.
- [ ] Create a Cloud Monitoring alerting policy to send an alert to Google Cloud Support email when Cloud Spanner CPU exceeds your threshold. Google support would scale resources up or down accordingly.
- [x] Create a Cloud Monitoring alerting policy to send an alert to webhook when Cloud Spanner CPU is over or under your threshold. Create a Cloud Function that listens to HTTP and resizes Spanner resources accordingly.

Right Ans.
Create a Cloud Monitoring alerting policy to send an alert to webhook when Cloud Spanner CPU is over or under your threshold. Create a Cloud Function that listens to HTTP and resizes Spanner resources accordingly.


--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### Your company publishes large files on an Apache web server that runs on a Compute Engine instance. The Apache web server is not the only application running in the project. You want to receive an email when the egress network costs for the server exceed 100 dollars for the current month as measured by Google Cloud. What should you do?

- [ ] Set up a budget alert on the project with an amount of 100 dollars, a threshold of 100%, and notification type of email.
- [ ] Set up a budget alert on the billing account with an amount of 100 dollars, a threshold of 100%, and notification type of email.
- [x] Export the billing data to BigQuery. Create a Cloud Function that uses BigQuery to sum the egress network costs of the exported billing data for the Apache web server for the current month and sends an email if it is over 100 dollars. Schedule the Cloud Function using Cloud Scheduler to run hourly.
- [ ] Use the Cloud Logging Agent to export the Apache web server logs to Cloud Logging. Create a Cloud Function that uses BigQuery to parse the HTTP response log data in Cloud Logging for the current month and sends an email if the size of all HTTP responses, multiplied by current Google Cloud egress prices, totals over 100 dollars. Schedule the Cloud Function using Cloud Scheduler to run hourly.

I apologize for the confusion. Given your specific requirement to receive an email notification when the egress network costs for the Apache web server exceed $100 for the current month, let's reassess the options with this in mind:

**Option [3] Export the billing data to BigQuery. Create a Cloud Function that uses BigQuery to sum the egress network costs of the exported billing data for the Apache web server for the current month and sends an email if it is over 100 dollars. Schedule the Cloud Function using Cloud Scheduler to run hourly.**

Here’s why this option fits your needs:

- **Egress Network Costs**: This option directly addresses the requirement to monitor egress network costs specifically for the Apache web server.

- **BigQuery and Cloud Function**: Exporting billing data to BigQuery allows you to query and analyze the data, specifically focusing on egress costs incurred by the Apache web server. By using a Cloud Function, you can automate the process of checking these costs against the $100 threshold and sending an email notification if the threshold is exceeded.

- **Scheduled Execution**: Using Cloud Scheduler to run the Cloud Function hourly ensures that you are regularly monitoring the egress costs and promptly alerted if they exceed the defined threshold.

**Why Other Options Are Less Suitable:**

- **Option [1] and [2]**: Setting up budget alerts at the project or billing account level without specific filtering for egress network costs won't provide the granularity needed to monitor only egress costs for the Apache web server.

- **Option [4]**: Monitoring HTTP response logs via Cloud Logging and calculating costs based on egress volume is indirect and may not accurately reflect the actual billed egress costs from Google Cloud, which are what you want to monitor.

Therefore, **Option [3]** is the most suitable approach for monitoring egress network costs for the Apache web server and ensuring that you receive email notifications when these costs exceed $100 for the current month. It leverages Google Cloud's billing data export capabilities and automation through Cloud Functions and Cloud Scheduler to meet your specific monitoring and alerting requirements.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You have designed a solution on Google Cloud that uses multiple Google Cloud products. Your company has asked you to estimate the costs of the solution. You need to provide estimates for the monthly total cost. What should you do?

- [x] For each Google Cloud product in the solution, review the pricing details on the products pricing page. Use the pricing calculator to total the monthly costs for each Google Cloud product.
- [ ] For each Google Cloud product in the solution, review the pricing details on the products pricing page. Create a Google Sheet that summarizes the expected monthly costs for each product.
- [ ] Provision the solution on Google Cloud. Leave the solution provisioned for 1 week. Navigate to the Billing Report page in the Cloud Console. Multiply the 1 week cost to determine the monthly costs.
- [ ] Provision the solution on Google Cloud. Leave the solution provisioned for 1 week. Use Cloud Monitoring to determine the provisioned and used resource amounts. Multiply the 1 week cost to determine the monthly costs.

To estimate the monthly total cost of your solution on Google Cloud, the recommended approach is:

**[1] For each Google Cloud product in the solution, review the pricing details on the product's pricing page. Use the pricing calculator to total the monthly costs for each Google Cloud product.**

Here's why this approach is appropriate:

- **Precision in Cost Estimation**: By reviewing the pricing details for each Google Cloud product that you are using in your solution, you can accurately estimate the cost based on your specific usage patterns (such as data storage, API calls, compute hours, etc.).

- **Flexibility**: The pricing calculator allows you to input your estimated usage parameters (e.g., number of instances, storage amount, data transfer) and provides an estimate of the monthly cost. This flexibility ensures that you can adjust the estimation based on different scenarios or changes in usage patterns.

- **Comprehensive Coverage**: You can cover all aspects of your solution, including compute, storage, networking, and any additional services, by individually estimating their costs and then summing them up.

**Why Other Options Are Less Suitable:**

- **[2] Google Sheet Summary**: While creating a Google Sheet for cost estimation might be useful for documentation purposes, it doesn't provide the dynamic calculation and flexibility that the pricing calculator offers.

- **[3] and [4] Provisioning and Billing Reports**: These options involve actual provisioning and monitoring costs over a short period (one week) and then extrapolating to estimate monthly costs. This approach may not accurately reflect long-term usage patterns or seasonal variations in usage.

Therefore, using the pricing details and the pricing calculator (option [1]) is the best approach to estimate the monthly total cost of your solution on Google Cloud. This method ensures accuracy and flexibility in adjusting estimates based on your specific usage scenarios and configurations.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You have an application that receives SSL-encrypted TCP traffic on port 443. Clients for this application are located all over the world. You want to minimize latency for the clients. Which load balancing option should you use?

- [ ] HTTPS Load Balancer.
- [ ] Network Load Balancer.
- [x] SSL Proxy Load Balancer.
- [ ] Internal TCP/UDP Load Balancer. Add a firewall rule allowing ingress traffic from 0.0.0.0/0 on the target instances.

To minimize latency for clients located all over the world while receiving SSL-encrypted TCP traffic on port 443, the most suitable load balancing option would be:

**3. SSL Proxy Load Balancer.**

Here’s why SSL Proxy Load Balancer is the appropriate choice:

- **SSL Offloading**: SSL Proxy Load Balancer terminates SSL/TLS connections at the load balancer, reducing the workload on backend instances. This offloading process improves latency because the load balancer handles the cryptographic operations, leaving the backend instances to focus on processing application logic.

- **Global Scope**: SSL Proxy Load Balancer operates at Layer 7 (Application Layer) and is designed to handle SSL/TLS traffic efficiently across global locations. It provides geographic proximity to clients, which helps minimize latency by directing traffic to the nearest available load balancing endpoint.

- **Optimized for HTTPS Traffic**: While HTTPS Load Balancer also operates at Layer 7, it expects HTTP/HTTPS traffic and is tailored more for web applications rather than raw SSL/TCP traffic. SSL Proxy Load Balancer, on the other hand, is explicitly designed for SSL/TLS termination and forwarding encrypted TCP traffic.

**Why Other Options Are Less Suitable:**

- **HTTPS Load Balancer**: While it operates at Layer 7 and handles HTTPS traffic efficiently, it may not be optimal for non-HTTP SSL/TCP traffic as it expects HTTP/HTTPS requests.

- **Network Load Balancer**: Operates at Layer 4 (Transport Layer) and directs traffic based on IP protocol data. It's suitable for raw TCP/UDP traffic but doesn't provide SSL termination or application-layer optimizations that can minimize latency for SSL-encrypted traffic.

- **Internal TCP/UDP Load Balancer**: Designed for internal traffic within a Virtual Private Cloud (VPC) network, it's not suitable for handling traffic from clients located worldwide or external to the VPC network.

Therefore, **SSL Proxy Load Balancer** is the best choice for your scenario to minimize latency for clients globally while efficiently handling SSL-encrypted TCP traffic on port 443.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You have an application on a general-purpose Compute Engine instance that is experiencing excessive disk read throttling on its Zonal SSD Persistent Disk. The application primarily reads large files from disk. The disk size is currently 350 GB. You want to provide the maximum amount of throughput while minimizing costs. What should you do?

- [ ] Increase the size of the disk to 1 TB.
- [ ] Increase the allocated CPU to the instance.
- [x] Migrate to use a Local SSD on the instance.
- [ ] Migrate to use a Regional SSD on the instance.

Given the scenario where your application on a general-purpose Compute Engine instance is experiencing excessive disk read throttling on its Zonal SSD Persistent Disk, and the application primarily reads large files from disk, the recommended approach to provide maximum throughput while minimizing costs is:

- [x] **Migrate to use a Local SSD on the instance.**

Here's why this option is suitable:

1. **Local SSD Performance**: Local SSDs offer significantly higher IOPS (Input/Output Operations Per Second) and throughput compared to Zonal SSD Persistent Disks. They are particularly optimized for high-performance read and write operations, making them ideal for applications that require maximum disk performance.

2. **Reduced Latency**: Local SSDs have lower latency compared to Zonal SSD Persistent Disks because they are physically attached to the host machine. This reduces the time it takes to read large files from disk, thereby improving overall application performance.

3. **Cost Efficiency**: While Local SSDs are more expensive per GB compared to Zonal SSD Persistent Disks, they offer higher performance capabilities that can often justify the cost, especially when the application requires high throughput and low latency.

**Why Other Options Are Not Ideal:**

- **Increase the size of the disk to 1 TB**: Increasing the size of the Zonal SSD Persistent Disk may provide more storage capacity but won't necessarily improve the read throughput or reduce throttling, which is the primary issue.

- **Increase the allocated CPU to the instance**: While CPU resources are important for overall application performance, the issue here is specifically related to disk read throttling, not CPU-bound tasks. Increasing CPU resources wouldn't directly address the disk performance bottleneck.

- **Migrate to use a Regional SSD on the instance**: Regional SSDs provide redundancy across zones within the same region but have similar characteristics to Zonal SSDs in terms of performance. They don't offer the same level of performance improvement for disk read operations as Local SSDs do.

Therefore, **migrating to use a Local SSD on the instance** is the most effective solution to enhance disk read performance, address excessive read throttling, and ensure maximum throughput for your application while considering cost-efficiency.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### Your Dataproc cluster runs in a single Virtual Private Cloud (VPC) network in a single subnet with range 172.16.20.128/25. There are no private IP addresses available in the VPC network. You want to add new VMs to communicate with your cluster using the minimum number of steps. What should you do?    -----------------Issue

- [x] Modify the existing subnet range to 172.16.20.0/24. Yes
- [ ] Create a new Secondary IP Range in the VPC and configure the VMs to use that range. Yes
- [ ] Create a new VPC network for the VMs. Enable VPC Peering between the VMs' VPC network and the Dataproc cluster VPC network.
- [ ] Create a new VPC network for the VMs with a subnet of 172.32.0.0/16. Enable VPC network Peering between the Dataproc VPC network and the VMs VPC network. Configure a custom Route exchange.

If there are no private IP addresses available in the current VPC network subnet (172.16.20.128/25) and you want to add new VMs to communicate with your Dataproc cluster with minimal steps, the correct approach would be:

- [x] **Modify the existing subnet range to 172.16.20.0/24.**

Here’s why this option is appropriate:

- **Subnet Expansion**: By modifying the existing subnet range from `172.16.20.128/25` to `172.16.20.0/24`, you effectively expand the available private IP address space within the same VPC network. This allows you to allocate more IP addresses to new VMs without creating additional complexity or requiring peering with another VPC network.

- **Minimal Configuration Changes**: This option involves a straightforward adjustment of the subnet range, which is manageable through the Google Cloud Console or via `gcloud` command-line tools. It avoids the need to create secondary IP ranges, new VPC networks, or set up VPC peering, thereby minimizing configuration steps and potential operational overhead.

**Why Other Options Are Not Ideal:**

- **Creating a new Secondary IP Range in the VPC**: While this is a valid approach in some cases, modifying the subnet range directly is often simpler and more direct when you need to expand IP address availability within the same VPC subnet.

- **Creating a new VPC network and enabling VPC Peering**: This introduces additional complexity and administrative overhead, especially if it involves setting up peering between multiple VPC networks. It's a more suitable solution when distinct network isolation or management domains are necessary, which doesn't seem to be the case here.

- **Creating a new VPC network for the VMs with a subnet of 172.32.0.0/16 and enabling VPC network Peering**: This option is overly complex for simply expanding IP address space within the existing VPC network.

Therefore, **modifying the existing subnet range to 172.16.20.0/24** is the recommended approach to efficiently add new VMs that need to communicate with your Dataproc cluster while minimizing configuration steps and maintaining simplicity.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You manage an App Engine Service that aggregates and visualizes data from BigQuery. The application is deployed with the default App Engine Service account. The data that needs to be visualized resides in a different project managed by another team. You do not have access to this project, but you want your application to be able to read data from the BigQuery dataset. What should you do?

- [ ] Ask the other team to grant your default App Engine Service account the role of BigQuery Job User.
- [x] Ask the other team to grant your default App Engine Service account the role of BigQuery Data Viewer.
- [ ] In Cloud IAM of your project, ensure that the default App Engine service account has the role of BigQuery Data Viewer.
- [ ] In Cloud IAM of your project, grant a newly created service account from the other team the role of BigQuery Job User in your project.

To enable your App Engine service to read data from a BigQuery dataset in a different project where you do not have direct access, you should follow these steps:

**Option 2: Ask the other team to grant your default App Engine Service account the role of BigQuery Data Viewer.**

Here’s why this option is correct:

- **BigQuery Data Viewer Role**: Granting the BigQuery Data Viewer role to your default App Engine service account in the other team's project allows your application to query and read data from the BigQuery dataset. This role provides read access to datasets and tables, which is sufficient for your application to retrieve data for aggregation and visualization purposes.

**Why the other options are incorrect:**

- **Option 1 (BigQuery Job User)**: This role is more focused on submitting jobs to execute queries or load data into BigQuery. While it includes permissions to read data, it is broader than necessary for your requirement of only needing read access.

- **Option 3 (Granting roles in your project)**: Granting roles in your own project doesn’t provide access to data in the other team's project where the dataset resides.

- **Option 4 (Creating a new service account)**: This option involves granting access to a newly created service account from the other team in your project, which does not address the requirement of your App Engine service needing access to the dataset in the other team's project.

Therefore, **Option 2** is the correct approach as it directly addresses your need for read access to the BigQuery dataset without requiring access to the other team's project itself.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You need to create a copy of a custom Compute Engine Virtual Machine (VM) to facilitate an expected increase in application traffic due to a business acquisition. What should you do?

- [ ] Create a Compute Engine snapshot of your base VM. Create your images from that snapshot.
- [ ] Create a Compute Engine snapshot of your base VM. Create your instances from that snapshot.
- [ ] Create a custom Compute Engine image from a snapshot. Create your images from that image.
- [x] Create a custom Compute Engine image from a snapshot. Create your instances from that image.

To create a copy of a custom Compute Engine Virtual Machine (VM) to handle increased application traffic due to a business acquisition, you should:

**4. Create a custom Compute Engine image from a snapshot. Create your instances from that image.**

Here’s why this option is correct:

- **Custom Image Creation**: By creating a custom Compute Engine image from a snapshot of your base VM, you capture the exact configuration, software, and data stored on that VM at a specific point in time.
  
- **Instance Creation from Image**: Once you have the custom image, you can easily create new instances (VMs) from this image. These instances will inherit all the configurations and software settings of the original VM, including any customizations you made.

**Why other options are incorrect:**

- **Create a Compute Engine snapshot of your base VM. Create your images from that snapshot:**
  - This option is incorrect because Compute Engine snapshots are used to capture the state of persistent disks attached to VMs, not to directly create VM instances. Snapshots are used for backup, data recovery, and creating images, but you do not create instances directly from snapshots.

- **Create a Compute Engine snapshot of your base VM. Create your instances from that snapshot:**
  - Similar to the previous option, creating instances directly from a snapshot is not a standard practice. Instances are typically created from images, not from snapshots of disks.

- **Create a custom Compute Engine image from a snapshot. Create your images from that image:**
  - This option doesn’t make sense because it suggests creating images from another image, which is not a typical workflow. Images are typically created from snapshots or directly from a VM disk, not from other images.

### Conclusion:

Creating a custom Compute Engine image from a snapshot of your base VM allows you to replicate the VM's configuration efficiently. Subsequently, creating new VM instances from this custom image ensures consistency and replicates the environment to handle increased application traffic effectively.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You have deployed an application on a single Compute Engine instance. The application writes logs to disk. Users start reporting errors with the application. You want to diagnose the problem. What should you do?

- [ ] Navigate to Cloud Logging and view the application logs.
- [ ] Connect to the instance's serial console and read the application logs.
- [ ] Configure a Health Check on the instance and set a Low Healthy Threshold value.
- [x] Install and configure the Cloud Logging Agent and view the logs from Cloud Logging.

To diagnose the problem with the application that users are reporting errors with, you should:

**Install and configure the Cloud Logging Agent and view the logs from Cloud Logging.**

Here’s why this option is correct:

1. **Logging Configuration**: When an application writes logs to disk on a Compute Engine instance, the Cloud Logging Agent is typically used to stream these logs to Cloud Logging (formerly Stackdriver Logging).

2. **Centralized Log Management**: Cloud Logging provides a centralized platform to collect, view, and analyze logs from various sources, including Compute Engine instances. By installing the Cloud Logging Agent, you ensure that logs are captured and available for troubleshooting and analysis.

3. **Real-Time Monitoring**: Once the Cloud Logging Agent is configured and running on your Compute Engine instance, logs are streamed in real-time to Cloud Logging. This allows you to quickly access the most recent logs generated by your application.

**Why other options are incorrect:**

- **Navigate to Cloud Logging and view the application logs:**
  - This option assumes the logs are already being streamed to Cloud Logging. If the Cloud Logging Agent is not installed and configured, the logs written to disk on the instance won't be available in Cloud Logging. You would not see the current application logs without the agent.

- **Connect to the instance's serial console and read the application logs:**
  - This method is generally used for troubleshooting low-level system issues or when direct SSH access is not available. It's not the standard approach for viewing application logs, especially in a cloud environment where centralized logging tools like Cloud Logging are available.

- **Configure a Health Check on the instance and set a Low Healthy Threshold value:**
  - Health Checks are used to monitor the health and availability of instances based on network traffic. They are not related to application-specific logging or troubleshooting application errors.

### Conclusion:

Installing and configuring the Cloud Logging Agent on your Compute Engine instance ensures that application logs written to disk are captured and streamed to Cloud Logging. This approach allows you to efficiently diagnose and troubleshoot application errors reported by users by providing access to centralized logs in near real-time.



--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### An application generates daily reports in a Compute Engine Virtual Machine (VM). The VM is in the project corp-iot-insights. Your team operates only in the project corp-aggregate-reports and needs a copy of the daily exports in the bucket corp-aggregate-reports-storage. You want to configure access so that the daily reports from the VM are available in the bucket corp-aggregate-reports-storage and use as few steps as possible while following Google-recommended practices. What should you do?

- [ ] Move both projects under the same folder.
- [x] Grant the VM Service Account the role Storage Object Creator on corp-aggregate-reports-storage.
- [ ] Create a Shared VPC network between both projects. Grant the VM Service Account the role Storage Object Creator on corp-iot-insights.
- [ ] Make corp-aggregate-reports-storage public and create a folder with a pseudo-randomized suffix name. Share the folder with the IoT team.

To configure access so that daily reports generated by a Compute Engine VM in project `corp-iot-insights` are available in the bucket `corp-aggregate-reports-storage` in project `corp-aggregate-reports`, while following Google-recommended practices with minimal steps, you should:

**Option 2: Grant the VM Service Account the role Storage Object Creator on `corp-aggregate-reports-storage`.**

Here’s why this option is the correct choice:

1. **Service Account Access**: By granting the VM's service account the `Storage Object Creator` role on the bucket (`corp-aggregate-reports-storage`), you allow the VM to write objects (daily reports) directly to the bucket. This role specifically grants permissions to create objects, which aligns with the requirement to store daily exports.

2. **Least Privilege**: Google Cloud recommends granting the least privilege necessary for any service or user. The `Storage Object Creator` role provides sufficient permissions for the VM to perform the required task without unnecessarily broad permissions.

**Why other options are incorrect:**

- **Option 1: Move both projects under the same folder.**
  - Moving projects under the same folder does not directly address the access requirement between projects. It's a structural organization within Google Cloud and does not grant permissions across project boundaries.

- **Option 3: Create a Shared VPC network between both projects. Grant the VM Service Account the role Storage Object Creator on `corp-iot-insights`.**
  - Shared VPC is used for network connectivity and management across projects, not for granting access to storage buckets. Granting permissions via Shared VPC would not provide the necessary access to write objects to `corp-aggregate-reports-storage`.

- **Option 4: Make `corp-aggregate-reports-storage` public and create a folder with a pseudo-randomized suffix name. Share the folder with the IoT team.**
  - Making storage buckets public is generally not recommended due to security risks unless absolutely necessary. This option also involves unnecessary steps and does not follow the principle of least privilege.

### Conclusion:

Granting the VM's service account the `Storage Object Creator` role on the `corp-aggregate-reports-storage` bucket in the `corp-aggregate-reports` project ensures that the VM can write its daily reports to the specified bucket. This approach is straightforward, aligns with Google-recommended practices by using IAM roles effectively, and minimizes complexity and steps involved in managing access across projects.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You built an application on your development laptop that uses Google Cloud services. Your application uses Application Default Credentials for authentication and works fine on your development laptop. You want to migrate this application to a Compute Engine Virtual Machine (VM) and set up authentication using Google-recommended practices and minimal changes. What should you do?

- [x] Assign appropriate access for Google services to the service account used by the Compute Engine VM.
- [ ] Create a service account with appropriate access for Google services, and configure the application to use this account.
- [ ] Store credentials for service accounts with appropriate access for Google services in a config file, and deploy this config file with your application.
- [ ] Store credentials for your user account with appropriate access for Google services in a config file, and deploy this config file with your application.

To migrate your application to a Compute Engine Virtual Machine (VM) and set up authentication using Google-recommended practices with minimal changes, you should:

**Option 2: Create a service account with appropriate access for Google services, and configure the application to use this account.**

Here's why this option is the correct choice:

1. **Service Account Best Practice**: Google Cloud recommends using service accounts for authentication instead of individual user accounts for applications running on Compute Engine VMs. Service accounts are specifically designed for this purpose and provide secure access to Google Cloud services without exposing personal user credentials.

2. **Minimal Changes**: This option involves minimal changes to your existing application. You would create a service account in Google Cloud IAM, assign it the necessary roles (permissions) required by your application to interact with Google Cloud services, and then configure your application running on the Compute Engine VM to use this service account.

**Why other options are incorrect:**

- **Option 1**: While assigning appropriate access to the service account used by the Compute Engine VM is necessary, it doesn't address the authentication mechanism directly. Service accounts should be explicitly created and used for authentication purposes.
  
- **Option 3**: Storing credentials in a config file is not recommended for service accounts, as it introduces security risks and complicates credential management (e.g., handling key rotation). Service accounts are preferred because they manage credentials securely within Google Cloud IAM.
  
- **Option 4**: Storing credentials for your user account in a config file and deploying them with your application is insecure and not recommended. User accounts should not be used for application authentication due to security concerns and the lack of appropriate permissions management.

### Conclusion:

To adhere to Google-recommended practices and ensure secure authentication for your application on a Compute Engine VM, create a service account in Google Cloud IAM with the necessary roles and configure your application to use this service account for authentication. This approach provides both security and ease of management for accessing Google Cloud services from your VM-hosted application.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You need to create a Compute Engine instance in a new project that doesn't exist yet. What should you do?

- [x] Using the Cloud SDK, create a new project, enable the Compute Engine API in that project, and then create the instance specifying your new project.
- [ ] Enable the Compute Engine API in the Cloud Console, use the Cloud SDK to create the instance, and then use the --project flag to specify a new project.
- [ ] Using the Cloud SDK, create the new instance, and use the --project flag to specify the new project. Answer yes when prompted by Cloud SDK to enable the Compute Engine API.
- [ ] Enable the Compute Engine API in the Cloud Console. Go to the Compute Engine section of the Console to create a new instance, and look for the Create In A New Project option in the creation form.

To create a Compute Engine instance in a new project that doesn't exist yet, you should follow these steps:

**Option 1: Using the Cloud SDK, create a new project, enable the Compute Engine API in that project, and then create the instance specifying your new project.**

Here’s a breakdown of why this is the correct approach:

1. **Create a new project**: Use the Cloud SDK (`gcloud`) command to create a new Google Cloud project. This step ensures that the project exists before attempting to create any resources in it.
   
2. **Enable the Compute Engine API**: Once the project is created, enable the Compute Engine API using the Cloud SDK. This API needs to be enabled before you can create Compute Engine instances.

3. **Create the instance**: After enabling the API, use another Cloud SDK command to create the Compute Engine instance, specifying the newly created project using the `--project` flag.

**Why other options are incorrect:**

- **Option 2**: Enabling the Compute Engine API in the Cloud Console first doesn’t create the new project. You need to create the project first before enabling APIs.
  
- **Option 3**: While this option mentions using the `--project` flag to specify the new project, it suggests answering yes to enable the Compute Engine API during instance creation, which is not the correct sequence. API enabling should be done separately before creating instances.
  
- **Option 4**: There is no explicit option in the Compute Engine instance creation form to "Create In A New Project." Projects need to be created first, then resources like instances can be created within them.

### Conclusion:

The recommended approach is to use the Cloud SDK to first create a new project, enable the Compute Engine API in that project, and then proceed to create the Compute Engine instance specifying the newly created project using the `--project` flag. This sequence ensures that you have a project to place your resources in and that the necessary API is enabled for resource creation.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### Your company runs one batch process in an on-premises server that takes around 30 hours to complete. The task runs monthly, can be performed offline, and must be restarted if interrupted. You want to migrate this workload to the cloud while minimizing cost. What should you do?  ------------------Issue

- [ ] Migrate the workload to a Compute Engine Preemptible VM.
- [ ] Migrate the workload to a Google Kubernetes Engine cluster with Preemptible nodes.
- [x] Migrate the workload to a Compute Engine VM. Start and stop the instance as needed.
- [ ] Create an Instance Template with Preemptible VMs On. Create a Managed Instance Group from the template and adjust Target CPU Utilization. Migrate the workload.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You are developing a new application and are looking for a Jenkins installation to build and deploy your source code. You want to automate the installation as quickly and easily as possible. What should you do?

- [x] Deploy Jenkins through the Google Cloud Marketplace.
- [ ] Create a new Compute Engine instance. Run the Jenkins executable.
- [ ] Create a new Kubernetes Engine cluster. Create a deployment for the Jenkins image.
- [ ] Create an instance template with the Jenkins executable. Create a Managed Instance Group with this template.

To automate the installation of Jenkins for building and deploying your source code as quickly and easily as possible on Google Cloud Platform, you should choose:

**Option 1: Deploy Jenkins through the Google Cloud Marketplace.**

### Why This Option is Suitable:

- **Google Cloud Marketplace:** Deploying Jenkins through the Google Cloud Marketplace offers several advantages:
  - **Easy Deployment:** Jenkins can be deployed with just a few clicks, automating the setup process.
  - **Pre-configured Environment:** The Jenkins installation from the Marketplace is typically pre-configured and optimized for use on Google Cloud.
  - **Integration with Google Cloud Services:** Simplifies integration with other Google Cloud services such as Cloud Storage, Compute Engine, Kubernetes Engine, etc.
  - **Automated Updates:** Ensures that Jenkins is kept up-to-date with the latest patches and updates.

### Why Other Options are Less Suitable:

- **Option 2: Create a new Compute Engine instance. Run the Jenkins executable.**
  - **Issues:** This option requires manual installation and configuration of Jenkins on a Compute Engine instance, which is more labor-intensive and prone to configuration errors. It lacks the ease and automation provided by the Marketplace deployment.

- **Option 3: Create a new Kubernetes Engine cluster. Create a deployment for the Jenkins image.**
  - **Issues:** While Kubernetes can automate deployment and scaling, setting up and managing a Kubernetes cluster for Jenkins adds complexity. It may be overkill if you only need Jenkins for CI/CD without leveraging Kubernetes features extensively.

- **Option 4: Create an instance template with the Jenkins executable. Create a Managed Instance Group with this template.**
  - **Issues:** This approach is similar to Option 2 but involves managing instances as part of a group, which doesn't inherently simplify Jenkins installation or management compared to Marketplace deployment. It also lacks the integration benefits with Google Cloud services.

### Summary:
Deploying Jenkins through the Google Cloud Marketplace is the recommended approach because it provides an automated, pre-configured solution that minimizes setup time and effort while integrating well with other Google Cloud services you might use for your CI/CD pipeline.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You have downloaded and installed the gcloud command line interface (CLI) and have authenticated with your Google Account. Most of your Compute Engine instances in your project run in the europe-west1-d zone. You want to avoid having to specify this zone with each CLI command when managing these instances. What should you do?

- [x] Set the europe-west1-d zone as the default zone using the gcloud config subcommand.
- [ ] In the Settings page for Compute Engine under Default location, set the zone to europe-west1-d.
- [ ] In the CLI installation directory, create a file called default.conf containing zone=europe-west1-d.
- [ ] Create a Metadata entry on the Compute Engine page with key compute/zone and value europe-west1-d.

To avoid specifying the zone with each CLI command when managing your Compute Engine instances, you should:

**Option 1: Set the europe-west1-d zone as the default zone using the gcloud config subcommand.**

### Why This is the Correct Option:

- **gcloud config Subcommand:** Using the `gcloud config` command, you can set default configurations such as the zone. This is the recommended and straightforward method to set default values for your gcloud commands.

  ```sh
  gcloud config set compute/zone europe-west1-d
  ```

  This command sets the default zone to `europe-west1-d` for your gcloud CLI, so you don't have to specify it with every command.

### Why Other Options Are Incorrect:

- **Option 2: In the Settings page for Compute Engine under Default location, set the zone to europe-west1-d.**
  - **Incorrect:** Google Cloud Console settings for default location affect the web interface but do not influence the CLI configuration. This setting is for default values in the console UI, not for the gcloud CLI.

- **Option 3: In the CLI installation directory, create a file called default.conf containing zone=europe-west1-d.**
  - **Incorrect:** There is no such mechanism in gcloud CLI to read default configuration from a `default.conf` file in the installation directory. The gcloud CLI uses configuration files stored in the user's home directory under `.config/gcloud`.

- **Option 4: Create a Metadata entry on the Compute Engine page with key compute/zone and value europe-west1-d.**
  - **Incorrect:** Metadata entries for Compute Engine instances do not set default configuration values for the gcloud CLI. Metadata entries are typically used for passing information to instances, not for setting gcloud CLI defaults.

### Summary:
Using the `gcloud config set compute/zone europe-west1-d` command is the correct and recommended way to set the default zone for your gcloud CLI commands.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### The core business of your company is to rent out construction equipment at large scale. All the equipment that is being rented out has been equipped with multiple sensors that send event information every few seconds. These signals can vary from engine status, distance traveled, fuel level, and more. Customers are billed based on the consumption monitored by these sensors. You expect high throughput - up to thousands of events per hour per device - and need to retrieve consistent data based on the time of the event. Storing and retrieving individual signals should be atomic. What should you do?

- [ ] Create a file in Cloud Storage per device and append new data to that file.
- [ ] Create a file in Cloud Filestore per device and append new data to that file.
- [ ] Ingest the data into Datastore. Store data in an entity group based on the device.
- [x] Ingest the data into Cloud Bigtable. Create a row key based on the event timestamp.

For a scenario where you need to handle high-throughput, time-series data with consistent and atomic storage and retrieval, **Cloud Bigtable** is the best fit. Here’s why:

**Option 4: Ingest the data into Cloud Bigtable. Create a row key based on the event timestamp.**

### Why Cloud Bigtable is Suitable:
- **High Throughput:** Cloud Bigtable is designed for high-throughput, low-latency workloads. It can handle thousands of events per hour per device efficiently.
- **Time-Series Data:** Creating a row key based on the event timestamp allows for efficient time-based queries, making it ideal for time-series data.
- **Atomic Operations:** Cloud Bigtable supports atomic read and write operations, ensuring data consistency.
- **Scalability:** It scales seamlessly to accommodate large volumes of data from numerous devices.

### Why Other Options Are Less Suitable:
- **Option 1: Create a file in Cloud Storage per device and append new data to that file.**
  - **Not Designed for High Throughput:** Cloud Storage is not optimized for high-throughput, low-latency writes and reads.
  - **Atomicity:** Ensuring atomic append operations and consistent reads can be complex and error-prone.

- **Option 2: Create a file in Cloud Filestore per device and append new data to that file.**
  - **Not Ideal for High Throughput:** Cloud Filestore, while providing a shared file system, is not designed for handling the volume and velocity of data in this use case.
  - **Complexity in Atomic Operations:** Similar to Cloud Storage, ensuring atomic operations can be challenging.

- **Option 3: Ingest the data into Datastore. Store data in an entity group based on the device.**
  - **Limited Throughput:** Datastore (now Firestore in Datastore mode) is optimized for high-availability and consistency but may not handle the required throughput as efficiently as Bigtable.
  - **Time-Series Queries:** Datastore is not optimized for time-series data storage and retrieval, making it less suitable for querying based on event timestamps.

### Summary:
Using **Cloud Bigtable** with row keys based on event timestamps is the most appropriate solution for handling high-throughput, time-series data with consistent and atomic operations. This approach ensures that you can efficiently store, retrieve, and process the large volume of sensor data generated by your construction equipment.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You are asked to set up application performance monitoring on Google Cloud projects A, B, and C as a single pane of glass. You want to monitor CPU, memory, and disk. What should you do?

- [ ] Enable API and then share charts from project A, B, and C.
- [ ] Enable API and then give the metrics.reader role to projects A, B, and C.
- [ ] Enable API and then use default dashboards to view all projects in sequence.
- [x] Enable API, create a workspace under project A, and then add projects B and C.

To set up application performance monitoring on Google Cloud projects A, B, and C as a single pane of glass for monitoring CPU, memory, and disk, you should:

- **Option 4: Enable API, create a workspace under project A, and then add projects B and C.**

### Explanation:

**Option 4** is the best approach because it allows you to use Google Cloud Monitoring (formerly Stackdriver) to aggregate and view metrics from multiple projects in a single place. By creating a Monitoring Workspace in project A and adding projects B and C to this workspace, you can seamlessly monitor and visualize metrics across all three projects.

### Why the Other Options Are Less Suitable:

- **Option 1: Enable API and then share charts from project A, B, and C.**
  - This option involves manually sharing charts, which can be cumbersome and does not provide a unified, single-pane-of-glass view.

- **Option 2: Enable API and then give the metrics.reader role to projects A, B, and C.**
  - This option focuses on permissions but does not address the need for a centralized view. It only ensures that the projects can read metrics, not that they can be viewed together in one dashboard.

- **Option 3: Enable API and then use default dashboards to view all projects in sequence.**
  - Default dashboards are limited to individual projects. Viewing each project in sequence does not provide a consolidated view, which is less efficient and more fragmented.

### Summary:

**Option 4** provides the best solution by leveraging Google Cloud Monitoring workspaces to create a single, centralized dashboard. This allows for an integrated view of CPU, memory, and disk metrics across projects A, B, and C, providing a cohesive and efficient monitoring setup.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You created several resources in multiple Google Cloud projects. All projects are linked to different billing accounts. To better estimate future charges, you want to have a single visual representation of all costs incurred. You want to include new cost data as soon as possible. What should you do?

- [x] Configure Billing Data Export to BigQuery and visualize the data in Data Studio.
- [ ] Visit the Cost Table page to get a CSV export and visualize it using Data Studio.
- [ ] Fill all resources in the Pricing Calculator to get an estimate of the monthly cost.
- [ ] Use the Reports view in the Cloud Billing Console to view the desired cost information.

The best approach to achieve a single visual representation of all costs incurred across multiple Google Cloud projects, with new cost data included as soon as possible, is:

- **Option 1: Configure Billing Data Export to BigQuery and visualize the data in Data Studio.**

### Explanation:

**Option 1** is the most effective method because it allows for a comprehensive and up-to-date visualization of all costs. By exporting billing data to BigQuery, you can aggregate cost data from multiple projects and billing accounts. Then, using Data Studio, you can create dynamic and customizable visual reports that update automatically as new data is added to BigQuery.

### Why the Other Options Are Less Suitable:

- **Option 2: Visit the Cost Table page to get a CSV export and visualize it using Data Studio.**
  - While this method allows for visualization, it is manual and not real-time. You would need to regularly export the CSV and update the visualization, which is not efficient and can lead to outdated information.

- **Option 3: Fill all resources in the Pricing Calculator to get an estimate of the monthly cost.**
  - The Pricing Calculator provides estimates, not actual costs. It does not account for real-time usage data and changes, making it less accurate for current cost tracking and forecasting.

- **Option 4: Use the Reports view in the Cloud Billing Console to view the desired cost information.**
  - The Reports view in the Cloud Billing Console provides insights but is limited in its ability to customize and aggregate data across multiple projects and billing accounts in the same visual representation. It also lacks the flexibility and depth of visualization that Data Studio offers.

### Summary:

**Option 1** combines the strengths of BigQuery and Data Studio to provide a scalable, real-time, and customizable solution for visualizing billing data across multiple projects and billing accounts. This method ensures that you have the most up-to-date information and a comprehensive view of your costs.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### Your company has workloads running on Compute Engine and on-premises. The Google Cloud Virtual Private Cloud (VPC) is connected to your WAN over a Virtual Private Network (VPN). You need to deploy a new Compute Engine instance and ensure that no public Internet traffic can be routed to it. What should you do?

- [x] Create the instance without a public IP address.
- [ ] Create the instance with Private Google Access enabled.
- [ ] Create a deny-all egress firewall rule on the VPC network.
- [ ] Create a route on the VPC to route all traffic to the instance over the VPN tunnel.

The correct approach is:

- **Option 1: Create the instance without a public IP address.**

### Explanation:

**Option 1** ensures that the Compute Engine instance cannot send or receive traffic directly over the public internet, as it will not have a public IP address. This setup inherently restricts the instance to private network communication only, which can route traffic through your VPN or other internal networks as necessary.

### Why the Other Options Are Less Suitable:

- **Option 2: Create the instance with Private Google Access enabled.**
  - Private Google Access allows instances without a public IP to access Google APIs and services over Google's internal network. However, it doesn't inherently prevent public internet access if the instance has a public IP.

- **Option 3: Create a deny-all egress firewall rule on the VPC network.**
  - While a deny-all egress firewall rule can prevent the instance from sending traffic to the internet, it may be overly restrictive and impact other required communications within the VPC. It also does not prevent the instance from being accessible from the internet if it has a public IP.

- **Option 4: Create a route on the VPC to route all traffic to the instance over the VPN tunnel.**
  - This option focuses on directing traffic over the VPN but doesn't address the fundamental issue of the instance having a public IP. The instance could still potentially route traffic over the internet if it has a public IP address.

### Summary:
**Option 1** directly addresses the requirement by ensuring the instance does not have a public IP address, thus preventing any public internet traffic from being routed to or from the instance. This is the simplest and most straightforward method to ensure compliance with the requirement.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### Your team maintains the infrastructure for your organization. The current infrastructure requires changes. You need to share your proposed changes with the rest of the team. You want to follow Google's recommended best practices. What should you do?     -------------------Issue

- [ ] Use Deployment Manager templates to describe the proposed changes and store them in a Cloud Storage bucket.
- [x] Use Deployment Manager templates to describe the proposed changes and store them in Cloud Source Repositories.
- [ ] Apply the changes in a development environment, run gcloud compute instances list, and then save the output in a shared Storage bucket.
- [ ] Apply the changes in a development environment, run gcloud compute instances list, and then save the output in Cloud Source Repositories.

To follow Google's recommended best practices for sharing proposed infrastructure changes with your team, you should:

**Option 2: Use Deployment Manager templates to describe the proposed changes and store them in Cloud Source Repositories.**

Here’s why this option is the correct choice:

- **Deployment Manager Templates:** Google Cloud Deployment Manager allows you to define your infrastructure in templates using YAML or Python. These templates are declarative and version-controlled, making it easier to manage changes over time.
  
- **Cloud Source Repositories:** Google Cloud Source Repositories provide a Git version control system with built-in collaboration tools. Storing Deployment Manager templates in Cloud Source Repositories allows your team members to review, collaborate, and track changes effectively.
  
- **Best Practice:** Storing infrastructure-as-code (IaC) templates in version-controlled repositories like Cloud Source Repositories ensures that changes are documented, auditable, and can be rolled back if necessary. It also promotes consistency across environments and enables continuous integration and continuous deployment (CI/CD) pipelines.

**Why the Other Options Are Wrong:**

- **Option 1: Use Deployment Manager templates to describe the proposed changes and store them in a Cloud Storage bucket:**
  - While Cloud Storage can store files, it lacks version control and collaboration features that are essential for managing infrastructure changes in a team environment. It's not designed for versioning or code review processes.

- **Option 3: Apply the changes in a development environment, run `gcloud compute instances list`, and then save the output in a shared Storage bucket:**
  - Saving the output of `gcloud compute instances list` in a Storage bucket does not provide a structured way to share proposed infrastructure changes. It also doesn’t capture the declarative nature of infrastructure changes or allow for versioning and rollback capabilities.

- **Option 4: Apply the changes in a development environment, run `gcloud compute instances list`, and then save the output in Cloud Source Repositories:**
  - Saving command output in Cloud Source Repositories is not suitable for sharing proposed infrastructure changes. It does not provide structured templates or version control for infrastructure-as-code, which are critical for managing complex environments.

Therefore, **Option 2** is the best approach as it aligns with Google's recommended practices for managing infrastructure changes using Deployment Manager templates in a version-controlled repository like Cloud Source Repositories.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You have a Compute Engine instance hosting an application used between 9 AM and 6 PM on weekdays. You want to back up this instance daily for disaster recovery purposes. You want to keep the backups for 30 days. You want the Google-recommended solution with the least management overhead and the least number of services. What should you do?

- [ ] 1. Update your instances' metadata to add the following value: snapshot-schedule: 0 1 * * * 2. Update your instances' metadata to add the following value: snapshot-retention: 30.
- [x] 1. In the Cloud Console, go to the Compute Engine Disks page and select your instance's disk. 2. In the Snapshot Schedule section, select Create Schedule and configure the following parameters: Schedule frequency: Daily. Start time: 1:00 AM - 2:00 AM. Autodelete snapshots after: 30 days.
- [ ] 1. Create a Cloud Function that creates a snapshot of your instance's disk. 2. Create a Cloud Function that deletes snapshots that are older than 30 days. 3. Use Cloud Scheduler to trigger both Cloud Functions daily at 1:00 AM.
- [ ] 1. Create a bash script in the instance that copies the content of the disk to Cloud Storage. 2. Create a bash script in the instance that deletes data older than 30 days in the backup Cloud Storage bucket. 3. Configure the instance's crontab to execute these scripts daily at 1:00 AM.

The correct choice for your requirement is:

- **Option 2:**
  - **In the Cloud Console, go to the Compute Engine Disks page and select your instance's disk.**
  - **In the Snapshot Schedule section, select Create Schedule and configure the following parameters: Schedule frequency: Daily. Start time: 1:00 AM - 2:00 AM. Autodelete snapshots after: 30 days.**

### Explanation:
**Option 2** is the best choice because it provides a straightforward and Google-recommended solution with the least management overhead and the fewest number of services involved. Here’s why:

1. **Ease of Configuration:** The Cloud Console offers a user-friendly interface to create and manage snapshot schedules effortlessly.
2. **Automated Management:** The snapshot schedule feature in Compute Engine automatically handles the creation and deletion of snapshots based on your specified schedule and retention period, ensuring your backups are consistent and reliable.
3. **Minimal Overhead:** This approach leverages the built-in functionalities of Google Cloud, reducing the need for additional services or custom scripts, which simplifies the management.
4. **Cost-Effective:** By using the built-in snapshot scheduling, you avoid the potential costs associated with additional services like Cloud Functions or Cloud Storage.

### Why the Other Options Are Less Suitable:

- **Option 1:**
  - **Not a Standard Practice:** Updating instance metadata to manage snapshots is not a standard or recommended method for managing backups in Google Cloud, making it less reliable and harder to maintain.

- **Option 3:**
  - **More Services Involved:** This option requires setting up Cloud Functions and Cloud Scheduler, adding unnecessary complexity and additional services to manage.
  - **Maintenance Overhead:** You would need to develop, deploy, and maintain the Cloud Functions code, increasing operational overhead.

- **Option 4:**
  - **Manual Script Management:** This option involves creating and managing custom scripts, increasing maintenance effort.
  - **Less Reliable:** Using crontab for scheduling backups can be less reliable compared to the built-in cloud scheduling features, and it also involves managing Cloud Storage manually.

Therefore, **Option 2** offers a simple, reliable, and Google-recommended solution with minimal management overhead and the least number of additional services required.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### Your existing application running in Google Kubernetes Engine (GKE) consists of multiple pods running on four GKE n1-standard-2 nodes. You need to deploy additional pods requiring n2-highmem-16 nodes without any downtime. What should you do?

- [ ] Use gcloud container clusters upgrade. Deploy the new services.
- [x] Create a new Node Pool and specify machine type n2-highmem-16. Deploy the new pods.
- [ ] Create a new cluster with n2-highmem-16 nodes. Redeploy the pods and delete the old cluster.
- [ ] Create a new cluster with both n1-standard-2 and n2-highmem-16 nodes. Redeploy the pods and delete the old cluster.

The correct approach is:

- **Option 2: Create a new Node Pool and specify machine type n2-highmem-16. Deploy the new pods.**

### Explanation:

**Option 2** is the best choice because it allows you to add new nodes with the desired machine type to your existing cluster without causing downtime. Here's why:

1. **Node Pools:** GKE allows you to create multiple node pools within a single cluster. Each node pool can have different machine types, allowing you to run workloads with different resource requirements within the same cluster.
2. **No Downtime:** By adding a new node pool with the `n2-highmem-16` machine type, you can deploy the additional pods to this new node pool without affecting the existing pods running on the `n1-standard-2` nodes.
3. **Scalability:** This approach allows you to scale your resources based on the requirements of different workloads while maintaining high availability and minimizing disruption.

### Why the Other Options Are Less Suitable:

- **Option 1: Use gcloud container clusters upgrade. Deploy the new services.**
  - This option is for upgrading the control plane and node versions of your cluster. It does not address adding different machine types or handling workloads requiring different resource profiles.

- **Option 3: Create a new cluster with n2-highmem-16 nodes. Redeploy the pods and delete the old cluster.**
  - Creating a new cluster and migrating all services involves significant overhead, potential downtime, and complexity in managing the transition, which is unnecessary when you can simply add a new node pool to the existing cluster.

- **Option 4: Create a new cluster with both n1-standard-2 and n2-highmem-16 nodes. Redeploy the pods and delete the old cluster.**
  - Similar to Option 3, this option introduces unnecessary complexity and potential downtime. It is more efficient to manage different workloads within a single cluster using multiple node pools.

Therefore, **Option 2** is the most efficient and effective method to deploy additional pods requiring `n2-highmem-16` nodes without causing downtime.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You have an application that uses Cloud Spanner as a database backend to keep current state information about users. Cloud Bigtable logs all events triggered by users. You export Cloud Spanner data to Cloud Storage during daily backups. One of your analysts asks you to join data from Cloud Spanner and Cloud Bigtable for specific users. You want to complete this ad hoc request as efficiently as possible. What should you do?

- [ ] Create a dataflow job that copies data from Cloud Bigtable and Cloud Storage for specific users.
- [ ] Create a dataflow job that copies data from Cloud Bigtable and Cloud Spanner for specific users.
- [ ] Create a Cloud Dataproc cluster that runs a Spark job to extract data from Cloud Bigtable and Cloud Storage for specific users.
- [x] Create two separate BigQuery external tables on Cloud Storage and Cloud Bigtable. Use the BigQuery console to join these tables through user fields, and apply appropriate filters.

To efficiently join data from Cloud Spanner and Cloud Bigtable for specific users, considering your setup and requirements, the best approach would be:

**Option 2: Create a dataflow job that copies data from Cloud Bigtable and Cloud Spanner for specific users.**

Here’s why this option is suitable:

- **Dataflow for Data Integration:** Google Cloud Dataflow is designed for large-scale data integration and processing. It can handle data from multiple sources (Cloud Spanner and Cloud Bigtable) and perform transformations or joins as needed.
  
- **Efficiency:** Dataflow allows you to parallelize data processing tasks, ensuring efficient data retrieval and processing. You can optimize the job to fetch data only for specific users, reducing unnecessary data transfer and processing.
  
- **Integration of Cloud Spanner and Cloud Bigtable:** Since your analyst needs to join data from both Cloud Spanner (for current state information about users) and Cloud Bigtable (for event logs), Dataflow provides a unified framework to integrate these datasets seamlessly.

**Why the Other Options Are Not Suitable:**

- **Option 1: Create a dataflow job that copies data from Cloud Bigtable and Cloud Storage for specific users:**
  - This option involves Cloud Storage, which is typically used for storing backups or large datasets but might not be directly suitable for real-time data processing or joining with Cloud Spanner data.

- **Option 3: Create a Cloud Dataproc cluster that runs a Spark job to extract data from Cloud Bigtable and Cloud Storage for specific users:**
  - Dataproc with Spark is powerful for data processing, but it adds complexity compared to Dataflow for this scenario. Dataproc clusters need management and scaling considerations, which might not be necessary for an ad hoc request.

- **Option 4: Create two separate BigQuery external tables on Cloud Storage and Cloud Bigtable. Use the BigQuery console to join these tables through user fields, and apply appropriate filters:**
  - BigQuery can handle large datasets and complex queries, but using external tables from Cloud Storage and Cloud Bigtable requires loading data into BigQuery, which might not be ideal for ad hoc, real-time query needs. It's more suited for structured data analysis after data is already loaded into BigQuery.

Therefore, **Option 2** is the most efficient choice as it leverages Dataflow’s capabilities for integrating and processing data from Cloud Spanner and Cloud Bigtable directly, tailored to the specific user data join requirements.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You are hosting an application from Compute Engine Virtual Machines (VMs) in us-central1-a. You want to adjust your design to support the failure of a single Compute Engine zone, eliminate downtime, and minimize cost. What should you do?

- [x] Create Compute Engine resources in us-central1-b. Balance the load across both us-central1-a and us-central1-b.
- [ ] Create a Managed Instance Group and specify us-central1-a as the zone. Configure the Health Check with a short Health Interval.
- [ ] Create an HTTP(S) Load Balancer. Create one or more global forwarding rules to direct traffic to your VMs.
- [ ] Perform regular backups of your application. Create a Cloud Monitoring Alert and be notified if your application becomes unavailable. Restore from backups when notified.

To adjust your design to support the failure of a single Compute Engine zone in us-central1-a, eliminate downtime, and minimize cost, the best approach would be:

**Option 1: Create Compute Engine resources in us-central1-b. Balance the load across both us-central1-a and us-central1-b.**

Here's why this option is suitable:

- **High Availability:** By deploying Compute Engine resources (VM instances) across multiple zones (us-central1-a and us-central1-b), you ensure that if one zone experiences a failure, your application can continue running from the other zone without downtime.
  
- **Load Balancing:** Balancing the load across both zones allows your application to distribute traffic effectively. You can use either a regional or global load balancer to achieve this, ensuring that traffic is routed to healthy instances across zones.
  
- **Cost Optimization:** This setup helps minimize costs because you can distribute your resources across zones within the same region, leveraging Google Cloud's regional pricing models.

**Why the Other Options Are Not Suitable:**

- **Option 2: Create a Managed Instance Group and specify us-central1-a as the zone. Configure the Health Check with a short Health Interval:**
  - This option focuses on a single zone (us-central1-a), which does not provide fault tolerance in case of zone failure. It does not address the requirement to support failure of a single zone.

- **Option 3: Create an HTTP(S) Load Balancer. Create one or more global forwarding rules to direct traffic to your VMs:**
  - While a global load balancer can distribute traffic globally, it does not inherently solve the problem of zone failure. It is more focused on global traffic distribution rather than zone-level fault tolerance.

- **Option 4: Perform regular backups of your application. Create a Cloud Monitoring Alert and be notified if your application becomes unavailable. Restore from backups when notified:**
  - This option addresses backup and monitoring for disaster recovery, which is important but does not directly relate to minimizing downtime due to zone failure. It's a reactive measure rather than a proactive high availability solution.

Therefore, **Option 1** is the correct choice as it directly aligns with the requirement to support the failure of a single Compute Engine zone (us-central1-a), ensures high availability, and minimizes costs by leveraging multiple zones within the same region.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### A colleague handed over a Google Cloud Platform project for you to maintain. As part of a security checkup, you want to review who has been granted the Project Owner role. What should you do?

- [ ] In the console, validate which SSH keys have been stored as project-wide keys.
- [ ] Navigate to Identity-Aware Proxy and check the permissions for these resources.
- [ ] Enable Audit Logs on the IAM &amp; admin page for all resources, and validate the results.
- [x] Use the command gcloud projects get-iam-policy to view the current role assignments.

To review who has been granted the Project Owner role in a Google Cloud Platform project, the correct approach is:

**4. Use the command `gcloud projects get-iam-policy` to view the current role assignments.**

**Reasons why other options are wrong:**

1. **In the console, validate which SSH keys have been stored as project-wide keys:**
   - Checking SSH keys stored as project-wide keys does not directly provide information about IAM roles assigned to users. SSH keys are used for authentication purposes and are not directly related to IAM role assignments.

2. **Navigate to Identity-Aware Proxy and check the permissions for these resources:**
   - Identity-Aware Proxy (IAP) is used for controlling access to your web applications and services rather than reviewing IAM role assignments across the project. Checking permissions in IAP settings won't give you a comprehensive view of all IAM role assignments in the project.

3. **Enable Audit Logs on the IAM & admin page for all resources, and validate the results:**
   - Enabling Audit Logs provides a record of actions performed in Google Cloud, but it doesn't directly show the current IAM role assignments. Audit Logs can help track changes to IAM policies but won't provide a straightforward list of who currently holds the Project Owner role.

**Why Option 4 is Correct:**
- **gcloud command (`gcloud projects get-iam-policy`):** This command allows you to retrieve the IAM policy bindings for a project, which includes detailed information about who has what role (such as Project Owner, Editor, Viewer, etc.) in the project. It provides a clear and direct way to review the current IAM role assignments, including the Project Owner role.

In summary, using the `gcloud projects get-iam-policy` command is the appropriate method to review who has been granted the Project Owner role in a Google Cloud Platform project, as it directly retrieves the IAM policy bindings for detailed examination.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You are running multiple VPC-native Google Kubernetes Engine clusters in the same subnet. The IPs available for the nodes are exhausted, and you want to ensure that the clusters can grow in nodes when needed. What should you do?

- [ ] Create a new subnet in the same region as the subnet being used.
- [ ] Add an alias IP range to the subnet used by the GKE clusters.
- [ ] Create a new VPC, and set up VPC peering with the existing VP.
- [x] Expand the CIDR range of the relevant subnet for the cluster.

To ensure that your VPC-native Google Kubernetes Engine (GKE) clusters can grow in nodes when needed and the IPs available for the nodes are exhausted, the best approach is:

- **Expand the CIDR range of the relevant subnet for the cluster.**

**Reasoning:**
- **IP Address Expansion:** By expanding the CIDR range of the subnet, you increase the pool of available IP addresses for nodes within that subnet. This directly addresses the issue of IP address exhaustion.
- **Minimal Disruption:** While expanding the CIDR range requires careful planning to avoid disruption, it allows you to scale your clusters within the same subnet without the need for additional subnets or VPCs.
- **Scalability:** This approach ensures that your existing clusters can grow in terms of node count without running into IP address limitations.

**Why Other Options are Wrong:**
- **Create a new subnet in the same region:** Creating a new subnet doesn't solve the problem of IP address exhaustion in the existing subnet. It also adds complexity and requires migration of existing resources.
- **Add an alias IP range:** Adding an alias IP range is useful for adding more IPs within a subnet but might not solve the problem if the subnet's CIDR range itself is too small.
- **Create a new VPC and set up VPC peering:** This approach involves unnecessary complexity and doesn't directly address the IP address exhaustion issue in the current subnet.

Therefore, **expanding the CIDR range of the relevant subnet for the cluster** is the correct choice to ensure that your VPC-native GKE clusters can grow in nodes when needed while maintaining network efficiency and minimizing disruption.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You have a batch workload that runs every night and uses a large number of Virtual Machines (VMs). It is fault-tolerant and can tolerate some of the VMs being terminated. The current cost of VMs is too high. What should you do?

- [x] Run a test using simulated maintenance events. If the test is successful, use preemptible N1 Standard VMs when running future jobs.
- [ ] Run a test using simulated maintenance events. If the test is successful, use N1 Standard VMs when running future jobs.
- [ ] Run a test using a Managed Instance Group. If the test is successful, use N1 Standard VMs in the Managed Instance Group when running future jobs.
- [ ] Run a test using N1 standard VMs instead of N2. If the test is successful, use N1 Standard VMs when running future jobs.

The correct option and reasoning are as follows:

**Option 1: Run a test using simulated maintenance events. If the test is successful, use preemptible N1 Standard VMs when running future jobs.**

**Reasoning:**
- **Preemptible VMs:** Preemptible VMs are much cheaper compared to regular VMs because they can be preempted by Google Cloud with short notice (up to 24 hours). They are ideal for fault-tolerant workloads like batch processing where instances can be terminated and restarted without impacting the overall job.
- **Simulated Maintenance Events:** Testing with simulated maintenance events allows you to verify how your workload handles instance terminations. Since your workload is fault-tolerant and can tolerate VM terminations, preemptible VMs are a suitable choice to reduce costs.
- **N1 Standard VMs:** N1 Standard VMs are a generation of VM types in Google Cloud and opting for preemptible instances within this category provides cost savings without sacrificing performance, assuming your workload can handle interruptions.

**Why Other Options are Wrong:**
- **Option 2:** Testing with simulated maintenance events alone without specifying the use of preemptible VMs does not address cost concerns directly. Regular N1 Standard VMs are more expensive and wouldn't optimize costs.
- **Option 3:** Using Managed Instance Groups (MIGs) is a good practice for managing groups of VM instances for scalability and autohealing, but it doesn't inherently reduce costs unless combined with preemptible VMs.
- **Option 4:** Switching between N1 and N2 VM types doesn't directly address cost concerns related to the type of VM being used; preemptible instances offer cost savings irrespective of the specific VM generation.

Therefore, **Option 1** is the best choice because it directly addresses cost reduction by leveraging preemptible VMs, which are suitable for your fault-tolerant batch workload and can significantly lower your compute costs.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You are working with a user to set up an application in a new VPC behind a firewall. The user is concerned about data egress. You want to configure the fewest open egress ports. What should you do?

- [x] Set up a low-priority (65534) rule that blocks all egress and a high-priority rule (1000) that allows only the appropriate ports.
- [ ] Set up a high-priority (1000) rule that pairs both ingress and egress ports.
- [ ] Set up a high-priority (1000) rule that blocks all egress and a low-priority (65534) rule that allows only the appropriate ports.
- [ ] Set up a high-priority (1000) rule to allow the appropriate ports.

Based on the options provided and the requirement to minimize open egress ports while securing data egress in a VPC, the correct approach is:

**Set up a low-priority (65534) rule that blocks all egress and a high-priority rule (1000) that allows only the appropriate ports.**

Here’s why this option is the correct choice:

- **Low-Priority (65534) Rule Blocking All Egress:** By setting up a rule with a lower priority (higher numerical value) such as 65534, you effectively block all outbound traffic by default. This helps in ensuring that no unauthorized data leaves the VPC, which is crucial for security.

- **High-Priority (1000) Rule Allowing Specific Ports:** Following the rule that blocks all egress traffic, you then set up a rule with a higher priority (lower numerical value) such as 1000 to allow outbound traffic on only the necessary ports required for your application. This approach implements the principle of least privilege, allowing only essential outbound connections and reducing the risk of data exfiltration.

This configuration ensures that your VPC is secured by default with minimal open egress ports, thereby addressing the user's concern about data egress while maintaining necessary connectivity for your application.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### Your company runs its Linux workloads on Compute Engine instances. Your company will be working with a new operations partner that does not use Google Accounts. You need to grant access to the instances to your operations partner so they can maintain the installed tooling. What should you do?

- [x] Enable Cloud IAP for the Compute Engine instances, and add the operations partner as a Cloud IAP Tunnel User.
- [ ] Tag all the instances with the same network tag. Create a firewall rule in the VPC to grant TCP access on port 22 for traffic from the operations partner to instances with the network tag.
- [ ] Set up Cloud VPN between your Google Cloud VPC and the internal network of the operations partner.
- [ ] Ask the operations partner to generate SSH key pairs, and add the public keys to the VM instances.

Based on the scenario where your operations partner does not use Google Accounts and you need to grant them access to Compute Engine instances, the most appropriate option would be:

**Enable Cloud IAP for the Compute Engine instances, and add the operations partner as a Cloud IAP Tunnel User.**

### Explanation:

- **Cloud IAP (Identity-Aware Proxy):**
  - Cloud IAP provides a way to control access to your Compute Engine instances based on identities rather than IP addresses.
  - **Advantages:**
    - Secure access: Cloud IAP allows you to enforce access control policies based on user identity and context.
    - Centralized management: You can manage access centrally through IAM (Identity and Access Management) roles and policies.
    - No need to manage SSH keys: Unlike SSH key management, Cloud IAP does not require you to distribute or manage keys manually.

### Why Other Options are Not Ideal:

- **Tagging Instances and Firewall Rules:**
  - While you can use network tags and firewall rules to control SSH access, this approach requires managing IP addresses or tags, which may not align with your partner's operational setup. It also doesn't provide identity-based access control.

- **Cloud VPN:**
  - Setting up a Cloud VPN would establish a secure connection between networks, but it doesn't directly address granting access to individual Compute Engine instances based on user identity.

- **SSH Key Pairs:**
  - Asking the operations partner to generate SSH key pairs and adding them to VM instances is a viable approach but requires manual key management and may not align with your security policies if you prefer identity-based access control.

### Conclusion:

Enabling Cloud IAP for Compute Engine instances and adding the operations partner as a Cloud IAP Tunnel User aligns well with secure access practices and allows you to leverage identity-based access control without managing SSH keys or IP addresses explicitly. This approach provides a more scalable and secure solution for granting access to your instances.


--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You have created a code snippet that should be triggered whenever a new file is uploaded to a Cloud Storage bucket. You want to deploy this code snippet. What should you do?

- [ ] Use App Engine and configure Cloud Scheduler to trigger the application using Pub/Sub.
- [x] Use Cloud Functions and configure the bucket as a trigger resource.
- [ ] Use Google Kubernetes Engine and configure a CronJob to trigger the application using Pub/Sub.
- [ ] Use Dataflow as a batch job, and configure the bucket as a data source.

To deploy a code snippet that should be triggered whenever a new file is uploaded to a Cloud Storage bucket, the best option is:

**Option 2: Use Cloud Functions and configure the bucket as a trigger resource.**

### Explanation:

- **Cloud Functions:** Cloud Functions are serverless functions that automatically respond to events in Google Cloud services. They are designed to handle event-driven scenarios, such as reacting to changes in Cloud Storage.

- **Bucket Trigger:** Cloud Functions can be configured with Cloud Storage triggers, where the function is automatically invoked when specific events occur in the bucket, such as when a new file is uploaded.

### Why Other Options are Not Ideal:

- **Option 1: Use App Engine and configure Cloud Scheduler to trigger the application using Pub/Sub:**
  - **Issue:** This approach involves unnecessary complexity and overhead. App Engine is typically used for web applications, and using Cloud Scheduler with Pub/Sub introduces additional components that are not needed for a simple file upload trigger.

- **Option 3: Use Google Kubernetes Engine and configure a CronJob to trigger the application using Pub/Sub:**
  - **Issue:** Kubernetes is more suited for containerized applications that require orchestration. Using it for a simple file upload trigger is overkill and adds complexity without significant benefit.

- **Option 4: Use Dataflow as a batch job, and configure the bucket as a data source:**
  - **Issue:** Dataflow is used for large-scale data processing tasks, typically involving data transformations and batch processing. It is not suitable for responding to real-time events such as file uploads to trigger a code snippet immediately.

### Conclusion:

Cloud Functions with a Cloud Storage trigger (Option 2) is the most appropriate choice because it directly addresses the requirement to trigger a code snippet in response to a file upload event in a Cloud Storage bucket. It's lightweight, serverless, and scales automatically, making it ideal for event-driven scenarios like this one.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You have been asked to set up Object Lifecycle Management for objects stored in storage buckets. The objects are written once and accessed frequently for 30 days. After 30 days, the objects are not read again unless there is a special need. The objects should be kept for three years, and you need to minimize cost. What should you do?

- [ ] Set up a policy that uses Nearline storage for 30 days and then moves to Archive storage for three years.
- [x] Set up a policy that uses Standard storage for 30 days and then moves to Archive storage for three years.
- [ ] Set up a policy that uses Nearline storage for 30 days, then moves the Coldline for one year, and then moves to Archive storage for two years.
- [ ] Set up a policy that uses Standard storage for 30 days, then moves to Coldline for one year, and then moves to Archive storage for two years.

To minimize cost while meeting the requirements for Object Lifecycle Management, here’s the recommended approach:

**Option 1: Set up a policy that uses Nearline storage for 30 days and then moves to Archive storage for three years.**

### Explanation:

- **Nearline Storage:** Nearline storage is cost-effective for data that is accessed less frequently but requires quick access when needed. It's suitable for objects accessed less than once a month.
  
- **Archive Storage:** Archive storage is the lowest-cost storage option in Cloud Storage, ideal for data that is rarely accessed and stored for long-term retention. Accessing data in Archive storage has a retrieval time of milliseconds to hours.

### Why Other Options are Not Ideal:

- **Option 2: Set up a policy that uses Standard storage for 30 days and then moves to Archive storage for three years:**
  - **Issue:** Standard storage is more expensive than Nearline storage and is designed for frequently accessed data, which is not cost-effective for data that becomes infrequently accessed after 30 days.

- **Option 3: Set up a policy that uses Nearline storage for 30 days, then moves to Coldline for one year, and then moves to Archive storage for two years:**
  - **Issue:** Coldline storage is designed for data that is accessed less frequently than once a month over a year, which might not be necessary if the data is expected to be accessed even less frequently.

- **Option 4: Set up a policy that uses Standard storage for 30 days, then moves to Coldline for one year, and then moves to Archive storage for two years:**
  - **Issue:** Similar to Option 2, using Standard storage for the initial 30 days incurs unnecessary cost for data that will become infrequently accessed after that period.

### Conclusion:

Option 1 is the best choice because it optimizes cost by using Nearline storage for the initial 30 days when data is accessed frequently and then transitions to Archive storage, which offers the lowest cost for long-term retention. This setup aligns with the requirement to keep the objects for three years while minimizing storage costs after the initial 30-day period of frequent access.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You are storing sensitive information in a Cloud Storage bucket. For legal reasons, you need to be able to record all requests that read any of the stored data. You want to make sure you comply with these requirements. What should you do?

- [ ] Enable the Identity Aware Proxy API on the project.
- [ ] Scan the bucket using the Data Loss Prevention API.
- [ ] Allow only a single Service Account access to read the data.
- [x] Enable Data Access audit logs for the Cloud Storage API.

The correct approach to comply with the requirement of recording all requests that read sensitive information from a Cloud Storage bucket is:

**4. Enable Data Access audit logs for the Cloud Storage API.**

### Explanation:

**Option 4: Enable Data Access audit logs for the Cloud Storage API.**
- **Audit Logging:** Enabling Data Access audit logs for the Cloud Storage API allows you to record and monitor all actions and requests made on objects within your Cloud Storage bucket.
- **Compliance Requirement:** This option directly addresses the need to record all read requests for sensitive information, ensuring compliance with legal requirements.
- **Visibility and Accountability:** Audit logs provide detailed information such as who accessed the data, when the access occurred, and what actions were taken, which is crucial for security audits and compliance checks.

**Why Other Options are Wrong:**

**Option 1: Enable the Identity Aware Proxy API on the project.**
- **Purpose Misalignment:** Identity Aware Proxy (IAP) is used for controlling access to applications rather than auditing access to data stored in Cloud Storage. It does not provide the logging and auditing capabilities required to record all read requests.

**Option 2: Scan the bucket using the Data Loss Prevention API.**
- **Data Loss Prevention:** While Data Loss Prevention (DLP) API is useful for identifying and protecting sensitive data within your bucket, it does not log all access requests. It focuses on data classification and prevention rather than logging access activities.

**Option 3: Allow only a single Service Account access to read the data.**
- **Access Restriction:** Limiting access to a single Service Account can enhance security by reducing the attack surface but does not inherently log all access requests. It does not provide the comprehensive audit trail needed to meet the compliance requirement of recording all read requests.

### Conclusion:

Enabling Data Access audit logs for the Cloud Storage API (Option 4) is the appropriate solution as it directly addresses the requirement to record all requests that read sensitive information from your Cloud Storage bucket. It ensures transparency, accountability, and compliance with legal and regulatory requirements regarding data access auditing.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You are the team lead of a group of 10 developers. You provided each developer with an individual Google Cloud Project that they can use as their personal sandbox to experiment with different Google Cloud solutions. You want to be notified if any of the developers are spending above $500 per month on their sandbox environment. What should you do?

- [ ] Create a single budget for all projects and configure budget alerts on this budget.
- [ ] Create a separate billing account per sandbox project and enable BigQuery billing exports. Create a Data Studio dashboard to plot the spending per billing account.
- [x] Create a budget per project and configure budget alerts on all of these budgets.
- [ ] Create a single billing account for all sandbox projects and enable BigQuery billing exports. Create a Data Studio dashboard to plot the spending per project.

The correct approach would be:

**3. Create a budget per project and configure budget alerts on all of these budgets.**

### Explanation:

**Option 3: Create a budget per project and configure budget alerts on all of these budgets.**
- **Granular Control:** Creating a budget per project allows you to set specific spending limits tailored to each developer's sandbox environment.
- **Alert Configuration:** By configuring budget alerts on each individual project's budget, you can receive notifications when the spending reaches or exceeds the defined threshold ($500 per month in this case).
- **Visibility and Control:** This approach provides clear visibility into spending for each developer's sandbox project and enables proactive management by alerting you to potential overspending early.

**Why Other Options are Wrong:**

**Option 1: Create a single budget for all projects and configure budget alerts on this budget.**
- **Lack of Granularity:** A single budget for all projects would aggregate spending across all sandbox environments, making it difficult to identify which specific project is exceeding the budget threshold.
- **Limited Control:** This option does not provide the fine-grained control needed to monitor individual developer's spending patterns effectively.

**Option 2: Create a separate billing account per sandbox project and enable BigQuery billing exports. Create a Data Studio dashboard to plot the spending per billing account.**
- **Overly Complex:** Creating separate billing accounts per project is unnecessary for monitoring spending thresholds. It also complicates billing management and does not directly provide budget alerts for proactive monitoring.
- **BigQuery Usage:** Enabling BigQuery billing exports and using Data Studio for reporting adds unnecessary complexity for a straightforward budget monitoring requirement.

**Option 4: Create a single billing account for all sandbox projects and enable BigQuery billing exports. Create a Data Studio dashboard to plot the spending per project.**
- **Similar Issues:** Like Option 2, using a single billing account for all projects does not allow for individual budgeting and alerting per project. It also introduces complexity with BigQuery exports and Data Studio reporting which are not essential for basic budget monitoring.

### Conclusion:
Creating a budget per project and configuring budget alerts on each individual project's budget (Option 3) is the recommended approach. It provides the necessary granularity, control, and simplicity to effectively monitor and manage spending across multiple sandbox environments in Google Cloud.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You are deploying a production application on Compute Engine. You want to prevent anyone from accidentally destroying the instance by clicking the wrong button. What should you do?

- [ ] Disable the flag Delete boot disk when instance is deleted.
- [x] Enable delete protection on the instance.
- [ ] Disable Automatic restart on the instance.
- [ ] Enable Preemptibility on the instance.

The best approach is:

**2. Enable delete protection on the instance.**

### Explanation:

**Option 2: Enable delete protection on the instance.**
- **Prevents Accidental Deletion:** Enabling delete protection directly prevents the instance from being accidentally deleted. This feature is specifically designed to protect instances from accidental deletion by adding an additional step and confirmation when attempting to delete the instance.
- **Suitable for Production Environments:** This is the most straightforward and effective method to ensure that critical production instances are not removed unintentionally.

**Why Other Options are Wrong:**

**Option 1: Disable the flag Delete boot disk when instance is deleted.**
- **Not a Direct Solution:** While this ensures that the boot disk persists after the instance is deleted, it does not prevent the instance itself from being deleted. The instance can still be accidentally terminated, causing downtime.

**Option 3: Disable Automatic restart on the instance.**
- **Irrelevant to Deletion Protection:** Disabling automatic restart affects the behavior of the instance in the event of a crash or maintenance event, not its deletion. It has no impact on preventing accidental deletions.

**Option 4: Enable Preemptibility on the instance.**
- **Increased Risk of Deletion:** Enabling preemptibility makes instances more prone to being automatically terminated by Google Cloud after a short period (typically 24 hours). This option is intended for cost-saving on non-critical workloads and is the opposite of what is needed to protect a critical production instance from accidental deletion.

### Conclusion:
Enabling delete protection on the instance (Option 2) is the most appropriate measure to safeguard a production application from accidental deletion. This approach directly addresses the requirement to prevent unintentional instance termination, ensuring the instance remains operational until a deliberate action is taken to remove the delete protection.
--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### Your company uses a large number of Google Cloud services centralized in a single project. All teams have specific projects for testing and development. The DevOps team needs access to all of the production services in order to perform their job. You want to prevent Google Cloud product changes from broadening their permissions in the future. You want to follow Google-recommended practices. What should you do?

- [ ] Grant all members of the DevOps team the role of Project Editor on the organization level.
- [ ] Grant all members of the DevOps team the role of Project Editor on the production project.
- [x] Create a custom role that combines the required permissions. Grant the DevOps team the custom role on the production project.
- [ ] Create a custom role that combines the required permissions. Grant the DevOps team the custom role on the organization level.

The best approach is:

**3. Create a custom role that combines the required permissions. Grant the DevOps team the custom role on the production project.**

### Explanation:

**Option 3: Create a custom role that combines the required permissions. Grant the DevOps team the custom role on the production project.**
- **Principle of Least Privilege:** By creating a custom role, you ensure that the DevOps team has exactly the permissions they need to perform their tasks, and nothing more. This minimizes security risks.
- **Scoped Access:** Granting the custom role specifically on the production project ensures that permissions are limited to the relevant scope, preventing unnecessary access to other projects or environments.
- **Avoiding Future Broadening of Permissions:** Custom roles are defined by you and will not change unless you update them, so future changes to Google Cloud products or predefined roles won't inadvertently grant additional permissions.

**Why Other Options are Wrong:**

**Option 1: Grant all members of the DevOps team the role of Project Editor on the organization level.**
- **Excessive Permissions:** This grants broad access to all projects within the organization, not just the production project. It violates the principle of least privilege.
- **Risk of Misuse:** Any changes or actions taken by the DevOps team could impact all projects, increasing the risk of accidental or malicious changes.

**Option 2: Grant all members of the DevOps team the role of Project Editor on the production project.**
- **Excessive Permissions:** The Project Editor role includes broad permissions that might not all be necessary for the DevOps team, increasing the potential for misuse or accidental changes.
- **Future Broadening of Permissions:** If Google Cloud changes the permissions associated with the Project Editor role, the DevOps team could gain additional permissions that are not intended.

**Option 4: Create a custom role that combines the required permissions. Grant the DevOps team the custom role on the organization level.**
- **Excessive Scope:** Granting the custom role at the organization level provides permissions beyond the production project, which is not necessary and increases security risks.
- **Increased Risk:** Similar to option 1, this could lead to unintended changes or access across the entire organization.

### Conclusion:
Creating a custom role and granting it specifically on the production project (Option 3) provides a tailored, secure, and controlled approach, adhering to Google-recommended practices and the principle of least privilege.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You are building an application that processes data files uploaded from thousands of suppliers. Your primary goals for the application are data security and the expiration of aged data. You need to design the application to: Restrict access so that suppliers can access only their own data. Give suppliers write access to data only for 30 minutes. Delete data that is over 45 days old. You have a very short development cycle, and you need to make sure that the application requires minimal maintenance. Which two strategies should you use? (Choose two.)

- [x] Build a lifecycle policy to delete Cloud Storage objects after 45 days.
- [x] Use signed URLs to allow suppliers limited time access to store their objects.
- [ ] Set up an SFTP server for your application, and create a separate user for each supplier.
- [ ] Build a Cloud function that triggers a timer of 45 days to delete objects that have expired.
- [ ] Develop a script that loops through all Cloud Storage buckets and deletes any buckets that are older than 45 days.

The best strategies to meet the requirements are:

**1. Build a lifecycle policy to delete Cloud Storage objects after 45 days.**
**2. Use signed URLs to allow suppliers limited time access to store their objects.**

### Explanation:

**Option 1: Build a lifecycle policy to delete Cloud Storage objects after 45 days.**
- **Automated Data Expiration:** Cloud Storage lifecycle policies allow you to automatically delete objects after a specified period. This meets the requirement of deleting data that is over 45 days old without requiring manual intervention or additional maintenance.
- **Minimal Maintenance:** Lifecycle policies are easy to set up and manage, providing a low-maintenance solution for automatic data expiration.

**Option 2: Use signed URLs to allow suppliers limited time access to store their objects.**
- **Restricted Access:** Signed URLs can be generated to give time-limited access to specific Cloud Storage objects. This ensures that suppliers can only upload data within a specific time frame (e.g., 30 minutes).
- **Granular Access Control:** Signed URLs allow you to control access at a fine-grained level, ensuring that each supplier can only access their own data.
- **Minimal Maintenance:** Signed URLs are straightforward to implement and do not require a complex setup or ongoing maintenance.

**Why Other Options are Wrong:**

**Option 3: Set up an SFTP server for your application, and create a separate user for each supplier.**
- **Complex and High Maintenance:** Setting up and managing an SFTP server and individual user accounts for thousands of suppliers is complex and high-maintenance. This approach does not easily support the requirement for time-limited access or automated data deletion.

**Option 4: Build a Cloud function that triggers a timer of 45 days to delete objects that have expired.**
- **Additional Development and Maintenance:** While this approach could meet the data expiration requirement, it involves additional development and ongoing maintenance. Cloud Storage lifecycle policies provide a simpler and more efficient solution for this requirement.

**Option 5: Develop a script that loops through all Cloud Storage buckets and deletes any buckets that are older than 45 days.**
- **Inefficient and Error-Prone:** This approach is not efficient for handling a large number of objects and is prone to errors. It also requires regular execution and maintenance of the script, making it a less desirable solution compared to lifecycle policies.

### Conclusion:

**Option 1 (lifecycle policies)** and **Option 2 (signed URLs)** are the most suitable strategies. They provide automated, secure, and low-maintenance solutions to meet the requirements of restricting access, providing time-limited write access, and deleting aged data.
--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### Your company wants to standardize the creation and management of multiple Google Cloud resources using Infrastructure as Code. You want to minimize the amount of repetitive code needed to manage the environment. What should you do?

- [x] Develop templates for the environment using Cloud Deployment Manager.
- [ ] Use curl in a terminal to send a REST request to the relevant Google API for each individual resource.
- [ ] Use the Cloud Console interface to provision and manage all related resources.
- [ ] Create a bash script that contains all requirement steps as gcloud commands.

The correct answer is:

**1. Develop templates for the environment using Cloud Deployment Manager.**

### Explanation:

**Option 1: Develop templates for the environment using Cloud Deployment Manager.**
- **Infrastructure as Code (IaC):** Cloud Deployment Manager allows you to define and manage your Google Cloud resources in a declarative manner using templates. This approach is well-suited for Infrastructure as Code (IaC) as it enables you to specify the desired state of your resources, which Deployment Manager then uses to create and manage those resources automatically.
- **Reusability and Standardization:** Templates in Cloud Deployment Manager can be reused and shared across different projects and environments, minimizing repetitive code and ensuring a consistent setup.
- **Complex Resource Management:** It supports managing complex resource configurations and dependencies, making it easier to handle multiple interconnected resources.

**Why Other Options are Wrong:**

**Option 2: Use curl in a terminal to send a REST request to the relevant Google API for each individual resource.**
- **Manual and Error-Prone:** Using `curl` to send REST requests for each resource is a highly manual process that requires detailed knowledge of the API and is prone to human error. It lacks the benefits of a declarative approach and does not support reusability or standardization.

**Option 3: Use the Cloud Console interface to provision and manage all related resources.**
- **Not Scalable:** While the Cloud Console interface is user-friendly, it is not practical for managing multiple resources, especially in a standardized and repeatable manner. It is a manual process and does not support Infrastructure as Code practices.

**Option 4: Create a bash script that contains all required steps as gcloud commands.**
- **Imperative Approach:** While bash scripts can automate resource creation using `gcloud` commands, they follow an imperative approach rather than a declarative one. This makes them harder to maintain and less efficient for managing complex infrastructure.
- **Lack of Advanced Features:** Bash scripts do not natively support features like dependency management, error handling, and rollback, which are crucial for managing infrastructure at scale.

### Conclusion:

Option 1 is the best choice because Cloud Deployment Manager allows you to manage your infrastructure using templates, providing a declarative, reusable, and standardized approach to Infrastructure as Code. This minimizes repetitive code and simplifies the management of complex resource configurations.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You are performing a monthly security check of your Google Cloud environment and want to know who has access to view data stored in your Google Cloud Project. What should you?

- [ ] Enable Audit Logs for all APIs that are related to data storage.
- [x] Review the IAM permissions for any role that allows for data access.
- [ ] Review the Identity-Aware Proxy settings for each resource.
- [ ] Create a Data Loss Prevention job.

The correct answer is:

**2. Review the IAM permissions for any role that allows for data access.**

### Explanation:

**Option 2: Review the IAM permissions for any role that allows for data access.**
- **Access Control:** Reviewing IAM permissions is the most direct way to determine who has access to view data in your Google Cloud project. IAM (Identity and Access Management) allows you to assign roles to users, groups, or service accounts, and each role has specific permissions associated with it. By reviewing these roles and permissions, you can see exactly who has access to your data.
- **Comprehensive:** This method provides a clear overview of all the permissions granted within your project and helps identify potential security risks or over-privileged accounts.

**Why Other Options are Wrong:**

**Option 1: Enable Audit Logs for all APIs that are related to data storage.**
- **Monitoring, Not Access Control:** While enabling audit logs is a good practice for monitoring access and activity, it does not directly show you who has access. Instead, it logs actions taken on resources, which is useful for forensic analysis but not for understanding current access permissions.

**Option 3: Review the Identity-Aware Proxy settings for each resource.**
- **Limited Scope:** Identity-Aware Proxy (IAP) settings are specific to applications protected by IAP and do not cover all data storage resources. This method would not provide a comprehensive view of all access permissions for data stored across different services in your Google Cloud project.

**Option 4: Create a Data Loss Prevention job.**
- **Data Sensitivity, Not Access:** A Data Loss Prevention (DLP) job is used to scan for sensitive information within your data, such as personally identifiable information (PII). It does not provide information about who has access to view the data.

### Conclusion:

Option 2 is the best choice because reviewing IAM permissions gives you a direct and comprehensive understanding of who has access to view data in your Google Cloud project. This method allows you to audit and manage access control effectively, ensuring that only authorized users can view sensitive data.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### Your company has embraced a hybrid cloud strategy where some of the applications are deployed on Google Cloud. A Virtual Private Network (VPN) tunnel connects your Virtual Private Cloud (VPC) in Google Cloud with your company's on-premises network. Multiple applications in Google Cloud need to connect to an on-premises database server, and you want to avoid having to change the IP configuration in all of your applications when the IP of the database changes. What should you do?

- [ ] Configure Cloud NAT for all subnets of your VPC to be used when egressing from the VM instances.
- [x] Create a private zone on Cloud DNS, and configure the applications with the DNS name.
- [ ] Configure the IP of the database as custom metadata for each instance, and query the metadata server.
- [ ] Query the Compute Engine internal DNS from the applications to retrieve the IP of the database.

The correct answer is:

**2. Create a private zone on Cloud DNS, and configure the applications with the DNS name.**

### Explanation:

**Option 2: Create a private zone on Cloud DNS, and configure the applications with the DNS name.**
- **DNS Flexibility:** By creating a private DNS zone in Cloud DNS, you can create a DNS record for the on-premises database. Applications can be configured to connect to the database using its DNS name. If the IP address of the database changes, you can simply update the DNS record, and all applications will resolve the new IP address without requiring any changes in their configurations.
- **Centralized Management:** This approach centralizes the management of the database's IP address and eliminates the need to update each application's configuration individually.

**Why Other Options are Wrong:**

**Option 1: Configure Cloud NAT for all subnets of your VPC to be used when egressing from the VM instances.**
- **Purpose of Cloud NAT:** Cloud NAT is used to provide outgoing (egress) internet access for instances without assigning them external IP addresses. It does not help with managing internal connectivity between Google Cloud VPC and on-premises resources or with dynamic IP resolution.

**Option 3: Configure the IP of the database as custom metadata for each instance, and query the metadata server.**
- **Inconvenient Updates:** This method would require updating the custom metadata for each instance whenever the database IP changes, which can be cumbersome and error-prone. It lacks the flexibility and ease of use provided by a DNS-based solution.

**Option 4: Query the Compute Engine internal DNS from the applications to retrieve the IP of the database.**
- **Not Applicable for On-Premises:** The Compute Engine internal DNS is designed to resolve internal Google Cloud resource names to their respective IP addresses. It cannot be used to resolve the IP addresses of on-premises resources.

### Conclusion:

Option 2 is the most appropriate solution as it provides a scalable and maintainable way to manage the IP address of the on-premises database server. By using Cloud DNS with a private zone, you can ensure that applications in Google Cloud always connect to the correct IP address via the DNS name, even if the database's IP address changes. This method simplifies management and avoids the need for frequent reconfiguration of the applications.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You have developed a containerized web application that will serve internal colleagues during business hours. You want to ensure that no costs are incurred outside of the hours the application is used. You have just created a new Google Cloud project and want to deploy the application. What should you do?

- [ ] Deploy the container on Cloud Run for Anthos, and set the minimum number of instances to zero.
- [x] Deploy the container on Cloud Run (fully managed), and set the minimum number of instances to zero.
- [ ] Deploy the container on App Engine flexible environment with autoscaling, and set the value min_instances to zero in the app.yaml.
- [ ] Deploy the container on App Engine flexible environment with manual scaling, and set the value instances to zero in the app.yaml.

Cloud Run is a managed compute platform that lets you run containers directly on top of Google's scalable infrastructure.
Cloud Run adds and removes instances automatically to handle all incoming requests. If there are no incoming requests to your service, even the last remaining instance will be removed. This behavior is commonly referred to as scale to zero.

The correct answer is:

**2. Deploy the container on Cloud Run (fully managed), and set the minimum number of instances to zero.**

### Explanation:

**Option 2: Deploy the container on Cloud Run (fully managed), and set the minimum number of instances to zero.**
- **Fully Managed Service:** Cloud Run (fully managed) is designed to run containerized applications and automatically scale down to zero instances when there is no traffic. This means you will not incur costs outside of business hours when the application is not in use.
- **Cost Efficiency:** By setting the minimum number of instances to zero, you ensure that no costs are incurred when the application is not being accessed, which aligns with your requirement to avoid costs outside of business hours.

**Why Other Options are Wrong:**

**Option 1: Deploy the container on Cloud Run for Anthos, and set the minimum number of instances to zero.**
- **Complexity:** Cloud Run for Anthos runs on GKE (Google Kubernetes Engine), which might incur additional costs for the underlying GKE cluster, even if the application instances are scaled to zero. This does not fully prevent costs outside of business hours.

**Option 3: Deploy the container on App Engine flexible environment with autoscaling, and set the value min_instances to zero in the app.yaml.**
- **Minimum Instances:** In the App Engine flexible environment, you cannot set `min_instances` to zero. The minimum value is 1, which means at least one instance will always be running and incurring costs, even outside of business hours.

**Option 4: Deploy the container on App Engine flexible environment with manual scaling, and set the value instances to zero in the app.yaml.**
- **Invalid Configuration:** You cannot set the number of instances to zero in the manual scaling configuration of App Engine flexible environment. Manual scaling requires a fixed number of instances, which means there will always be running instances incurring costs.

### Conclusion:

Option 2 is the best choice because Cloud Run (fully managed) allows for the containerized application to automatically scale to zero instances when not in use, ensuring no costs are incurred outside of business hours. This meets your requirement of avoiding costs during non-business hours while providing a managed environment for your application.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You have experimented with Google Cloud using your own credit card and expensed the costs to your company. Your company wants to streamline the billing process and charge the costs of your projects to their monthly invoice. What should you do?

- [ ] Grant the financial team the IAM role of Billing Account User on the billing account linked to your credit card.
- [ ] Set up BigQuery billing export and grant your financial department IAM access to query the data.
- [ ] Create a ticket with Google Billing Support to ask them to send the invoice to your company.
- [x] Change the billing account of your projects to the billing account of your company.

The correct answer is:

**4. Change the billing account of your projects to the billing account of your company.**

### Explanation:

**Option 4: Change the billing account of your projects to the billing account of your company.**
- **Direct Solution:** This option directly addresses the requirement to streamline the billing process by charging the costs of your projects to your company’s billing account. By changing the billing account associated with your projects, you ensure that all future expenses are billed to your company’s account and included in their monthly invoice.
- **Simplicity and Efficiency:** This method is straightforward and efficient. It ensures that all costs are consolidated under the company's billing account, simplifying the billing and reconciliation process for the financial team.

**Why Other Options are Wrong:**

**Option 1: Grant the financial team the IAM role of Billing Account User on the billing account linked to your credit card.**
- **Incorrect Scope:** This does not change the billing source of the projects. It only gives the financial team access to the existing billing account linked to your credit card, which doesn’t help in consolidating the expenses under the company’s account.

**Option 2: Set up BigQuery billing export and grant your financial department IAM access to query the data.**
- **Monitoring Only:** This option allows the financial team to monitor and analyze billing data but does not change where the costs are billed. It doesn’t address the need to charge the costs to the company’s billing account.

**Option 3: Create a ticket with Google Billing Support to ask them to send the invoice to your company.**
- **Not Automated:** This option might result in a temporary solution but does not provide an automated or long-term fix. Changing the billing account ensures all future charges are directed appropriately without needing ongoing manual intervention.

### Conclusion:

Option 4 is the most appropriate and efficient solution to ensure that all project costs are charged to the company’s billing account, thereby streamlining the billing process and aligning with the company’s financial policies.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You are running a data warehouse on BigQuery. A partner company is offering a recommendation engine based on the data in your data warehouse. The partner company is also running their application on Google Cloud. They manage the resources in their own project, but they need access to the BigQuery dataset in your project. You want to provide the partner company with access to the dataset. What should you do?

- [ ] Create a Service Account in your own project, and grant this Service Account access to BigQuery in your project.
- [ ] Create a Service Account in your own project, and ask the partner to grant this Service Account access to BigQuery in their project.
- [ ] Ask the partner to create a Service Account in their project, and have them give the Service Account access to BigQuery in their project.
- [x] Ask the partner to create a Service Account in their project, and grant their Service Account access to the BigQuery dataset in your project.

The correct answer is:

**4. Ask the partner to create a Service Account in their project, and grant their Service Account access to the BigQuery dataset in your project.**

### Explanation:

**Option 4: Ask the partner to create a Service Account in their project, and grant their Service Account access to the BigQuery dataset in your project.**
- **Delegation and Security:** This approach ensures that the partner company has control over the credentials and usage of the Service Account. By granting their Service Account access to your BigQuery dataset, you maintain a clear boundary between your projects while allowing the necessary access.
- **IAM Best Practices:** This method follows best practices for Identity and Access Management (IAM) by granting the least privilege necessary for the partner to perform their tasks.
- **Ease of Management:** It simplifies management and auditing since the partner company manages their own Service Account.

**Why Other Options are Wrong:**

**Option 1: Create a Service Account in your own project, and grant this Service Account access to BigQuery in your project.**
- **Control and Management:** This would mean you are responsible for managing the credentials and any potential misuse by the partner, which complicates security and accountability.

**Option 2: Create a Service Account in your own project, and ask the partner to grant this Service Account access to BigQuery in their project.**
- **Incorrect Scope:** This option doesn't address the requirement of granting access to your BigQuery dataset. Instead, it suggests granting your Service Account access to their project, which isn't the requirement.

**Option 3: Ask the partner to create a Service Account in their project, and have them give the Service Account access to BigQuery in their project.**
- **Incorrect Target:** This option suggests that the partner should give access to their own BigQuery dataset, but the requirement is to give access to the dataset in your project.

### Conclusion:

Option 4 is the correct approach because it allows the partner to manage their own Service Account while you grant the necessary access to your BigQuery dataset. This ensures a clear division of responsibilities, adheres to security best practices, and simplifies management and auditing.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### Your web application has been running successfully on Cloud Run for Anthos. You want to evaluate an updated version of the application with a specific percentage of your production users (canary deployment). What should you do?

- [ ] Create a new service with the new version of the application. Split traffic between this version and the version that is currently running.
- [x] Create a new revision with the new version of the application. Split traffic between this version and the version that is currently running.
- [ ] Create a new service with the new version of the application. Add HTTP Load Balancer in front of both services.
- [ ] Create a new revision with the new version of the application. Add HTTP Load Balancer in front of both revisions.


The correct answer is:

**2. Create a new revision with the new version of the application. Split traffic between this version and the version that is currently running.**

### Explanation:

**Option 2: Create a new revision with the new version of the application. Split traffic between this version and the version that is currently running.**
- **Revision and Traffic Split:** Cloud Run allows you to deploy multiple revisions of your application. You can create a new revision with the updated version of your application. When you deploy a new revision, you can control the amount of traffic that is routed to it using traffic splitting.
- **Canary Deployment:** By splitting traffic, you can gradually increase the percentage of users who are directed to the new revision (canary deployment). This allows you to evaluate the new version in production with a subset of users before rolling it out fully.
- **Managed Traffic Splitting:** Cloud Run manages the traffic splitting for you, making it easy to control how much traffic goes to each revision.

**Why Other Options are Wrong:**

**Option 1: Create a new service with the new version of the application. Split traffic between this version and the version that is currently running.**
- In Cloud Run, services are logical groupings of revisions. You typically use services to represent different components or functionalities of your application. Creating a new service would not directly allow you to split traffic between different versions (revisions) of the same application.

**Option 3: Create a new service with the new version of the application. Add HTTP Load Balancer in front of both services.**
- While you can use HTTP Load Balancer with Cloud Run, it is typically used to distribute traffic across multiple Cloud Run services or to expose Cloud Run services externally. This option is not necessary for performing canary deployments within a single service with multiple revisions.

**Option 4: Create a new revision with the new version of the application. Add HTTP Load Balancer in front of both revisions.**
- Cloud Run itself manages traffic routing and load balancing for revisions within a service. There is no need to manually add an HTTP Load Balancer in front of individual revisions. Cloud Run's built-in traffic splitting feature handles this functionality.

### Conclusion:

Option 2 is the correct approach because it leverages Cloud Run's built-in capabilities to create and manage revisions of your application, allowing you to perform canary deployments by controlling traffic splitting between versions. This method is straightforward, aligns with best practices for deploying applications on Cloud Run, and provides the flexibility to evaluate updates with a subset of production users before full deployment.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### Your company developed a mobile game that is deployed on Google Cloud. Gamers are connecting to the game with their personal phones over the Internet. The game sends UDP packets to update the servers about the gamers' actions while they are playing in multiplayer mode. Your game backend can scale over multiple Virtual Machines (VMs), and you want to expose the VMs over a single IP address. What should you do?

- [ ] Configure an SSL Proxy load balancer in front of the application servers.
- [ ] Configure an Internal UDP load balancer in front of the application servers.
- [ ] Configure an External HTTP(s) load balancer in front of the application servers.
- [x] Configure an External Network load balancer in front of the application servers.

The most suitable option for your scenario is:

**D. Configure an External Network load balancer in front of the application servers.**

### Explanation:

**Option D: Configure an External Network load balancer:**
- **UDP Protocol Support:** External Network load balancers in Google Cloud support UDP traffic, which is essential for handling the UDP packets sent by gamers' phones to update the game servers about their actions.
- **Single IP Address:** This type of load balancer provides a single global IP address, which can simplify the configuration for gamers connecting from personal phones over the Internet.
- **Scalability:** Network load balancers are designed to handle high-performance, scalable applications, making them suitable for a game backend that needs to scale across multiple VM instances.

**Why Option D is the Best Choice:**
- **UDP Protocol:** Since your game sends UDP packets to update servers about gamers' actions, you specifically need a load balancer that can handle UDP traffic.
- **Single IP Address:** It provides a consistent endpoint for gamers to connect to, simplifying client configuration and management.
- **Performance:** Network load balancers are optimized for handling network traffic with minimal latency, which is crucial for real-time applications like multiplayer games.

**Why Other Options are Wrong:**

**Option A: Configure an SSL Proxy load balancer:**
- SSL Proxy load balancers are designed for handling SSL/TLS traffic and terminating SSL connections. They are not suitable for UDP traffic, as they do not support UDP protocol.
- This option would not meet your requirement to handle UDP packets from gamers' phones.

**Option B: Configure an Internal UDP load balancer:**
- Internal UDP load balancers are designed for routing UDP traffic within a Virtual Private Cloud (VPC) network. They are not intended for handling UDP traffic from external clients over the Internet.
- This option is not suitable because it does not expose the VMs to external clients like gamers' phones.

**Option C: Configure an External HTTP(s) load balancer:**
- HTTP(s) load balancers are designed for HTTP/HTTPS traffic and do not support UDP protocol.
- This option would not work for your game backend, which relies on UDP packets for real-time updates.

### Conclusion:

Configuring an External Network load balancer (Option D) ensures that your game backend can efficiently handle UDP traffic from gamers' phones over the Internet, while providing scalability and a single IP address endpoint. This solution aligns with the requirements of exposing your VMs over a single IP address for your multiplayer game deployed on Google Cloud.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You are working for a hospital that stores its medical images in an on-premises data room. The hospital wants to use Cloud Storage for archival storage of these images. The hospital wants an automated process to upload any new medical images to Cloud Storage. You need to design and implement a solution. What should you do?

- [ ] Create a Pub/Sub topic, and enable a Cloud Storage trigger for the Pub/Sub topic. Create an application that sends all medical images to the Pub/Sub topic.
- [ ] Deploy a Dataflow job from the batch template, Datastore to Cloud Storage. Schedule the batch job on the desired interval.
- [x] Create a script that uses the gsutil command line interface to synchronize the on-premises storage with Cloud Storage. Schedule the script as a cron job.
- [ ] In the Cloud Console, go to Cloud Storage. Upload the relevant images to the appropriate bucket.


Given the scenario, the most suitable solution is:

**3. Create a script that uses the `gsutil` command line interface to synchronize the on-premises storage with Cloud Storage. Schedule the script as a cron job.**

### Explanation:

**Option 1:** Creating a Pub/Sub topic and enabling a Cloud Storage trigger is more suited for real-time event-driven architectures and assumes you have a cloud-native way to send images to Pub/Sub. It does not directly address the need for an automated process to handle new images from an on-premises environment.

**Option 2:** Deploying a Dataflow job from Datastore to Cloud Storage is not suitable since your images are stored on-premises and not in Datastore. Dataflow is also more complex and generally used for large-scale data processing pipelines, which may be overkill for this task.

**Option 3:** This involves creating a script that uses the `gsutil` command to synchronize files between your on-premises storage and Cloud Storage. Scheduling this script as a cron job ensures that the synchronization happens at regular intervals automatically. This is a straightforward and efficient way to automate the upload of new images from your on-premises environment to Cloud Storage.

**Option 4:** Manually uploading images through the Cloud Console does not automate the process and is not practical for ongoing operations.

### Why Option 3 is the Best Choice:
- **Automation:** Scheduling the script ensures that the process runs automatically without manual intervention.
- **Ease of Use:** The `gsutil` command is specifically designed for interacting with Cloud Storage and can efficiently handle file uploads.
- **Synchronization:** The `gsutil rsync` command can synchronize directories, making sure only new or changed files are uploaded.
- **Scalability:** This method can easily scale with the number of images, as the `gsutil` command is capable of handling large volumes of data.

### Implementation Steps:
1. **Write the Script:**
    ```bash
    #!/bin/bash
    gsutil rsync -r /path/to/local/images gs://your-cloud-storage-bucket
    ```

2. **Schedule the Script:**
   - Open the crontab file:
     ```bash
     crontab -e
     ```
   - Add a cron job to run the script at your desired interval, for example, daily at midnight:
     ```bash
     0 0 * * * /path/to/your/script.sh
     ```

This will ensure that your medical images are regularly uploaded to Cloud Storage, automating the archival process as required.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### Your auditor wants to view your organization's use of data in Google Cloud. The auditor is most interested in auditing who accessed data in Cloud Storage buckets. You need to help the auditor access the data they need. What should you do?

- [x] Turn on Data Access Logs for the buckets they want to audit, and then build a query in the log viewer that filters on Cloud Storage.
- [ ] Assign the appropriate permissions, and then create a Data Studio report on Admin Activity Audit Logs.
- [ ] Assign the appropriate permissions, and the use Cloud Monitoring to review metrics.
- [ ] Use the export logs API to provide the Admin Activity Audit Logs in the format they want.

To help the auditor view your organization's use of data in Google Cloud, particularly who accessed data in Cloud Storage buckets, the most appropriate action would be:

**1. Turn on Data Access Logs for the buckets they want to audit, and then build a query in the log viewer that filters on Cloud Storage.**

**Explanation:**
- **Data Access Logs:** By enabling Data Access Logs for Cloud Storage buckets, you can capture detailed information about operations performed on objects within those buckets. This includes who accessed the data, when they accessed it, and from where.
- **Log Viewer Query:** After enabling Data Access Logs, you can use the Google Cloud Console's Log Viewer to filter and query these logs specifically for Cloud Storage operations. This allows you to generate reports and queries that detail access to data within the specified buckets.
- This method directly addresses the auditor's interest in auditing who accessed data in Cloud Storage, providing granular visibility into access events.

**Why the Other Options are Not Suitable:**
- **Option 2 (Admin Activity Audit Logs in Data Studio):** Admin Activity Audit Logs primarily focus on administrative actions related to Google Cloud resources and services, rather than granular data access events within Cloud Storage.
- **Option 3 (Cloud Monitoring for Metrics):** Cloud Monitoring provides metrics and monitoring data related to performance and health of Google Cloud resources, but it does not provide detailed logs specifically tailored for auditing data access in Cloud Storage.
- **Option 4 (Export Logs API for Admin Activity Audit Logs):** While you can export logs using APIs, Admin Activity Audit Logs focus on administrative actions rather than data access in Cloud Storage, which may not meet the auditor's specific requirement for data access auditing.

Therefore, **Option 1** is the most appropriate choice as it directly enables and utilizes Data Access Logs for Cloud Storage to facilitate auditing of data access events, aligning closely with the auditor's needs.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You received a JSON file that contained a private key of a Service Account in order to get access to several resources in a Google Cloud project. You downloaded and installed the Cloud SDK and want to use this private key for authentication and authorization when performing gcloud commands. What should you do?

- [ ] Use the command gcloud auth login and point it to the private key.
- [x] Use the command gcloud auth activate-service-account and point it to the private key.
- [ ] Place the private key file in the installation directory of the Cloud SDK and rename it to credentials.json.
- [ ] Place the private key file in your home directory and rename it to GOOGLE_APPLICATION_CREDENTIALS.

The correct option for using the private key of a Service Account with the Cloud SDK for authentication and authorization when performing `gcloud` commands is:

**2. Use the command `gcloud auth activate-service-account` and point it to the private key.**

### Explanation:

1. **`gcloud auth activate-service-account` Command:**
   - This command is used to authenticate as a service account. It activates a Service Account by specifying the path to its private key file.
   - Syntax: `gcloud auth activate-service-account --key-file=path/to/private-key.json`
   - It establishes the credentials for subsequent `gcloud` commands to authorize actions based on the roles assigned to the Service Account.

2. **Private Key File:**
   - The private key file (`private-key.json`) contains the credentials necessary to authenticate as the Service Account.
   - This file should be securely stored and managed to prevent unauthorized access.
   - It's important to ensure that the private key file is accessible only to authorized individuals and processes.

### Why other options are incorrect:

- **Option 1: Use the command `gcloud auth login` and point it to the private key:**
  - `gcloud auth login` is used to obtain user credentials interactively for `gcloud` tool access, typically via a browser-based authentication flow.
  - It is not used for authenticating as a Service Account using a private key file.

- **Option 3: Place the private key file in the installation directory of the Cloud SDK and rename it to `credentials.json`:**
  - Placing the private key file in the Cloud SDK installation directory and renaming it to `credentials.json` does not automatically configure authentication for `gcloud`.
  - The `credentials.json` file conventionally refers to OAuth 2.0 credentials for user authentication, not Service Account keys.

- **Option 4: Place the private key file in your home directory and rename it to `GOOGLE_APPLICATION_CREDENTIALS`:**
  - Setting the `GOOGLE_APPLICATION_CREDENTIALS` environment variable to point to the private key file is a valid method for authentication, but it is not directly related to using the `gcloud` command-line tool.
  - This approach is more commonly used by client libraries and applications running outside of the Cloud SDK environment.

### Conclusion:

Option 2 (`gcloud auth activate-service-account`) is the correct choice for using a Service Account's private key with the Cloud SDK (`gcloud`) for authentication and authorization purposes. It directly configures `gcloud` to use the specified Service Account credentials, allowing seamless interaction with Google Cloud resources via CLI commands.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You are working with a Cloud SQL MySQL database at your company. You need to retain a month-end copy of the database for three years for audit purposes. What should you do?   ---------------Issue  

- [x] Set up an export job for the first of the month. Write the export file to an Archive class Cloud Storage bucket.
- [ ] Save the automatic first-of-the-month backup for three years. Store the backup file in an Archive class Cloud Storage bucket.
- [ ] Set up an on-demand backup for the first of the month. Write the backup to an Archive class Cloud Storage bucket.
- [ ] Convert the automatic first-of-the-month backup to an export file. Write the export file to a Coldline class Cloud Storage bucket.

Certainly! Let's clarify the difference between option 1 and option 2 for retaining a month-end copy of a Cloud SQL MySQL database for three years:

### Option 1:
- **Set up an export job for the first of the month. Write the export file to an Archive class Cloud Storage bucket.**

**Explanation:**
- **Export Job:** This involves configuring a scheduled export job within Cloud SQL to run on the first day of every month. Export jobs in Cloud SQL allow you to create backups or exports of your database at specified intervals.
- **Archive class Cloud Storage bucket:** The export file generated by the export job is stored in a Cloud Storage bucket configured with the Archive storage class. Archive class storage is designed for data that is accessed infrequently, making it cost-effective for long-term retention. It provides low storage costs but higher access costs compared to other storage classes.

### Option 2:
- **Save the automatic first-of-the-month backup for three years. Store the backup file in an Archive class Cloud Storage bucket.**

**Explanation:**
- **Automatic backups:** Cloud SQL automatically creates backups of your database according to its backup retention policy. Typically, these backups are stored in a specified Cloud Storage bucket associated with your Cloud SQL instance.
- **Archive class Cloud Storage bucket:** Similar to option 1, this involves storing the backups in an Archive class Cloud Storage bucket. Archive class storage is suitable for long-term retention due to its lower cost compared to other storage classes.

### Difference:
The primary difference between option 1 and option 2 lies in the method of creating and storing the backup:
- **Option 1** involves setting up a specific export job on the first day of each month to create an export file, which is then stored in an Archive class Cloud Storage bucket. This approach gives you more control over the export process and allows you to schedule exports at regular intervals.
  
- **Option 2** relies on the automatic backups created by Cloud SQL according to its backup retention policy. These backups are already managed by Cloud SQL and stored in a designated Cloud Storage bucket. You would configure this bucket to use Archive class storage for cost-effectiveness.

### Simplest Way:
Given the need to retain a month-end copy of the database for three years in the simplest way possible, **Option 2** might be simpler because it leverages Cloud SQL's built-in backup functionality:

1. **Configure Backup Retention:** Set up Cloud SQL to retain backups for the desired duration (three years).
  
2. **Storage Configuration:** Ensure the Cloud Storage bucket where Cloud SQL backups are stored is configured to use the Archive storage class for long-term retention and cost-effectiveness.
  
3. **Monitoring and Compliance:** Regularly monitor the backups to ensure they are being created and retained as per your retention policy. Ensure compliance with any audit requirements regarding data retention.

This approach leverages Cloud SQL's automated backup capabilities, simplifying management while meeting long-term data retention needs. It's important to verify and test the restoration process periodically to ensure the backups are usable if needed.

The most suitable option for retaining a month-end copy of a Cloud SQL MySQL database for three years for audit purposes is:

**2. Save the automatic first-of-the-month backup for three years. Store the backup file in an Archive class Cloud Storage bucket.**

### Explanation:

1. **Automatic Backups:**
   - Cloud SQL automatically performs daily backups and retains them for a certain period based on the backup retention policy set for the instance.
   - For MySQL instances, Cloud SQL also allows you to trigger an on-demand backup, which can be useful for capturing a specific point-in-time snapshot.

2. **Retention Period:**
   - Cloud SQL allows you to configure the backup retention period, which is typically up to 365 days for automated backups.
   - To retain backups for longer periods, especially for audit purposes such as retaining a month-end copy for three years, you would need to archive these backups separately.

3. **Archive Class Cloud Storage Bucket:**
   - Using an Archive class Cloud Storage bucket is cost-effective for long-term storage of infrequently accessed data, such as backup files.
   - Archive class storage offers lower storage costs but higher access costs compared to other storage classes like Standard or Nearline.

### Why other options are less suitable:

- **Option 1: Set up an export job for the first of the month:**
  - While exporting data can be useful, especially for creating specific snapshots or extracts, it does not leverage the built-in backup capabilities of Cloud SQL.
  - Exported files do not benefit from the automatic management and retention policies provided by Cloud SQL backups.

- **Option 3: Set up an on-demand backup for the first of the month:**
  - On-demand backups are useful for capturing a specific point-in-time snapshot but are not typically designed for long-term retention spanning multiple years.
  - Storing frequent on-demand backups for three years can be costly and may not be necessary unless specific audit requirements demand it.

- **Option 4: Convert the automatic first-of-the-month backup to an export file:**
  - Converting backups to export files and storing them in Cloud Storage can be complex and may not align with the automated backup retention policies of Cloud SQL.
  - It also involves additional manual steps and may not efficiently utilize Cloud SQL's built-in backup capabilities.

### Conclusion:

Option 2 is the recommended approach as it leverages Cloud SQL's automatic daily backups, which can be configured to retain the first-of-the-month backups for up to a year. Storing these backups in an Archive class Cloud Storage bucket ensures cost-effective, long-term retention for audit purposes over three years, aligning with best practices for data retention and compliance requirements.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You are monitoring an application and receive user feedback that a specific error is spiking. You notice that the error is caused by a Service Account having insufficient permissions. You are able to solve the problem but want to be notified if the problem recurs. What should you do?

- [ ] In the Log Viewer, filter the logs on severity ˜Error' and the name of the Service Account.
- [ ] Create a sink to BigQuery to export all the logs. Create a Data Studio dashboard on the exported logs.
- [x] Create a custom log-based metric for the specific error to be used in an Alerting Policy.
- [ ] Grant Project Owner access to the Service Account.

The correct option for your scenario is:

**3. Create a custom log-based metric for the specific error to be used in an Alerting Policy.**

### Explanation:

1. **Custom Log-based Metric:**
   - By creating a custom log-based metric, you can specifically define a metric that monitors occurrences of the specific error caused by the Service Account's insufficient permissions.
   - Custom log-based metrics allow you to extract and aggregate specific information from logs, such as the occurrence of errors related to a particular Service Account.
   - Once the metric is defined, you can set up an Alerting Policy in Google Cloud Monitoring (formerly Stackdriver Monitoring) to alert you whenever the metric threshold is met or exceeded, indicating that the error has recurred.
   - This approach provides targeted monitoring and alerting for the specific issue, enabling proactive notification if the problem resurfaces.

### Why other options are less suitable:

- **Option 1: Filtering logs in Log Viewer:**
  - Filtering logs manually in the Log Viewer based on severity and the name of the Service Account can help identify past occurrences but does not provide automated alerting for future occurrences.
  - It requires manual intervention to monitor continuously, which may not be efficient for detecting recurrent issues promptly.

- **Option 2: Exporting logs to BigQuery and creating a Data Studio dashboard:**
  - While exporting logs to BigQuery and visualizing them in Data Studio can provide insights into historical trends and patterns, it does not offer real-time or proactive alerting capabilities.
  - It focuses more on analytics and reporting rather than immediate notification of specific recurring errors.

- **Option 4: Granting Project Owner access to the Service Account:**
  - Granting broad Project Owner access to the Service Account is not a recommended practice for addressing permissions issues. It introduces unnecessary security risks and does not provide proactive monitoring or alerting for errors.
  - It does not address the root cause of the issue nor provide a mechanism to notify if the problem occurs again in the future.

### Conclusion:

Creating a custom log-based metric in Google Cloud Monitoring for the specific error related to the Service Account and setting up an Alerting Policy based on this metric is the most effective approach. It allows you to monitor the occurrence of the error in real-time and receive automated notifications if the issue reoccurs, enabling timely response and resolution to maintain application reliability and availability.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You are developing a financial trading application that will be used globally. Data is stored and queried using a relational structure, and clients from all over the world should get the exact identical state of the data. The application will be deployed in multiple regions to provide the lowest latency to end users. You need to select a storage option for the application data while minimizing latency. What should you do?

- [ ] Use Cloud Bigtable for data storage.
- [ ] Use Cloud SQL for data storage.
- [x] Use Cloud Spanner for data storage.
- [ ] Use Firestore for data storage.

The correct option for your scenario is:

**3. Use Cloud Spanner for data storage.**

### Explanation:

1. **Cloud Spanner:**
   - **Global Consistency:** Cloud Spanner is a horizontally scalable, strongly consistent relational database service. It provides ACID transactions and SQL semantics, ensuring that clients from different regions see a consistent view of the data without the need for complex data replication or synchronization.
   - **Multi-Region Support:** Spanner is designed to operate seamlessly across multiple regions. It maintains strong consistency across these regions with synchronous replication, ensuring that clients globally see the exact same state of the data with minimal latency.
   - **Low Latency:** Spanner's architecture allows it to provide low-latency reads and writes globally due to its distributed design and use of synchronized clocks.
   - **Scalability:** It can automatically scale horizontally to handle large volumes of data and high throughput requirements.
   - **SQL Support:** Spanner supports SQL queries, making it easier for developers familiar with relational databases to work with.

### Why other options are less suitable:

- **Cloud Bigtable:** Bigtable is a NoSQL database optimized for large analytical and operational workloads. It offers high throughput and low-latency access to large amounts of data, but it sacrifices strong consistency for eventual consistency. It's not suitable for applications requiring strong ACID properties across multiple regions.

- **Cloud SQL:** While Cloud SQL offers managed relational databases, achieving low-latency global reads with strong consistency across multiple regions is challenging. Cloud SQL replicas can provide high availability, but strong consistency guarantees globally are not as robust as with Cloud Spanner.

- **Firestore:** Firestore is a NoSQL document database designed for mobile and web applications, offering real-time data synchronization and offline support. It does not provide the relational data model or strong consistency guarantees required for financial trading applications where data integrity and consistency are critical.

### Conclusion:

For a financial trading application that requires globally consistent data access with minimal latency across multiple regions, Cloud Spanner is the optimal choice. It combines the benefits of a relational data model with global distribution, strong consistency, and low-latency reads and writes, making it well-suited for mission-critical applications like financial trading platforms.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You are about to deploy a new Enterprise Resource Planning (ERP) system on Google Cloud. The application holds the full database in-memory for fast data access, and you need to configure the most appropriate resources on Google Cloud for this application. What should you do?   -----------------Issue

- [ ] Provision preemptible Compute Engine instances.
- [ ] Provision Compute Engine instances with GPUs attached.
- [ ] Provision Compute Engine instances with local SSDs attached.
- [x] Provision Compute Engine instances with M1 machine type.

The most appropriate option for configuring resources on Google Cloud for an Enterprise Resource Planning (ERP) system that requires fast data access with an in-memory database is:

4.** Provision Compute Engine instances with M1 machine type.**
D: M1 Machine types for ERP i.e. SAP-HANA

Medium-large in-memory databases such as SAP HANA
In-memory databases and in-memory analytics
Microsoft SQL Server and similar databases

### Explanation:

1. **Local SSDs:**
   - Local SSDs are directly attached to the physical machine hosting your Compute Engine instance, providing very high input/output operations per second (IOPS) and low latency.
   - They offer excellent performance for applications that require fast data access, such as databases that hold the full dataset in-memory.
   - Local SSDs are ideal for workloads where data durability is managed at the application level or where data is replicated across multiple instances or regions for high availability.
   - They are designed for temporary storage and are automatically deleted when the instance is stopped, so they are suitable for transient data or caching scenarios.

### Why other options are less appropriate:

1. **Provision preemptible Compute Engine instances:**
   - Preemptible instances are cost-effective but are not suitable for applications that require persistent data storage or where data loss could be an issue, as they can be preempted with short notice.
   - They are ideal for fault-tolerant and batch processing workloads, rather than for mission-critical databases.

2. **Provision Compute Engine instances with GPUs attached:**
   - GPUs are used for accelerating specific types of computations, such as machine learning or rendering tasks.
   - For an ERP system focused on fast data access, GPUs are not typically required unless there are specific computational tasks within the ERP that would benefit from GPU acceleration, which is unlikely for typical ERP operations.

4. **Provision Compute Engine instances with M1 machine type:**
   - M1 machine types are general-purpose machines without specific features tailored for high-performance storage or compute-intensive tasks like in-memory database operations.
   - They do not provide the same level of high-performance storage as local SSDs or specialized compute capabilities like GPUs.

### Conclusion:

For an ERP system that requires fast data access with an in-memory database, provisioning Compute Engine instances with local SSDs attached is the most appropriate choice. It ensures that your application can leverage high-performance storage for rapid data retrieval and processing, meeting the requirements for efficient operation of an ERP system.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You have developed an application that consists of multiple microservices, with each microservice packaged in its own Docker container image. You want to deploy the entire application on Google Kubernetes Engine so that each microservice can be scaled individually. What should you do?

- [ ] Create and deploy a Custom Resource Definition per microservice.
- [ ] Create and deploy a Docker Compose File.
- [ ] Create and deploy a Job per microservice.
- [x] Create and deploy a Deployment per microservice.

The correct approach is:

- **4. Create and deploy a Deployment per microservice.**

### Explanation:

1. **Create and deploy a Deployment per microservice:**
   - In Kubernetes, a `Deployment` is a resource object that provides declarative updates to applications. It manages the lifecycle and scaling of Pods (which run the containers) and ensures the desired state of the application.
   - Deploying a `Deployment` per microservice allows you to manage each microservice independently. You can define the number of replicas (instances) for each microservice, handle rolling updates, and manage scaling based on the workload.
   - Each `Deployment` references a specific Docker container image that represents a microservice, enabling Kubernetes to manage and orchestrate the containers effectively.

### Why other options are wrong:

2. **Create and deploy a Custom Resource Definition per microservice:**
   - Custom Resource Definitions (CRDs) are used to extend Kubernetes with custom resources and controllers. They are not typically used to manage individual microservices directly.
   - Using CRDs for each microservice would involve more complex custom development and is not a standard approach for managing application deployments.

3. **Create and deploy a Docker Compose File:**
   - Docker Compose is a tool for defining and running multi-container Docker applications. It is designed for development environments and is not suitable for production-grade orchestration on Kubernetes.
   - Kubernetes uses YAML configuration files (`Deployment`, `Service`, etc.) to define and manage applications, providing more robust features for production deployments and scaling.

4. **Create and deploy a Job per microservice:**
   - Kubernetes `Job` objects are used for batch processing tasks that run once to completion. They are not suitable for long-running microservices that need to be continuously available and scalable.
   - Using `Job` objects for microservices would not provide the desired functionality for managing microservice lifecycles and scaling.

### Conclusion:

Deploying a `Deployment` per microservice on Google Kubernetes Engine (GKE) is the recommended approach for deploying and managing a microservices-based application. It leverages Kubernetes' capabilities for container orchestration, scaling, and management, allowing you to deploy and scale each microservice independently based on your application's requirements. This approach provides flexibility, scalability, and robustness for running microservices in a production environment.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You will have several applications running on different Compute Engine instances in the same project. You want to specify at a more granular level the service account each instance uses when calling Google Cloud APIs. What should you do?

- [x] When creating the instances, specify a Service Account for each instance.
- [ ] When creating the instances, assign the name of each Service Account as instance metadata.
- [ ] After starting the instances, use gcloud compute instances update to specify a Service Account for each instance.
- [ ] After starting the instances, use gcloud compute instances update to assign the name of the relevant Service Account as instance metadata.

The correct approach is:

- **1. When creating the instances, specify a Service Account for each instance.**

### Explanation:

1. **When creating the instances, specify a Service Account for each instance:**
   - When you create a Compute Engine instance using Google Cloud Console, `gcloud` command-line tool, or API, you have the option to specify a service account that the instance will use to authenticate and authorize its interactions with Google Cloud APIs.
   - This allows you to choose a specific service account identity for each instance, ensuring that each application running on those instances has its own distinct set of permissions.
   - Specifying the service account during instance creation ensures that the instance starts with the correct identity and permissions, providing granular control over access to Google Cloud resources.

### Why other options are wrong:

2. **When creating the instances, assign the name of each Service Account as instance metadata:**
   - Instance metadata is typically used for configuration data and startup scripts, not for specifying the service account used for API authentication.
   - Assigning the name of the service account as metadata does not configure the instance to use that service account for API calls.

3. **After starting the instances, use `gcloud compute instances update` to specify a Service Account for each instance:**
   - This option suggests updating instance attributes after the instances have been created. However, specifying the service account during instance creation ensures proper initialization and configuration from the start.

4. **After starting the instances, use `gcloud compute instances update` to assign the name of the relevant Service Account as instance metadata:**
   - Similar to option 2, this approach focuses on metadata updates rather than specifying the service account used for API calls. It does not address the core requirement of controlling service account identities for secure API access.

### Conclusion:

Specifying a service account for each Compute Engine instance during instance creation is the recommended approach for ensuring that each application running on different instances has the appropriate permissions to interact with Google Cloud APIs. This approach provides security, governance, and operational benefits by enabling fine-grained control over access to Google Cloud resources at the instance level.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You are creating an application that will run on Google Kubernetes Engine. You have identified MongoDB as the most suitable database system for your application and want to deploy a managed MongoDB environment that provides a support SLA. What should you do?

- [ ] Create a Cloud Bigtable cluster, and use the HBase API.
- [x] Deploy MongoDB Atlas from the Google Cloud Marketplace.
- [ ] Download a MongoDB installation package, and run it on Compute Engine instances.
- [ ] Download a MongoDB installation package, and run it on a Managed Instance Group.

The correct answer is:

- **Deploy MongoDB Atlas from the Google Cloud Marketplace.**

### Explanation:

1. **Deploy MongoDB Atlas from the Google Cloud Marketplace**:
   - MongoDB Atlas is a fully managed database service provided by MongoDB, Inc. It offers a managed MongoDB environment with features like automated backups, scaling, and support SLAs.
   - By deploying MongoDB Atlas from the Google Cloud Marketplace, you get a managed MongoDB service that is integrated with Google Cloud Platform (GCP). This means you can manage and scale your MongoDB clusters easily using familiar GCP tools and interfaces.
   - MongoDB Atlas also provides support SLAs, ensuring that you have access to MongoDB experts for assistance and issue resolution.

2. **Why other options are wrong:**

   - **Create a Cloud Bigtable cluster, and use the HBase API:**
     - Cloud Bigtable is a NoSQL Big Data database service, but it is not suitable as a drop-in replacement for MongoDB. It uses a different data model and API (HBase API), which is not compatible with MongoDB's document-based model.

   - **Download a MongoDB installation package, and run it on Compute Engine instances:**
     - This option involves self-managing MongoDB on Compute Engine VM instances. While possible, it lacks the benefits of a managed service such as automatic scaling, backups, and SLAs. Managing MongoDB manually on Compute Engine also requires significant effort in terms of monitoring, maintenance, and scalability.

   - **Download a MongoDB installation package, and run it on a Managed Instance Group:**
     - Similar to running MongoDB on Compute Engine instances, this approach involves managing MongoDB manually on Managed Instance Groups (MIGs). While MIGs provide some automation for managing VM instances, it still requires manual setup and maintenance of MongoDB, lacking the benefits of a fully managed service like MongoDB Atlas.

### Conclusion:

Deploying MongoDB Atlas from the Google Cloud Marketplace is the recommended approach for deploying a managed MongoDB environment on Google Kubernetes Engine (GKE). It provides the benefits of a fully managed service with support SLAs, ensuring reliability, scalability, and ease of management for your application's database needs.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### You are managing a project for the Business Intelligence (BI) department in your company. A data pipeline ingests data into BigQuery via streaming. You want the users in the BI department to be able to run the custom SQL queries against the latest data in BigQuery. What should you do?

- [ ] Create a Data Studio dashboard that uses the related BigQuery tables as a source and give the BI team view access to the Data Studio dashboard.
- [ ] Create a Service Account for the BI team and distribute a new private key to each member of the BI team.
- [ ] Use Cloud Scheduler to schedule a batch Dataflow job to copy the data from BigQuery to the BI team's internal data warehouse.
- [x] Assign the IAM role of BigQuery User to a Google Group that contains the members of the BI team.

The correct approach is:

- **Assign the IAM role of BigQuery User to a Google Group that contains the members of the BI team.**

### Explanation of why other options are wrong:

1. **Create a Data Studio dashboard that uses the related BigQuery tables as a source and give the BI team view access to the Data Studio dashboard.**
   - **Reason for being wrong:** While Data Studio can visualize data from BigQuery and provide interactive dashboards, it doesn't directly enable running custom SQL queries. Users interact with predefined visualizations rather than writing their own SQL queries.

2. **Create a Service Account for the BI team and distribute a new private key to each member of the BI team.**
   - **Reason for being wrong:** Distributing private keys to individual team members is not a scalable or secure approach. Service Accounts are typically used for automated processes or applications accessing Google Cloud services, not for individual user access to BigQuery.

3. **Use Cloud Scheduler to schedule a batch Dataflow job to copy the data from BigQuery to the BI team's internal data warehouse.**
   - **Reason for being wrong:** This option involves copying data from BigQuery to another data warehouse, which may not provide real-time access to the latest data in BigQuery. It introduces complexity and latency in data access, which is not suitable for scenarios requiring querying the latest data in BigQuery directly.

### Why Option 4 is correct:

- **Assigning IAM role of BigQuery User to a Google Group:**
  - By assigning the BigQuery User role to a Google Group containing BI team members, you grant them the necessary permissions to run custom SQL queries directly against BigQuery datasets.
  - This approach adheres to the principle of least privilege by granting access at the group level rather than individually managing permissions for each user.
  - It ensures that BI team members have the flexibility to query the latest data in BigQuery and leverage its powerful querying capabilities without the need for additional infrastructure or tools.

### Conclusion:

Assigning the IAM role of BigQuery User to a Google Group is the correct approach because it provides secure and scalable access for BI team members to run custom SQL queries against the latest data in BigQuery, aligning with best practices for managing permissions in Google Cloud Platform.

In Google BigQuery, IAM roles are used to manage permissions that control access to datasets, tables, views, and other resources within BigQuery. Here are some of the key IAM roles available in BigQuery and their typical use cases:

1. **BigQuery Admin (`roles/bigquery.admin`)**:
   - **Permissions**: Full control over BigQuery resources including datasets, tables, jobs, and permissions.
   - **Use Case**: Typically assigned to administrators who need to manage all aspects of BigQuery, including creating and deleting datasets, managing IAM policies, and running any type of job.

2. **BigQuery Data Editor (`roles/bigquery.dataEditor`)**:
   - **Permissions**: Edit and delete data within datasets and tables, but cannot manage IAM policies or view job logs.
   - **Use Case**: Useful for users who need to modify data in existing datasets, create new tables, and manage schema changes.

3. **BigQuery Data Viewer (`roles/bigquery.dataViewer`)**:
   - **Permissions**: View data within datasets and tables, but cannot make changes to data or schema.
   - **Use Case**: Typically assigned to users who need read-only access to BigQuery resources for querying and analysis purposes.

4. **BigQuery Job User (`roles/bigquery.jobUser`)**:
   - **Permissions**: Submit and manage jobs, including queries, but cannot create or modify datasets or tables.
   - **Use Case**: Suitable for users who need to run queries and manage their own jobs within existing datasets without administrative privileges.

5. **BigQuery User (`roles/bigquery.user`)**:
   - **Permissions**: Query data and run jobs, but cannot create datasets or tables.
   - **Use Case**: Provides minimal access for users who only need to run queries against existing datasets and do not require any administrative capabilities.

6. **BigQuery Metadata Viewer (`roles/bigquery.metadataViewer`)**:
   - **Permissions**: View dataset and table metadata, including schema information and ACLs, but cannot view data.
   - **Use Case**: Useful for auditing purposes or for users who need to understand the structure and access controls of datasets without accessing the actual data.

7. **BigQuery Data Owner (`roles/bigquery.dataOwner`)**:
   - **Permissions**: All permissions of `bigquery.dataEditor` and `bigquery.jobUser`, plus the ability to manage dataset IAM policies.
   - **Use Case**: Provides full control over data within datasets, including modifying data, schema, and managing access permissions.

These roles can be assigned at the project level or directly to specific datasets or tables within BigQuery, allowing fine-grained control over who can access and manipulate data. It's essential to assign roles based on the principle of least privilege to ensure that users have only the permissions necessary to perform their tasks.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------

### Your company is moving its entire workload to Compute Engine. Some servers should be accessible through the Internet, and other servers should only be accessible over the internal network. All servers need to be able to talk to each other over specific ports and protocols. The current on-premises network relies on a demilitarized zone (DMZ) for the public servers and a Local Area Network (LAN) for the private servers. You need to design the networking infrastructure on Google Cloud to match these requirements. What should you do?

- [x] 1. Create a single VPC with a subnet for the DMZ and a subnet for the LAN. 2. Set up firewall rules to open up relevant traffic between the DMZ and the LAN subnets, and another firewall rule to allow public ingress traffic for the DMZ.
- [ ] 1. Create a single VPC with a subnet for the DMZ and a subnet for the LAN. 2. Set up firewall rules to open up relevant traffic between the DMZ and the LAN subnets, and another firewall rule to allow public egress traffic for the DMZ.
- [ ] 1. Create a VPC with a subnet for the DMZ and another VPC with a subnet for the LAN. 2. Set up firewall rules to open up relevant traffic between the DMZ and the LAN subnets, and another firewall rule to allow public ingress traffic for the DMZ.
- [ ] 1. Create a VPC with a subnet for the DMZ and another VPC with a subnet for the LAN. 2. Set up firewall rules to open up relevant traffic between the DMZ and the LAN subnets, and another firewall rule to allow public egress traffic for the DMZ.

The correct answer is:

1. **Create a single VPC with a subnet for the DMZ and a subnet for the LAN. Set up firewall rules to open up relevant traffic between the DMZ and the LAN subnets, and another firewall rule to allow public ingress traffic for the DMZ.**

### Explanation of why other options are wrong:

- Option 2: 
  1. **Create a single VPC with a subnet for the DMZ and a subnet for the LAN.**
     - This part is correct as it aligns with the requirement to have both DMZ (public servers) and LAN (private servers) within the same VPC.

  2. **Set up firewall rules to open up relevant traffic between the DMZ and the LAN subnets, and another firewall rule to allow public egress traffic for the DMZ.**
     - This option incorrectly mentions allowing public egress traffic for the DMZ. Egress traffic refers to traffic leaving a network, typically to the internet. The requirement states that public servers in the DMZ should allow ingress traffic (incoming traffic from the internet), not egress traffic (outgoing traffic to the internet).

- Option 3 and 4:
  - **Create a VPC with a subnet for the DMZ and another VPC with a subnet for the LAN.**
  - These options involve creating separate VPCs for DMZ and LAN. While this setup can work, it complicates network configuration and management by requiring peering or VPN connections between VPCs to allow communication between DMZ and LAN. The requirement specifies using a single VPC, so these options are less aligned with best practices and may introduce unnecessary complexity.

### Why Option 1 is correct:

- **Single VPC with Subnets**: Using a single VPC simplifies network management and allows for straightforward communication between DMZ and LAN subnets using internal IPs.

- **Firewall Rules**: By setting up firewall rules:
  - **Between DMZ and LAN subnets**: You can control and restrict traffic flow between public (DMZ) and private (LAN) servers based on specific ports and protocols.
  - **For Public Ingress Traffic**: You can define firewall rules to allow incoming traffic from the internet to the DMZ, ensuring that public servers are accessible as needed.

- **Security and Isolation**: This design mirrors the on-premises DMZ and LAN setup, ensuring that public-facing servers are securely isolated from internal servers while allowing controlled communication between them.

### Conclusion:

Option 1 is the correct choice because it adheres to best practices by using a single VPC with segregated subnets for DMZ and LAN, and it correctly implements firewall rules to meet the specified requirements for both internal communication and public accessibility. This design ensures security, scalability, and ease of management for your workload on Google Cloud Platform.

--------------------------------------------------------------x-----x----x-----x-----------------------------------------------------------





BigQuery
The **BigQuery Job User** role (`roles/bigquery.jobUser`) in Google Cloud Platform (GCP) grants permissions specifically for running jobs in BigQuery. Here’s what this role allows:

1. **Running Queries**: Users with the BigQuery Job User role can submit queries to BigQuery. This includes SELECT queries to retrieve data from datasets and tables.

2. **Loading Data**: They can load data into BigQuery from Cloud Storage or other sources.

3. **Exporting Data**: They can export query results from BigQuery to Cloud Storage.

However, the BigQuery Job User role does **not** grant direct access to view or read data stored in BigQuery tables unless the user has been explicitly granted the **BigQuery Data Viewer** (`roles/bigquery.dataViewer`) role on the specific dataset or table. 

In summary:

- **BigQuery Job User**: Can run queries, load data, and export query results, but cannot view or read data in BigQuery tables unless granted additional permissions.
  
- **BigQuery Data Viewer**: Can view (read) data within datasets and tables in BigQuery, run queries, and export data.

Therefore, if a user or service account needs to both run jobs (queries, data loading) and view data in BigQuery tables, they would typically need both the BigQuery Job User and BigQuery Data Viewer roles assigned appropriately.

In Google Cloud Platform (GCP), BigQuery offers several IAM (Identity and Access Management) roles that govern access to resources within BigQuery. These roles help control permissions for various operations such as querying data, managing datasets, and administering BigQuery resources. Here are some key IAM roles related to BigQuery:

1. **BigQuery Data Viewer**:
   - **Role Name**: roles/bigquery.dataViewer
   - **Permissions**: Allows viewing (reading) data within datasets and tables in BigQuery. Users with this role can run queries and export data, but cannot modify datasets or tables.

2. **BigQuery Data Editor**:
   - **Role Name**: roles/bigquery.dataEditor
   - **Permissions**: Includes all permissions of the Data Viewer role. Additionally, users can update and delete data within datasets and tables, and create new tables.

3. **BigQuery Data Owner**:
   - **Role Name**: roles/bigquery.dataOwner
   - **Permissions**: Includes all permissions of the Data Editor role. Additionally, users can manage (create, update, delete) datasets and tables, and set access controls at the dataset level.

4. **BigQuery Job User**:
   - **Role Name**: roles/bigquery.jobUser
   - **Permissions**: Allows users to run jobs (queries, load data) in BigQuery. Users with this role can submit queries, load data into BigQuery, and export query results. They cannot modify datasets or tables.

5. **BigQuery Admin**:
   - **Role Name**: roles/bigquery.admin
   - **Permissions**: Includes all permissions in BigQuery. This role can manage all aspects of BigQuery, including creating and deleting datasets, tables, and jobs. It also includes permissions to set IAM policies and manage storage used by BigQuery.

These roles can be assigned at various levels within GCP, including project level, dataset level, and specific resources within BigQuery. Assigning these roles correctly ensures that users and service accounts have appropriate access to BigQuery resources based on their responsibilities and needs.


Google App Engine offers several scaling types to accommodate different workload patterns and performance needs:

1. **Automatic Scaling**:
   - **Description**: Scales based on request rate, automatically adjusting the number of instances needed to handle incoming traffic.
   - **Configuration**:
     - `min_idle_instances`: Specifies the minimum number of idle instances to keep running and ready to serve requests.
     - `max_instances`: Sets an upper limit on the number of instances that can be running at any given time.
   - **Use Case**: Ideal for applications with varying traffic patterns where you want App Engine to handle scaling automatically based on demand.

2. **Basic Scaling**:
   - **Description**: Scales based on request rate, but allows for a more controlled environment with a consistent number of instances.
   - **Configuration**:
     - `max_instances`: Sets the maximum number of instances that can be running.
     - Automatically spins up new instances as traffic increases and stops them when traffic decreases, but does not maintain idle instances.
   - **Use Case**: Suitable for applications that have predictable traffic patterns and can benefit from cost control with a fixed number of instances.

3. **Manual Scaling**:
   - **Description**: Allows you to manually specify the number of instances that should be running at all times.
   - **Configuration**:
     - `instances`: Specifies the exact number of instances that should be running continuously.
   - **Use Case**: Useful for applications with consistent workloads where you want full control over the number of instances and their resource allocation.

Each scaling type offers different levels of control and automation, catering to various application requirements and workload characteristics. Choosing the appropriate scaling type depends on factors such as traffic variability, cost considerations, and the need for instance availability.
