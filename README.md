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

**[⬆ Back to Top](#table-of-contents)**

### Your company has a 3-tier solution running on Compute Engine. The configuration of the current infrastructure is shown below. Each tier has a service account that is associated with all instances within it. You need to enable communication on TCP port 8080 between tiers as follows: Instances in tier #1 must communicate with tier #2. Instances in tier #2 must communicate with tier #3. What should you do?

![3-tier solution running on Compute Engine](images/tier3.png)

- [ ] 1. Create an ingress firewall rule with the following settings: Targets: all instances. Source filter: IP ranges (with the range set to 10.0.2.0/24). Protocols: allow all. 2. Create an ingress firewall rule with the following settings: Targets: all instances. Source filter: IP ranges (with the range set to 10.0.1.0/24). Protocols: allow all.
- [x] 1. Create an ingress firewall rule with the following settings: Targets: all instances with tier #2 service account. Source filter: all instances with tier #1 service account. Protocols: allow TCP: 8080. 2. Create an ingress firewall rule with the following settings: Targets: all instances with tier #3 service account. Source filter: all instances with tier #2 service account. Protocols: allow TCP: 8080.
- [ ] 1. Create an ingress firewall rule with the following settings: Targets: all instances with tier #2 service account. Source filter: all instances with tier #1 service account. Protocols: allow all. 2. Create an ingress firewall rule with the following settings: Targets: all instances with tier #3 service account. Source filter: all instances with tier #2 service account. Protocols: allow all.
- [ ] 1. Create an egress firewall rule with the following settings: Targets: all instances. Source filter: IP ranges (with the range set to 10.0.2.0/24). Protocols: allow TCP: 8080. 2. Create an egress firewall rule with the following settings: Targets: all instances. Source filter: IP ranges (with the range set to 10.0.1.0/24). Protocols: allow TCP: 8080.

**[⬆ Back to Top](#table-of-contents)**

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

**[⬆ Back to Top](#table-of-contents)**

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

  
**[⬆ Back to Top](#table-of-contents)**

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

**[⬆ Back to Top](#table-of-contents)**

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

**[⬆ Back to Top](#table-of-contents)**

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

**[⬆ Back to Top](#table-of-contents)**

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

**[⬆ Back to Top](#table-of-contents)**

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
  
**[⬆ Back to Top](#table-of-contents)**

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
  
**[⬆ Back to Top](#table-of-contents)**

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
  
**[⬆ Back to Top](#table-of-contents)**

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

**[⬆ Back to Top](#table-of-contents)**

### You are deploying an application to a Compute Engine VM in a Managed Instance Group. The application must be running at all times, but only a single instance of the VM should run per GCP project. How should you configure the instance group?

- [x] Set autoscaling to On, set the minimum number of instances to 1, and then set the maximum number of instances to 1.
- [ ] Set autoscaling to Off, set the minimum number of instances to 1, and then set the maximum number of instances to 1.
- [ ] Set autoscaling to On, set the minimum number of instances to 1, and then set the maximum number of instances to 2.
- [ ] Set autoscaling to Off, set the minimum number of instances to 1, and then set the maximum number of instances to 2.

**Option 1: Set autoscaling to On, set the minimum number of instances to 1, and then set the maximum number of instances to 1**
**Autoscaling Behavior:** Even though both the minimum and maximum instances are set to 1, having autoscaling enabled means that if the single instance in the Managed Instance Group fails (becomes unhealthy), Google Cloud Platform (GCP) will automatically detect this and replace the failed instance with a new one.

**Failure Recovery:** This configuration ensures that your application remains resilient to instance failures. The autoscaler continuously monitors the health of instances using health checks. If it detects that the instance has failed or is unhealthy based on the configured health checks, it terminates the failed instance and starts a new one to maintain the desired instance count.

**Operational Continuity:** By utilizing autoscaling in this way, you benefit from automated instance replacement without manual intervention. This helps in maintaining the application's availability and ensures that the instance group always runs the specified number of instances.

**[⬆ Back to Top](#table-of-contents)**

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

**[⬆ Back to Top](#table-of-contents)**

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

**[⬆ Back to Top](#table-of-contents)**

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

**[⬆ Back to Top](#table-of-contents)**

### You need to grant access for three users so that they can view and edit table data on a Cloud Spanner instance. What should you do?

- [ ] Run gcloud iam roles describe roles/spanner.databaseUser. Add the users to the role.
- [x] Run gcloud iam roles describe roles/spanner.databaseUser. Add the users to a new group. Add the group to the role.
- [ ] Run gcloud iam roles describe roles/spanner.viewer –project my-project. Add the users to the role.
- [ ] Run gcloud iam roles describe roles/spanner.viewer –project my-project. Add the users to a new group. Add the group to the role.

**[⬆ Back to Top](#table-of-contents)**

### You need to create a new billing account and then link it with an existing Google Cloud Platform project. What should you do?

- [ ] Verify that you are Project Billing Manager for the GCP project. Update the existing project to link it to the existing billing account.
- [x] Verify that you are Project Billing Manager for the GCP project. Create a new billing account and link the new billing account to the existing project.
- [ ] Verify that you are Billing Administrator for the billing account. Create a new project and link the new project to the existing billing account.
- [ ] Verify that you are Billing Administrator for the billing account. Update the existing project to link it to the existing billing account.

**[⬆ Back to Top](#table-of-contents)**

### You have sensitive data stored in three Cloud Storage buckets and have enabled data access logging. You want to verify activities for a particular user for these buckets, using the fewest possible steps. You need to verify the addition of metadata labels and which files have been viewed from those buckets. What should you do?

- [x] Using the GCP Console, filter the Activity log to view the information.
- [ ] Using the GCP Console, filter the Stackdriver log to view the information.
- [ ] View the bucket in the Storage section of the GCP Console.
- [ ] Create a trace in Stackdriver to view the information.

**[⬆ Back to Top](#table-of-contents)**

### You need to run an important query in BigQuery but expect it to return a lot of records. You want to find out how much it will cost to run the query. You are using on-demand pricing. What should you do?

- [ ] Arrange to switch to Flat-Rate pricing for this query, then move back to on-demand.
- [x] Use the command line to run a dry run query to estimate the number of bytes read. Then convert that bytes estimate to dollars using the Pricing Calculator.
- [ ] Use the command line to run a dry run query to estimate the number of bytes returned. Then convert that bytes estimate to dollars using the Pricing Calculator.
- [ ] Run a select count (*) to get an idea of how many records your query will look through. Then convert that number of rows to dollars using the Pricing Calculator.

**[⬆ Back to Top](#table-of-contents)**

### You need to monitor resources that are distributed over different projects in Google Cloud Platform. You want to consolidate reporting under the same Stackdriver Monitoring dashboard. What should you do?

- [ ] Use Shared VPC to connect all projects, and link Stackdriver to one of the projects.
- [ ] For each project, create a Stackdriver account. In each project, create a service account for that project and grant it the role of Stackdriver Account Editor in all other projects.
- [x] Configure a single Stackdriver account, and link all projects to the same account.
- [ ] Configure a single Stackdriver account for one of the projects. In Stackdriver, create a Group and add the other project names as criteria for that Group.

**[⬆ Back to Top](#table-of-contents)**

### You need a dynamic way of provisioning VMs on Compute Engine. The exact specifications will be in a dedicated configuration file. You want to follow Google's recommended practices. Which method should you use?

- [x] Deployment Manager.
- [ ] Cloud Composer.
- [ ] Managed Instance Group.
- [ ] Unmanaged Instance Group.

**[⬆ Back to Top](#table-of-contents)**

### You created an instance of SQL Server 2017 on Compute Engine to test features in the new version. You want to connect to this instance using the fewest number of steps. What should you do?

- [ ] Install a RDP client on your desktop. Verify that a firewall rule for port 3389 exists.
- [x] Install a RDP client in your desktop. Set a Windows username and password in the GCP Console. Use the credentials to log in to the instance.
- [ ] Set a Windows password in the GCP Console. Verify that a firewall rule for port 22 exists. Click the RDP button in the GCP Console and supply the credentials to log in.
- [ ] Set a Windows username and password in the GCP Console. Verify that a firewall rule for port 3389 exists. Click the RDP button in the GCP Console, and supply the credentials to log in.

**[⬆ Back to Top](#table-of-contents)**

### You are the organization and billing administrator for your company. The engineering team has the Project Creator role on the organization. You do not want the engineering team to be able to link projects to the billing account. Only the finance team should be able to link a project to a billing account, but they should not be able to make any other changes to projects. What should you do?

- [x] Assign the finance team only the Billing Account User role on the billing account.
- [ ] Assign the engineering team only the Billing Account User role on the billing account.
- [ ] Assign the finance team the Billing Account User role on the billing account and the Project Billing Manager role on the organization.
- [ ] Assign the engineering team the Billing Account User role on the billing account and the Project Billing Manager role on the organization.

**[⬆ Back to Top](#table-of-contents)**

### You are creating a Google Kubernetes Engine (GKE) cluster with a cluster autoscaler feature enabled. You need to make sure that each node of the cluster will run a monitoring pod that sends container metrics to a third-party monitoring solution. What should you do?

- [ ] Deploy the monitoring pod in a StatefulSet object.
- [x] Deploy the monitoring pod in a DaemonSet object.
- [ ] Reference the monitoring pod in a Deployment object.
- [ ] Reference the monitoring pod in a cluster initializer at the GKE cluster creation time.

**[⬆ Back to Top](#table-of-contents)**

### You create a new Google Kubernetes Engine (GKE) cluster and want to make sure that it always runs a supported and stable version of Kubernetes. What should you do?

- [ ] Enable the Node Auto-Repair feature for your GKE cluster.
- [x] Enable the Node Auto-Upgrades feature for your GKE cluster.
- [ ] Select the latest available cluster version for your GKE cluster.
- [ ] Select 'Container-Optimized OS (cos)' as a node image for your GKE cluster.

**[⬆ Back to Top](#table-of-contents)**

### Your company uses Cloud Storage to store application backup files for disaster recovery purposes. You want to follow Google's recommended practices. Which storage option should you use?

- [ ] Multi-Regional Storage.
- [ ] Regional Storage.
- [ ] Nearline Storage.
- [x] Coldline Storage.

**[⬆ Back to Top](#table-of-contents)**

### You need to set up a policy so that videos stored in a specific Cloud Storage Regional bucket are moved to Coldline after 90 days, and then deleted after one year from their creation. How should you set up the policy?

- [ ] Use Cloud Storage Object Lifecycle Management using Age conditions with SetStorageClass and Delete actions. Set the SetStorageClass action to 90 days and the Delete action to 275 days (365-90).
- [x] Use Cloud Storage Object Lifecycle Management using Age conditions with SetStorageClass and Delete actions. Set the SetStorageClass action to 90 days and the Delete action to 365 days.
- [ ] Use gsutil rewrite and set the Delete action to 275 days (365-90).
- [ ] Use gsutil rewrite and set the Delete action to 365 days.

**[⬆ Back to Top](#table-of-contents)**

### Your company has an existing GCP organization with hundreds of projects and a billing account. Your company recently acquired another company that also has hundreds of projects and its own billing account. You would like to consolidate all GCP costs of both GCP organizations onto a single invoice. You would like to consolidate all costs as of tomorrow. What should you do?

- [x] Link the acquired company's projects to your company's billing account.
- [ ] Configure the acquired company's billing account and your company's billing account to export the billing data into the same BigQuery dataset.
- [ ] Migrate the acquired company's projects into your company's GCP organization. Link the migrated projects to your company's billing account.
- [ ] Create a new GCP organization and a new billing account. Migrate the acquired company's projects and your company's projects into the new GCP organization and link the projects to the new billing account.

**[⬆ Back to Top](#table-of-contents)**

### You want to configure 10 Compute Engine instances for availability when maintenance occurs. Your requirements state that these instances should attempt to automatically restart if they crash. Also, the instances should be highly available including during system maintenance. What should you do?

- [x] Create an instance template for the instances. Set the 'Automatic Restart' to on. Set the 'On-host maintenance' to Migrate VM instance. Add the instance template to an instance group.
- [ ] Create an instance template for the instances. Set 'Automatic Restart' to off. Set 'On-host maintenance' to Terminate VM instances. Add the instance template to an instance group.
- [ ] Create an instance group for the instances. Set the 'Autohealing' health check to healthy (HTTP).
- [ ] Create an instance group for the instance. Verify that the 'Advanced creation options' setting for 'do not retry machine creation' is set to off.

**[⬆ Back to Top](#table-of-contents)**

### You have a development project with appropriate IAM roles defined. You are creating a production project and want to have the same IAM roles on the new project, using the fewest possible steps. What should you do?

- [x] Use gcloud iam roles copy and specify the production project as the destination project.
- [ ] Use gcloud iam roles copy and specify your organization as the destination organization.
- [ ] In the Google Cloud Platform Console, use the 'create role from role' functionality.
- [ ] In the Google Cloud Platform Console, use the 'create role' functionality and select all applicable permissions.

**[⬆ Back to Top](#table-of-contents)**

### You are using multiple configurations for gcloud. You want to review the configured Kubernetes Engine cluster of an inactive configuration using the fewest possible steps. What should you do?

- [ ] Use gcloud config configurations describe to review the output.
- [ ] Use gcloud config configurations activate and gcloud config list to review the output.
- [ ] Use kubectl config get-contexts to review the output.
- [x] Use kubectl config use-context and kubectl config view to review the output.

**[⬆ Back to Top](#table-of-contents)**

### You need to configure IAM access audit logging in BigQuery for external auditors. You want to follow Google-recommended practices. What should you do?

- [x] Add the auditors group to the 'logging.viewer' and 'bigQuery.dataViewer' predefined IAM roles.
- [ ] Add the auditors group to two new custom IAM roles.
- [ ] Add the auditor user accounts to the 'logging.viewer' and 'bigQuery.dataViewer' predefined IAM roles.
- [ ] Add the auditor user accounts to two new custom IAM roles.

**[⬆ Back to Top](#table-of-contents)**

### You need to create a custom VPC with a single subnet. The subnet's range must be as large as possible. Which range should you use?

- [ ] 0.0.0.0/0.
- [x] 10.0.0.0/8.
- [ ] 172.16.0.0/12.
- [ ] 192.168.0.0/16.

**[⬆ Back to Top](#table-of-contents)**

### You recently deployed a new version of an application to App Engine and then discovered a bug in the release. You need to immediately revert to the prior version of the application. What should you do?

- [ ] Run gcloud app restore.
- [ ] On the App Engine page of the GCP Console, select the application that needs to be reverted and click Revert.
- [x] On the App Engine Versions page of the GCP Console, route 100% of the traffic to the previous version.
- [ ] Deploy the original version as a separate application. Then go to App Engine settings and split traffic between applications so that the original version serves 100% of the requests.

**[⬆ Back to Top](#table-of-contents)**

### You want to configure Autohealing for network load balancing for a group of Compute Engine instances that run in multiple zones, using the fewest possible steps. You need to configure re-creation of VMs if they are unresponsive after 3 attempts of 10 seconds each. What should you do?

- [ ] Create an HTTP load balancer with a backend configuration that references an existing instance group. Set the health check to healthy (HTTP).
- [ ] Create an HTTP load balancer with a backend configuration that references an existing instance group. Define a balancing mode and set the maximum RPS to 10.
- [x] Create a Managed Instance Group. Set the Autohealing health check to healthy (HTTP).
- [ ] Create a Managed Instance Group. Verify that the autoscaling setting is on.

**[⬆ Back to Top](#table-of-contents)**

### You have a Linux VM that must connect to Cloud SQL. You created a service account with the appropriate access rights. You want to make sure that the VM uses this service account instead of the default Compute Engine service account. What should you do?

- [x] When creating the VM via the web console, specify the service account under the 'Identity and API Access' section.
- [ ] Download a JSON Private Key for the service account. On the Project Metadata, add that JSON as the value for the key compute-engine-service-account.
- [ ] Download a JSON Private Key for the service account. On the Custom Metadata of the VM, add that JSON as the value for the key compute-engine-service-account.
- [ ] Download a JSON Private Key for the service account. After creating the VM, ssh into the VM and save the JSON under ~/.gcloud/compute-engine-service-account.json.

**[⬆ Back to Top](#table-of-contents)**

### You have one project called proj-sa where you manage all your service accounts. You want to be able to use a service account from this project to take snapshots of VMs running in another project called proj-vm. What should you do?

- [ ] Download the private key from the service account, and add it to each VMs custom metadata.
- [ ] Download the private key from the service account, and add the private key to each VM's SSH keys.
- [x] Grant the service account the IAM role of Compute Storage Admin in the project called proj-vm.
- [ ] When creating the VMs, set the service account's API scope for Compute Engine to read/write.

**[⬆ Back to Top](#table-of-contents)**

### You have one GCP account running in your default region and zone and another account running in a non-default region and zone. You want to start a new Compute Engine instance in these two Google Cloud Platform accounts using the command line interface. What should you do?

- [x] Create two configurations using gcloud config configurations create [NAME]. Run gcloud config configurations activate [NAME] to switch between accounts when running the commands to start the Compute Engine instances.
- [ ] Create two configurations using gcloud config configurations create [NAME]. Run gcloud configurations list to start the Compute Engine instances.
- [ ] Activate two configurations using gcloud configurations activate [NAME]. Run gcloud config list to start the Compute Engine instances.
- [ ] Activate two configurations using gcloud configurations activate [NAME]. Run gcloud configurations list to start the Compute Engine instances.

**[⬆ Back to Top](#table-of-contents)**

### Every employee of your company has a Google account. Your operational team needs to manage a large number of instances on Compute Engine. Each member of this team needs only administrative access to the servers. Your security team wants to ensure that the deployment of credentials is operationally efficient and must be able to determine who accessed a given instance. What should you do?

- [ ] Generate a new SSH key pair. Give the private key to each member of your team. Configure the public key in the metadata of each instance.
- [ ] Ask each member of the team to generate a new SSH key pair and to send you their public key. Use a configuration management tool to deploy those keys on each instance.
- [x] Ask each member of the team to generate a new SSH key pair and to add the public key to their Google account. Grant the 'compute.osAdminLogin' role to the Google group corresponding to this team.
- [ ] Generate a new SSH key pair. Give the private key to each member of your team. Configure the public key as a project-wide public SSH key in your Cloud Platform project and allow project-wide public SSH keys on each instance.

**[⬆ Back to Top](#table-of-contents)**

### You need to deploy an application, which is packaged in a container image, in a new project. The application exposes an HTTP endpoint and receives very few requests per day. You want to minimize costs. What should you do?

- [x] Deploy the container on Cloud Run.
- [ ] Deploy the container on Cloud Run on GK.
- [ ] Deploy the container on App Engine Flexible.
- [ ] Deploy the container on Google Kubernetes Engine, with cluster autoscaling and horizontal pod autoscaling enabled.

**[⬆ Back to Top](#table-of-contents)**

### Your development team needs a new Jenkins server for their project. You need to deploy the server using the fewest steps possible. What should you do?

- [ ] Download and deploy the Jenkins Java WAR to App Engine Standard.
- [ ] Create a new Compute Engine instance and install Jenkins through the command line interface.
- [ ] Create a Kubernetes cluster on Compute Engine and create a deployment with the Jenkins Docker image.
- [x] Use GCP Marketplace to launch the Jenkins solution.

**[⬆ Back to Top](#table-of-contents)**

### You are building an application that stores relational data from users. Users across the globe will use this application. Your CTO is concerned about the scaling requirements because the size of the user base is unknown. You need to implement a database solution that can scale with your user growth with minimum configuration changes. Which storage solution should you use?

- [ ] Cloud SQL.
- [x] Cloud Spanner.
- [ ] Cloud Firestore.
- [ ] Cloud Datastore.

**[⬆ Back to Top](#table-of-contents)**

### You are using Deployment Manager to create a Google Kubernetes Engine cluster. Using the same Deployment Manager deployment, you also want to create a DaemonSet in the kube-system namespace of the cluster. You want a solution that uses the fewest possible services.

- [x] Add the cluster's API as a new Type Provider in Deployment Manager, and use the new type to create the DaemonSet.
- [ ] Use the Deployment Manager Runtime Configurator to create a new Config resource that contains the DaemonSet definition.
- [ ] With Deployment Manager, create a Compute Engine instance with a startup script that uses kubectl to create the DaemonSet.
- [ ] In the cluster's definition in Deployment Manager, add a metadata that has kube-system as key and the DaemonSet manifest as value.

**[⬆ Back to Top](#table-of-contents)**

### You have a Virtual Machine that is currently configured with 2 vCPUs and 4 GB of memory. It is running out of memory. You want to upgrade the Virtual Machine to have 8 GB of memory. What should you do?

- [ ] Rely on live migration to move the workload to a machine with more memory.
- [ ] Use gcloud to add metadata to the V. Set the key to required-memory-size and the value to 8 GB.
- [ ] Stop the VM, change the machine type to n1-standard-8, and start the VM.
- [x] Stop the VM, increase the memory to 8 GB, and start the VM.

**[⬆ Back to Top](#table-of-contents)**

### You created a Google Cloud Platform project with an App Engine application inside the project. You initially configured the application to be served from the us-central region. Now you want the application to be served from the asia-northeast1 region. What should you do?

- [ ] Change the default region property setting in the existing GCP project to asia-northeast1.
- [ ] Change the region property setting in the existing App Engine application from us-central to asia-northeast1.
- [ ] Create a second App Engine application in the existing GCP project and specify asia-northeast1 as the region to serve your application.
- [x] Create a new GCP project and create an App Engine application inside this new project. Specify asia-northeast1 as the region to serve your application.

**[⬆ Back to Top](#table-of-contents)**

### Several employees at your company have been creating projects with Cloud Platform and paying for it with their personal credit cards, which the company reimburses. The company wants to centralize all these projects under a single, new billing account. What should you do?

- [ ] Contact [email protected] with your bank account details and request a corporate billing account for your company.
- [ ] Create a ticket with Google Support and wait for their call to share your credit card details over the phone.
- [ ] In the Google Platform Console, go to the Resource Manage and move all projects to the root Organization.
- [x] In the Google Cloud Platform Console, create a new billing account and set up a payment method.

**[⬆ Back to Top](#table-of-contents)**

### You have a Dockerfile that you need to deploy on Kubernetes Engine. What should you do?

- [ ] Use kubectl app deploy `<dockerfilename>`.
- [ ] Use gcloud app deploy `<dockerfilename>`.
- [x] Create a docker image from the Dockerfile and upload it to Container Registry. Create a Deployment YAML file to point to that image. Use kubectl to create the deployment with that file.
- [ ] Create a docker image from the Dockerfile and upload it to Cloud Storage. Create a Deployment YAML file to point to that image. Use kubectl to create the deployment with that file.

**[⬆ Back to Top](#table-of-contents)**

### You have a project for your App Engine application that serves a development environment. The required testing has succeeded and you want to create a new project to serve as your production environment. What should you do?

- [x] Use gcloud to create the new project, and then deploy your application to the new project.
- [ ] Use gcloud to create the new project and to copy the deployed application to the new project.
- [ ] Create a Deployment Manager configuration file that copies the current App Engine deployment into a new project.
- [ ] Deploy your application again using gcloud and specify the project parameter with the new project name to create the new project.

**[⬆ Back to Top](#table-of-contents)**

### You are building an application that will run in your data center. The application will use Google Cloud Platform (GCP) services like AutoML. You created a service account that has appropriate access to AutoML. You need to enable authentication to the APIs from your on-premises environment. What should you do?

- [ ] Use service account credentials in your on-premises application.
- [x] Use gcloud to create a key file for the service account that has appropriate permissions.
- [ ] Set up direct interconnect between your data center and Google Cloud Platform to enable authentication for your on-premises applications.
- [ ] Go to the IAM & admin console, grant a user account permissions similar to the service account permissions, and use this user account for authentication from your data center.

**[⬆ Back to Top](#table-of-contents)**

### You host a static website on Cloud Storage. Recently, you began to include links to PDF files on this site. Currently, when users click on the links to these PDF files, their browsers prompt them to save the file onto their local system. Instead, you want the clicked PDF files to be displayed within the browser window directly, without prompting the user to save the file locally. What should you do?

- [ ] Enable Cloud CDN on the website frontend.
- [ ] Enable 'Share publicly' on the PDF file objects.
- [x] Set Content-Type metadata to application/pdf on the PDF file objects.
- [ ] Add a label to the storage bucket with a key of Content-Type and value of application/pdf.

**[⬆ Back to Top](#table-of-contents)**

### You have an application that looks for its licensing server on the IP 10.0.3.21. You need to deploy the licensing server on Compute Engine. You do not want to change the configuration of the application and want the application to be able to reach the licensing server. What should you do?

- [x] Reserve the IP 10.0.3.21 as a static internal IP address using gcloud and assign it to the licensing server.
- [ ] Reserve the IP 10.0.3.21 as a static public IP address using gcloud and assign it to the licensing server.
- [ ] Use the IP 10.0.3.21 as a custom ephemeral IP address and assign it to the licensing server.
- [ ] Start the licensing server with an automatic ephemeral IP address, and then promote it to a static internal IP address.

**[⬆ Back to Top](#table-of-contents)**

### You are deploying an application to App Engine. You want the number of instances to scale based on request rate. You need at least 3 unoccupied instances at all times. Which scaling type should you use?

- [ ] Manual Scaling with 3 instances.
- [ ] Basic Scaling with min_instances set to 3.
- [ ] Basic Scaling with max_instances set to 3.
- [x] Automatic Scaling with min_idle_instances set to 3.

**[⬆ Back to Top](#table-of-contents)**

### You are the project owner of a GCP project and want to delegate control to colleagues to manage buckets and files in Cloud Storage. You want to follow Google-recommended practices. Which IAM roles should you grant your colleagues?

- [ ] Project Editor.
- [x] Storage Admin.
- [ ] Storage Object Admin.
- [ ] Storage Object Creator.

**[⬆ Back to Top](#table-of-contents)**

### You need to update a deployment in Deployment Manager without any resource downtime in the deployment. Which command should you use?

- [ ] gcloud deployment-manager deployments create –config <deployment-config-path>.
- [x] gcloud deployment-manager deployments update –config <deployment-config-path>.
- [ ] gcloud deployment-manager resources create –config <deployment-config-path>.
- [ ] gcloud deployment-manager resources update –config <deployment-config-path>.

**[⬆ Back to Top](#table-of-contents)**

### You are running an application on multiple Virtual Machines within a Managed Instance Group and have autoscaling enabled. The autoscaling policy is configured so that additional instances are added to the group if the CPU utilization of instances goes above 80%. VMs are added until the instance group reaches its maximum limit of five VMs or until CPU utilization of instances lowers to 80%. The initial delay for HTTP health checks against the instances is set to 30 seconds. The Virtual Machine instances take around three minutes to become available for users. You observe that when the instance group autoscales, it adds more instances then necessary to support the levels of end-user traffic. You want to properly maintain instance group sizes when autoscaling. What should you do?

- [ ] Set the maximum number of instances to 1.
- [ ] Decrease the maximum number of instances to 3.
- [ ] Use a TCP health check instead of an HTTP health check.
- [x] Increase the initial delay of the HTTP health check to 200 seconds.

**[⬆ Back to Top](#table-of-contents)**

### You have 32 GB of data in a single file that you need to upload to a Nearline Storage bucket. The WAN connection you are using is rated at 1 Gbps, and you are the only one on the connection. You want to use as much of the rated 1 Gbps as possible to transfer the file rapidly. How should you upload the file?

- [ ] Use the GCP Console to transfer the file instead of gsutil.
- [x] Enable parallel composite uploads using gsutil on the file transfer.
- [ ] Decrease the TCP window size on the machine initiating the transfer.
- [ ] Change the storage class of the bucket from Nearline to Multi-Regional.

**[⬆ Back to Top](#table-of-contents)**

### You deployed an App Engine application using gcloud app deploy, but it did not deploy to the intended project. You want to find out why this happened and where the application deployed. What should you do?

- [ ] Check the app.yaml file for your application and check project settings.
- [ ] Check the web-application.xml file for your application and check project settings.
- [ ] Go to Deployment Manager and review settings for deployment of applications.
- [x] Go to Cloud Shell and run gcloud config list to review the Google Cloud configuration used for deployment.

**[⬆ Back to Top](#table-of-contents)**

### You want to verify the IAM users and roles assigned within a GCP project named my-project. What should you do?

- [ ] Run gcloud iam roles list. Review the output section.
- [ ] Run gcloud iam service-accounts list. Review the output section.
- [x] Navigate to the project and then to the IAM section in the GCP Console. Review the members and roles.
- [ ] Navigate to the project and then to the Roles section in the GCP Console. Review the roles and status.

**[⬆ Back to Top](#table-of-contents)**

### You need to select and configure compute resources for a set of batch processing jobs. These jobs take around 2 hours to complete and are run nightly. You want to minimize service costs. What should you do?

- [ ] Select Google Kubernetes Engine. Use a single-node cluster with a small instance type.
- [ ] Select Google Kubernetes Engine. Use a three-node cluster with micro instance types.
- [x] Select Compute Engine. Use preemptible VM instances of the appropriate standard machine type.
- [ ] Select Compute Engine. Use VM instance types that support micro bursting.

**[⬆ Back to Top](#table-of-contents)**

### You want to select and configure a cost-effective solution for relational data on Google Cloud Platform. You are working with a small set of operational data in one geographic location. You need to support point-in-time recovery. What should you do?

- [x] Select Cloud SQL (MySQL). Verify that the enable binary logging option is selected.
- [ ] Select Cloud SQL (MySQL). Select the create failover replicas option.
- [ ] Select Cloud Spanner. Set up your instance with 2 nodes.
- [ ] Select Cloud Spanner. Set up your instance as multi-regional.

**[⬆ Back to Top](#table-of-contents)**

### You are hosting an application on bare-metal servers in your own data center. The application needs access to Cloud Storage. However, security policies prevent the servers hosting the application from having public IP addresses or access to the internet. You want to follow Google-recommended practices to provide the application with access to Cloud Storage. What should you do?

- [ ] 1. Use nslookup to get the IP address for storage.googleapis.com. 2. Negotiate with the security team to be able to give a public IP address to the servers. 3. Only allow egress traffic from those servers to the IP addresses for storage.googleapis.com.
- [ ] 1. Using Cloud VPN, create a VPN tunnel to a Virtual Private Cloud (VPC) in Google Cloud. 2. In this VPC, create a Compute Engine instance and install the Squid proxy server on this instance. 3. Configure your servers to use that instance as a proxy to access Cloud Storage.
- [ ] 1. Use Migrate for Compute Engine (formerly known as Velostrata) to migrate those servers to Compute Engine. 2. Create an internal load balancer (ILB) that uses storage.googleapis.com as backend. 3. Configure your new instances to use this ILB as proxy.
- [x] 1. Using Cloud VPN or Interconnect, create a tunnel to a VPC in Google Cloud. 2. Use Cloud Router to create a custom route advertisement for 199.36.153.4/30. Announce that network to your on-premises network through the VPN tunnel. 3. In your on-premises network, configure your DNS server to resolve *.googleapis.com as a CNAME to restricted.googleapis.com.

**[⬆ Back to Top](#table-of-contents)**

### Your company has a Google Cloud Platform project that uses BigQuery for data warehousing. Your data science team changes frequently and has few members. You need to allow members of this team to perform queries. You want to follow Google-recommended practices. What should you do?

- [ ] 1. Create an IAM entry for each data scientist's user account. 2. Assign the BigQuery jobUser role to the group.
- [ ] 1. Create an IAM entry for each data scientist's user account. 2. Assign the BigQuery dataViewer user role to the group.
- [x] 1. Create a dedicated Google group in Cloud Identity. 2. Add each data scientist's user account to the group. 3. Assign the BigQuery jobUser role to the group.
- [ ] 1. Create a dedicated Google group in Cloud Identity. 2. Add each data scientist's user account to the group. 3. Assign the BigQuery dataViewer user role to the group.

**[⬆ Back to Top](#table-of-contents)**

### You are given a project with a single Virtual Private Cloud (VPC) and a single subnetwork in the us-central1 region. There is a Compute Engine instance hosting an application in this subnetwork. You need to deploy a new instance in the same project in the europe-west1 region. This new instance needs access to the application. You want to follow Google-recommended practices. What should you do?

- [x] 1. Create a subnetwork in the same VPC, in europe-west1. 2. Create the new instance in the new subnetwork and use the first instance's private address as the endpoint.
- [ ] 1. Create a VPC and a subnetwork in europe-west1. 2. Expose the application with an internal load balancer. 3. Create the new instance in the new subnetwork and use the load balancer's address as the endpoint.
- [ ] 1. Create a subnetwork in the same VPC, in europe-west1. 2. Use Cloud VPN to connect the two subnetworks. 3. Create the new instance in the new subnetwork and use the first instance's private address as the endpoint.
- [ ] 1. Create a VPC and a subnetwork in europe-west1. 2. Peer the 2 VPCs. 3. Create the new instance in the new subnetwork and use the first instance's private address as the endpoint.

**[⬆ Back to Top](#table-of-contents)**

### You are building a pipeline to process time-series data. Which Google Cloud Platform services should you put in boxes 1,2,3, and 4?

![Google Cloud Platform services](images/pipeline.jpeg)

- [ ] Cloud Pub/Sub, Cloud Dataflow, Cloud Datastore, BigQuery.
- [ ] Firebase Messages, Cloud Pub/Sub, Cloud Spanner, BigQuery.
- [ ] Cloud Pub/Sub, Cloud Storage, BigQuery, Cloud Bigtable.
- [x] Cloud Pub/Sub, Cloud Dataflow, Cloud Bigtable, BigQuery.

**[⬆ Back to Top](#table-of-contents)**

### For analysis purposes, you need to send all the logs from all of your Compute Engine instances to a BigQuery dataset called platform-logs. You have already installed the Cloud Logging agent on all the instances. You want to minimize cost. What should you do?

- [ ] 1. Give the BigQuery Data Editor role on the platform-logs dataset to the service accounts used by your instances. 2. Update your instances' metadata to add the following value: logs-destination: bq://platform-logs.
- [ ] 1. In Cloud Logging, create a logs export with a Cloud Pub/Sub topic called logs as a sink. 2. Create a Cloud Function that is triggered by messages in the logs topic. 3. Configure that Cloud Function to drop logs that are not from Compute Engine and to insert Compute Engine logs in the platform-logs dataset.
- [x] 1. In Cloud Logging, create a filter to view only Compute Engine logs. 2. Click Create Export. 3. Choose BigQuery as Sink Service, and the platform-logs dataset as Sink Destination.
- [ ] 1. Create a Cloud Function that has the BigQuery User role on the platform-logs dataset. 2. Configure this Cloud Function to create a BigQuery Job that executes this query: INSERT INTO dataset.platform-logs (timestamp, log) SELECT timestamp, log FROM compute.logs WHERE timestamp > DATE_SUB(CURRENT_DATE(), INTERVAL 1 DAY) 3. Use Cloud Scheduler to trigger this Cloud Function once a day.

**[⬆ Back to Top](#table-of-contents)**

### You want to deploy an application on Cloud Run that processes messages from a Cloud Pub/Sub topic. You want to follow Google-recommended practices. What should you do?

- [ ] 1. Create a Cloud Function that uses a Cloud Pub/Sub trigger on that topic. 2. Call your application on Cloud Run from the Cloud Function for every message.
- [ ] 1. Grant the Pub/Sub Subscriber role to the service account used by Cloud Run. 2. Create a Cloud Pub/Sub subscription for that topic. 3. Make your application pull messages from that subscription.
- [x] 1. Create a service account. 2. Give the Cloud Run Invoker role to that service account for your Cloud Run application. 3. Create a Cloud Pub/Sub subscription that uses that service account and uses your Cloud Run application as the push endpoint.
- [ ] 1. Deploy your application on Cloud Run on GKE with the connectivity set to Internal. 2. Create a Cloud Pub/Sub subscription for that topic. 3. In the same Google Kubernetes Engine cluster as your application, deploy a container that takes the messages and sends them to your application.

**[⬆ Back to Top](#table-of-contents)**

### Your projects incurred more costs than you expected last month. Your research reveals that a development GKE container emitted a huge number of logs, which resulted in higher costs. You want to disable the logs quickly using the minimum number of steps. What should you do?

- [x] 1. Go to the Logs ingestion window in Stackdriver Logging, and disable the log source for the GKE container resource.
- [ ] 1. Go to the Logs ingestion window in Stackdriver Logging, and disable the log source for the GKE Cluster Operations resource.
- [ ] 1. Go to the GKE console, and delete existing clusters. 2. Recreate a new cluster. 3. Clear the option to enable legacy Stackdriver Logging.
- [ ] 1. Go to the GKE console, and delete existing clusters. 2. Recreate a new cluster. 3. Clear the option to enable legacy Stackdriver Monitoring.

**[⬆ Back to Top](#table-of-contents)**

### You've deployed a microservice called myapp1 to a Google Kubernetes Engine cluster using the YAML file specified below. You need to refactor this configuration so that the database password is not stored in plain text. You want to follow Google-recommended practices. What should you do?

![YAML of microservice myapp1](images/yaml.jpg)

- [ ] Store the database password inside the Docker image of the container, not in the YAML file.
- [x] Store the database password inside a Secret object. Modify the YAML file to populate the DB_PASSWORD environment variable from the Secret.
- [ ] Store the database password inside a ConfigMap object. Modify the YAML file to populate the DB_PASSWORD environment variable from the ConfigMap.
- [ ] Store the database password in a file inside a Kubernetes persistent volume, and use a persistent volume claim to mount the volume to the container.

**[⬆ Back to Top](#table-of-contents)**

### You have an application running in Google Kubernetes Engine (GKE) with cluster autoscaling enabled. The application exposes a TCP endpoint. There are several replicas of this application. You have a Compute Engine instance in the same region, but in another Virtual Private Cloud (VPC), called gce-network, that has no overlapping IP ranges with the first VPC. This instance needs to connect to the application on GKE. You want to minimize effort. What should you do?

- [x] 1. In GKE, create a Service of type LoadBalancer that uses the application's Pods as backend. 2. Set the service's externalTrafficPolicy to Cluster. 3. Configure the Compute Engine instance to use the address of the load balancer that has been created.
- [ ] 1. In GKE, create a Service of type NodePort that uses the application's Pods as backend. 2. Create a Compute Engine instance called proxy with 2 network interfaces, one in each VPC. 3. Use iptables on this instance to forward traffic from gce-network to the GKE nodes. 4. Configure the Compute Engine instance to use the address of proxy in gce-network as endpoint.
- [ ] 1. In GKE, create a Service of type LoadBalancer that uses the application's Pods as backend. 2. Add an annotation to this service: cloud.google.com/load-balancer-type: Internal 3. Peer the two VPCs together. 4. Configure the Compute Engine instance to use the address of the load balancer that has been created.
- [ ] 1. In GKE, create a Service of type LoadBalancer that uses the application's Pods as backend. 2. Add a Cloud Armor Security Policy to the load balancer that whitelists the internal IPs of the MIG's instances. 3. Configure the Compute Engine instance to use the address of the load balancer that has been created.

**[⬆ Back to Top](#table-of-contents)**

### You are using Container Registry to centrally store your company's container images in a separate project. In another project, you want to create a Google Kubernetes Engine (GKE) cluster. You want to ensure that Kubernetes can download images from Container Registry. What should you do?

- [x] In the project where the images are stored, grant the Storage Object Viewer IAM role to the service account used by the Kubernetes nodes.
- [ ] When you create the GKE cluster, choose the Allow full access to all Cloud APIs option under 'Access scopes'.
- [ ] Create a service account, and give it access to Cloud Storage. Create a P12 key for this service account and use it as an imagePullSecrets in Kubernetes.
- [ ] Configure the ACLs on each image in Cloud Storage to give read-only access to the default Compute Engine service account.

**[⬆ Back to Top](#table-of-contents)**

### You deployed a new application inside your Google Kubernetes Engine cluster using the YAML file specified below. You check the status of the deployed pods and notice that one of them is still in PENDING status. You want to find out why the pod is stuck in pending status. What should you do?

![YAML of Google Kubernetes Engine](images/yaml2.png)

![Deployed pods status](images/pods.png)

- [ ] Review details of the myapp-service Service object and check for error messages.
- [ ] Review details of the myapp-deployment Deployment object and check for error messages.
- [x] Review details of myapp-deployment-58ddbbb995-lp86m Pod and check for warning messages.
- [ ] View logs of the container in myapp-deployment-58ddbbb995-lp86m pod and check for warning messages.

**[⬆ Back to Top](#table-of-contents)**

### You are setting up a Windows VM on Compute Engine and want to make sure you can log in to the VM via RDP. What should you do?

- [ ] After the VM has been created, use your Google Account credentials to log in into the VM.
- [x] After the VM has been created, use gcloud compute reset-windows-password to retrieve the login credentials for the VM.
- [ ] When creating the VM, add metadata to the instance using 'windows-password' as the key and a password as the value.
- [ ] After the VM has been created, download the JSON Private Key for the default Compute Engine service account. Use the credentials in the JSON file to log in to the VM.

**[⬆ Back to Top](#table-of-contents)**

### You want to configure an SSH connection to a single Compute Engine instance for users in the dev1 group. This instance is the only resource in this particular Google Cloud Platform project that the dev1 users should be able to connect to. What should you do?

- [x] Set metadata to enable-oslogin=true for the instance. Grant the dev1 group the compute.osLogin role. Direct them to use the Cloud Shell to ssh to that instance.
- [ ] Set metadata to enable-oslogin=true for the instance. Set the service account to no service account for that instance. Direct them to use the Cloud Shell to ssh to that instance.
- [ ] Enable block project wide keys for the instance. Generate an SSH key for each user in the dev1 group. Distribute the keys to dev1 users and direct them to use their third-party tools to connect.
- [ ] Enable block project wide keys for the instance. Generate an SSH key and associate the key with that instance. Distribute the key to dev1 users and direct them to use their third-party tools to connect.

**[⬆ Back to Top](#table-of-contents)**

### You need to produce a list of the enabled Google Cloud Platform APIs for a GCP project using the gcloud command line in the Cloud Shell. The project name is my-project. What should you do?

- [x] Run gcloud projects list to get the project ID, and then run gcloud services list --project <project ID>.
- [ ] Run gcloud init to set the current project to my-project, and then run gcloud services list --available.
- [ ] Run gcloud info to view the account value, and then run gcloud services list --account <Account>.
- [ ] Run gcloud projects describe <project ID> to verify the project value, and then run gcloud services list --available.

**[⬆ Back to Top](#table-of-contents)**

### You are building a new version of an application hosted in an App Engine environment. You want to test the new version with 1% of users before you completely switch your application over to the new version. What should you do?

- [ ] Deploy a new version of your application in Google Kubernetes Engine instead of App Engine and then use GCP Console to split traffic.
- [ ] Deploy a new version of your application in a Compute Engine instance instead of App Engine and then use GCP Console to split traffic.
- [ ] Deploy a new version as a separate app in App Engine. Then configure App Engine using GCP Console to split traffic between the two apps.
- [x] Deploy a new version of your application in App Engine. Then go to App Engine settings in GCP Console and split traffic between the current version and newly deployed versions accordingly.

**[⬆ Back to Top](#table-of-contents)**

### You need to provide a cost estimate for a Kubernetes cluster using the GCP pricing calculator for Kubernetes. Your workload requires high IOPs, and you will also be using disk snapshots. You start by entering the number of nodes, average hours, and average days. What should you do next?

- [x] Fill in local SSD. Fill in persistent disk storage and snapshot storage.
- [ ] Fill in local SSD. Add estimated cost for cluster management.
- [ ] Select Add GPUs. Fill in persistent disk storage and snapshot storage.
- [ ] Select Add GPUs. Add estimated cost for cluster management.

**[⬆ Back to Top](#table-of-contents)**

### You are using Google Kubernetes Engine with autoscaling enabled to host a new application. You want to expose this new application to the public, using HTTPS on a public IP address. What should you do?

- [x] Create a Kubernetes Service of type NodePort for your application, and a Kubernetes Ingress to expose this Service via a Cloud Load Balancer.
- [ ] Create a Kubernetes Service of type ClusterIP for your application. Configure the public DNS name of your application using the IP of this Service.
- [ ] Create a Kubernetes Service of type NodePort to expose the application on port 443 of each node of the Kubernetes cluster. Configure the public DNS name of your application with the IP of every node of the cluster to achieve load-balancing.
- [ ] Create a HAProxy pod in the cluster to load-balance the traffic to all the pods of the application. Forward the public traffic to HAProxy with an iptable rule. Configure the DNS name of your application using the public IP of the node HAProxy is running on.

**[⬆ Back to Top](#table-of-contents)**

### You need to enable traffic between multiple groups of Compute Engine instances that are currently running two different GCP projects. Each group of Compute Engine instances is running in its own VPC. What should you do?

- [ ] Verify that both projects are in a GCP Organization. Create a new VPC and add all instances.
- [x] Verify that both projects are in a GCP Organization. Share the VPC from one project and request that the Compute Engine instances in the other project use this shared VPC.
- [ ] Verify that you are the Project Administrator of both projects. Create two new VPCs and add all instances.
- [ ] Verify that you are the Project Administrator of both projects. Create a new VPC and add all instances.

**[⬆ Back to Top](#table-of-contents)**

### You want to add a new auditor to a Google Cloud Platform project. The auditor should be allowed to read, but not modify, all project items. How should you configure the auditor's permissions?

- [ ] Create a custom role with view-only project permissions. Add the user's account to the custom role.
- [ ] Create a custom role with view-only service permissions. Add the user's account to the custom role.
- [x] Select the built-in IAM project Viewer role. Add the user's account to this role.
- [ ] Select the built-in IAM service Viewer role. Add the user's account to this role.

**[⬆ Back to Top](#table-of-contents)**

### You are operating a Google Kubernetes Engine (GKE) cluster for your company where different teams can run non-production workloads. Your Machine Learning (ML) team needs access to Nvidia Tesla P100 GPUs to train their models. You want to minimize effort and cost. What should you do?

- [ ] Ask your ML team to add the accelerator: gpu annotation to their pod specification.
- [ ] Recreate all the nodes of the GKE cluster to enable GPUs on all of them.
- [ ] Create your own Kubernetes cluster on top of Compute Engine with nodes that have GPUs. Dedicate this cluster to your ML team.
- [x] Add a new, GPU-enabled, node pool to the GKE cluster. Ask your ML team to add the cloud.google.com/gke -accelerator: nvidia-tesla-p100 nodeSelector to their pod specification.

**[⬆ Back to Top](#table-of-contents)**

### Your VMs are running in a subnet that has a subnet mask of 255.255.255.240. The current subnet has no more free IP addresses and you require an additional 10 IP addresses for new VMs. The existing and new VMs should all be able to reach each other without additional routes. What should you do?

- [x] Use gcloud to expand the IP range of the current subnet.
- [ ] Delete the subnet, and recreate it using a wider range of IP addresses.
- [ ] Create a new project. Use Shared VPC to share the current network with the new project.
- [ ] Create a new subnet with the same starting IP but a wider range to overwrite the current subnet.

**[⬆ Back to Top](#table-of-contents)**

### Your organization uses G Suite for communication and collaboration. All users in your organization have a G Suite account. You want to grant some G Suite users access to your Cloud Platform project. What should you do?

- [ ] Enable Cloud Identity in the GCP Console for your domain.
- [x] Grant them the required IAM roles using their G Suite email address.
- [ ] Create a CSV sheet with all users' email addresses. Use the gcloud command line tool to convert them into Google Cloud Platform accounts.
- [ ] In the G Suite console, add the users to a special group called cloud-console-users@yourdomain.com. Rely on the default behavior of the Cloud Platform to grant users access if they are members of this group.

**[⬆ Back to Top](#table-of-contents)**

### You have a Google Cloud Platform account with access to both production and development projects. You need to create an automated process to list all compute instances in development and production projects on a daily basis. What should you do?

- [x] Create two configurations using gcloud config. Write a script that sets configurations as active, individually. For each configuration, use gcloud compute instances list to get a list of compute resources.
- [ ] Create two configurations using gsutil config. Write a script that sets configurations as active, individually. For each configuration, use gsutil compute instances list to get a list of compute resources.
- [ ] Go to Cloud Shell and export this information to Cloud Storage on a daily basis.
- [ ] Go to GCP Console and export this information to Cloud SQL on a daily basis.

**[⬆ Back to Top](#table-of-contents)**

### You have a large 5-TB AVRO file stored in a Cloud Storage bucket. Your analysts are proficient only in SQL and need access to the data stored in this file. You want to find a cost-effective way to complete their request as soon as possible. What should you do?

- [ ] Load data in Cloud Datastore and run a SQL query against it.
- [ ] Create a BigQuery table and load data in BigQuery. Run a SQL query on this table and drop this table after you complete your request.
- [x] Create external tables in BigQuery that point to Cloud Storage buckets and run a SQL query on these external tables to complete your request.
- [ ] Create a Hadoop cluster and copy the AVRO file to NDFS by compressing it. Load the file in a hive table and provide access to your analysts so that they can run SQL queries.

**[⬆ Back to Top](#table-of-contents)**

### You need to verify that a Google Cloud Platform service account was created at a particular time. What should you do?

- [x] Filter the Activity log to view the Configuration category. Filter the Resource type to Service Account.
- [ ] Filter the Activity log to view the Configuration category. Filter the Resource type to Google Project.
- [ ] Filter the Activity log to view the Data Access category. Filter the Resource type to Service Account.
- [ ] Filter the Activity log to view the Data Access category. Filter the Resource type to Google Project.

**[⬆ Back to Top](#table-of-contents)**

### You deployed an LDAP server on Compute Engine that is reachable via TLS through port 636 using UDP. You want to make sure it is reachable by clients over that port. What should you do?

- [ ] Add the network tag allow-udp-636 to the VM instance running the LDAP server.
- [ ] Create a route called allow-udp-636 and set the next hop to be the VM instance running the LDAP server.
- [x] Add a network tag of your choice to the instance. Create a firewall rule to allow ingress on UDP port 636 for that network tag.
- [ ] Add a network tag of your choice to the instance running the LDAP server. Create a firewall rule to allow egress on UDP port 636 for that network tag.

**[⬆ Back to Top](#table-of-contents)**

### You need to set a budget alert for use of Compute Engine services on one of the three Google Cloud Platform projects that you manage. All three projects are linked to a single billing account. What should you do?

- [x] Verify that you are the project billing administrator. Select the associated billing account and create a budget and alert for the appropriate project.
- [ ] Verify that you are the project billing administrator. Select the associated billing account and create a budget and a custom alert.
- [ ] Verify that you are the project administrator. Select the associated billing account and create a budget for the appropriate project.
- [ ] Verify that you are project administrator. Select the associated billing account and create a budget and a custom alert.

**[⬆ Back to Top](#table-of-contents)**

### You are migrating a production-critical on-premises application that requires 96 vCPUs to perform its task. You want to make sure the application runs in a similar environment on GCP. What should you do?

- [x] When creating the VM, use machine type n1-standard-96.
- [ ] When creating the VM, use Intel Skylake as the CPU platform.
- [ ] Create the VM using Compute Engine default settings. Use gcloud to modify the running instance to have 96 vCPUs.
- [ ] Start the VM using Compute Engine default settings, and adjust as you go based on Rightsizing Recommendations.

**[⬆ Back to Top](#table-of-contents)**

### You want to configure a solution for archiving data in a Cloud Storage bucket. The solution must be cost-effective. Data with multiple versions should be archived after 30 days. Previous versions are accessed once a month for reporting. This archive data is also occasionally updated at month-end. What should you do?

- [ ] Add a bucket lifecycle rule that archives data with newer versions after 30 days to Coldline Storage.
- [x] Add a bucket lifecycle rule that archives data with newer versions after 30 days to Nearline Storage.
- [ ] Add a bucket lifecycle rule that archives data from regional storage after 30 days to Coldline Storage.
- [ ] Add a bucket lifecycle rule that archives data from regional storage after 30 days to Nearline Storage.

**[⬆ Back to Top](#table-of-contents)**

### Your company's infrastructure is on-premises, but all machines are running at maximum capacity. You want to burst to Google Cloud. The workloads on Google Cloud must be able to directly communicate to the workloads on-premises using a private IP range. What should you do?

- [ ] In Google Cloud, configure the VPC as a host for Shared VP.
- [ ] In Google Cloud, configure the VPC for VPC Network Peering.
- [ ] Create bastion hosts both in your on-premises environment and on Google Cloud. Configure both as proxy servers using their public IP addresses.
- [x] Set up Cloud VPN between the infrastructure on-premises and Google Cloud.

**[⬆ Back to Top](#table-of-contents)**

### You want to select and configure a solution for storing and archiving data on Google Cloud Platform. You need to support compliance objectives for data from one geographic location. This data is archived after 30 days and needs to be accessed annually. What should you do?

- [ ] Select Multi-Regional Storage. Add a bucket lifecycle rule that archives data after 30 days to Coldline Storage.
- [ ] Select Multi-Regional Storage. Add a bucket lifecycle rule that archives data after 30 days to Nearline Storage.
- [ ] Select Regional Storage. Add a bucket lifecycle rule that archives data after 30 days to Nearline Storage.
- [x] Select Regional Storage. Add a bucket lifecycle rule that archives data after 30 days to Coldline Storage.

**[⬆ Back to Top](#table-of-contents)**

### Your company uses BigQuery for data warehousing. Over time, many different business units in your company have created 1000+ datasets across hundreds of projects. Your CIO wants you to examine all datasets to find tables that contain an employee_ssn column. You want to minimize effort in performing this task. What should you do?

- [x] Go to Data Catalog and search for employee_ssn in the search box.
- [ ] Write a shell script that uses the bq command line tool to loop through all the projects in your organization.
- [ ] Write a script that loops through all the projects in your organization and runs a query on INFORMATION_SCHEMA.COLUMNS view to find the employee_ssn column.
- [ ] Write a Cloud Dataflow job that loops through all the projects in your organization and runs a query on INFORMATION_SCHEMA.COLUMNS view to find employee_ssn column.

**[⬆ Back to Top](#table-of-contents)**

### You create a Deployment with 2 replicas in a Google Kubernetes Engine cluster that has a single preemptible node pool. After a few minutes, you use kubectl to examine the status of your Pod and observe that one of them is still in Pending status. What is the most likely cause?

![Deployed pods status](images/pods.png)

- [ ] The pending Pod's resource requests are too large to fit on a single node of the cluster.
- [ ] Too many Pods are already running in the cluster, and there are not enough resources left to schedule the pending Pod.
- [ ] The node pool is configured with a service account that does not have permission to pull the container image used by the pending Pod.
- [x] The pending Pod was originally scheduled on a node that has been preempted between the creation of the Deployment and your verification of the Pods' status. It is currently being rescheduled on a new node.

**[⬆ Back to Top](#table-of-contents)**

### You want to find out when users were added to Cloud Spanner Identity Access Management (IAM) roles on your Google Cloud Platform (GCP) project. What should you do in the GCP Console?

- [ ] Open the Cloud Spanner console to review configurations.
- [ ] Open the IAM &amp; admin console to review IAM policies for Cloud Spanner roles.
- [ ] Go to the Stackdriver Monitoring console and review information for Cloud Spanner.
- [x] Go to the Stackdriver Logging console, review admin activity logs, and filter them for Cloud Spanner IAM roles.

**[⬆ Back to Top](#table-of-contents)**

### Your company implemented BigQuery as an enterprise data warehouse. Users from multiple business units run queries on this data warehouse. However, you notice that query costs for BigQuery are very high, and you need to control costs. Which two methods should you use? (Choose two.)

- [ ] Split the users from business units to multiple projects.
- [x] Apply a user- or project-level custom query quota for BigQuery data warehouse.
- [ ] Create separate copies of your BigQuery data warehouse for each business unit.
- [ ] Split your BigQuery data warehouse into multiple data warehouses for each business unit.
- [x] Change your BigQuery query model from on-demand to flat rate. Apply the appropriate number of slots to each Project.

**[⬆ Back to Top](#table-of-contents)**

### You are building a product on top of Google Kubernetes Engine (GKE). You have a single GKE cluster. For each of your customers, a Pod is running in that cluster, and your customers can run arbitrary code inside their Pod. You want to maximize the isolation between your customers' Pods. What should you do?

- [ ] Use Binary Authorization and whitelist only the container images used by your customers' Pods.
- [ ] Use the Container Analysis API to detect vulnerabilities in the containers used by your customers' Pods.
- [x] Create a GKE node pool with a sandbox type configured to gvisor. Add the parameter runtimeClassName: gvisor to the specification of your customers' Pods.
- [ ] Use the cos_containerd image for your GKE nodes. Add a nodeSelector with the value cloud.google.com/gke-os-distribution: cos_containerd to the specification of your customers' Pods.

**[⬆ Back to Top](#table-of-contents)**

### Your customer has implemented a solution that uses Cloud Spanner and notices some read latency-related performance issues on one table. This table is accessed only by their users using a primary key. The table schema is shown below. You want to resolve the issue. What should you do?

![Database table](images/db_table.png)

- [ ] Remove the profile_picture field from the table.
- [ ] Add a secondary index on the person_id column.
- [x] Change the primary key to not have monotonically increasing values.
- [ ] Create a secondary index using the following Data Definition Language (DDL):

![DDL](images/ddl.png)

**[⬆ Back to Top](#table-of-contents)**

### Your finance team wants to view the billing report for your projects. You want to make sure that the finance team does not get additional permissions to the project. What should you do?

- [ ] Add the group for the finance team to roles/billing user role.
- [ ] Add the group for the finance team to roles/billing admin role.
- [x] Add the group for the finance team to roles/billing viewer role.
- [ ] Add the group for the finance team to roles/billing project/Manager role.

**[⬆ Back to Top](#table-of-contents)**

### Your organization has strict requirements to control access to Google Cloud projects. You need to enable your Site Reliability Engineers (SREs) to approve requests from the Google Cloud support team when an SRE opens a support case. You want to follow Google-recommended practices. What should you do?

- [ ] Add your SREs to roles/iam.roleAdmin role.
- [ ] Add your SREs to roles/accessapproval.approver role.
- [ ] Add your SREs to a group and then add this group to roles/iam.roleAdmin.role.
- [x] Add your SREs to a group and then add this group to roles/accessapproval.approver role.

**[⬆ Back to Top](#table-of-contents)**

### You need to host an application on a Compute Engine instance in a project shared with other teams. You want to prevent the other teams from accidentally causing downtime on that application. Which feature should you use?

- [ ] Use a Shielded VM.
- [ ] Use a Preemptible VM.
- [ ] Use a sole-tenant node.
- [x] Enable deletion protection on the instance.

**[⬆ Back to Top](#table-of-contents)**

### Your organization needs to grant users access to query datasets in BigQuery but prevent them from accidentally deleting the datasets. You want a solution that follows Google-recommended practices. What should you do?

- [ ] Add users to roles/bigquery user role only, instead of roles/bigquery dataOwner.
- [ ] Add users to roles/bigquery dataEditor role only, instead of roles/bigquery dataOwner.
- [ ] Create a custom role by removing delete permissions, and add users to that role only.
- [x] Create a custom role by removing delete permissions. Add users to the group, and then add the group to the custom role.

**[⬆ Back to Top](#table-of-contents)**

### You have a developer laptop with the Cloud SDK installed on Ubuntu. The Cloud SDK was installed from the Google Cloud Ubuntu package repository. You want to test your application locally on your laptop with Cloud Datastore. What should you do?

- [ ] Export Cloud Datastore data using gcloud datastore export.
- [ ] Create a Cloud Datastore index using gcloud datastore indexes create.
- [x] Install the google-cloud-sdk-datastore-emulator component using the apt get install command.
- [ ] Install the cloud-datastore-emulator component using the gcloud components install command.

**[⬆ Back to Top](#table-of-contents)**

### Your company set up a complex organizational structure on Google Cloud. The structure includes hundreds of folders and projects. Only a few team members should be able to view the hierarchical structure. You need to assign minimum permissions to these team members, and you want to follow Google-recommended practices. What should you do?

- [ ] Add the users to roles/browser role.
- [ ] Add the users to roles/iam.roleViewer role.
- [x] Add the users to a group, and add this group to roles/browser.
- [ ] Add the users to a group, and add this group to roles/iam.roleViewer role.

**[⬆ Back to Top](#table-of-contents)**

### Your company has a single sign-on (SSO) identity provider that supports Security Assertion Markup Language (SAML) integration with service providers. Your company has users in Cloud Identity. You would like users to authenticate using your company's SSO provider. What should you do?

- [ ] In Cloud Identity, set up SSO with Google as an identity provider to access custom SAML apps.
- [x] In Cloud Identity, set up SSO with a third-party identity provider with Google as a service provider.
- [ ] Obtain OAuth 2.0 credentials, configure the user consent screen, and set up OAuth 2.0 for Mobile &amp; Desktop Apps.
- [ ] Obtain OAuth 2.0 credentials, configure the user consent screen, and set up OAuth 2.0 for Web Server Applications.

**[⬆ Back to Top](#table-of-contents)**

### Your organization has a dedicated person who creates and manages all service accounts for Google Cloud projects. You need to assign this person the minimum role for projects. What should you do?

- [ ] Add the user to roles/iam.roleAdmin role.
- [ ] Add the user to roles/iam.securityAdmin role.
- [ ] Add the user to roles/iam.serviceAccountUser role.
- [x] Add the user to roles/iam.serviceAccountAdmin role.

**[⬆ Back to Top](#table-of-contents)**

### You are building an archival solution for your data warehouse and have selected Cloud Storage to archive your data. Your users need to be able to access this archived data once a quarter for some regulatory requirements. You want to select a cost-efficient option. Which storage option should you use?

- [ ] Cold Storage.
- [x] Nearline Storage.
- [ ] Regional Storage.
- [ ] Multi-Regional Storage.

**[⬆ Back to Top](#table-of-contents)**

### A team of data scientists infrequently needs to use a Google Kubernetes Engine (GKE) cluster that you manage. They require GPUs for some long-running, nonrestartable jobs. You want to minimize cost. What should you do?

- [ ] Enable node auto-provisioning on the GKE cluster.
- [ ] Create a VerticalPodAutscaler for those workloads.
- [ ] Create a node pool with preemptible VMs and GPUs attached to those VMs.
- [x] Create a node pool of instances with GPUs, and enable autoscaling on this node pool with a minimum size of 1.

**[⬆ Back to Top](#table-of-contents)**

### Your organization has user identities in Active Directory. Your organization wants to use Active Directory as their source of truth for identities. Your organization wants to have full control over the Google accounts used by employees for all Google services, including your Google Cloud Platform (GCP) organization. What should you do?

- [x] Use Google Cloud Directory Sync (GCDS) to synchronize users into Cloud Identity.
- [ ] Use the cloud Identity APIs and write a script to synchronize users to Cloud Identity.
- [ ] Export users from Active Directory as a CSV and import them to Cloud Identity via the Admin Console.
- [ ] Ask each employee to create a Google account using self signup. Require that each employee use their company email address and password.

**[⬆ Back to Top](#table-of-contents)**

### You have successfully created a development environment in a project for an application. This application uses Compute Engine and Cloud SQL. Now you need to create a production environment for this application. The security team has forbidden the existence of network routes between these 2 environments and has asked you to follow Google-recommended practices. What should you do?

- [x] Create a new project, enable the Compute Engine and Cloud SQL APIs in that project, and replicate the setup you have created in the development environment.
- [ ] Create a new production subnet in the existing VPC and a new production Cloud SQL instance in your existing project, and deploy your application using those resources.
- [ ] Create a new project, modify your existing VPC to be a Shared VPC, share that VPC with your new project, and replicate the setup you have in the development environment in that new project in the Shared VP.
- [ ] Ask the security team to grant you the Project Editor role in an existing production project used by another division of your company. Once they grant you that role, replicate the setup you have in the development environment in that project.

**[⬆ Back to Top](#table-of-contents)**

### Your management has asked an external auditor to review all the resources in a specific project. The security team has enabled the Organization Policy called Domain Restricted Sharing on the organization node by specifying only your Cloud Identity domain. You want the auditor to only be able to view, but not modify, the resources in that project. What should you do?

- [ ] Ask the auditor for their Google account, and give them the Viewer role on the project.
- [ ] Ask the auditor for their Google account, and give them the Security Reviewer role on the project.
- [x] Create a temporary account for the auditor in Cloud Identity, and give that account the Viewer role on the project.
- [ ] Create a temporary account for the auditor in Cloud Identity, and give that account the Security Reviewer role on the project.

**[⬆ Back to Top](#table-of-contents)**

### You have a workload running on Compute Engine that is critical to your business. You want to ensure that the data on the boot disk of this workload is backed up regularly. You need to be able to restore a backup as quickly as possible in case of disaster. You also want older backups to be cleaned automatically to save on cost. You want to follow Google-recommended practices. What should you do?

- [ ] Create a Cloud Function to create an instance template.
- [x] Create a snapshot schedule for the disk using the desired interval.
- [ ] Create a cron job to create a new disk from the disk using gcloud.
- [ ] Create a Cloud Task to create an image and export it to Cloud Storage.

**[⬆ Back to Top](#table-of-contents)**

### You need to assign a Cloud Identity and Access Management (Cloud IAM) role to an external auditor. The auditor needs to have permissions to review your Google Cloud Platform (GCP) Audit Logs and also to review your Data Access logs. What should you do?

- [ ] Assign the auditor the IAM role roles/logging.privateLogViewer. Perform the export of logs to Cloud Storage.
- [x] Assign the auditor the IAM role roles/logging.privateLogViewer. Direct the auditor to also review the logs for changes to Cloud IAM policy.
- [ ] Assign the auditor's IAM user to a custom role that has logging.privateLogEntries.list permission. Perform the export of logs to Cloud Storage.
- [ ] Assign the auditor's IAM user to a custom role that has logging.privateLogEntries.list permission. Direct the auditor to also review the logs for changes to Cloud IAM policy.

**[⬆ Back to Top](#table-of-contents)**

### You are managing several Google Cloud Platform (GCP) projects and need access to all logs for the past 60 days. You want to be able to explore and quickly analyze the log contents. You want to follow Google-recommended practices to obtain the combined logs for all projects. What should you do?

- [ ] Navigate to Stackdriver Logging and select resource.labels.project_id="*".
- [x] Create a Stackdriver Logging Export with a Sink destination to a BigQuery dataset. Configure the table expiration to 60 days.
- [ ] Create a Stackdriver Logging Export with a Sink destination to Cloud Storage. Create a lifecycle rule to delete objects after 60 days.
- [ ] Configure a Cloud Scheduler job to read from Stackdriver and store the logs in BigQuery. Configure the table expiration to 60 days.

**[⬆ Back to Top](#table-of-contents)**

### You need to reduce GCP service costs for a division of your company using the fewest possible steps. You need to turn off all configured services in an existing GCP project. What should you do?

- [x] 1. Verify that you are assigned the Project Owners IAM role for this project. 2. Locate the project in the GCP console, click Shut down and then enter the project I.
- [ ] 1. Verify that you are assigned the Project Owners IAM role for this project. 2. Switch to the project in the GCP console, locate the resources and delete them.
- [ ] 1. Verify that you are assigned the Organizational Administrator IAM role for this project. 2. Locate the project in the GCP console, enter the project ID and then click Shut down.
- [ ] 1. Verify that you are assigned the Organizational Administrators IAM role for this project. 2. Switch to the project in the GCP console, locate the resources and delete them.

**[⬆ Back to Top](#table-of-contents)**

### You are configuring service accounts for an application that spans multiple projects. Virtual Machines (VMs) running in the web-applications project need access to BigQuery datasets in crm-databases-proj. You want to follow Google-recommended practices to give access to the service account in the web-applications project. What should you do?

- [ ] Give project owner for web-applications appropriate roles to crm-databases-proj.
- [ ] Give project owner role to crm-databases-proj and the web-applications project.
- [ ] Give project owner role to crm-databases-proj and bigquery.dataViewer role to web-applications.
- [x] Give bigquery.dataViewer role to crm-databases-proj and appropriate roles to web-applications.

**[⬆ Back to Top](#table-of-contents)**

### An employee was terminated, but their access to Google Cloud Platform (GCP) was not removed until 2 weeks later. You need to find out this employee accessed any sensitive customer information after their termination. What should you do?

- [ ] View System Event Logs in Stackdriver. Search for the user's email as the principal.
- [ ] View System Event Logs in Stackdriver. Search for the service account associated with the user.
- [x] View Data Access audit logs in Stackdriver. Search for the user's email as the principal.
- [ ] View the Admin Activity log in Stackdriver. Search for the service account associated with the user.

**[⬆ Back to Top](#table-of-contents)**

### You need to create a custom IAM role for use with a GCP service. All permissions in the role must be suitable for production use. You also want to clearly share with your organization the status of the custom role. This will be the first version of the custom role. What should you do?

- [x] Use permissions in your role that use the 'supported' support level for role permissions. Set the role stage to ALPHA while testing the role permissions.
- [ ] Use permissions in your role that use the 'supported' support level for role permissions. Set the role stage to BETA while testing the role permissions.
- [ ] Use permissions in your role that use the 'testing' support level for role permissions. Set the role stage to ALPHA while testing the role permissions.
- [ ] Use permissions in your role that use the 'testing' support level for role permissions. Set the role stage to BETA while testing the role permissions.

**[⬆ Back to Top](#table-of-contents)**

### Your company has a large quantity of unstructured data in different file formats. You want to perform ETL transformations on the data. You need to make the data accessible on Google Cloud so it can be processed by a Dataflow job. What should you do?

- [ ] Upload the data to BigQuery using the bq command line tool.
- [x] Upload the data to Cloud Storage using the gsutil command line tool.
- [ ] Upload the data into Cloud SQL using the import function in the console.
- [ ] Upload the data into Cloud Spanner using the import function in the console.

**[⬆ Back to Top](#table-of-contents)**

### You need to manage multiple Google Cloud projects in the fewest steps possible. You want to configure the Google Cloud SDK command line interface (CLI) so that you can easily manage multiple projects. What should you do?

- [x] 1. Create a configuration for each project you need to manage. 2. Activate the appropriate configuration when you work with each of your assigned Google Cloud projects.
- [ ] 1. Create a configuration for each project you need to manage. 2. Use gcloud init to update the configuration values when you need to work with a non-default project.
- [ ] 1. Use the default configuration for one project you need to manage. 2. Activate the appropriate configuration when you work with each of your assigned Google Cloud projects.
- [ ] 1. Use the default configuration for one project you need to manage. 2. Use gcloud init to update the configuration values when you need to work with a non-default project.

**[⬆ Back to Top](#table-of-contents)**

### Your Managed Instance Group raised an alert stating that new instance creation has failed to create new instances. You need to maintain the number of running instances specified by the template to be able to process expected application traffic. What should you do?

- [x] Create an instance template that contains valid syntax which will be used by the instance group. Delete any persistent disks with the same name as instance names.
- [ ] Create an instance template that contains valid syntax that will be used by the instance group. Verify that the instance name and persistent disk name values are not the same in the template.
- [ ] Verify that the instance template being used by the instance group contains valid syntax. Delete any persistent disks with the same name as instance names. Set the disks.autoDelete property to true in the instance template.
- [ ] Delete the current instance template and replace it with a new instance template. Verify that the instance name and persistent disk name values are not the same in the template. Set the disks.autoDelete property to true in the instance template.

**[⬆ Back to Top](#table-of-contents)**

### Your company is moving from an on-premises environment to Google Cloud. You have multiple development teams that use Cassandra environments as backend databases. They all need a development environment that is isolated from other Cassandra instances. You want to move to Google Cloud quickly and with minimal support effort. What should you do?

- [ ] 1. Build an instruction guide to install Cassandra on Google Cloud. 2. Make the instruction guide accessible to your developers.
- [x] 1. Advise your developers to go to Cloud Marketplace. 2. Ask the developers to launch a Cassandra image for their development work.
- [ ] 1. Build a Cassandra Compute Engine instance and take a snapshot of it. 2. Use the snapshot to create instances for your developers.
- [ ] 1. Build a Cassandra Compute Engine instance and take a snapshot of it. 2. Upload the snapshot to Cloud Storage and make it accessible to your developers. 3. Build instructions to create a Compute Engine instance from the snapshot so that developers can do it themselves.

**[⬆ Back to Top](#table-of-contents)**

### You have a Compute Engine instance hosting a production application. You want to receive an email if the instance consumes more than 90% of its CPU resources for more than 15 minutes. You want to use Google services. What should you do?

- [ ] 1. Create a consumer Gmail account. 2. Write a script that monitors the CPU usage. 3. When the CPU usage exceeds the threshold, have that script send an email using the Gmail account and smtp.gmail.com on port 25 as SMTP server.
- [x] 1. Create a Stackdriver Workspace, and associate your Google Cloud Platform (GCP) project with it. 2. Create an Alerting Policy in Stackdriver that uses the threshold as a trigger condition. 3. Configure your email address in the notification channel.
- [ ] 1. Create a Stackdriver Workspace, and associate your GCP project with it. 2. Write a script that monitors the CPU usage and sends it as a custom metric to Stackdriver. 3. Create an uptime check for the instance in Stackdriver.
- [ ] 1. In Stackdriver Logging, create a logs-based metric to extract the CPU usage by using this regular expression: CPU Usage: ([0-9] {1,3})% 2. In Stackdriver Monitoring, create an Alerting Policy based on this metric. 3. Configure your email address in the notification channel.

**[⬆ Back to Top](#table-of-contents)**

### You have an application that uses Cloud Spanner as a backend database. The application has a very predictable traffic pattern. You want to automatically scale up or down the number of Spanner nodes depending on traffic. What should you do?

- [ ] Create a cron job that runs on a scheduled basis to review Cloud Monitoring metrics, and then resize the Spanner instance accordingly.
- [ ] Create a Cloud Monitoring alerting policy to send an alert to oncall SRE emails when Cloud Spanner CPU exceeds the threshold. SREs would scale resources up or down accordingly.
- [ ] Create a Cloud Monitoring alerting policy to send an alert to Google Cloud Support email when Cloud Spanner CPU exceeds your threshold. Google support would scale resources up or down accordingly.
- [x] Create a Cloud Monitoring alerting policy to send an alert to webhook when Cloud Spanner CPU is over or under your threshold. Create a Cloud Function that listens to HTTP and resizes Spanner resources accordingly.

**[⬆ Back to Top](#table-of-contents)**

### Your company publishes large files on an Apache web server that runs on a Compute Engine instance. The Apache web server is not the only application running in the project. You want to receive an email when the egress network costs for the server exceed 100 dollars for the current month as measured by Google Cloud. What should you do?

- [ ] Set up a budget alert on the project with an amount of 100 dollars, a threshold of 100%, and notification type of email.
- [ ] Set up a budget alert on the billing account with an amount of 100 dollars, a threshold of 100%, and notification type of email.
- [x] Export the billing data to BigQuery. Create a Cloud Function that uses BigQuery to sum the egress network costs of the exported billing data for the Apache web server for the current month and sends an email if it is over 100 dollars. Schedule the Cloud Function using Cloud Scheduler to run hourly.
- [ ] Use the Cloud Logging Agent to export the Apache web server logs to Cloud Logging. Create a Cloud Function that uses BigQuery to parse the HTTP response log data in Cloud Logging for the current month and sends an email if the size of all HTTP responses, multiplied by current Google Cloud egress prices, totals over 100 dollars. Schedule the Cloud Function using Cloud Scheduler to run hourly.

**[⬆ Back to Top](#table-of-contents)**

### You have designed a solution on Google Cloud that uses multiple Google Cloud products. Your company has asked you to estimate the costs of the solution. You need to provide estimates for the monthly total cost. What should you do?

- [x] For each Google Cloud product in the solution, review the pricing details on the products pricing page. Use the pricing calculator to total the monthly costs for each Google Cloud product.
- [ ] For each Google Cloud product in the solution, review the pricing details on the products pricing page. Create a Google Sheet that summarizes the expected monthly costs for each product.
- [ ] Provision the solution on Google Cloud. Leave the solution provisioned for 1 week. Navigate to the Billing Report page in the Cloud Console. Multiply the 1 week cost to determine the monthly costs.
- [ ] Provision the solution on Google Cloud. Leave the solution provisioned for 1 week. Use Cloud Monitoring to determine the provisioned and used resource amounts. Multiply the 1 week cost to determine the monthly costs.

**[⬆ Back to Top](#table-of-contents)**

### You have an application that receives SSL-encrypted TCP traffic on port 443. Clients for this application are located all over the world. You want to minimize latency for the clients. Which load balancing option should you use?

- [ ] HTTPS Load Balancer.
- [ ] Network Load Balancer.
- [x] SSL Proxy Load Balancer.
- [ ] Internal TCP/UDP Load Balancer. Add a firewall rule allowing ingress traffic from 0.0.0.0/0 on the target instances.

**[⬆ Back to Top](#table-of-contents)**

### You have an application on a general-purpose Compute Engine instance that is experiencing excessive disk read throttling on its Zonal SSD Persistent Disk. The application primarily reads large files from disk. The disk size is currently 350 GB. You want to provide the maximum amount of throughput while minimizing costs. What should you do?

- [ ] Increase the size of the disk to 1 TB.
- [ ] Increase the allocated CPU to the instance.
- [x] Migrate to use a Local SSD on the instance.
- [ ] Migrate to use a Regional SSD on the instance.

**[⬆ Back to Top](#table-of-contents)**

### Your Dataproc cluster runs in a single Virtual Private Cloud (VPC) network in a single subnet with range 172.16.20.128/25. There are no private IP addresses available in the VPC network. You want to add new VMs to communicate with your cluster using the minimum number of steps. What should you do?

- [x] Modify the existing subnet range to 172.16.20.0/24.
- [ ] Create a new Secondary IP Range in the VPC and configure the VMs to use that range.
- [ ] Create a new VPC network for the VMs. Enable VPC Peering between the VMs' VPC network and the Dataproc cluster VPC network.
- [ ] Create a new VPC network for the VMs with a subnet of 172.32.0.0/16. Enable VPC network Peering between the Dataproc VPC network and the VMs VPC network. Configure a custom Route exchange.

**[⬆ Back to Top](#table-of-contents)**

### You manage an App Engine Service that aggregates and visualizes data from BigQuery. The application is deployed with the default App Engine Service account. The data that needs to be visualized resides in a different project managed by another team. You do not have access to this project, but you want your application to be able to read data from the BigQuery dataset. What should you do?

- [ ] Ask the other team to grant your default App Engine Service account the role of BigQuery Job User.
- [x] Ask the other team to grant your default App Engine Service account the role of BigQuery Data Viewer.
- [ ] In Cloud IAM of your project, ensure that the default App Engine service account has the role of BigQuery Data Viewer.
- [ ] In Cloud IAM of your project, grant a newly created service account from the other team the role of BigQuery Job User in your project.

**[⬆ Back to Top](#table-of-contents)**

### You need to create a copy of a custom Compute Engine Virtual Machine (VM) to facilitate an expected increase in application traffic due to a business acquisition. What should you do?

- [ ] Create a Compute Engine snapshot of your base VM. Create your images from that snapshot.
- [ ] Create a Compute Engine snapshot of your base VM. Create your instances from that snapshot.
- [ ] Create a custom Compute Engine image from a snapshot. Create your images from that image.
- [x] Create a custom Compute Engine image from a snapshot. Create your instances from that image.

**[⬆ Back to Top](#table-of-contents)**

### You have deployed an application on a single Compute Engine instance. The application writes logs to disk. Users start reporting errors with the application. You want to diagnose the problem. What should you do?

- [ ] Navigate to Cloud Logging and view the application logs.
- [ ] Connect to the instance's serial console and read the application logs.
- [ ] Configure a Health Check on the instance and set a Low Healthy Threshold value.
- [x] Install and configure the Cloud Logging Agent and view the logs from Cloud Logging.

**[⬆ Back to Top](#table-of-contents)**

### An application generates daily reports in a Compute Engine Virtual Machine (VM). The VM is in the project corp-iot-insights. Your team operates only in the project corp-aggregate-reports and needs a copy of the daily exports in the bucket corp-aggregate-reports-storage. You want to configure access so that the daily reports from the VM are available in the bucket corp-aggregate-reports-storage and use as few steps as possible while following Google-recommended practices. What should you do?

- [ ] Move both projects under the same folder.
- [x] Grant the VM Service Account the role Storage Object Creator on corp-aggregate-reports-storage.
- [ ] Create a Shared VPC network between both projects. Grant the VM Service Account the role Storage Object Creator on corp-iot-insights.
- [ ] Make corp-aggregate-reports-storage public and create a folder with a pseudo-randomized suffix name. Share the folder with the IoT team.

**[⬆ Back to Top](#table-of-contents)**

### You built an application on your development laptop that uses Google Cloud services. Your application uses Application Default Credentials for authentication and works fine on your development laptop. You want to migrate this application to a Compute Engine Virtual Machine (VM) and set up authentication using Google-recommended practices and minimal changes. What should you do?

- [x] Assign appropriate access for Google services to the service account used by the Compute Engine VM.
- [ ] Create a service account with appropriate access for Google services, and configure the application to use this account.
- [ ] Store credentials for service accounts with appropriate access for Google services in a config file, and deploy this config file with your application.
- [ ] Store credentials for your user account with appropriate access for Google services in a config file, and deploy this config file with your application.

**[⬆ Back to Top](#table-of-contents)**

### You need to create a Compute Engine instance in a new project that doesn't exist yet. What should you do?

- [x] Using the Cloud SDK, create a new project, enable the Compute Engine API in that project, and then create the instance specifying your new project.
- [ ] Enable the Compute Engine API in the Cloud Console, use the Cloud SDK to create the instance, and then use the --project flag to specify a new project.
- [ ] Using the Cloud SDK, create the new instance, and use the --project flag to specify the new project. Answer yes when prompted by Cloud SDK to enable the Compute Engine API.
- [ ] Enable the Compute Engine API in the Cloud Console. Go to the Compute Engine section of the Console to create a new instance, and look for the Create In A New Project option in the creation form.

**[⬆ Back to Top](#table-of-contents)**

### Your company runs one batch process in an on-premises server that takes around 30 hours to complete. The task runs monthly, can be performed offline, and must be restarted if interrupted. You want to migrate this workload to the cloud while minimizing cost. What should you do?

- [ ] Migrate the workload to a Compute Engine Preemptible VM.
- [ ] Migrate the workload to a Google Kubernetes Engine cluster with Preemptible nodes.
- [x] Migrate the workload to a Compute Engine VM. Start and stop the instance as needed.
- [ ] Create an Instance Template with Preemptible VMs On. Create a Managed Instance Group from the template and adjust Target CPU Utilization. Migrate the workload.

**[⬆ Back to Top](#table-of-contents)**

### You are developing a new application and are looking for a Jenkins installation to build and deploy your source code. You want to automate the installation as quickly and easily as possible. What should you do?

- [x] Deploy Jenkins through the Google Cloud Marketplace.
- [ ] Create a new Compute Engine instance. Run the Jenkins executable.
- [ ] Create a new Kubernetes Engine cluster. Create a deployment for the Jenkins image.
- [ ] Create an instance template with the Jenkins executable. Create a Managed Instance Group with this template.

**[⬆ Back to Top](#table-of-contents)**

### You have downloaded and installed the gcloud command line interface (CLI) and have authenticated with your Google Account. Most of your Compute Engine instances in your project run in the europe-west1-d zone. You want to avoid having to specify this zone with each CLI command when managing these instances. What should you do?

- [x] Set the europe-west1-d zone as the default zone using the gcloud config subcommand.
- [ ] In the Settings page for Compute Engine under Default location, set the zone to europe-west1-d.
- [ ] In the CLI installation directory, create a file called default.conf containing zone=europe-west1-d.
- [ ] Create a Metadata entry on the Compute Engine page with key compute/zone and value europe-west1-d.

**[⬆ Back to Top](#table-of-contents)**

### The core business of your company is to rent out construction equipment at large scale. All the equipment that is being rented out has been equipped with multiple sensors that send event information every few seconds. These signals can vary from engine status, distance traveled, fuel level, and more. Customers are billed based on the consumption monitored by these sensors. You expect high throughput - up to thousands of events per hour per device - and need to retrieve consistent data based on the time of the event. Storing and retrieving individual signals should be atomic. What should you do?

- [ ] Create a file in Cloud Storage per device and append new data to that file.
- [ ] Create a file in Cloud Filestore per device and append new data to that file.
- [ ] Ingest the data into Datastore. Store data in an entity group based on the device.
- [x] Ingest the data into Cloud Bigtable. Create a row key based on the event timestamp.

**[⬆ Back to Top](#table-of-contents)**

### You are asked to set up application performance monitoring on Google Cloud projects A, B, and C as a single pane of glass. You want to monitor CPU, memory, and disk. What should you do?

- [ ] Enable API and then share charts from project A, B, and C.
- [ ] Enable API and then give the metrics.reader role to projects A, B, and C.
- [ ] Enable API and then use default dashboards to view all projects in sequence.
- [x] Enable API, create a workspace under project A, and then add projects B and C.

**[⬆ Back to Top](#table-of-contents)**

### You created several resources in multiple Google Cloud projects. All projects are linked to different billing accounts. To better estimate future charges, you want to have a single visual representation of all costs incurred. You want to include new cost data as soon as possible. What should you do?

- [x] Configure Billing Data Export to BigQuery and visualize the data in Data Studio.
- [ ] Visit the Cost Table page to get a CSV export and visualize it using Data Studio.
- [ ] Fill all resources in the Pricing Calculator to get an estimate of the monthly cost.
- [ ] Use the Reports view in the Cloud Billing Console to view the desired cost information.

**[⬆ Back to Top](#table-of-contents)**

### Your company has workloads running on Compute Engine and on-premises. The Google Cloud Virtual Private Cloud (VPC) is connected to your WAN over a Virtual Private Network (VPN). You need to deploy a new Compute Engine instance and ensure that no public Internet traffic can be routed to it. What should you do?

- [x] Create the instance without a public IP address.
- [ ] Create the instance with Private Google Access enabled.
- [ ] Create a deny-all egress firewall rule on the VPC network.
- [ ] Create a route on the VPC to route all traffic to the instance over the VPN tunnel.

**[⬆ Back to Top](#table-of-contents)**

### Your team maintains the infrastructure for your organization. The current infrastructure requires changes. You need to share your proposed changes with the rest of the team. You want to follow Google's recommended best practices. What should you do?

- [ ] Use Deployment Manager templates to describe the proposed changes and store them in a Cloud Storage bucket.
- [x] Use Deployment Manager templates to describe the proposed changes and store them in Cloud Source Repositories.
- [ ] Apply the changes in a development environment, run gcloud compute instances list, and then save the output in a shared Storage bucket.
- [ ] Apply the changes in a development environment, run gcloud compute instances list, and then save the output in Cloud Source Repositories.

**[⬆ Back to Top](#table-of-contents)**

### You have a Compute Engine instance hosting an application used between 9 AM and 6 PM on weekdays. You want to back up this instance daily for disaster recovery purposes. You want to keep the backups for 30 days. You want the Google-recommended solution with the least management overhead and the least number of services. What should you do?

- [ ] 1. Update your instances' metadata to add the following value: snapshot-schedule: 0 1 * * * 2. Update your instances' metadata to add the following value: snapshot-retention: 30.
- [x] 1. In the Cloud Console, go to the Compute Engine Disks page and select your instance's disk. 2. In the Snapshot Schedule section, select Create Schedule and configure the following parameters: Schedule frequency: Daily. Start time: 1:00 AM - 2:00 AM. Autodelete snapshots after: 30 days.
- [ ] 1. Create a Cloud Function that creates a snapshot of your instance's disk. 2. Create a Cloud Function that deletes snapshots that are older than 30 days. 3. Use Cloud Scheduler to trigger both Cloud Functions daily at 1:00 AM.
- [ ] 1. Create a bash script in the instance that copies the content of the disk to Cloud Storage. 2. Create a bash script in the instance that deletes data older than 30 days in the backup Cloud Storage bucket. 3. Configure the instance's crontab to execute these scripts daily at 1:00 AM.

**[⬆ Back to Top](#table-of-contents)**

### Your existing application running in Google Kubernetes Engine (GKE) consists of multiple pods running on four GKE n1-standard-2 nodes. You need to deploy additional pods requiring n2-highmem-16 nodes without any downtime. What should you do?

- [ ] Use gcloud container clusters upgrade. Deploy the new services.
- [x] Create a new Node Pool and specify machine type n2-highmem-16. Deploy the new pods.
- [ ] Create a new cluster with n2-highmem-16 nodes. Redeploy the pods and delete the old cluster.
- [ ] Create a new cluster with both n1-standard-2 and n2-highmem-16 nodes. Redeploy the pods and delete the old cluster.

**[⬆ Back to Top](#table-of-contents)**

### You have an application that uses Cloud Spanner as a database backend to keep current state information about users. Cloud Bigtable logs all events triggered by users. You export Cloud Spanner data to Cloud Storage during daily backups. One of your analysts asks you to join data from Cloud Spanner and Cloud Bigtable for specific users. You want to complete this ad hoc request as efficiently as possible. What should you do?

- [ ] Create a dataflow job that copies data from Cloud Bigtable and Cloud Storage for specific users.
- [ ] Create a dataflow job that copies data from Cloud Bigtable and Cloud Spanner for specific users.
- [ ] Create a Cloud Dataproc cluster that runs a Spark job to extract data from Cloud Bigtable and Cloud Storage for specific users.
- [x] Create two separate BigQuery external tables on Cloud Storage and Cloud Bigtable. Use the BigQuery console to join these tables through user fields, and apply appropriate filters.

**[⬆ Back to Top](#table-of-contents)**

### You are hosting an application from Compute Engine Virtual Machines (VMs) in us-central1-a. You want to adjust your design to support the failure of a single Compute Engine zone, eliminate downtime, and minimize cost. What should you do?

- [x] Create Compute Engine resources in us-central1-b. Balance the load across both us-central1-a and us-central1-b.
- [ ] Create a Managed Instance Group and specify us-central1-a as the zone. Configure the Health Check with a short Health Interval.
- [ ] Create an HTTP(S) Load Balancer. Create one or more global forwarding rules to direct traffic to your VMs.
- [ ] Perform regular backups of your application. Create a Cloud Monitoring Alert and be notified if your application becomes unavailable. Restore from backups when notified.

**[⬆ Back to Top](#table-of-contents)**

### A colleague handed over a Google Cloud Platform project for you to maintain. As part of a security checkup, you want to review who has been granted the Project Owner role. What should you do?

- [ ] In the console, validate which SSH keys have been stored as project-wide keys.
- [ ] Navigate to Identity-Aware Proxy and check the permissions for these resources.
- [ ] Enable Audit Logs on the IAM &amp; admin page for all resources, and validate the results.
- [x] Use the command gcloud projects get-iam-policy to view the current role assignments.

**[⬆ Back to Top](#table-of-contents)**

### You are running multiple VPC-native Google Kubernetes Engine clusters in the same subnet. The IPs available for the nodes are exhausted, and you want to ensure that the clusters can grow in nodes when needed. What should you do?

- [ ] Create a new subnet in the same region as the subnet being used.
- [ ] Add an alias IP range to the subnet used by the GKE clusters.
- [ ] Create a new VPC, and set up VPC peering with the existing VP.
- [x] Expand the CIDR range of the relevant subnet for the cluster.

**[⬆ Back to Top](#table-of-contents)**

### You have a batch workload that runs every night and uses a large number of Virtual Machines (VMs). It is fault-tolerant and can tolerate some of the VMs being terminated. The current cost of VMs is too high. What should you do?

- [x] Run a test using simulated maintenance events. If the test is successful, use preemptible N1 Standard VMs when running future jobs.
- [ ] Run a test using simulated maintenance events. If the test is successful, use N1 Standard VMs when running future jobs.
- [ ] Run a test using a Managed Instance Group. If the test is successful, use N1 Standard VMs in the Managed Instance Group when running future jobs.
- [ ] Run a test using N1 standard VMs instead of N2. If the test is successful, use N1 Standard VMs when running future jobs.

**[⬆ Back to Top](#table-of-contents)**

### You are working with a user to set up an application in a new VPC behind a firewall. The user is concerned about data egress. You want to configure the fewest open egress ports. What should you do?

- [x] Set up a low-priority (65534) rule that blocks all egress and a high-priority rule (1000) that allows only the appropriate ports.
- [ ] Set up a high-priority (1000) rule that pairs both ingress and egress ports.
- [ ] Set up a high-priority (1000) rule that blocks all egress and a low-priority (65534) rule that allows only the appropriate ports.
- [ ] Set up a high-priority (1000) rule to allow the appropriate ports.

**[⬆ Back to Top](#table-of-contents)**

### Your company runs its Linux workloads on Compute Engine instances. Your company will be working with a new operations partner that does not use Google Accounts. You need to grant access to the instances to your operations partner so they can maintain the installed tooling. What should you do?

- [x] Enable Cloud IAP for the Compute Engine instances, and add the operations partner as a Cloud IAP Tunnel User.
- [ ] Tag all the instances with the same network tag. Create a firewall rule in the VPC to grant TCP access on port 22 for traffic from the operations partner to instances with the network tag.
- [ ] Set up Cloud VPN between your Google Cloud VPC and the internal network of the operations partner.
- [ ] Ask the operations partner to generate SSH key pairs, and add the public keys to the VM instances.

**[⬆ Back to Top](#table-of-contents)**

### You have created a code snippet that should be triggered whenever a new file is uploaded to a Cloud Storage bucket. You want to deploy this code snippet. What should you do?

- [ ] Use App Engine and configure Cloud Scheduler to trigger the application using Pub/Sub.
- [x] Use Cloud Functions and configure the bucket as a trigger resource.
- [ ] Use Google Kubernetes Engine and configure a CronJob to trigger the application using Pub/Sub.
- [ ] Use Dataflow as a batch job, and configure the bucket as a data source.

**[⬆ Back to Top](#table-of-contents)**

### You have been asked to set up Object Lifecycle Management for objects stored in storage buckets. The objects are written once and accessed frequently for 30 days. After 30 days, the objects are not read again unless there is a special need. The objects should be kept for three years, and you need to minimize cost. What should you do?

- [ ] Set up a policy that uses Nearline storage for 30 days and then moves to Archive storage for three years.
- [x] Set up a policy that uses Standard storage for 30 days and then moves to Archive storage for three years.
- [ ] Set up a policy that uses Nearline storage for 30 days, then moves the Coldline for one year, and then moves to Archive storage for two years.
- [ ] Set up a policy that uses Standard storage for 30 days, then moves to Coldline for one year, and then moves to Archive storage for two years.

**[⬆ Back to Top](#table-of-contents)**

### You are storing sensitive information in a Cloud Storage bucket. For legal reasons, you need to be able to record all requests that read any of the stored data. You want to make sure you comply with these requirements. What should you do?

- [ ] Enable the Identity Aware Proxy API on the project.
- [ ] Scan the bucket using the Data Loss Prevention API.
- [ ] Allow only a single Service Account access to read the data.
- [x] Enable Data Access audit logs for the Cloud Storage API.

**[⬆ Back to Top](#table-of-contents)**

### You are the team lead of a group of 10 developers. You provided each developer with an individual Google Cloud Project that they can use as their personal sandbox to experiment with different Google Cloud solutions. You want to be notified if any of the developers are spending above $500 per month on their sandbox environment. What should you do?

- [ ] Create a single budget for all projects and configure budget alerts on this budget.
- [ ] Create a separate billing account per sandbox project and enable BigQuery billing exports. Create a Data Studio dashboard to plot the spending per billing account.
- [x] Create a budget per project and configure budget alerts on all of these budgets.
- [ ] Create a single billing account for all sandbox projects and enable BigQuery billing exports. Create a Data Studio dashboard to plot the spending per project.

**[⬆ Back to Top](#table-of-contents)**

### You are deploying a production application on Compute Engine. You want to prevent anyone from accidentally destroying the instance by clicking the wrong button. What should you do?

- [ ] Disable the flag Delete boot disk when instance is deleted.
- [x] Enable delete protection on the instance.
- [ ] Disable Automatic restart on the instance.
- [ ] Enable Preemptibility on the instance.

**[⬆ Back to Top](#table-of-contents)**

### Your company uses a large number of Google Cloud services centralized in a single project. All teams have specific projects for testing and development. The DevOps team needs access to all of the production services in order to perform their job. You want to prevent Google Cloud product changes from broadening their permissions in the future. You want to follow Google-recommended practices. What should you do?

- [ ] Grant all members of the DevOps team the role of Project Editor on the organization level.
- [ ] Grant all members of the DevOps team the role of Project Editor on the production project.
- [x] Create a custom role that combines the required permissions. Grant the DevOps team the custom role on the production project.
- [ ] Create a custom role that combines the required permissions. Grant the DevOps team the custom role on the organization level.

**[⬆ Back to Top](#table-of-contents)**

### You are building an application that processes data files uploaded from thousands of suppliers. Your primary goals for the application are data security and the expiration of aged data. You need to design the application to: Restrict access so that suppliers can access only their own data. Give suppliers write access to data only for 30 minutes. Delete data that is over 45 days old. You have a very short development cycle, and you need to make sure that the application requires minimal maintenance. Which two strategies should you use? (Choose two.)

- [x] Build a lifecycle policy to delete Cloud Storage objects after 45 days.
- [x] Use signed URLs to allow suppliers limited time access to store their objects.
- [ ] Set up an SFTP server for your application, and create a separate user for each supplier.
- [ ] Build a Cloud function that triggers a timer of 45 days to delete objects that have expired.
- [ ] Develop a script that loops through all Cloud Storage buckets and deletes any buckets that are older than 45 days.

**[⬆ Back to Top](#table-of-contents)**

### Your company wants to standardize the creation and management of multiple Google Cloud resources using Infrastructure as Code. You want to minimize the amount of repetitive code needed to manage the environment. What should you do?

- [x] Develop templates for the environment using Cloud Deployment Manager.
- [ ] Use curl in a terminal to send a REST request to the relevant Google API for each individual resource.
- [ ] Use the Cloud Console interface to provision and manage all related resources.
- [ ] Create a bash script that contains all requirement steps as gcloud commands.

**[⬆ Back to Top](#table-of-contents)**

### You are performing a monthly security check of your Google Cloud environment and want to know who has access to view data stored in your Google Cloud Project. What should you?

- [ ] Enable Audit Logs for all APIs that are related to data storage.
- [x] Review the IAM permissions for any role that allows for data access.
- [ ] Review the Identity-Aware Proxy settings for each resource.
- [ ] Create a Data Loss Prevention job.

**[⬆ Back to Top](#table-of-contents)**

### Your company has embraced a hybrid cloud strategy where some of the applications are deployed on Google Cloud. A Virtual Private Network (VPN) tunnel connects your Virtual Private Cloud (VPC) in Google Cloud with your company's on-premises network. Multiple applications in Google Cloud need to connect to an on-premises database server, and you want to avoid having to change the IP configuration in all of your applications when the IP of the database changes. What should you do?

- [ ] Configure Cloud NAT for all subnets of your VPC to be used when egressing from the VM instances.
- [x] Create a private zone on Cloud DNS, and configure the applications with the DNS name.
- [ ] Configure the IP of the database as custom metadata for each instance, and query the metadata server.
- [ ] Query the Compute Engine internal DNS from the applications to retrieve the IP of the database.

**[⬆ Back to Top](#table-of-contents)**

### You have developed a containerized web application that will serve internal colleagues during business hours. You want to ensure that no costs are incurred outside of the hours the application is used. You have just created a new Google Cloud project and want to deploy the application. What should you do?

- [ ] Deploy the container on Cloud Run for Anthos, and set the minimum number of instances to zero.
- [x] Deploy the container on Cloud Run (fully managed), and set the minimum number of instances to zero.
- [ ] Deploy the container on App Engine flexible environment with autoscaling, and set the value min_instances to zero in the app.yaml.
- [ ] Deploy the container on App Engine flexible environment with manual scaling, and set the value instances to zero in the app.yaml.

**[⬆ Back to Top](#table-of-contents)**

### You have experimented with Google Cloud using your own credit card and expensed the costs to your company. Your company wants to streamline the billing process and charge the costs of your projects to their monthly invoice. What should you do?

- [ ] Grant the financial team the IAM role of Billing Account User on the billing account linked to your credit card.
- [ ] Set up BigQuery billing export and grant your financial department IAM access to query the data.
- [ ] Create a ticket with Google Billing Support to ask them to send the invoice to your company.
- [x] Change the billing account of your projects to the billing account of your company.

**[⬆ Back to Top](#table-of-contents)**

### You are running a data warehouse on BigQuery. A partner company is offering a recommendation engine based on the data in your data warehouse. The partner company is also running their application on Google Cloud. They manage the resources in their own project, but they need access to the BigQuery dataset in your project. You want to provide the partner company with access to the dataset. What should you do?

- [ ] Create a Service Account in your own project, and grant this Service Account access to BigQuery in your project.
- [ ] Create a Service Account in your own project, and ask the partner to grant this Service Account access to BigQuery in their project.
- [ ] Ask the partner to create a Service Account in their project, and have them give the Service Account access to BigQuery in their project.
- [x] Ask the partner to create a Service Account in their project, and grant their Service Account access to the BigQuery dataset in your project.

**[⬆ Back to Top](#table-of-contents)**

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

**[⬆ Back to Top](#table-of-contents)**

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

**[⬆ Back to Top](#table-of-contents)**

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

**[⬆ Back to Top](#table-of-contents)**

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

**[⬆ Back to Top](#table-of-contents)**

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

**[⬆ Back to Top](#table-of-contents)**

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

**[⬆ Back to Top](#table-of-contents)**

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

**[⬆ Back to Top](#table-of-contents)**

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

**[⬆ Back to Top](#table-of-contents)**

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

**[⬆ Back to Top](#table-of-contents)**

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

**[⬆ Back to Top](#table-of-contents)**

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

**[⬆ Back to Top](#table-of-contents)**

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

**[⬆ Back to Top](#table-of-contents)**

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

**[⬆ Back to Top](#table-of-contents)**

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

**[⬆ Back to Top](#table-of-contents)**
