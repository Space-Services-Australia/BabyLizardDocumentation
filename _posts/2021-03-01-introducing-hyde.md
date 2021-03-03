---
layout: post
title: Introducing BabyLizard
---
This software allows people to create their simulation components and visualize them. If you have own/purchased a `Cyphys license`, you should be able to start testing quickly.

## Quick Startup

Welcome to BabyLizard quick start tutorial.

**Step 1 - Initial Setup**

- Install [.Net Core SDK 5.0](https://dotnet.microsoft.com/download/dotnet-core)
- Install [Visual Studio 2019](https://visualstudio.microsoft.com/thank-you-downloading-visual-studio/?sku=Community&rel=16)
- Install [Unreal Engine 4.26](https://www.unrealengine.com/en-US/download?install=true)
- Restart your computer (`recommended`)

- Run the `Setup.ps1` or install it manually:

    1) [Automation Tool](./1_AutomationTool/README.md) <br>
    2) [Asset Registry](./2_AssetRegistry/README.md)

- Open the `BabyLizardExample.uproject` and follow the steps

Step 2 - Congratulations

Congratulations! You now should be able to open the BabyLizard example project and start creating components. We will update out documentation more in the future with more tutorials on how to use our editor. Feel free to contact us if you require any assistant email: **info@spaceservicesaustralia.com**

## BabyLizard Tutorial

In this quick tutorial we are going to demonstrate how to create a custom battery.

#### Step1: Creating a Mod

Lets start by creating a mod first to store our battery. This will allow us to add extra functionality to a simulation component

- Launch Unreal Engine
- Open up the Baby Lizard project
- Press the "Create UGC" button on the toolbar
- Give your new mod a name and press "Create Mod"

<br/>

![Image 1](https://babylizard.s3-ap-southeast-2.amazonaws.com/Images/QuickTutorial_01.png)

<br/>

![Image 2](https://babylizard.s3-ap-southeast-2.amazonaws.com/Images/QuickTutorial_02.png)

#### Step 2: Creating a Battery

Next we need to create a new battery blueprint. On the content folder of our new mod we created:

- Right-Click and create a new blueprint
- Under all classes, search for BskSimpleBattery
- Press the "Select" button and give your blueprint a name

![Image 3](https://babylizard.s3-ap-southeast-2.amazonaws.com/Images/QuickTutorial_03.png)

<br/>

![Image 4](https://babylizard.s3-ap-southeast-2.amazonaws.com/Images/QuickTutorial_04.png)


#### Step3: Editing our Battery

Below is the blueprint graph for out battery

If you are not familiar with Unreal Engine, we sugest watching the official tutorial:

- [Intro to Blueprints: Blueprint Introduction | 01 | v4.8 Tutorial Series | Unreal Engine](https://www.youtube.com/watch?v=EFXMW_UEDco)

The left panel shows the simulation events and variables that our custom battery uses. In the example we are creating a battery that has a leak on it's charge by updating the final message


![Image 5](https://babylizard.s3-ap-southeast-2.amazonaws.com/Images/QuickTutorial_05.png)

![Image 6](https://babylizard.s3-ap-southeast-2.amazonaws.com/Images/QuickTutorial_06.png)

#### Step 4: Packaging your new Mod

Once you are happy to package your new battery or custom components:

- Press the "Package UGC" button in the toolbar

![Image 7](https://babylizard.s3-ap-southeast-2.amazonaws.com/Images/QuickTutorial_07.png)

#### Congratulations

Congratulations on making your first mod! You are now ready to submit your mod to our simulation pipeline. We will update out documentation more in the future with more tutorials on how to use our editor. Feel free to contact us if you require any assistant email: info@spaceservicesaustralia.com

### Download

(Add accordingly)
Hyde is developed on and hosted with GitHub. Head to the <a href="https://github.com/poole/hyde">GitHub repository</a> for downloads, bug reports, and features requests.

Thanks!
