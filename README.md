<h3 align="center">Drivable Area 3D Mapping</h3>
<p align="center">
  🗺️RGBD 센서를 이용한 주행 가능 영역 Semantic Segmentation 및 3D Mapping 
</p>

* * *

## Overview
<p align="left">
   <img
    src="/Image/ORB_SLAM2_Overview.gif" width=320 height = 227
  >
  <img
    src="/Image/rtab_map_result.gif" width=480 height = 227
  >
</p>

## Description
주행 가능영역을 Semantic Segmentation하고 pointcloud로 만들어 Large Scale 3D Map에 나타내는 프로젝트입니다. 

This is a project that semantic segmentation of the drivable area and makes it into a pointcloud and displays it on a 3D map.


## Purpose
RGBD Sensor 이용한 Localization & 3D Mapping

Localization & 3D Mapping using RGBD Sensor

## Project List
* Semantic Segmentation
* Localization
* 3D Mapping
* Map Merge

## Pre-requisties
|  <center>Requirement</center> |  <center>Description</center> |  
|:--------|:--------:|
|**ZED2i** | <center>RGBD Camera sensor</center> |
|**Ubuntu_20.04** | <center>Ubuntu_foxy version</center> |
|**ROS_noetic** | <center>noetic version of ROS</center> |
|**python** | <center>v3.8.10</center> |
|**opencv** | <center>v4.2.0 </center> |
|**tensorflow** | <center>v2.11.1 </center> |


## Result Video

**ORB_SLAM2+Segmentation**
<p align="left">
  <img
    src="/Image/ORB_SLAM2.gif" width=500
  >
</p>

**RTAB_Map+Segmentation**
<p align="left">
  <img
    src="/Image/rtab_map+seg.gif" width=500
  >
</p>

**Final_result**
<p align="left">
  <img
    src="/Image/Final_result.gif" width=500
  >
</p>

