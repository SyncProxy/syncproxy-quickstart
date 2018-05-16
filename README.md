# How to create a synchronization proxy with SyncProxy
This tutorial will show you to how to setup a synchronization proxy with SyncProxy to enable bidirectional, real time reactive synchronization between your backend database (MySQL, SQL Server, MongoDB...) and your offline apps embedding free open source SyncProxy client.

## What is SyncProxy ?
>SyncProxy is a proxy server that manages all synchronization between a backend database and offline mobile apps. It connects directly to your SQL/NoSQL database to turn it into a real time reactive datasource.

## Customization
SyncProxy can be either accessed online or installed on site. This tutorial describes the online use of SyncProxy, but it is also perfectly relevant to a custom installation, simply replace **my.syncproxy.com** with your own url.

## To start
First create an account on https://my.syncproxy.com and complete your profile (this is free and takes only one minute). You can later reuse the same account to create other proxies for different apps.
Since you will be the administrator of the proxy, don't forget to check the checkbox "I will manage proxies or groups" and to fill-in your short company info, this will give you access to the admin menu:

![admin menu](https://raw.githubusercontent.com/syncproxy/syncproxy-quickstart/master/admin-menu.png)

## Creating your first proxy
Creating a sync proxy is very easy: just click "New proxy" button from the "Proxies" page, then fill-in the database connection settings. Check the connection with "Test connection":

![admin menu](https://raw.githubusercontent.com/syncproxy/syncproxy-quickstart/master/new-prpxy.png)

## Links
To access **SyncProxy** administration to setup your sync proxy and connect to your backend database, go to www.syncproxy.com.  
Also have a look at the [Quick start guide for Ionic](https://github.com/SyncProxy/syncproxy-quickstart-ionic) which explains how to easily add sync client to your mobile apps.
