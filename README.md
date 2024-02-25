# FundNest Video Call Module Readme

## Overview
This repository contains the video call module for FundNest, utilizing WebRTC technology. The purpose of this module is to facilitate video calls between investors and founders within the FundNest platform.

## Issue with Hosting
Please note that the current hosting service being used for this module does not support sockets due to its serverless architecture. As a result, the video call functionality will not work when deployed to this hosting environment. However, the module functions properly on local machines.

## Potential Solution
To ensure the video call functionality works as intended in a production environment, consider hosting the module on services like AWS or GCP that support socket connections.
