---
title: Experimental features and origin trials
description: Learn how to test experimental PWA features in Microsoft Edge and enroll your site in origin trials to use these features in production with your users.
author: MSEdgeTeam
ms.author: msedgedevrel
ms.date: 09/15/2021
ms.topic: conceptual
ms.prod: microsoft-edge
ms.technology: pwa
keywords: progressive web apps, PWA, Microsoft Edge, experimental, origin trials
---
# Experimental features and origin trials  

Some of the PWA features in Microsoft Edge are still experimental. Experimental features can be used in 2 ways:   

*   By enabling the corresponding flag in Microsoft Edge.
*   By enrolling your site in an origin trial to test features in production with your users.  


<!-- ====================================================================== -->
## Toggle experimental features  

To turn on \(or off\) experimental features in Microsoft Edge, complete the following steps.  
  
1.  Open Microsoft Edge.  
1.  Navigate to `edge://flags`.  
1.  Navigate to the relevant experiment.  
1.  Select the dropdown menu next to the experiment description and select **Enabled** to enable the feature or **Disabled** to disable it.  
    
    :::image type="complex" source="../media/turn-on-experimental-flag.png" alt-text="Select Enabled to turn on an experiment" lightbox="../media/turn-on-experimental-flag.png":::
       Select **Enabled** to turn on an experiment  
    :::image-end:::  


<!-- ====================================================================== -->
## Enroll your site in an origin trial  

Microsoft Edge sometimes uses origin trials to test features for specific domains or websites. You may want to use an origin trial for your website to apply a specific feature. If you're a website owner, you can enroll in an origin trial. An origin trial provides features to a percentage of Microsoft Edge users who visit your website.  

For more information about Origin Trials, navigate to [Microsoft Edge Origin Trials Developer Console][MicrosoftDeveloperMicrosoftEdgeOriginTrials].  


<!-- ====================================================================== -->
## Features that are available to test

The following list describes experimental web app features that are available to test and validate on Microsoft Edge. To enable them, navigate to [Toggle experimental features](#toggle-experimental-features).  

| Feature | Platform |
|:--- |:--- |
| [URI Protocol Handling](handle-urls-protocols.md) | Windows and Linux |
| [URL Link Handling](handle-urls-protocols.md) | Windows|
| [Window Controls Overlay for Desktop Apps](window-controls-overlay.md) | Windows 10|
| [The Shortcuts object in the manifest](shortcuts.md) | All |
| [File Handling](handle-files.md) | All Desktop |

<!-- Links -->

[MicrosoftDeveloperMicrosoftEdgeOriginTrials]: https://developer.microsoft.com/microsoft-edge/origin-trials "Origin Trials | Microsoft Edge Developer"  