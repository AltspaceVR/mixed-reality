---
title: Mixed Reality Design Language
description: Exploring the new Mixed Reality Design Language.
author: Zee2
ms.author: finnsinclair
ms.date: 4/15/2022
keywords: Unity, HoloLens, HoloLens 2, Mixed Reality, development, MRTK, MRTK3, design, UI, design language, UX
---

# Mixed Reality Design Language &#8212; MRTK3

![Button Main](../../../mrtk3-overview/images/UXBuildingBlocks/MRTK_UX_v3_Button.png)

Over the last several years, we've shipped many different devices and form factors with different display types, resolutions, and user experiences. We've developed a set of best practices for designing great experiences in mixed reality, but these best practices continue to evolve as we test and evaluate designs across different products and devices. 

We're excited to introduce the latest Mixed Reality Design Language--first showcased in the Mesh app for HoloLens--to the public through MRTK's building blocks. The new design changes aim to empower developers to build production-ready applications that are more beautiful, usable, and portable. 

## Improvements

- Improved visual feedback for multi-modal input
- Beautiful rounded design elements, combining the traditional HoloLens iridescent look and feel with modern Fluent design
- Modular backplate system for building complex layouts that remain clear and usable
- Redesigned bounding box visuals to reduce visual noise and enable fluid gaze-powered interactions
- Dynamic layout with RectTransform and Canvas

## Key elements

**Geometry**

![Geometry](../../../mrtk3-overview/images/UXBuildingBlocks/MRDL_Elements_Geometry.png)

Geometry describes the shape, size, and position of UI elements. These fundamental design elements help experiences feel coherent across the entire design system. The new design language introduces geometry with rounded corners that create a more approachable, engaging, and modern experience. The geometry is also fully three-dimensional, with a tangible thickness that helps ground the designs in reality. It also reminds the user that these elements are real, physical objects that exist within their 3D space, and can be attached to objects and grabbed, moved, or manipulated.

**Color**

![Backplate color](../../../mrtk3-overview/images/UXBuildingBlocks/MRDL_Elements_Color.png)

Color helps users focus on their tasks by indicating a visual hierarchy and structure between user interface elements. The new design language uses a darker color scheme to minimize eye fatigue while still remaining bright and opaque enough on additive displays to strengthen user confidence when they make direct hand interactions.

**Light and Materials**

![Light](../../../mrtk3-overview/images/UXBuildingBlocks/MRDL_Elements_Light.png)

Light and materials play an essential role in providing visual feedback in spatial interactions. Using contextual 3D illumination helps the user perceive depth and interaction state, especially when the device's additive displays can cause depth confusion. For example, the user's fingertips cast a subtle glow on the pressable surfaces of buttons, improving the user's perception of the distance of their finger from the hologram.

**Layers**

![Layering and Elevation](../../../mrtk3-overview/images/UXBuildingBlocks/MRDL_Elements_Layering.png)

Layering is the concept of overlapping one surface with another. The Mixed Reality Design Language uses layering and elevation to create volumetric UI that enhances interaction quality and usability in spatial interactions, and delights users with a beautiful and intuitive response to their input.

**Iconography**

![Iconography](../../../mrtk3-overview/images/UXBuildingBlocks/MRDL_Elements_Iconography.png)

Iconography is a set of visual images and symbols that help users understand and navigate your app. The Mixed Reality Design Language uses Windows 11's iconography. Every glyph in our system icon font has been redesigned to embrace a softer geometry and more modern metaphors.  

**Typography**

![Typography](../../../mrtk3-overview/images/UXBuildingBlocks/MRDL_Elements_Typography.png)

As the visual representation of language, typography's main task is to communicate information. The Design Language's type ramp helps you create structure and hierarchy in your content to maximize legibility and readability in your UI.

## Mixed Reality Design Language in MRTK3

![MRTKv3 Tearsheet](../../../mrtk3-overview/images/UXBuildingBlocks/MRDL_MRTKv3_Tearsheet.png)<br>

## Examples of using Mixed Reality Design Language

Explore and learn about the Mixed Reality Design Language examples in action.

[Microsoft Mesh app for HoloLens 2](https://techcommunity.microsoft.com/t5/mixed-reality-blog/microsoft-mesh-app-august-2021-update-new-features/ba-p/2746856)

![Mesh app for HoloLens 2](../../../mrtk3-overview/images/UXBuildingBlocks/MRDL_MeshApp.png)<br>
