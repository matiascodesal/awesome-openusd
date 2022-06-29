# Awesome USD
A curated list of awesome Universal Scene Description (USD) resources and projects. These are hand-picked resources and projects that I find awesome. You might find more/others here: https://wiki.aswf.io/display/WGUSD/USD+Projects+and+Resources

## Contents
- [What is USD?](#what-is-usd)
- [Libraries & Tools](#libraries--tools)
- [Sample Assets](#sample-assets)
- [Learning](#learning)
- [References](#references)

## What is USD?
### Non-Technical Explanation
* [A USD primer for ARTISTS](https://www.youtube.com/watch?v=SaBXE4yQetk) - Video explanation focused for artists with some overview of Maya workflows. Short and sweet.
* [What is USD: A Primer | Rob Stauffer | SIGGRAPH 2019](https://www.youtube.com/watch?v=Yp_TRVD3wjQ) - Longer video, but more complete explanation of stage composition.
* [Five Things to Know About USD](https://www.youtube.com/watch?v=vFxytzQlOEs)
### Technical Explanation
* [Introduction to USD](https://graphics.pixar.com/usd/release/intro.html) - The official OpenUSD site provides a bried intro and overview.
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
* [Autodesk USD WebASM Demo](https://autodesk-forks.github.io/USD/) - A demo showing USD running on the browser and a Three.js Hydra render delegate. 
* [USDZ Web Viewer](https://www.usdz-viewer.net/) - View USDZ files in the browser. Builds on Autodesk's related work. [USDZ Loader Github ](https://github.com/ponahoum/three-usdz-loader) [Viewer Github](https://github.com/ponahoum/usdz-web-viewer)
* [UsdSkel Util](https://github.com/meshula/usdskelutil) - Utilities for use with the UsdSkel schema

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
* [NVIDIA's Python USD Tutorial](https://developer.nvidia.com/usd/tutorials) - A brief overview of working with USD using the Python API.
* [Pixar USD Tutorials](https://graphics.pixar.com/usd/release/tut_usd_tutorials.html) - 14 modules with step-by-step instructions showing how to use the Python API and the results in USDA and usdview
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
