---
title: Use the Admin UI
seotitle: Use the Admin UI for InfluxDB Cloud Dedicated
description: >
  The Admin UI for {{% product-name %}} provides a no-code way to manage your {{% product-name %}} environment.
  Use the Admin UI to view your {{% product-name %}} account information and manage cluster resources, such as tokens and databases.
menu:
  influxdb3_cloud_dedicated:
    parent: Administer InfluxDB Cloud
weight: 6
---

The Admin UI for {{% product-name %}} provides a no-code way to manage your {{% product-name %}} environment.
Use the Admin UI to view your {{% product-name %}} account information and manage cluster resources, such as tokens and databases.

## Access the Cloud Dedicated Admin UI

<img src="/img/influxdb3/cloud-dedicated-admin-ui-login.png" alt="InfluxDB Cloud Dedicated Admin UI login page" />

Cloud Dedicated customers can access the Admin UI at [console.influxdata.com](http://console.influxdata.com) using the credentials provided by InfluxData.
If you don't have login credentials, [contact InfluxData support](https://support.influxdata.com).

After you log in to the Admin UI, the Account Management portal lets you view your account information and manage your InfluxDB Cloud Dedicated resources.

## Account management

<img src="/img/influxdb3/cloud-dedicated-admin-ui-clusters-options.png" alt="InfluxDB Cloud Dedicated Admin UI account management cluster list" />

- View account details and associated clusters
- Create, view, and manage management tokens for account-level operations
- Access contract information (status, start date)

For more information, see the following:

- [View account information](/influxdb3/cloud-dedicated/admin/account/)
- [Manage management tokens](/influxdb3/cloud-dedicated/admin/tokens/)

## Resource management


The Admin UI lets you manage InfluxDB Cloud Dedicated resources, such as databases,
tables, and tokens, associated with a cluster. 

- [Manage clusters](#manage-clusters)
- [Manage databases](#manage-databases)
- [Manage tables](#manage-tables)
- [Manage database tokens](manage-database-tokens)

### Manage clusters

<img src="/img/influxdb3/cloud-dedicated-admin-ui-clusters-options.png" alt="InfluxDB Cloud Dedicated Admin UI cluster options" />

- View cluster IDs, statuses, creation date, and sizing information
- Access Grafana dashboards for operational monitoring (if enabled for the account)
- View and manage resources (such as databases, tables, and database tokens) associated with a cluster

For more information, see [Manage clusters](/influxdb3/cloud-dedicated/admin/clusters/).

### Manage databases

<img src="/img/influxdb3/cloud-dedicated-admin-ui-databases.png" alt="InfluxDB Cloud Dedicated Admin UI cluster resources databases list" />

- Create and delete databases
- Update retention periods
- Configure maximum tables and columns per table
- View and manage tables associated with a database

For more information, see [Manage databases](/influxdb3/cloud-dedicated/admin/databases/).

### Manage tables

<img src="/img/influxdb3/cloud-dedicated-admin-ui-tables.png" alt="InfluxDB Cloud Dedicated Admin UI database tables list" />

- View tables associated with databases
- See table IDs and sizes
- Create new tables

For more information, see [Manage tables](/influxdb3/cloud-dedicated/admin/tables/).

### Manage database tokens

<img src="/img/influxdb3/cloud-dedicated-admin-ui-database-tokens.png" alt="InfluxDB Cloud Dedicated Admin UI manage database tokens portal" />

- Create and manage authentication tokens for database-level operations
- Edit permissions or revoke existing tokens
- Control access with granular read and write permissions

For more information, see [Manage database tokens](/influxdb3/cloud-dedicated/admin/tokens/).

### Additional Features

- Help center for access to documentation 
- One-click connections to InfluxData sales and support
