<p align="center">
  <a href="https://github.com/matiascodesal/awesome-usd"><img alt="awesome" src="https://github.com/matiascodesal/awesome-usd/blob/c51c80497c0aee22a4f6172fda22cc8bfd3f8586/images/AwesomeUSD_2by1_sm.png" width="480" /></a>
</p>
<p align="center">
  <a href="https://awesome.re"><img alt="awesome" src="https://awesome.re/badge.svg" /></a>
</p>

# Awesome USD
A curated list of awesome Universal Scene Description (USD) resources and projects. These are hand-picked resources and projects that I find awesome. You might find more or others at the [ASWF USD Working Group Wiki](https://wiki.aswf.io/display/WGUSD/USD+Projects+and+Resources).

Curated by [@maticodes](https://twitter.com/maticodes)

## Contents
- [What is USD?](#what-is-usd)
- [Libraries & Tools](#libraries--tools)
- [Sample Assets](#sample-assets)
- [Learning](#learning)
- [References](#references)
- [Integrations](#integrations)

## What is USD?
### Non-Technical Explanation
* [A USD primer for ARTISTS](https://www.youtube.com/watch?v=SaBXE4yQetk) - Video explanation focused for artists with some overview of Maya workflows. Short and sweet.
* [What is USD: A Primer | Rob Stauffer | SIGGRAPH 2019](https://www.youtube.com/watch?v=Yp_TRVD3wjQ) - Longer video, but more complete explanation of stage composition.
* [Five Things to Know About USD](https://www.youtube.com/watch?v=vFxytzQlOEs)
### Technical Explanation
* [Introduction to USD](https://graphics.pixar.com/usd/release/intro.html) - The official OpenUSD site provides a brief intro and overview.
* [Understand USD Fundamentals](https://developer.apple.com/videos/play/wwdc2022/10129/) - An introductory overview video of USD with examples.
* [What Makes USD Unique in NVIDIA Omniverse](https://www.youtube.com/watch?v=o2x-30-PTkw) - Short high-level overview of USD and what makes it unique.

## Libraries & Tools
* [OpenUSD Github Repository](https://github.com/PixarAnimationStudios/USD) - The main repository for the Universal Scene Description (USD) project.
* [usd-core](https://pypi.org/project/usd-core/) - usd-core Python package on pypi. Use the USD core Python API without having to build USD.
* [UsdQt](https://github.com/LumaPictures/usd-qt) - Resuable Qt components for building custom USD tools from Luma.
* [usdtweak](https://github.com/cpichard/usdtweak) - USD editing tool. Kind of like usdview with editing capabilities.
* [USD Manager](https://github.com/dreamworksanimation/usdmanager) - Tool from DreamWorks Animation for browsing, managing, and editing USD files.
* [USD Shell Extension](https://github.com/Activision/USDShellExtension) - Tool from Activision that adds Hydra Preview, thumbnails, context menus, and metadata search to Windows Explorer.
* [UsdNodeGraph](https://github.com/1xinghuan/usdNodeGraph) - Node graph for visualizing and editing USD files. Maya and usdview embeddable.
* [USD Rust Bindings](https://github.com/vfx-rs/usd-bind) - Rust bindings for USD.
* [Luma URI Resolver](https://github.com/LumaPictures/usd-uri-resolver) - Luma's example URI asset resolver.
* [S3 Resolver](https://github.com/westerndigitalcorporation/usd-s3-resolver) - An Amazon S3 and MySQL asset resolver.
* [usdstubgen](https://github.com/chadrik/usdstubgen) - Generates python stub filles (.pyi) for USD Python API for static type analysis and code completion.
* [Switch](https://github.com/VictorYudin/switch) - A simple built on USD and Hydra.
* [Autodesk USD WebASM](https://forums.autodesk.com/t5/engineering-hub-blog/autodesk-open-sources-web-based-usd-viewing-implementation/ba-p/11071751) - USD running on the browser and a Three.js Hydra render delegate. [Demo](https://autodesk-forks.github.io/USD/) 
* [USDZ Web Viewer](https://www.usdz-viewer.net/) - View USDZ files in the browser. Builds on Autodesk's related work. [USDZ Loader Github ](https://github.com/ponahoum/three-usdz-loader) [Viewer Github](https://github.com/ponahoum/usdz-web-viewer)
* [UsdSkel Util](https://github.com/meshula/usdskelutil) - Utilities for use with the UsdSkel schema
* [Apple Schemas](https://developer.apple.com/documentation/arkit/usdz_schemas_for_ar) - USDZ schemas for AR (e.g. Anchoring, Behaviors, Text)

### Converters
* [guc](https://github.com/pablode/guc) - glTF to USD converter than boasts near-lossless material translation via MaterialX
* [USD from glTF](https://github.com/google/usd_from_gltf) - gltf to USD converter focused on AR Quick Look support.
* [gltf2usd](https://github.com/kcoley/gltf2usd) - glTF to USD converter with ARKit/USDZ support.
* [ptc2usd](https://github.com/simpassi/ptc2usd) - Converts Pixar's PTC and Houdini JSON point clouds to USD.
* [Omniverse Asset Converter](https://docs.omniverse.nvidia.com/app_create/prod_extensions/ext_asset-converter.html) - Python API and microservice for converting FBX/glTF/OBJ to USD.
* [fspy-USD](https://github.com/Vochsel/fspy-USD) - Converts fSpy camera matching file to USD.

### Hydra
* [Arnold USD](https://github.com/Autodesk/arnold-usd) - Arnold Hydra render delegate and schemas.
* [Blackbird (Blender Cycles)](https://github.com/tangent-opensource/hdBlackbird) - Blender Cycles Hydra render delegate from Tangent Animation.
* [LuxCoreRender](https://github.com/jbgann/LuxCoreRenderUSD) - LuxCoreRender Hydra render delegate.
* [gatling](https://github.com/pablode/gatling) - Hydra render delegate for GPU-based path tracer.
* [OSPRay](https://github.com/ospray/hdospray) - Hydra render delegate for Intel's OSPRay.
* [Radeon ProRender](https://github.com/GPUOpen-LibrariesAndSDKs/RadeonProRenderUSD) - Hydra render delegate for AMD's Radeon ProRender.

### Text Editor Plugins
* [usd-idea](https://github.com/justint/usd-idea) - PyCharm plugin adding syntax highlighting, reference linking, brace matching/folding, etc.
* [VS Code USD Language Extension](https://marketplace.visualstudio.com/items?itemName=AnimalLogic.vscode-usda-syntax) - From Animal Logic, adss syntax highlighting and reference linking.
* [usda-syntax](https://github.com/superfunc/usda-syntax) - Syntax Highlighting for USDA files in vim, emacs & sublime.
* [Notepad++ Syntax Highlighter](https://github.com/AndrewHazelden/PIXAR-USD-Syntax-Highlighter) - USDA file syntax highlighting in Notepad++.

### FileFormat Plugins
* [usdat](https://github.com/dreamworksanimation/dwa_usd_plugins/tree/master/pxr/usd/plugin/usdat) - A FileFormat plugin from DreamWorks Animation that enables working with templating in USD files.

## Sample Assets
Scene and other assets put together to test USD features and as examples of how to compose your assets and stages.
* [Pixar Sample Assets](https://graphics.pixar.com/usd/release/dl_downloads.html#assets) - Kitchen Set, City Set, UsdSkel Examples.
* [NVIDIA Sample Assets](https://developer.nvidia.com/usd#sample) - Marbles Sample, Attic Sample
* [Animal Logic](https://animallogic.com/usd-alab/) - USD ALab
* [Disney Moana Island Scene](https://www.disneyanimation.com/resources/moana-island-scene/) - Full island scene data from Moana animated feature film.
* [Lowe's Open Builder](https://www.lowesopenbuilder.com/) - Over 500 furniture models from the Lowe's catalog in USDZ format.
* [Intel Sample Assets](https://www.intel.com/content/www/us/en/developer/topic-technology/graphics-research/samples.html) - Provided under ASWF license by Intel.
* [ASWF USD WG Assets](https://github.com/usd-wg/assets) - Test assets and asset guidelines from the ASWF USD Working Group.
* [SideFX Sample Assets](https://www.sidefx.com/contentlibrary/) - Mexican Still Life, Elephant Seal, Bar Scene, Market Scene.
* [Blender Sample Assets](https://download.blender.org/institute/sybren/usd/)
* [J Cube Sample Assets](https://j-cube.jp/solutions/multiverse/assets/) - USD Esper Room scene and USDZ Maneki asset.
* [Apple Sample Assets](https://developer.apple.com/augmented-reality/quick-look/) - Quick Look sample USDZ.
* [Heri Sample Assets](https://heri.blog/category/freescenes/) - Water, debris, and chess set.

## Learning
### Non-Technical Learning
### Technical Learning
* [NVIDIA's USD DLI Course](https://courses.nvidia.com/courses/course-v1:DLI+S-FX-02+V1) - Free intro course completely in the browser running on JupyterLab.
* [Pixar USD Tutorials](https://graphics.pixar.com/usd/release/tut_usd_tutorials.html) - 14 modules with step-by-step instructions showing how to use the Python API and the results in USDA and usdview
* [NVIDIA's Python USD Tutorial](https://developer.nvidia.com/usd/tutorials) - A brief tutorial of working with USD using the Python API.
* [ASWF USD-WG Presentations](https://wiki.aswf.io/display/WGUSD/Presentations) - Interesting presentations from the ASWF USD Working Group.
* [USD Plugin Examples](https://github.com/wetadigital/USDPluginExamples) - Simple examples to demonstrate how to compile and build USD plugins.
* [Tiny USD program](https://github.com/meshula/tinyusd) - A really small getting-started program for USD on Windows.

## References
* [USD C++ API Documentation](https://graphics.pixar.com/usd/release/api/index.html) - The primary USD C++ API documentation.
* [NVIDIA's Python API Notes](https://developer.nvidia.com/usd/apinotes) - A primer for USD Python API usage.
* [Colin Kennedy's USD Cookbook](https://github.com/ColinKennedy/USD-Cookbook) - Basic to advanced examples of USD in C++, Python, and USDA formats.
* [usd-interest Google Group](https://groups.google.com/g/usd-interest) - Search years through years of USD questions or ask one here.
* [ASWF USD Working Group](https://github.com/AcademySoftwareFoundation/wg-usd) - Information about the ASWF USD Working Group.
* [usd-core on Google Colab](https://github.com/philsawicki/usd-core-on-google-colab) - Example showing how you can use usd-core on Google Colab notebooks.
* [USD Imaging on Google Colab](https://github.com/philsawicki/usd-imaging-on-google-colab) - Example showing how you can use USD Imaging on Google Colab notebooks.

## Integrations
* 3Delight - Hydra render delegate [[Gitlab](https://gitlab.com/3Delight/HydraNSI)]
* [3ds Max](https://knowledge.autodesk.com/support/3ds-max/learn-explore/caas/CloudHelp/cloudhelp/2022/ENU/3dsMax-USD/files/GUID-04F1DF51-0079-4DF8-8457-5AD12B6C0673-html.html#:~:text=USD%20Overview&text=USD%20is%20essentially%20an%20extensible,Maya%20and%203ds%20Max) - Import, Export, [via Omniverse](https://docs.omniverse.nvidia.com/con_connect/con_connect/3ds-max.html)
* [AnimVR](https://nvrmind.io/features) - Import
* Archicad - [via Omniverse](https://docs.omniverse.nvidia.com/con_connect/con_connect/archicad.html)
* [Arnold](https://docs.arnoldrenderer.com/display/A5ARP/Introduction+to+Arnold+USD) - Hydra render delagate and custom schemas. [[Github](https://github.com/Autodesk/arnold-usd)]
* Blender - A couple of different import/export implementations ([usd branch](https://builder.blender.org/download/experimental/), [AMD](https://github.com/GPUOpen-LibrariesAndSDKs/BlenderUSDHydraAddon)) and the [Cycles Hydra render delegate](https://github.com/tangent-opensource/hdBlackbird).
* [CAD Exchange](https://cadexchanger.com/) - Convert between various CAD formats including USD.
* Character Creator - Export, [via Omniverse](https://docs.omniverse.nvidia.com/con_connect/con_connect/character-creator.html)
* Cinema 4D - Import, Export
* CityEngine - [Import](https://doc.arcgis.com/en/cityengine/latest/help/help-import-usd.htm), [Export](https://doc.arcgis.com/en/cityengine/latest/help/help-export-usd.htm), [Omniverse Unidirectional Livesync](https://docs.omniverse.nvidia.com/con_connect/con_connect/cityengine.html)
* Clarisse - Import, Export
* Creo - [via Omniverse](https://docs.omniverse.nvidia.com/con_connect/con_connect/creo.html)
* Fusion 360 - Export
* Gaffer - Authoring, Import, Export
* Guerilla Render- Import
* [Golaem](https://golaem.com/content/doc/golaem-crowd-documentation/overview-6) - Dynamic FileFormat plugin [[Github](https://github.com/Golaem/GolaemForUSD)]
* Houdini - Native authoring, Import, Export, [via Omniverse](https://docs.omniverse.nvidia.com/con_connect/con_connect/houdini.html)
* iClone - Export, [via Omniverse](https://docs.omniverse.nvidia.com/con_connect/con_connect/iclone.html)
* [Katana](https://learn.foundry.com/katana/dev-guide/Plugins/KatanaUSDPlugins/index.html) - Import, Export, Hydra viewport
* Mari - Import, Export
* [Maya](https://makeanything.autodesk.com/usd) - Import, Export [[Github](https://github.com/Autodesk/maya-usd)]
* [Millefiori](https://dl.acm.org/doi/10.1145/3329715.3338882) -  MPC's USD-based Sequence Editor
* [Mineways](https://www.realtimerendering.com/erich/minecraft/public/mineways/) - Export
* Modo - Import, Export
* [Multiverse](https://j-cube.jp/solutions/multiverse/) - Maya plugin offering USD interop.
* [Nuke](https://learn.foundry.com/nuke/content/comp_environment/3d_compositing/usd.html) - Import, Hydra Viewport
* NVIDIA Omniverse - Native authoring, Import, Export, Hydra viewport, custom schemas 
* [NXT](https://nxt-dev.github.io/) - Native authoring
* [OpenPype](https://openpype.io/) - [USD resolver](https://github.com/antirotor/OpenPype-USD-Resolver)
* ParaView - [via Omniverse](https://docs.omniverse.nvidia.com/con_connect/con_connect/paraview.html)
* [PlantCalatog](https://info.e-onsoftware.com/plantcatalog/) - Export, via Omniverse
* [PlantFactory](https://info.e-onsoftware.com/plantfactory/overview) - Export, via Omniverse
* Quick Look - Apple's USDZ AR Viewer
* Radeon ProRender - Hydra render delegate [[Github](https://github.com/GPUOpen-LibrariesAndSDKs/RadeonProRenderUSD)]
* Reality Composer - Import, Export USDZ
* Revit - [third-party export plugin](https://apps.autodesk.com/RVT/en/Detail/Index?id=127804203175527993&appLang=en&os=Win64),  [via Omniverse](https://docs.omniverse.nvidia.com/con_connect/con_connect/revit.html)
* Rhino - [via Omniverse](https://docs.omniverse.nvidia.com/con_connect/con_connect/rhino.html)
* Shapr3D - USDZ Export
* [Shogun](https://www.vicon.com/software/shogun/) - Import, Export
* SketchUp - [via Omniverse](https://docs.omniverse.nvidia.com/con_connect/con_connect/sketchup.html)
* Substance 3D Painter - Export, [via Omniverse](https://docs.omniverse.nvidia.com/con_connect/con_connect/substance-3d-painter.html)
* Substance Designer - [SBSAR FileFormat Plugin via Omniverse](https://docs.omniverse.nvidia.com/prod_extensions/prod_extensions/ext_sbsar-support.html)
* [SynthEyes](https://www.ssontech.com/) - Export
* TiltBrush - Export
* [Unity](https://docs.unity3d.com/Packages/com.unity.formats.usd@3.0/manual/index.html) - Import, Export [[Github](https://github.com/Unity-Technologies/usd-unity-sdk)]
* [Unreal Engine](https://docs.unrealengine.com/4.26/en-US/WorkingWithContent/USDinUE4/) - Import, Export, Native reading, [via Omniverse](https://docs.omniverse.nvidia.com/con_connect/con_connect/ue4.html)
* [VUE](https://info.e-onsoftware.com/vue/overview) - Export, via Omniverse
* [V-Ray](https://www.chaos.com/blog/getting-started-with-usd-and-hydra-in-v-ray) - Hydra render delegate and USD procedural
* ZBrush - Import, Export
