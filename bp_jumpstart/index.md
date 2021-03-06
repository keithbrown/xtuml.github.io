# BridgePoint Tool Jumpstart

## Background

These instructions aim to give new users a basic introduction to the 
BridgePoint tool utilizing content from various sources.  The goal is 
to minimize blank paper shock and tool struggles.   

Help is available in the [xtUML Forum](https://xtuml.org/forums/) and 
[xtUML Community Chat](https://hangouts.google.com/group/vMohZ9oW08xR7wSd2). Don't
hesitate to use these resources!  Someone from our friendly community will help you.  

# Installation

## Download
[Download BridgePoint (xtUML Modeler version)](https://s3.amazonaws.com/xtuml-releases/nightly-build/buildfiles.html). 
* Create a folder `xtuml` in your home directory (hereafter referred to as `<home>`)  
* Extract the zipfile contents into the `<home>/xtuml` folder 

> __OS Compatibility Note:__  
> On Linux and MacOS directory paths are separated with `/`, while on 
> Windows you will use `\`

## Simplified User Interface

BridgePoint supports many UML diagrams. To simplify the user interface and focus
on only the executable diagrams:
* Using a text editor, open `bridgepoint.ini` in your installation under `<home>/xtuml` (will be under a subdirectory depending on your OS)  
* Append the following to the end of `bridgepoint.ini`  
```
-Dbridgepoint.AcceptEventAction=disabled
-Dbridgepoint.AcceptTimeEventAction=disabled
-Dbridgepoint.Action=disabled
-Dbridgepoint.ActivityEdge=disabled
-Dbridgepoint.ActivityFinalNode=disabled
-Dbridgepoint.ActivityPartition=disabled
-Dbridgepoint.Actor=disabled
-Dbridgepoint.AssociativeLink=disabled
-Dbridgepoint.AsynchronousMessage=disabled
-Dbridgepoint.CommunicationLine=disabled
-Dbridgepoint.DecisionMergeNode=disabled
-Dbridgepoint.Extend=disabled
-Dbridgepoint.Exception=disabled
-Dbridgepoint.FlowFinalNode=disabled
-Dbridgepoint.ForkJoinNode=disabled
-Dbridgepoint.Generalization=disabled
-Dbridgepoint.Include=disabled
-Dbridgepoint.InitialNode=disabled
-Dbridgepoint.Instance=disabled
-Dbridgepoint.InteractionClass=disabled
-Dbridgepoint.InteractionComponent=disabled
-Dbridgepoint.InteractionExternalEntity=disabled
-Dbridgepoint.Link=disabled
-Dbridgepoint.ObjectNode=disabled
-Dbridgepoint.PackageParticipant=disabled
-Dbridgepoint.ReturnMessage=disabled
-Dbridgepoint.SendSignalAction=disabled
-Dbridgepoint.SynchronousMessage=disabled
-Dbridgepoint.TimingMark=disabled
-Dbridgepoint.TimeSpan=disabled
-Dbridgepoint.UseCase=disabled
-Dbridgepoint.UseCaseAssociation=disabled
```
* Save and exit the text editing of `bridgepoint.ini`  
* Create a folder named `workspaces` in your home directory
* Start BridgePoint by running the executable file named `bridgepoint` 
* You are prompted for a "workspace".  Eclipse uses workspaces to contain
information about one or more projects.  Let's specify a workspace named
`sandbox1` by entering `<home>/workspaces/sandbox1`   
* Once BridgePoint starts, Click the "x" on the Welcome tab to close the Welcome page

# Project Creation and Editing Example

Now let's go step by step to create an example model.  This phase is intended
to teach you how to perform model edits.  Getting started from a blank canvas is
often challenging, so let's jump right in.  

[Build a Sumo model](../xtuml-class/sumo_edit/)  

# Additional Learning

Now that you have learned a little about the tool, many other resources are available
on [xtuml.org](https://xtuml.org) under the "Learn" section.  

## Online Course

Of specific note is the online [Modeling with xtUML](https://xtuml.org/learn/on-line-courses/)
course.  This course uses short-form videos to teach users about various 
parts and features of BridgePoint.  

## Example Models

BridgePoint has several sample models built into the tool.  Re-open the Welcome
page by choosing `Help > Welcome` in the application menu.  Then choose `Quick Start`.

