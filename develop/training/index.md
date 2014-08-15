---
layout: page
title: 交互响应
permalink: develop/training/index.html
---

# Getting Started

## 第一课程:Building Your First App

【本课内容简介】欢迎加入到安卓应用的开发大潮中！这门课程会教授你怎么去创建你的第一个安卓的应用程序。你会学习到怎么创建一个安卓项目，怎么去运行一个应用的调试版本。你还会学习到安卓应用的一些基本面，像是创建一个简单用界面并处理用户的输入。 

在你开始这门课程前，请确保你已经搭建好应用环境，你需要： 
*1、下载安卓的SDk新手包。 
*2、安装Eclipse的ADT插件（如果你用的是Eclipse的开发环境，即IDE）。 
*3、用SDK Manager[http://developer.android.com/sdk/index.html 下载最新的SDK工具]和platforms。 
如果你还没有环境的搭建，请阅读 安装SDK - Installing the SDK 。一旦你完成了环境的搭建，你就可以开始这门课程了。 这门课程为了教授你一些安卓开发的基本理念，使用了渐进式的教学方式来建造一个小小的安卓应用。所以请认真的按照步骤一步一步的进行学习。

### 第一课程目录

1、[[Creating an Android Project|创建一个安卓工程 -Creating an Android Project]]

本课的主要内容是演示怎么创建一个包含默认应用文件集的安卓应用项目

2、[[Running Your Application|运行你的应用-Running Your Application]]

本课的主要内容是演示怎样在一个安卓设备或者安卓模拟器上运行你的应用

3、[[Building a Simple User Interface|创建简单的用户交互-Building a Simple User Interface]]

本课的主要内容是演示怎么使用xml文件创建一个新的用户界面

4、[[Starting Another Activity|启动另一个活动-Starting Another Activity]] 

本课的主要内容是演示怎么响应一个按键去启动另一个活动，并且给这个活动发送一些数据。然后在后续启动的活动中接收这些数据

## 第二课:生命周期的管理 - Managing the Activity Lifecycle

【本课内容简介】当用户进出穿梭于你的应用程序时，你的应用程序的Activity实例会在不同的生命周期状态中变化。例如，在你的Activity第一次启动并且显示在你的屏幕上获取到用户的焦点的这个过程中，安卓系统调用activyt一系列的生命周期函数方法用来建立用户界面和其他组件。如果用户的操作启动了另外一个activity或者启动了另外一个应用程序，原来的Activity转到后台（此时Activity不可见，但其实例状态仍然保存），系统将会调用另外一些Activity的生命周期函数。

在生命周期的回调函数中，你可以设定用户离开或者返回到该Activity时你需要进行的操作。例如，当你的程序正在进行视频流媒体的连接，而用户跳去其他应用程序，此时你可以暂停播放你的视频且终止网络连接，当用户返回时，可以设定其再次连接网络和允许用户恢复视频播放的暂停点这一节的内容，将会介绍Activity中非常重要的生命周期回调函数，让用户做到能在在Activity生命周期里面进行的相关操作，在Activity不需要某些系统资源时暂停它们的使用。

### 第二课程目录

1、[[Starting an Activity|启动Activity- Starting an Activity]]

学习Activity生命周期的基础，用户启动你的应用程序的方法以及基础的Activity生成操作。

2、[[Pausing and Resuming an Activity|暂停和恢复Activity-Pausing and Resuming an Activity]]

学习到你的Activity暂停时和恢复时引发的事件，并知道你应该在这些状态改变的时候要做的事情。

3、[[Stopping and Restarting an Activity|停止和重启Activity-Stopping and Restarting an Activity]]

学习到当用户完全离开你的Activity时和返回时发生的事件。

4、[[Recreating an Activity|重置Activity-Recreating an Activity]]

学习到当activity被销毁时发生的事件，并在需要的时候如何重建Activity。


## 第三课：多设备支持-Supporting Different Devices

【本课内容简介】在全球，Android设备的外形和大小多种多样，可谓精彩纷呈。由于设备类型的多种多样，你和你的应用有机会面对广大的受众。为了能够在Android领域尽可能的接近成功，你的应用应该适用于各种各样的设备配置。支持多语言、多屏幕大小以及各种版本的Android平台，就是你应该认真考虑的几个重要方面。 
本课程教你如何在一个应用程序包（APK）中使用一些基础平台功能，比如替代资源等，来完成在各种各样Android的设备上提供统一且优异的用户体验的艰巨任务。 

### 第三课程列表
1、[[Supporting Different Languages|多语言支持 -Supporting Different Languages]]

学习怎么使用替代字符串资源来实现多语言支持。

2、[[Supporting Different Screens|多屏幕支持 -Supporting Different Screens]]

学习怎么使用创建不同layout布局来实现多屏幕支持。

3、[[Supporting Different Platform Versions|不同平台版本支持 -Supporting Different Platform Versions]]

学习在继续支持老的Android版本的同时，怎么使用最新版本的API。

## 第四课：通过片段创建灵活的用户界面-Building a Dynamic UI with Fragments

【本课内容简介】为了在android中创建一个灵活和多窗口的用户界面，你需要封装用户界面组件和Activity的行为成模块，那样才能交换你的活动。你可以通过片段类，表现的有点像一个嵌套的可以定义自己的布局和管理自己的生命周期的Activity，来创建这些模块。当一个片段指定了自身的布局时，它能被配置到带有其他片段的组合中，在活动中去修改你的布局来配置不同的屏幕尺寸（小屏幕可能每次显示一个片段，而大屏幕则可以显示两个或更多）。这个类显示给你如何去利用片段创造灵活的用户体验以及优化你的应用程序在不同屏幕尺寸的设备中的用户体验，而且同时支持老版本android 1.6。

### 第四课程列表

1、[[Using the Support Library|利用android支持的库-Using the Support Library]]

学习如何在早些的android版本中，在你的应用程序中建立android支持的库来利用最新的片段APIs。

2、[[Creating a Fragment|创建一个片段-Creating a Fragment]]

学习如何建立一个片段，以及在它的回调函数中执行基本的操作

3、[[Building a Flexible UI|建立一个灵活的用户界面-Building a Flexible UI]]

学习如何通过提供用于不同屏幕的的不同的片段配置的布局来构建你自己的应用程序

4、[[Communicating with Other Fragments|与其他片段交互-Communicating with Other Fragments]]

学习如何建立从一个片段到Activity和其他片段的交互桥梁

## 第五课内容：与其他应用程序进行交互 - Interacting with Other Apps

【本课内容简介】一个Android应用程序通常都会有若干个Activity，每一个Activity都让用户执行指定的操作(例如查看地图或照相)。把用户从一个Activity带到另一个Activity，必须使用一个Intent去指定你的应用程序“意图”去做的事。当你用startActivity()函数向系统传递一个Intent，系统就会利用这个Intent去界定和开启对应的应用程序组件。使用Intent甚至可以允许你的应用程序启动一个独立应用程序的Activity。
Intent可以用来启动一个指定的组件(一个指定的Activity实例)，或者用来启动任何能够处理这个Intent功能的组件。（例如捕获一张照片）这节课的内容将会讲到如何使用一个Intent来执行一些与其他应用程序的基本交互，如启动另一个应用程序，并从该启动的应用程序返回相应的结果，还有让你自己的应用程序能够对别的应用程序传来的intent行为作出反应。 

### 第五课课程目录

1、[[Sending the User to Another App|让用户转移到另一个应用程序-Sending the User to Another App]]

介绍如何建立一个Intent去启动另一个有相应功能的应用程序。

2、[[Getting a Result from the Activity|从另一个Activity中取回反馈结果-Getting a Result from the Activity]]

介绍如何去启动另一个Activity并且从该Activity取得一个反馈结果。

3、[[Allowing Other Apps to Start Your Activity|允许其他应用程序去启动您的Activity-Allowing Other Apps to Start Your Activity]]

介绍如何让您的Activity对外开放，通过定义一个intent filters使得其他应用程序可以使用您的Activity。

