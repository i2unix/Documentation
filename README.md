Zend Server Plugins - API Version 1.0.3
==========

This document describes the concept of Zend Server Plugins, including basic instructions on how to use the feature and code samples. 

## What is a Zend Server Plugin ?
A Zend Server plugin is an archive file that consists of a [Z-Ray extension](http://files.zend.com/help/Zend-Server/zend-server.htm#z-ray_concept.htm) and Routing information, each one of these being optional. A plugin can be installed via the Zend Server UI.

## Plugin Structure
A plugin is comprised of two main directories: `zray` and `route`, respectively including Z-Ray extension and routing information. An additional file that is required for deployment is the `deployment.json` file which describes the plugin package.

## Skeleton package
You can download the skeleton package from here: [Z-Ray Skeleton Plugin](https://github.com/zend-server-plugins/Skeleton)

## UI Plugin Example
A very useful UI plugin, which also facilitates the UI Extensions API, can be downloaded from here: [Zend Server Web Api Client](https://github.com/zend-server-plugins/zs_web_api_client)

## Table of Contents
- [deployment.json](DeploymentJson.md)
- [Z-Ray extension API](ZRayApi.md)
- [Routing information API](RouteAPI.md)
- [UI Extensions API](UIAPI.md)
