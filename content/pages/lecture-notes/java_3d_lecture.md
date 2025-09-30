---
content_type: page
description: Lecture notes and related links
draft: false
file_size: ''
file_type: ''
image_metadata:
  caption: ''
  credit: ''
  image-alt: ''
learning_resource_types:
- Lecture Notes
license: https://creativecommons.org/licenses/by-nc-sa/4.0/
ocw_type: CourseSection
parent_title: Lecture Notes
parent_type: CourseSection
parent_uid: dd846b6b-f0c7-fd62-35a9-4e87d772d0e9
resourcetype: Document
title: Java 3D Lecture
uid: c9c9104a-ac54-a054-d006-354e424ccb63
video_files:
  archive_url: ''
  video_captions_file: ''
  video_thumbnail_file: ''
  video_transcript_file: ''
video_metadata:
  video_speakers: ''
  video_tags: ''
  youtube_description: ''
  youtube_id: ''
---
This lecture is courtesy of Petros Komodromos.

Topics

1. {{% resource_link "1e1a0075-f426-4eb2-9cee-b4ed5fc22dcc" "Introduction to Java® 3D" %}}
2. {{% resource_link "efa8899f-c983-4e64-804a-6d55cad4623f" "Java® 3D References" %}}
3. {{% resource_link "c25a472d-d83a-45bf-931b-9e85e820f801" "Examples and Applications" %}}
4. {{% resource_link "9c845ac0-3ef9-44ad-82f4-5df4e020f53b" "Scene Graph Structure and basic Java® 3D concepts and classes" %}}
5. {{% resource_link "efd812ab-0a7a-49e9-80f8-9f630c64aae8" "A simple Java® 3D program" %}}
6. {{% resource_link "03e2c978-eb7c-4cbe-a56e-ec56deba3e82" "Performance of Java® 3D" %}}

{{\< anchor "1" >}}{{\< /anchor >}}1. Introduction to Java® 3D

*Java® 3D* is a general-purpose, platform-independent, object-oriented API for 3D-graphics that enables high-level development of Java® applications and applets with 3D interactive rendering capabilities. With *Java® 3D*, 3D scenes can be built programmatically, or, alternatively, 3D content can be loaded from VRML or other external files. *Java® 3D*, as a part of the *Java® Media APIs*, integrates well with the other {{% resource_link "9ae05e59-2295-4a64-9778-a527fb0f89d9" "Java® technologies and APIs" %}}. For example, {{% resource_link "821e36f9-3dfe-4ff1-9a29-5b6b45d7e0d5" "*Java® 2D*" %}} API can be used to plot selected results, while the {{% resource_link "9805786b-f9df-4c6a-aa92-3fb583c21836" "*Java® Media Framework (JMF)*" %}} API can be used to capture and stream audio and video.

Java® 3D is based on a directed acyclic graph-based scene structure, known as scene graph, that is used for representing and rendering the scene. The scene structure is a tree-like diagram that contains nodes with all the necessary information to create and render the scene. In particular, the {{% resource_link "9c845ac0-3ef9-44ad-82f4-5df4e020f53b" "scene graph" %}} contains the nodes that are used to represent and transform all objects in the scene, and all viewing control parameters, i.e. all objects with information related to the viewing of the scene. The scene graph can be manipulated very easily and quickly allowing efficient rendering by following a certain optimal order and bypassing hidden parts of objects in the scene.

Java® 3D API has been developed under a joint collaboration between Intel, Silicon Graphics, Apple, and Sun, combining the related knowledge of these companies. It has been designed to be a platform-independent API concerning the host's operating system (PC/Solaris/Irix/HPUX/Linux) and graphics (OpenGL/Direct3D) platform, as well as the input and output (display) devices. The implementation of Java® 3D is built on top of OpenGL, or Direct3D. The high level Java® 3D API allows rapid application development which is very critical, especially nowadays.

However, Java® 3D has some weaknesses such as the performance, which is inferior to that of OpenGL, and the limited access to the rendering pipeline details. It is also still under development and several bugs need to be fixed. Although Java® 3D cannot achieve peak performance, portability and rapid development advantages may overweigh the slight performance penalty for many applications.

The current version of the Java® 3D API is the Version 1.2, which works together with the {{% resource_link "f832e53c-dd87-4441-baef-5955bf44fa35" "Java® 2 Platform" %}}. Both APIs can be downloaded for free from the {{% resource_link "9ae05e59-2295-4a64-9778-a527fb0f89d9" "Java® products page of Sun" %}}.

 

{{\< anchor "2" >}}{{\< /anchor >}}2. Java® 3D References

The following list includes many links related to the Java® 3D API

- {{% resource_link "447f3cf2-76cc-423a-9557-af7a3a48f0ee" "*Java® 3D 1.2 API Documentation*" %}}  
- {{% resource_link "4cc53695-30c1-4fcb-a96f-5c59653c8d86" "*Java® 3D 1.2 Specification*" %}}  
- Java® 3D Tutorial (PDF format):       
      
    - {{% resource_link "bd4733d0-a626-43e8-8af6-be40c676dd61" "*Chapter 0*" %}} , Preface, Appendices, and Glossary
    - {{% resource_link "20f514a6-bc93-49d4-8ee8-485b1c9b7fb7" "*Chapter 1*" %}} , Getting Started
    - {{% resource_link "d34608dd-a131-4b89-90e0-0d5f6a44e814" "*Chapter 2*" %}} , Creating Content
    - {{% resource_link "02fe8764-a417-45eb-8557-470f6829283b" "*Chapter 3*" %}} , Easier Content Creation
    - {{% resource_link "5deebcdb-389a-4c7c-ad64-bb41632bb8ef" "*Chapter 4*" %}} , Interaction
    - {{% resource_link "7c7ce424-6192-46cb-bfb2-d7e4fbdbfcd4" "*Chapter 5*" %}} , Animation
    - {{% resource_link "1369c9ff-2cec-4230-ba19-7df341f8c988" "*Chapter 6*" %}} *,* Lights
    - {{% resource_link "ddcba9e8-2b4a-41c0-8d73-a2b13475ef78" "*Chapter 7*" %}} , Textures        
         
- {{% resource_link "b9bcb320-238d-4a2c-aada-d1db1105c3cf" "*Raw J3D*" %}}
- {{% resource_link "4ccec2d4-f31a-4d3b-a987-f1a519fc903b" "*Java® 3D: For Developers and End-User*" %}}
- *A Fourth generation Java® 3D graphics API*
- *Java® 3D FAQ at Sun*
- {{% resource_link "50961313-135b-485f-83bb-a701d549d191" "*Java® 3D Community FAQ*" %}}
- *Extensive Java® 3D FAQ at Sun*
- *Java® 3D Group at NCSA*
- {{% resource_link "47f03875-c038-41a6-9396-c6101864bede" "*Java® 3D Community site*" %}}
- *The Java® 3D and VRML Working group*
- *VRML and Java® 3D Information Center*
- *Web 3D consortium*
- {{% resource_link "bc74e4fe-32cf-401a-b041-31dae67f587a" "*Java® 3D Loader Archive*" %}}

Java® 3D is specified in the packages: {{% resource_link "0257b0aa-8607-4698-ac1c-7ab9320f479e" "*javax.media.j3d*" %}} and {{% resource_link "ddc09426-f46f-4958-9741-30f2c073f8d5" "*javax.vecmath*" %}}. Supporting classes and utilities are provided in the *com.sun.j3d* packages.

{{\< anchor "3" >}}{{\< /anchor >}}3. Examples and Applications

The following are examples provided by Java® 3D in directories with the names as follows under the subdirectory *java3d* of the directory *demo*.

- AlternateAppearance
- Appearance
- AppearanceMixed
- AWT\_Interaction: *java AWTInteraction*
- Background
- Billboard
- ConicWorld: *java  SimpleCylinder* ; *java  TexturedSphere*
- FourByFour: *appletviewer fbf.html*
- GearTest: *java GearBox*
- GeometryByReference
- GeometryCompression
- HelloUniverse
- Lightwave
- LOD
- ModelClip
- Morphing
- ObjLoad
- OffScreenCanvas3D
- OrientedShape3D
- PackageInfo
- PickTest
- PickText3D: *java PickText3DGeometry*
- PlatformGeometry
- PureImmediate
- ReadRaster
- Sound
- SphereMotion: *appletviewer SphereMotion.html*
- SplineAnim
- Text2D
- Text3D
- TextureByReference
- TextureTest
- TickTockCollision:  *java TickTockCollision*
- TickTockPicking
- VirtualInputDevice

For example, on a Sun Ultra 10 workstation the files for the *GearTest* example are located under the subdirectory:\_

mit/java\_v1.2ref/distrib/sun4x\_56/demo/java3d/GearTest\_

Similarly, if you download *Java® 3D* on your computer, the examples are typically stored in subdirectories in the subdirectory *demo\\java3d* of the directory where Java® has been downloaded, e.g. at *C:\\Java\\jdk1.3\\demo\\java3d*.

There are many fields in which Java® 3D can be used. The following are just a small selection of Java® 3D applications that are available on the net.

- *NCSA Astro3D*
- {{% resource_link "2c6ce32a-6e88-44a4-82f7-4d1782b11381" "*Collaborative Visualization Space Science and Engineering Center (SSEC)*" %}}
- {{% resource_link "b0ef4ae3-0e58-4838-857f-ad73866b0499" "*Java® 3D API Customer Success Stories*" %}}

{{\< anchor "4" >}}{{\< /anchor >}}4. Scene Graph Structure and Basic Java® 3D Concepts and Classes

*Scene graph: Content-View Branches*

A Java® 3D scene is created as a tree-like graph structure, which is traversed during rendering. The scene graph structure contains nodes that represent either the actual objects of the scene, or, specifications that describe how to view the objects. Usually, there are two  branches in Java® 3D, the **content branch**, which contains the nodes that describe the actual objects in the scene, and  the **view branch**, which contains nodes that specify viewing related conditions. Usually, the content branch contains much larger number of nodes than the view branch.

The following image shows a basic Java® 3D graph scene, where the content branch is located on the left and the view branch on the right side of the graph:

{{< resource uuid="cb6b58f7-abe0-910f-9d4c-1a4e758995c5" >}}

Java® 3D applications construct individual graphic components as separate objects, called nodes, and connects them together into a tree-like scene graph, in which the objects and the viewing of them can easily be manipulated. The scene graph structure contains the description of the virtual universe, which represents the entire scene. All information concerning geometric objects, their attributes, position and orientation, as well as the viewing information are all contained into the scene graph.

The above scene graph consists of superstructure components, in particular a {{% resource_link "8fdd208b-26f4-46cb-a320-3669b10b343d" "*VirtualUniverse*" %}} and a {{% resource_link "67712dbb-1d4d-41a2-ac4f-5272e68d3ad0" "*Locale*" %}} object, and a two {{% resource_link "30c2145d-ea77-4534-8d83-96b23b832f27" "*BranchGroup*" %}} objects, which are attached to the superstructure. The one branch graph, rooted at the left {{% resource_link "30c2145d-ea77-4534-8d83-96b23b832f27" "*BranchGroup*" %}} node, is a content branch, containing all the relevant to the contents of the scene objects. The other branch, known as view branch, contains all the information related to the viewing and the rendering details of the scene.

The state of a shape node, or any other leaf node, is defined, during rendering, by the nodes that lie in the direct path between that node and the root node, i.e. the {{% resource_link "8fdd208b-26f4-46cb-a320-3669b10b343d" "*VirtualUniverse*" %}}. For example, a {{% resource_link "0e297c42-7626-48dc-8f59-9ddcd24dc942" "*TransformGroup*" %}} node in a path between a leaf node and the scene's root can change the position, orientation, and scale of the object represented by the leaf node.

{{% resource_link "93240c24-4159-4544-a421-c04e7292d138" "*SceneGraphObject*" %}} Hierarchy

The Java® 3D node objects of a Java® 3D scene graph, which are instances of the {{% resource_link "c4b27802-f6c5-4e41-8e7a-190c7a0faf2e" "*Node*" %}} class, may reference node component objects, which are instances of the class NodeComponent. The {{% resource_link "c4b27802-f6c5-4e41-8e7a-190c7a0faf2e" "*Node*" %}} and {{% resource_link "d09959a1-afe7-47d5-8bce-ad84e63e2824" "*NodeComponent*" %}} classes are subclasses of the {{% resource_link "d43b003a-261a-48a2-8ff8-eb58e1142396" "*SceneGraphObject*" %}} abstract class. Almost all objects that may be included in a scene graph are instances of subclasses of the {{% resource_link "d43b003a-261a-48a2-8ff8-eb58e1142396" "*SceneGraphObject*" %}} class. A scene graph object is constructed by instantiating the corresponding class, and then, it can be accessed and manipulated using the provided set and get methods.

The following graph shows the class hierarchy of the major subclasses of the {{% resource_link "d43b003a-261a-48a2-8ff8-eb58e1142396" "*SceneGraphObject*" %}} class:

{{< resource uuid="d718435c-535c-ef73-9917-b89c8413f90f" >}}

*Class* {{% resource_link "c4b27802-f6c5-4e41-8e7a-190c7a0faf2e" "*Node*" %}} *and its subclasses*

The abstract Class {{% resource_link "c4b27802-f6c5-4e41-8e7a-190c7a0faf2e" "*Node*" %}} is the base class for almost all objects that constitute the scene graph. It has two subclasses the {{% resource_link "5e9dbefe-fcae-460c-89e1-31926eb561ec" "*Group*," %}} and {{% resource_link "80696289-fb5d-48f9-8f5b-9444fb9d3127" "*Leaf*" %}} classes, which have many useful subclasses. Class {{% resource_link "5b84cd39-a996-4bc1-8255-7fbe2da23cde" "*Group*" %}} is a superclass of, among others, the classes {{% resource_link "30c2145d-ea77-4534-8d83-96b23b832f27" "*BranchGroup*" %}} and {{% resource_link "0e297c42-7626-48dc-8f59-9ddcd24dc942" "*TransformGroup*." %}} Class {{% resource_link "80696289-fb5d-48f9-8f5b-9444fb9d3127" "*Leaf*" %}}, which is used for nodes with no children, is a superclass of, among others, the classes {{% resource_link "3400e6ea-e523-4f65-81ce-6968a6a727ec" "*Behavior*" %}}, {{% resource_link "52fe5d56-44d0-494b-a143-c07bd2526edd" "*Light*" %}}, {{% resource_link "37c626d8-4742-4b60-a1a2-27d247afc22c" "*Shape3D*" %}}, and {{% resource_link "4337e9ef-445c-4c33-b080-9e42562e555c" "*ViewPlatform*" %}}. The {{% resource_link "0de6004b-6aca-4c3c-881b-e12c3aaa2866" "*ViewPlatform*" %}} node is used to define from where the scene is viewed. In particular, it can be used to specify the location and the orientation of the point of view.

*Class* {{% resource_link "d09959a1-afe7-47d5-8bce-ad84e63e2824" "*NodeComponent*" %}} *and its subclasses*

Class {{% resource_link "d09959a1-afe7-47d5-8bce-ad84e63e2824" "*NodeComponent*" %}} is the base class for classes that represent attributes associated with the nodes of the scene graph. It is the superclass of all scene graph node component classes, such as the {{% resource_link "f9ab15c5-8f61-42f5-95b7-9c4b106556ad" "*Appearance*" %}}, {{% resource_link "839a43e7-6002-43a1-9bf6-75d5b9b306ab" "*Geometry*" %}}, {{% resource_link "41eeb086-0003-4cd9-80bc-dd8c87ff551c" "*PointAttributes*" %}}, and {{% resource_link "28d58967-29a5-459d-926c-70f8db95b2d9" "*PolygonAttributes*" %}} classes. {{% resource_link "d09959a1-afe7-47d5-8bce-ad84e63e2824" "*NodeComponent*" %}} objects are used to specify attributes for a node, such as the color and geometry of a shape node, i.e. a {{% resource_link "37c626d8-4742-4b60-a1a2-27d247afc22c" "*Shape3D*" %}} node. In particular, a {{% resource_link "37c626d8-4742-4b60-a1a2-27d247afc22c" "*Shape3D*" %}} node uses an {{% resource_link "f9ab15c5-8f61-42f5-95b7-9c4b106556ad" "*Appearance*" %}} and a {{% resource_link "839a43e7-6002-43a1-9bf6-75d5b9b306ab" "*Geometry*" %}} objects, where the {{% resource_link "f9ab15c5-8f61-42f5-95b7-9c4b106556ad" "*Appearance*" %}} object is used to control how the associated geometry should be rendered by Java® 3D.

The geometry component information of a {{% resource_link "37c626d8-4742-4b60-a1a2-27d247afc22c" "*Shape3D*" %}} node, i.e. its geometry and topology, can be specified in an instance of a subclass of the abstract {{% resource_link "839a43e7-6002-43a1-9bf6-75d5b9b306ab" "*Geometry*" %}} class. A Geometry object is used as a component object of a {{% resource_link "37c626d8-4742-4b60-a1a2-27d247afc22c" "*Shape3D*" %}} leaf node. Geometry objects consist of the following four generic geometric types. Each of these geometric types defines a visible object, or a set of objects.

- {{% resource_link "5d598d30-e22c-4913-8000-7a24298b656f" "*CompressedGeometry*" %}}
- {{% resource_link "9c7884d2-a7ae-46a3-a800-436a15e7e2df" "*GeometryArray*" %}}
- {{% resource_link "c3a5c2e2-860f-4167-9da3-35e8af0573cb" "*Raster*" %}}
- {{% resource_link "17aa8d63-6c2d-4d6a-b7d0-5cf5260d69e8" "*Text3D*" %}}

For example, the {{% resource_link "9c7884d2-a7ae-46a3-a800-436a15e7e2df" "*GeometryArray*" %}} is a subclass of the class {{% resource_link "839a43e7-6002-43a1-9bf6-75d5b9b306ab" "*Geometry*" %}}, which itself extends the {{% resource_link "d09959a1-afe7-47d5-8bce-ad84e63e2824" "*NodeComponent*" %}} class, that is extended to create the various primitive types such as lines, triangle strips and quadrilaterals.

{{< resource uuid="d404ba55-8789-1a59-f627-8f8ae65b49b3" >}}

The {{% resource_link "93908871-b407-4897-a5b6-4c370e8c08e8" "*IndexedGeometryArray*" %}} object above contains separate integer arrays that index, among others, into arrays of positional coordinates specifying how vertices are connected to form geometry primitives. This class is extended to create the various indexed primitive types, such as {{% resource_link "a4dc5e3d-919d-4bbf-908c-08fa7c101371" "*IndexedLineArray*" %}}, {{% resource_link "de365495-46c1-40b3-bd87-5401316e9fb4" "*IndexedPointArray*" %}}, and {{% resource_link "5ddb77f1-2fe7-4260-b02e-948087426b23" "*IndexedQuadArray*" %}}.

Vertex data may be passed to the geometry array either by copying the data into the array using the existing methods, which is the default mode, or by passing a reference to the data.

The methods for setting positional coordinates, colors, normals, and texture coordinates, such as the method {{% resource_link "f1a6e559-8bfd-4442-b045-25da089fa3a1" "*setCoordinates*()" %}}, copy the data into the {{% resource_link "9c7884d2-a7ae-46a3-a800-436a15e7e2df" "*GeometryArray*" %}}, which offers much flexibility in organizing the data.

Another set of methods allows data to be passed and accessed by reference, such as the {{% resource_link "3a55f719-9071-40dc-ae41-9f1b30ec50fa" "*setCoordRef3d*()" %}} method, set a reference to user-supplied data, e.g. coordinate arrays. In order to enable the passing of data by reference, the {{% resource_link "8d5fa6e9-c1c4-43ab-a20a-bac6267293e1" "*BY*\_\_REFERENCE\_" %}} bit in the {{% resource_link "24d9fd99-79fc-4c00-b83d-e25e8d0bf354" "*vertexFormat*" %}} field of the constructor for the corresponding {{% resource_link "9c7884d2-a7ae-46a3-a800-436a15e7e2df" "*GeometryArray*" %}} must be set accordingly. Data in any array that is referenced by a live or compiled {{% resource_link "9c7884d2-a7ae-46a3-a800-436a15e7e2df" "*GeometryArray*" %}} object may only be modified using the {{% resource_link "43c03e6a-9f7d-4435-9f66-0c8cc189e915" "*updateData*" %}} method assuming that the {{% resource_link "10ed0071-ca4f-4edb-9ecc-f75f9bcfb74b" "*ALLOW\_REF\_DATA\_WRITE*" %}} capability bit is set accordingly, which can be done using the {{% resource_link "1a0534af-9f5c-40d5-8488-a8bb164cb934" "*setCapability*" %}} method.

The {{% resource_link "f9ab15c5-8f61-42f5-95b7-9c4b106556ad" "*Appearance*" %}} object defines all rendering state that control the way the associated geometry should be rendered. The rendering state consists of the following:

- Point attributes: a {{% resource_link "41eeb086-0003-4cd9-80bc-dd8c87ff551c" "*PointAttributes*" %}} object defines attributes used to define points, such as the size to be used
- Line attributes: using a {{% resource_link "6838907f-0a71-4c8d-8190-a3c9f45de505" "*LineAttributes*" %}} object attributes used to define lines, such as the width and pattern, can be defined
- Polygon attributes: using a {{% resource_link "28d58967-29a5-459d-926c-70f8db95b2d9" "*PolygonAttributes*" %}} object the attributes used to define polygons, such as rasterization mode (i.e.. filled, lines, or points) are defined
- Coloring attributes: a {{% resource_link "88a0570d-6651-4792-9992-c52287abc9a2" "*ColoringAttributes*" %}} object is used to defines attributes used in color selection and shading.
- Rendering attributes: defines rendering operations, such as whether invisible objects are rendered, using a {{% resource_link "c7ebac4e-24ec-4b0d-8e7f-bf92ef31e42b" "*RenderingAttributes*" %}} object.
- Transparency attributes: a {{% resource_link "c29d5bc5-9c0e-4276-af5c-ef8daedff136" "*TransparencyAttributes*" %}} defines the attributes that affect transparency of the object
- Material: a {{% resource_link "f47e3d1d-5d64-490d-b77b-1250087bb899" "*Material*" %}} object defines the appearance of an object under illumination, such as the ambient color, specular color, diffuse color, emissive color, and shininess. It is used to control the color of the shape.
- Texture: the texture image and filtering parameters used, when texture mapping is enabled, can be defined in a {{% resource_link "98f84bb1-17f8-44b6-8aad-55a30bbe6ca7" "*Texture*" %}} object.
- Texture attributes: a {{% resource_link "1ea5aaa5-e554-4c29-b8b4-0bd42bedfebe" "*TextureAttributes*" %}} object can be used to define the attributes that apply to texture mapping, such as the texture mode, texture transform, blend color, and perspective correction mode.
- Texture coordinate generation: the attributes that apply to texture coordinate generation can be defined in a {{% resource_link "a1e052ce-3de6-46a2-add3-dc5c7080e68a" "*TexCoordGeneration*" %}} object.
- Texture unit state: array that defines texture state for each of N separate texture units allowing multiple textures to be applied to geometry. Each {{% resource_link "9b6cb0b0-0813-4fb5-a545-8a53f3f3f808" "*TextureUnitState*" %}} object contains a Texture object, TextureAttributes, and TexCoordGeneration object for one texture unit.

{{% resource_link "8fdd208b-26f4-46cb-a320-3669b10b343d" "***VirtualUniverse***" %}}

and {{% resource_link "67712dbb-1d4d-41a2-ac4f-5272e68d3ad0" "*Locale*" %}}

After constructing a subgraph, it can be attached to a {{% resource_link "eeba427b-e3e7-4458-88d5-fc290c823fd9" "*VirtualUniverse*" %}} object through a high-resolution {{% resource_link "67712dbb-1d4d-41a2-ac4f-5272e68d3ad0" "*Locale*" %}} object, which is itself attached to the virtual universe. The {{% resource_link "8fdd208b-26f4-46cb-a320-3669b10b343d" "*VirtualUniverse*" %}} is the root of all Java® 3D scenes, while {{% resource_link "67712dbb-1d4d-41a2-ac4f-5272e68d3ad0" "*Locale*" %}} objects are used for basic spatial placement. The attachment to a {{% resource_link "67712dbb-1d4d-41a2-ac4f-5272e68d3ad0" "*Locale*" %}} object makes all objects in the attached subgraph live (i.e. drawable), while removing it from the locale reverses the effect. Any node added to a live scene graph becomes live. However, in order to be able to modify a live node the corresponding {{% resource_link "1a0534af-9f5c-40d5-8488-a8bb164cb934" "*capability* bits" %}} should be set accordingly.

Typically, a Java® 3D program has only one {{% resource_link "8fdd208b-26f4-46cb-a320-3669b10b343d" "*VirtualUniverse*" %}} which consists of one, or more, {{% resource_link "67712dbb-1d4d-41a2-ac4f-5272e68d3ad0" "*Locale*" %}} objects that may contain collections of subgraphs of the scene graph that are rooted by {{% resource_link "30c2145d-ea77-4534-8d83-96b23b832f27" "*BranchGroup*" %}} nodes, i.e. a large number of  branch graphs. Although a {{% resource_link "67712dbb-1d4d-41a2-ac4f-5272e68d3ad0" "*Locale*" %}} has no explicit children, it may reference an arbitrary number of {{% resource_link "30c2145d-ea77-4534-8d83-96b23b832f27" "*BranchGroup*" %}} nodes. The subgraphs contain all the scene graph nodes that exist in the universe. A {{% resource_link "69682cd8-fb3e-4ea2-8526-f036a3b6d62c" "*Locale*" %}} node is used to accurately position a branch graph in a universe specifying a location within the virtual universe using high-resolution coordinates ({{% resource_link "8c550c3e-7c65-4443-b390-e6bf0407361f" "*HiResCoord*" %}}), which represent 768 bits of floating point values. A {{% resource_link "67712dbb-1d4d-41a2-ac4f-5272e68d3ad0" "*Locale*" %}} is positioned in a single {{% resource_link "8fdd208b-26f4-46cb-a320-3669b10b343d" "*VirtualUniverse*" %}} node using one of its constructors.

The {{% resource_link "8fdd208b-26f4-46cb-a320-3669b10b343d" "*VirtualUniverse*" %}} and {{% resource_link "67712dbb-1d4d-41a2-ac4f-5272e68d3ad0" "*Locale*" %}} classes, as well as the {{% resource_link "a0407526-1e84-4863-8741-46fb41709f0b" "*View*" %}} class, are subclasses of the basic superclass {{% resource_link "c70e881a-6d6f-4406-a6fb-56d8705eae02" "***Object***" %}}, as shown below:

{{< resource uuid="e45316c9-a420-f0b0-66d3-544026497bcd" >}}

 

Branch Graphs

A branch graph is a scene graph rooted in a {{% resource_link "30c2145d-ea77-4534-8d83-96b23b832f27" "*BranchGroup*" %}} node and can be used to point to the root of a scene graph branch. A graph branch can be added to the list of branch graphs of a {{% resource_link "67712dbb-1d4d-41a2-ac4f-5272e68d3ad0" "*Locale*" %}} node using its {{% resource_link "97ab5723-24d8-4596-867d-07bc8ef8a905" "*addBranchGraph*(*BranchGroup* bg)" %}} method. {{% resource_link "30c2145d-ea77-4534-8d83-96b23b832f27" "*BranchGroup*" %}} objects are the only objects that can be inserted into a {{% resource_link "67712dbb-1d4d-41a2-ac4f-5272e68d3ad0" "*Locale*" %}}*'s* list of objects.

A {{% resource_link "30c2145d-ea77-4534-8d83-96b23b832f27" "*BranchGroup*" %}} may be compiled by calling its compile method, which causes the entire subgraph to be compiled including any {{% resource_link "30c2145d-ea77-4534-8d83-96b23b832f27" "*BranchGroup*" %}} nodes that may be contained within the subgraph. A graph branch, rooted by a  {{% resource_link "30c2145d-ea77-4534-8d83-96b23b832f27" "*BranchGroup*" %}} *node,* becomes live when inserted into a virtual universe by attaching it to a {{% resource_link "67712dbb-1d4d-41a2-ac4f-5272e68d3ad0" "*Locale*" %}}. However, if a {{% resource_link "30c2145d-ea77-4534-8d83-96b23b832f27" "*BranchGroup*" %}} is contained in another subgraph as a child of some other group node, it may not be attached to a {{% resource_link "67712dbb-1d4d-41a2-ac4f-5272e68d3ad0" "*Locale*" %}} node.

Capability Bits, Making Live and Compiling

Certain optimizations can be done to achieve better performance by compiling a subgraph into an optimized internal format, prior to its attachment to a virtual universe. However, many *set* and *get* methods of objects that are part of a live or compiled scene graph cannot be accessed. In general, the *set* and *get* methods can be used only during the creation of a scene graph, except where explicitly allowed, in order to allow certain optimizations during rendering. The set and get methods that can be used when the object is live or compiled should be specified using a set of capability bits, which by default are disabled, prior to compiling or making live the object. The methods {{% resource_link "539f8854-5f49-470e-97e1-48f1a688c429" "*isCompiled()*" %}} and {{% resource_link "e0e3aff5-ad0f-41e3-8acd-711380d0f236" "*isLive()*" %}} can be used to find out whether a scene graph object is compiled or live. The methods {{% resource_link "1a0534af-9f5c-40d5-8488-a8bb164cb934" "*setCapability*()" %}} and {{% resource_link "054d90db-9faf-4357-9752-51a04316229a" "*getCapability*()" %}} can be used to set properly the capability bits to allow access to the object's methods. However, the less the capability bits that are enabled, the more optimizations can be performed during rendering.

Viewing Branch: {{% resource_link "0de6004b-6aca-4c3c-881b-e12c3aaa2866" "*ViewPlatform*" %}}*,*  {{% resource_link "a0407526-1e84-4863-8741-46fb41709f0b" "*View*" %}}*,* {{% resource_link "e8930041-68e2-4dac-95ef-1e72c7873794" "*Screen3D*" %}}

The view branch has usually the following structure, consisting of nodes that control the viewing of the scene.

{{< resource uuid="be7231df-1539-a99c-6e1a-611c255912f1" >}}

The view branch contains some scene graph viewing objects that can be used to define the viewing parameters and details, such as the {{% resource_link "0de6004b-6aca-4c3c-881b-e12c3aaa2866" "*ViewPlatform*" %}}, {{% resource_link "a0407526-1e84-4863-8741-46fb41709f0b" "*View*" %}}, {{% resource_link "e8930041-68e2-4dac-95ef-1e72c7873794" "*Screen3D*" %}}, {{% resource_link "a3845c7a-3fc9-4a2b-80ee-229d1b0b805d" "*PhysicalBody*" %}}, and {{% resource_link "f89f4f7a-3c89-4512-87bc-d3859315f573" "*PhysicalEnvironment*" %}} classes.

Java® 3D uses a viewing model that can be used to transform the position and direction of the viewing while the content branch remains unmodified. This is achieved with the use of the {{% resource_link "0de6004b-6aca-4c3c-881b-e12c3aaa2866" "*ViewPlatform*" %}} and the {{% resource_link "a0407526-1e84-4863-8741-46fb41709f0b" "*View*" %}} classes, to specify from where and how, respectively, the scene is being viewed.

The {{% resource_link "0de6004b-6aca-4c3c-881b-e12c3aaa2866" "*ViewPlatform*" %}} node controls the position, orientation and scale of the viewer. A viewer can navigate through the virtual universe by changing the transformation in the scene graph hierarchy above the {{% resource_link "0de6004b-6aca-4c3c-881b-e12c3aaa2866" "*ViewPlatform*" %}} node. The location of the viewer can be set using a {{% resource_link "0e297c42-7626-48dc-8f59-9ddcd24dc942" "*TransformGroup*" %}} node above the {{% resource_link "0de6004b-6aca-4c3c-881b-e12c3aaa2866" "*ViewPlatform*" %}} node. The {{% resource_link "0de6004b-6aca-4c3c-881b-e12c3aaa2866" "*ViewPlatform*" %}} node has an activation radius that is used together with the bounding volumes of {{% resource_link "3400e6ea-e523-4f65-81ce-6968a6a727ec" "*Behavior*" %}}, {{% resource_link "65783ce0-b947-4f10-85f5-6ed1e822e355" "*Background*" %}} and other nodes in order to determine whether the latter nodes should be scheduled, or turned on, respectively. The method {{% resource_link "83b3c0de-e93b-4b75-9a4b-a0b9c3c070ee" "*setActivationRadius*()" %}} can be used to set the activation radius.

A {{% resource_link "a0407526-1e84-4863-8741-46fb41709f0b" "*View*" %}} object connects to the {{% resource_link "0de6004b-6aca-4c3c-881b-e12c3aaa2866" "*ViewPlatform*" %}} node in the scene graph, and specifies all viewing parameters of the rendering process of a 3D scene. Although it exists outside of the scene graph, it attaches to a {{% resource_link "0de6004b-6aca-4c3c-881b-e12c3aaa2866" "*ViewPlatform*" %}} leaf node in the scene graph, using the method {{% resource_link "e1dcd4f6-a6dd-47ed-a046-725a871e98e0" "*attachViewPlatform*(*ViewPlatform* vp)" %}}. A {{% resource_link "a0407526-1e84-4863-8741-46fb41709f0b" "*View*" %}} object contains references to a {{% resource_link "a3845c7a-3fc9-4a2b-80ee-229d1b0b805d" "*PhysicalBody*" %}} and a {{% resource_link "f89f4f7a-3c89-4512-87bc-d3859315f573" "*PhysicalEnvironment*" %}} object, which can be set using the methods {{% resource_link "42fe8362-e190-4931-b6ea-2c2eea6953ca" "*setPhysicalBody*()" %}} and {{% resource_link "951f3f35-1062-4fed-b83c-2d24548f0f64" "*setPhysicalEnvironment*()" %}}*, respectively*.

A {{% resource_link "a0407526-1e84-4863-8741-46fb41709f0b" "*View*" %}} object contains a list of {{% resource_link "ce7c7bd2-176a-4f33-9717-dd6bfa2b8eab" "*Canvas3D*" %}} objects where rendering of the view is done. The method {{% resource_link "c9767af7-46b1-46dd-b493-a4d4e936ca39" "*addCanvas3D*(Canvas3D c)" %}} of the class {{% resource_link "a0407526-1e84-4863-8741-46fb41709f0b" "*View*" %}} can be used to add the provided {{% resource_link "ce7c7bd2-176a-4f33-9717-dd6bfa2b8eab" "*Canvas3D*" %}} object to the list of canvases of the {{% resource_link "a0407526-1e84-4863-8741-46fb41709f0b" "View" %}} object.

{{< resource uuid="962db16a-d746-33a5-7a2a-a1311a65fb65" >}}

Class {{% resource_link "2d26c87a-37d4-454f-9fc1-83bbbd16cb20" "*Canvas3D*" %}} extends the heavyweight class {{% resource_link "2b10426e-0cf6-4f8c-a7d4-2456f4d5dadc" "*Canvas*" %}} in order to achieve hardware acceleration, since a low rendering library, such as OpenGL, requires the rendering to be done in a native window to enable hardware acceleration.

Finally, all {{% resource_link "2d26c87a-37d4-454f-9fc1-83bbbd16cb20" "*Canvas3D*" %}} objects on the same physical display device refer to a {{% resource_link "e8930041-68e2-4dac-95ef-1e72c7873794" "*Screen3D*" %}} object, which contains all information about that particular display device. {{% resource_link "e8930041-68e2-4dac-95ef-1e72c7873794" "*Screen3D*" %}} can be obtained from the {{% resource_link "2d26c87a-37d4-454f-9fc1-83bbbd16cb20" "*Canvas3D*" %}} using the {{% resource_link "04d2008e-cbf4-446a-93c4-d3d81d1dedda" "*getScreen3D*()" %}} method.

Default Coordinate System

The default coordinate system is a right-handed Cartesian coordinate system centered on the screen with the x and y-axes directed towards the right and top of the screen, respectively. The z-axis is, by default directed out of the screen towards the viewer, as shown below. The default distances are in meter and the angles in radians.        
 

{{< resource uuid="b4b7e83d-b897-f4fe-b33f-16f275d7751d" >}}

Transformations

Class {{% resource_link "0e297c42-7626-48dc-8f59-9ddcd24dc942" "*TransformGroup*" %}} which extends the class {{% resource_link "5e9dbefe-fcae-460c-89e1-31926eb561ec" "*Group*" %}} can be used to set a spatial transformation, such as positioning, orientation, and scaling of its children through the use of a {{% resource_link "ca08d8d3-e80f-44aa-b375-cd553a298acc" "*Transform3D*" %}} object. A {{% resource_link "0e297c42-7626-48dc-8f59-9ddcd24dc942" "*TransformGroup*" %}} node enables the setting and use of a coordinate system relative to its parent coordinate system.

The {{% resource_link "ca08d8d3-e80f-44aa-b375-cd553a298acc" "*Transform3D*" %}} object of a {{% resource_link "0e297c42-7626-48dc-8f59-9ddcd24dc942" "*TransformGroup*" %}} object can be set using the method {{% resource_link "e8f43853-e942-492c-ac1f-b52d2ebfe84f" "*setTransform*(Transform3D  t)" %}}, which is used to set the transformation components of the {{% resource_link "ca08d8d3-e80f-44aa-b375-cd553a298acc" "*Transform3D*" %}} object to the ones of the passed parameter.

A {{% resource_link "ca08d8d3-e80f-44aa-b375-cd553a298acc" "*Transform3D*" %}} object is a 4x4 double-precision matrix that is used to determine the transformations of a {{% resource_link "0e297c42-7626-48dc-8f59-9ddcd24dc942" "*TransformGroup*" %}} node, as shown in the following equation. The elements T{{\< sub "00" >}}, T{{\< sub "01" >}}, T{{\< sub "02" >}}, T{{\< sub "10" >}}, T{{\< sub "11" >}}, T{{\< sub "12" >}},T{{\< sub "20" >}}, T{{\< sub "21" >}}, and T{{\< sub "22" >}} are used to set the rotation and scaling, and the T{{\< sub "03" >}}, T{{\< sub "13" >}}, and T{{\< sub "23" >}} are used to set the translation.

{{< resource uuid="339b4938-a492-82c1-5254-af6bded234ec" >}}

As the scene graph is traversed by the Java® 3D renderer, the transformations specified by any transformation nodes accumulate. The transformations closer to the geometry nodes executed prior to the ones closer to the virtual universe node.

{{\< anchor "5" >}}{{\< /anchor >}}5. A Simple Java® 3D Program

A Java® 3D program builds a scene graph, using Java® 3D classes and methods, that can be rendered onto the screen.

The following program creates 2 color cubes and a sphere as shown to the snapshot that follows the code.

*import java.awt.\*;*        
*import javax.swing.\*;*        
*import javax.media.j3d.\*;*        
*import javax.vecmath.\*;*        
*import java.awt.event.\*;*        
*import com.sun.j3d.utils.geometry.\*;*

*public class MyJava3D extends JFrame*        
*{*        
*//  Virtual Universe object.*        
*private VirtualUniverse universe;*

*//  Locale of the scene graph.*        
*private Locale locale;*        
 

*// BranchGroup for the Content Branch of the scene*        
*private BranchGroup contentBranch;*

*//  TransformGroup  node of the scene contents*        
*private TransformGroup contentsTransGr;*        
 

*// BranchGroup for the View Branch of the scene*        
*private BranchGroup viewBranch;*

*// ViewPlatform node, defines from where the scene is viewed.*        
*private ViewPlatform viewPlatform;*

*//  Transform group for the ViewPlatform node*        
*private TransformGroup vpTransGr;*

*//  View node, defines the View parameters.*        
*private View view;*

*// A PhysicalBody object can specify the user's head*        
*PhysicalBody body;*

*// A PhysicalEnvironment object can specify the physical*        
*// environment in which the view will be generated*        
*PhysicalEnvironment environment;*

*// Drawing canvas for 3D rendering*        
*private Canvas3D canvas;*

*// Screen3D Object contains screen's information*        
*private Screen3D screen;*

*private Bounds bounds;*        
 

*public MyJava3D()*        
*{*        
*super("My First Java3D Example");*

*// Creating and setting the Canvas3D*        
*canvas = new Canvas3D(null);*        
*getContentPane().setLayout( new BorderLayout( ) );*        
*getContentPane().add(canvas, "Center");*

*// Setting the VirtualUniverse and the Locale nodes*        
*setUniverse();*

*// Setting the content branch*        
*setContent();*

*// Setting the view branch*        
*setViewing();*

*// To avoid problems between Java3D and Swing*        
*JPopupMenu.setDefaultLightWeightPopupEnabled(false);*

*// enabling window closing*        
*addWindowListener(new WindowAdapter() {*        
*public void windowClosing(WindowEvent e)*        
*{System.exit(0); }   });*        
*setSize(600, 600);*        
*bounds = new BoundingSphere(new Point3d(0.0,0.0,0.0), Double.MAX\_VALUE);*        
*}*        
 

*private void setUniverse()*        
*{*        
*// Creating the VirtualUniverse and the Locale nodes*        
*universe = new VirtualUniverse();*        
*locale = new Locale(universe);*        
*}*

*private void setContent()*        
*{*        
*// Creating the content branch*

*contentsTransGr = new TransformGroup();*        
*contentsTransGr.setCapability(TransformGroup.ALLOW\_TRANSFORM\_WRITE);*

*setLighting();*

*ColorCube cube1 = new ColorCube(0.1);*

*Appearance appearance = new Appearance();*        
*cube1.setAppearance(appearance);*

*contentsTransGr.addChild(cube1);*        
 

*ColorCube cube2 = new ColorCube(0.25);*

*Transform3D t1 = new Transform3D();*        
*t1.rotZ(0.5);*        
*Transform3D t2 = new Transform3D();*        
*t2.set(new Vector3f(0.7f, 0.6f,-1.0f));*        
*t2.mul(t1);*        
*TransformGroup trans2 = new TransformGroup(t2);*        
*trans2.addChild(cube2);*        
*contentsTransGr.addChild(trans2);*        
 

*Sphere sphere = new Sphere(0.2f);*        
*Transform3D t3 = new Transform3D();*        
*t3.set(new Vector3f(-0.2f, 0.5f,-0.2f));*        
*TransformGroup trans3 = new TransformGroup(t3);*

*Appearance appearance3 = new Appearance();*

*Material mat = new Material();*        
*mat.setEmissiveColor(-0.2f, 1.5f, 0.1f);*        
*mat.setShininess(5.0f);*        
*appearance3.setMaterial(mat);*        
*sphere.setAppearance(appearance3);*        
*trans3.addChild(sphere);*        
*contentsTransGr.addChild(trans3);*        
 

*contentBranch = new BranchGroup();*        
*contentBranch.addChild(contentsTransGr);*        
*// Compiling the branch graph before making it live*        
*contentBranch .compile();*

*// Adding a branch graph into a locale makes its nodes live (drawable)*        
*locale.addBranchGraph(contentBranch);*        
*}*

*private void setLighting()*        
*{*        
*AmbientLight ambientLight =  new AmbientLight();*        
*ambientLight.setEnable(true);*        
*ambientLight.setColor(new Color3f(0.10f, 0.1f, 1.0f) );*        
*ambientLight.setCapability(AmbientLight.ALLOW\_STATE\_READ);*        
*ambientLight.setCapability(AmbientLight.ALLOW\_STATE\_WRITE);*        
*ambientLight.setInfluencingBounds(bounds);*        
*contentsTransGr.addChild(ambientLight);*

*DirectionalLight dirLight =  new DirectionalLight();*        
*dirLight.setEnable(true);*        
*dirLight.setColor( new Color3f( 1.0f, 0.0f, 0.0f ) );*        
*dirLight.setDirection( new Vector3f( 1.0f, -0.5f, -0.5f ) );*        
*dirLight.setCapability( AmbientLight.ALLOW\_STATE\_WRITE );*        
*dirLight.setInfluencingBounds(bounds);*        
*contentsTransGr.addChild(dirLight);*        
*}*

*private void setViewing()*        
*{*        
*// Creating the viewing branch*

*viewBranch = new BranchGroup();*

*// Setting the viewPlatform*        
*viewPlatform = new ViewPlatform();*        
*viewPlatform.setActivationRadius(Float.MAX\_VALUE);*        
*viewPlatform.setBounds(bounds);*

*Transform3D t = new Transform3D();*        
*t.set(new Vector3f(0.3f, 0.7f, 3.0f));*        
*vpTransGr = new TransformGroup(t);*

*// Node capabilities control (granding permission) read and write access*        
*//  after a node is live or compiled*        
*//  The number of capabilities small to allow more optimizations during compilation*        
*vpTransGr.setCapability(TransformGroup.ALLOW\_TRANSFORM\_WRITE);*        
*vpTransGr.setCapability( TransformGroup.ALLOW\_TRANSFORM\_READ);*

*vpTransGr.addChild(viewPlatform);*        
*viewBranch.addChild(vpTransGr);*

*// Setting the view*        
*view = new View();*        
*view.setProjectionPolicy(View.PERSPECTIVE\_PROJECTION );*        
*view.addCanvas3D(canvas);*

*body = new PhysicalBody();*        
*view.setPhysicalBody(body);*        
*environment = new PhysicalEnvironment();*        
*view.setPhysicalEnvironment(environment);*

*view.attachViewPlatform(viewPlatform);*

*view.setWindowResizePolicy(View.PHYSICAL\_WORLD);*

*locale.addBranchGraph(viewBranch);*        
*}*

*public static void main(String\[\] args)*        
*{*        
*JFrame frame = new MyJava3D();*        
*frame.setVisible(true);*

*}*        
*}*

{{< resource uuid="6b5587cd-656d-0bd0-fb79-7b5e50916d6c" >}}

 

A utility class, called *SimpleUniverse*, can alternatively be used to automatically build a common arrangement of a universe, locale, and viewing classes, avoiding the need to create explicitly the viewing branch. Then, a branch is added into the simple universe to make its nodes live (i.e. drawable).

*SimpleUniverse simpleUniverse = new SimpleUniverse(canvas);*        
*simpleUniverse.addBranchGraph(contentBranch);*

6\. More on Java® 3D

*Java® 3D and Swing*

Since the {{% resource_link "2d26c87a-37d4-454f-9fc1-83bbbd16cb20" "*Canvas3D*" %}} extends the heavyweight AWT class *Canvas*, it should be handled with care if Swing is used. The information provided when {{% resource_link "8cd3fe1e-8592-40bf-a69c-14593db97d01" "*mixing AWT and Swing*" %}} components should be followed. The main problem is that there is one-to-one correspondence between heavyweight components and their window system peers, i.e. native OS window components. In contrast, a lightweight component expects to use the peer of its enclosing container since it does not have a peer.

When lightweight components overlap with heavyweight components, the heavyweight components are always painted on top. In general, the heavyweight {{% resource_link "2d26c87a-37d4-454f-9fc1-83bbbd16cb20" "*Canvas3D*" %}} of Java® 3D should be kept apart from lightweight Swing components using different containers to avoid problems.

To avoid heavyweight components overlapping *Swing* popup menus, which are lightweight, the popup menus  can be forced to be heavyweight using the method *setLightWeightPopupEnabled()* of the *JPopupMenu* class.

Similarly, problems with tooltips can be avoided by invoking the following method

*ToolTipManager.sharedInstance().setLightWeightPopupEnabled(false)*

Behaviors

Behaviors are essentially Java® methods that are scheduled to run only when certain requirements are satisfied according to wakeup conditions. Although a {{% resource_link "3400e6ea-e523-4f65-81ce-6968a6a727ec" "*Behavior*" %}} object is connected to the scene it is kept in a separate area of the Java® 3D runtime environment and it is not considered part of the scene graph. The runtime environment treats a {{% resource_link "3400e6ea-e523-4f65-81ce-6968a6a727ec" "*Behavior*" %}} object differently ensuring that certain actions take place. All behaviors in Java® 3D extend the {{% resource_link "3400e6ea-e523-4f65-81ce-6968a6a727ec" "*Behavior*" %}} class, which is an abstract class that itself extends the {{% resource_link "80696289-fb5d-48f9-8f5b-9444fb9d3127" "*Leaf*" %}} class. The {{% resource_link "3400e6ea-e523-4f65-81ce-6968a6a727ec" "*Behavior*" %}} class provides a way to execute certain statements, provided in the {{% resource_link "73b50d82-a0f0-4764-bc4c-f593327d6586" "*processStimulus()*" %}} method, in order to modify the scene graph when specified criteria are satisfied.

The {{% resource_link "3400e6ea-e523-4f65-81ce-6968a6a727ec" "*Behavior*" %}} class has two major methods, in particular the {{% resource_link "5fd54b82-5c31-43f8-8d02-8ad22d1de16a" "*initialize()*" %}} method, which is called when the behavior becomes live, and the {{% resource_link "73b50d82-a0f0-4764-bc4c-f593327d6586" "*processStimulus()*" %}} method, which is called by the Java® 3D scheduler whenever appropriate,  and  a scheduling region. Typically, in order to create a custom behavior, the class {{% resource_link "3400e6ea-e523-4f65-81ce-6968a6a727ec" "*Behavior*" %}} is extended and referenced by the scene graph from an appropriate place that should be able to effect. A custom behavior that extends the {{% resource_link "3400e6ea-e523-4f65-81ce-6968a6a727ec" "*Behavior*" %}} class should implement the {{% resource_link "5fd54b82-5c31-43f8-8d02-8ad22d1de16a" "*initialize()*" %}} and {{% resource_link "73b50d82-a0f0-4764-bc4c-f593327d6586" "*processStimulus()*" %}} methods, and provide other methods and constructors that may be needed. The {{% resource_link "3400e6ea-e523-4f65-81ce-6968a6a727ec" "*Behavior*" %}} class object contains the state information that is needed by its {{% resource_link "5fd54b82-5c31-43f8-8d02-8ad22d1de16a" "*initialize()*" %}}and the {{% resource_link "73b50d82-a0f0-4764-bc4c-f593327d6586" "*processStimulus()*" %}} methods. A constructor or another method may be used to set references to the scene graph objects upon which the behavior acts. In addition, the {{% resource_link "3400e6ea-e523-4f65-81ce-6968a6a727ec" "*Behavior*" %}} class is extended by the following three classes {{% resource_link "71896bfd-7bba-42ff-ae44-d80a120cfb2d" "*Billboard*" %}}, {{% resource_link "22fa17cb-daaf-4bfa-9705-031e74fa4307" "*Interpolator*" %}}, and {{% resource_link "ecb6efe2-23f9-4a3e-bd64-9992701d05a6" "*LOD*" %}}.

The {{% resource_link "5fd54b82-5c31-43f8-8d02-8ad22d1de16a" "*initialize()*" %}} method is called once when the behavior becomes "live", i.e. when its {{% resource_link "30c2145d-ea77-4534-8d83-96b23b832f27" "*BranchGroup*" %}} node is added to a {{% resource_link "8fdd208b-26f4-46cb-a320-3669b10b343d" "*VirtualUniverse*" %}}, to initialize this behavior. The Java® 3D behavior scheduler calls the {{% resource_link "5fd54b82-5c31-43f8-8d02-8ad22d1de16a" "*initialize()*" %}} method, which should never be called directly. The {{% resource_link "5fd54b82-5c31-43f8-8d02-8ad22d1de16a" "*initialize()*" %}} method is used to set a {{% resource_link "3400e6ea-e523-4f65-81ce-6968a6a727ec" "*Behavior*" %}} object, which has been "added" to the scene graph, into a "known" condition and register the criteria to be used to decide on its execution. Classes that extend Behavior must provide their own {{% resource_link "5fd54b82-5c31-43f8-8d02-8ad22d1de16a" "*initialize()*" %}} method. The {{% resource_link "5fd54b82-5c31-43f8-8d02-8ad22d1de16a" "*initialize()*" %}} method allows a {{% resource_link "3400e6ea-e523-4f65-81ce-6968a6a727ec" "*Behavior*" %}} object to initialize its internal state and specify its initial wakeup conditions. Java® 3D automatically invokes a behavior's initialize code when a {{% resource_link "30c2145d-ea77-4534-8d83-96b23b832f27" "*BranchGroup*" %}} node that contains the behavior is added to the virtual universe, i.e. becomes live. The {{% resource_link "5fd54b82-5c31-43f8-8d02-8ad22d1de16a" "*initialize()*" %}} method should return, since Java® 3D does not invoke the initialize method in a new thread, and therefore it must regain control. Finally, a wakeup condition must be set in order to be able to invoke the {{% resource_link "73b50d82-a0f0-4764-bc4c-f593327d6586" "*processStimulus()*" %}} method of the behavior.

However, a {{% resource_link "3400e6ea-e523-4f65-81ce-6968a6a727ec" "*Behavior*" %}} object is considered active only when its scheduling bounds intersect the activation volume of a {{% resource_link "0de6004b-6aca-4c3c-881b-e12c3aaa2866" "*ViewPlatform*" %}} node. Therefore, the scheduling bounds should be provided for a behavior in order to be able to receive stimuli. The scheduling bounds of a behavior can be specified as a bounded spatial volume, such as a sphere, using the method {{% resource_link "f179282f-e10c-4c4f-9e14-a8e9518b94eb" "*setSchedulingBounds(Bounds region)*" %}}. Bounds are used for selective scheduling to improve performance. Bounds are used to decide whether a behavior should be added to the list of scheduled behaviors.

The {{% resource_link "73b50d82-a0f0-4764-bc4c-f593327d6586" "*processStimulus()*" %}} method is called whenever the wakeup criteria are satisfied and the ViewPlatform's activation region intersect with the Behavior's scheduling region. The method is called by the Java® 3D behavior scheduler when something happens that causes the behavior to execute. A stimulus, i.e. a notification, informs the behavior that it should execute its {{% resource_link "73b50d82-a0f0-4764-bc4c-f593327d6586" "*processStimulus()*" %}} method. Therefore, applications should not call explicitly this method. Classes that extend the {{% resource_link "3400e6ea-e523-4f65-81ce-6968a6a727ec" "*Behavior*" %}} class must provide their own  {{% resource_link "73b50d82-a0f0-4764-bc4c-f593327d6586" "*processStimulus()*" %}} method. The scheduling region defines a spatial volume that serves to enable the scheduling of {{% resource_link "3400e6ea-e523-4f65-81ce-6968a6a727ec" "*Behavior*" %}} nodes. A {{% resource_link "3400e6ea-e523-4f65-81ce-6968a6a727ec" "*Behavior*" %}} node is active, i.e. it can receive stimuli, whenever its scheduling region intersects the activation volume of a {{% resource_link "0de6004b-6aca-4c3c-881b-e12c3aaa2866" "*ViewPlatform*" %}}.

The Java® 3D behavior scheduler invokes the {{% resource_link "73b50d82-a0f0-4764-bc4c-f593327d6586" "*processStimulus()*" %}} method of a Behavior node when its scheduling region intersects the  activation volume of a {{% resource_link "0de6004b-6aca-4c3c-881b-e12c3aaa2866" "*ViewPlatform*" %}} node and all wakeup criteria  of that behavior are satisfied. Then, the statements in the {{% resource_link "73b50d82-a0f0-4764-bc4c-f593327d6586" "*processStimulus()*" %}} method may perform any computations and actions, such as including the registration of state change information that could cause Java® 3D to wake other Behavior objects and modify node values within the scene graph, change the internal state of the behavior, specify its next wakeup conditions, and exit. It is allowed to a {{% resource_link "3400e6ea-e523-4f65-81ce-6968a6a727ec" "*Behavior*" %}} object to change its next trigger event. The {{% resource_link "73b50d82-a0f0-4764-bc4c-f593327d6586" "*processStimulus()*" %}} method, typically, manipulates scene graph elements, as long as the associated capabilities bits are set accordingly. For example, a {{% resource_link "3400e6ea-e523-4f65-81ce-6968a6a727ec" "*Behavior*" %}} node can be used to repeatedly modify a {{% resource_link "0e297c42-7626-48dc-8f59-9ddcd24dc942" "*TransformGroup*" %}} node in order to animate the associated with the {{% resource_link "0e297c42-7626-48dc-8f59-9ddcd24dc942" "*TransformGroup*" %}} node objects.

The amount of work done in a {{% resource_link "49f66c03-aa0a-4e96-ae97-17862c5fdf7e" "*processStimulus()*" %}} method should be limited since the method may lower the frame rate of the renderer. Java® 3D assumes that {{% resource_link "3400e6ea-e523-4f65-81ce-6968a6a727ec" "*Behavior*" %}} methods run to completion and if necessary they spawn threads.

The application must provide the {{% resource_link "3400e6ea-e523-4f65-81ce-6968a6a727ec" "*Behavior*" %}} object with references to those scene graph elements that the Behavior object will manipulate. This is achieved by providing those references as arguments to the constructor of the behavior when the {{% resource_link "3400e6ea-e523-4f65-81ce-6968a6a727ec" "*Behavior*" %}} object is created. Alternatively, the Behavior object itself can obtain access to the relevant scene graph elements either when Java® 3D invokes its {{% resource_link "5fd54b82-5c31-43f8-8d02-8ad22d1de16a" "*initialize()*" %}} method or each time Java® 3D invokes its {{% resource_link "73b50d82-a0f0-4764-bc4c-f593327d6586" "*processStimulus()*" %}} method. Typically, the application provides references to the scene graph objects that a behavior should be able to access as arguments to its constructor when the {{% resource_link "3400e6ea-e523-4f65-81ce-6968a6a727ec" "*Behavior*" %}} is instantiated.

Java® 3D assumes that {{% resource_link "3400e6ea-e523-4f65-81ce-6968a6a727ec" "*Behavior*" %}} methods always run to completion and that if needed they can spawn threads. The structure of each {{% resource_link "3400e6ea-e523-4f65-81ce-6968a6a727ec" "*Behavior*" %}} method consists of the following parts:

- code to decode and extract references from the {{% resource_link "9548a435-9aac-453e-8ef6-7f3c93c749ad" "*WakeupCondition*" %}} enumeration that awoke the object
- code to perform the manipulations associated with the {{% resource_link "9548a435-9aac-453e-8ef6-7f3c93c749ad" "*WakeupCondition*" %}}
- code to establish new {{% resource_link "9548a435-9aac-453e-8ef6-7f3c93c749ad" "*WakeupCondition*" %}} for this behavior
- a path to exit, so that execution returns to the Java® 3D behavior scheduler

The {{% resource_link "9548a435-9aac-453e-8ef6-7f3c93c749ad" "*WakeupCondition*" %}} class is an abstract class that specifies a single wakeup condition. It is specialized to 14 different {{% resource_link "6de1b858-30ac-4923-ad29-91ab3b600be6" "*WakeupCriterion*" %}} subclasses and to 4 subclasses that can be used to create complex wakeup conditions using boolean logic combinations of individual  {{% resource_link "6de1b858-30ac-4923-ad29-91ab3b600be6" "*WakeupCriterion*" %}} objects. A Behavior node provides a {{% resource_link "9548a435-9aac-453e-8ef6-7f3c93c749ad" "*WakeupCondition*" %}} object to the Java® 3D behavior scheduler using its {{% resource_link "e686ea5a-f7b3-4dd8-aeae-2169254ff875" "*wakeupOn()*" %}} method. When that {{% resource_link "9548a435-9aac-453e-8ef6-7f3c93c749ad" "*WakeupCondition*" %}} is satisfied, while the scheduling region intersects the activation volume of a {{% resource_link "0de6004b-6aca-4c3c-881b-e12c3aaa2866" "*ViewPlatform*" %}} node, the behavior scheduler passes that same {{% resource_link "9548a435-9aac-453e-8ef6-7f3c93c749ad" "*WakeupCondition*" %}} back to the {{% resource_link "3400e6ea-e523-4f65-81ce-6968a6a727ec" "*Behavior*" %}} via an enumeration.

Java® 3D provides the following wakeup criteria that {{% resource_link "3400e6ea-e523-4f65-81ce-6968a6a727ec" "*Behavior*" %}} objects can use to specify a complex {{% resource_link "9548a435-9aac-453e-8ef6-7f3c93c749ad" "*WakeupCondition*" %}}. All of the following are subclasses of the {{% resource_link "6de1b858-30ac-4923-ad29-91ab3b600be6" "*WakeupCriterion*" %}} class, which itself is a subclass of the {{% resource_link "9548a435-9aac-453e-8ef6-7f3c93c749ad" "*WakeupCondition*" %}} class.

- {{% resource_link "a57845e1-6795-45a6-81e5-b249d1d683da" "*WakeupOnViewPlatformEntry:*" %}} when the center of a ViewPlatform enters a specified region
- {{% resource_link "42009572-d4be-4350-a45f-bb5414e54adf" "*WakeupOnViewPlatformExit:*" %}} when the center of a ViewPlatform exits a specified region
- {{% resource_link "4ff40fa7-ba2b-4c20-8180-498428c56b95" "*WakeupOnActivation*" %}}: when a behavior is activated
- {{% resource_link "20e27c40-5a0c-487a-94be-51ba0b3ab5b5" "*WakeupOnDeactivation*" %}}: when a behavior is deactivated
- {{% resource_link "91e34895-6890-4754-a8a6-11515bffea72" "*WakeupOnTransformChange*:" %}} when a specified TransformGroup node's transform changes
- {{% resource_link "e826751e-4822-4f3d-9977-c1f1fb94d229" "*WakeupOnCollisionEntry*" %}}: when collision is detected between a specified Shape3D node's Geometry object and any other object
- {{% resource_link "b6eda561-4781-43ab-a56d-dd2ea3e8c46e" "*WakeupOnCollisionMovement*" %}}: when movement occurs between a specified Shape3D node's Geometry object and any other object with which it collides
- {{% resource_link "b58c99cb-3f1b-4a63-ad79-cd12a27521b5" "*WakeupOnCollisionExit*" %}}: when a specified Shape3D node's Geometry object no longer collides with any other object
- {{% resource_link "93977eb1-c05d-4c16-9656-4214b6e66faa" "*WakeupOnBehaviorPost*" %}}: when a specified Behavior object posts a specific event
- {{% resource_link "ce0cd9d4-6f12-4874-8d0c-50c7f1851d01" "*WakeupOnAWTEvent*" %}}*:* when a specified AWT event occurs, such as. a mouse press
- {{% resource_link "883e9c01-f7df-432b-8c2a-cebaa3254085" "*WakeupOnElapsedTime*" %}}: when a specified time interval elapses
- {{% resource_link "a12ddf0b-4881-464c-a80a-fef20abba887" "*WakeupOnElapsedFrames:*" %}} when a specified number of frames have been drawn
- {{% resource_link "d35d75fb-1406-445c-9558-c340ddf7b9e5" "*WakeupOnSensorEntry:*" %}} when the center of a specified Sensor enters a specified region
- {{% resource_link "42009572-d4be-4350-a45f-bb5414e54adf" "*WakeupOnSensorExit*" %}}: when the center of a specified Sensor exits a specified region

A {{% resource_link "3400e6ea-e523-4f65-81ce-6968a6a727ec" "*Behavior*" %}} object constructs a {{% resource_link "6de1b858-30ac-4923-ad29-91ab3b600be6" "*WakeupCriterion*" %}} by providing the appropriate arguments, such as a reference to some scene graph object and a region of interest.

Multiple criteria can be combined using the following classes to form complex wakeup conditions.

- {{% resource_link "2d624504-f304-4876-a2cc-53714a7a7b11" "*WakeupOr*" %}}: specifies any number of wakeup conditions logically ORed together
- {{% resource_link "1be6bbe4-dea9-40dd-831e-2f5ceaec27f6" "*WakeupAnd*" %}}: specifies any number of wakeup conditions logically ANDed together
- {{% resource_link "f7e543a8-1291-41a8-8406-2f1ac1bb24fd" "*WakeupOrOfAnds*" %}}: specifies any number of OR wakeup conditions logically ANDed together
- {{% resource_link "95f5a340-dd25-439a-8147-f05ae1fdc00b" "*WakeupAndOfOr:*" %}}  specifies any number of AND wakeup conditions logically ORed together

The class hierarchy of the {{% resource_link "9548a435-9aac-453e-8ef6-7f3c93c749ad" "*WakeupCondition*" %}} class is shown below:

{{< resource uuid="76163ee3-f63d-c91c-3d9f-88be97281f08" >}}

The following code provides an example of setting a {{% resource_link "9548a435-9aac-453e-8ef6-7f3c93c749ad" "*WakeupCondition*" %}} object

    *public void initialize()*        
*{*        
{{% resource_link "6de1b858-30ac-4923-ad29-91ab3b600be6" "*WakeupCriterion*" %}} *criteria\[\] = new WakeupCriterion\[2\];*        
*criteria\[0\] = new* {{% resource_link "7f9703b0-5b7d-44a6-81c6-325dd50fdf1b" "*WakeupOnElapsedFrames(3)*" %}}*;*        
*criteria\[0\] = new* {{% resource_link "ffff9f22-291e-4b9a-944c-9a4a814ccd15" "*WakeupOnElapsedTime(500)*" %}}*;*

{{% resource_link "9548a435-9aac-453e-8ef6-7f3c93c749ad" "*WakeupCondition*" %}} *condition = new* {{% resource_link "2d624504-f304-4876-a2cc-53714a7a7b11" "*WakeupOr*" %}}*(criteria);*        
{{% resource_link "e686ea5a-f7b3-4dd8-aeae-2169254ff875" "*wakeupOn(*" %}}*condition);*        
*}*

A {{% resource_link "3400e6ea-e523-4f65-81ce-6968a6a727ec" "*Behavior*" %}} node provides a {{% resource_link "9548a435-9aac-453e-8ef6-7f3c93c749ad" "*WakeupCondition*" %}} object to the behavior scheduler via its {{% resource_link "e686ea5a-f7b3-4dd8-aeae-2169254ff875" "*wakeupOn()*" %}} method and the behavior scheduler provides an enumeration of that {{% resource_link "9548a435-9aac-453e-8ef6-7f3c93c749ad" "*WakeupCondition*" %}}. The {{% resource_link "e686ea5a-f7b3-4dd8-aeae-2169254ff875" "*wakeupOn()*" %}} method should be called from the {{% resource_link "5fd54b82-5c31-43f8-8d02-8ad22d1de16a" "*initialize()*" %}} and {{% resource_link "8638eb48-0cf8-46ac-9495-8fb40be8a593" "*processStimulus()*" %}} methods, just prior of exiting these methods.

In the current Java® 3D implementation the behavior scheduler, and, therefore, the {{% resource_link "8638eb48-0cf8-46ac-9495-8fb40be8a593" "*processStimulus*" %}} method of the {{% resource_link "3400e6ea-e523-4f65-81ce-6968a6a727ec" "*Behavior*" %}} class as well, run concurrently with the rendering thread. However, a new thread will not start until both the renderer, which may be working on the previous frame, and the behavior scheduler are done.

Java® 3D guarantees that all behaviors with a {{% resource_link "a12ddf0b-4881-464c-a80a-fef20abba887" "*WakeupOnElapsedFrames*" %}} will be executed before the next frame starts rendering, i.e. the rendering thread will wait until all behaviors are done with their {{% resource_link "73b50d82-a0f0-4764-bc4c-f593327d6586" "*processStimulus*" %}} methods before drawing the next frame. In addition, Java® 3D guarantees that all scene graph updates that occur from within a single {{% resource_link "3400e6ea-e523-4f65-81ce-6968a6a727ec" "*Behavior*" %}} object will be reflected in the same frame for consistency purposes.

Finally, {{% resource_link "22fa17cb-daaf-4bfa-9705-031e74fa4307" "*Interpolator*" %}} objects can be used for simple behaviors where a parameter can be varied between a starting and an ending value during a certain time interval.

Lights

Lights can be used in order to achieve higher quality and realism of the graphics. Lighting capabilities is provided by the class Light and its subclasses. All light objects have a color, an on/off state, and a bounding volume that controls their illumination range. Java3D provides the following four types of lights, which are subclasses of the class {{% resource_link "52fe5d56-44d0-494b-a143-c07bd2526edd" "*Light*" %}}:

- {{% resource_link "fbbf41ca-8ad2-4a75-abdc-15c2d07fe9c4" "*AmbientLight*" %}}: the rays from an ambient light source object come from all directions illuminating shapes evenly
- {{% resource_link "82ecf5b9-6a8d-4206-9d44-411678cf0d57" "*DirectionalLight*" %}}: a directional light source object has parallel rays of light aiming at a certain direction
- {{% resource_link "9a453be6-2f32-44f2-93de-3de37265a441" "*PointLight*" %}}: the rays from an point light source object are emitted radially from a point to all directions
- {{% resource_link "cac0924d-01e5-4c4b-888d-7d13b5523d7a" "*SpotLight*" %}}: the rays from a spot light source object are emitted radially from a point to all directions but within a cone

{{\< anchor "6" >}}{{\< /anchor >}}6. Performance of Java® 3D

Java® 3D aims at achieving high performance by utilizing the available graphics libraries (OpenGL/Direct3D), using 3D-graphics acceleration where available, and supporting some rendering optimizations (such as scene reorganization and content culling). It is optimized for performance rather than quality of image rendering. Compilation of branch groups and utilization of capability bits enable speed optimizations. It is as fast and high-level as Open Inventor and VRML (Virtual Reality Modeling Language), while it offers the portability of Java® and the direct access and well integration with all other available Java® APIs. Java® 3D uses native code of certain libraries, such as the OpenGL, at the final steps of rendering to achieve satisfactory performance levels. A scene reorganization and a content culling may be used by the renderer to optimize rendering by following an optimal order that bypasses hidden parts of the scene.

Java® 3D rendering is tuned to the underlying hardware utilizing a wide range of hardware and software platforms. Java® 3D is scalable, taking advantage of multithreading capabilities of Java® when multiple processors are available. The availability of multiple processors is automatically utilized by its independent and asynchronous components, such as the rendering thread and the behavior scheduler, that can be assigned to different processors. Also, branches of the scene tree-structure can be manipulated independently and concurrently utilizing multithreading and multiprocessing.

A thread scheduler was implemented inside the Java® 3D, providing to the Java® 3D architects full control of all threads and eliminating the need to deal with thread priorities. the underlying architecture uses messages to propagate scnegraph changes into certain structures that are used to optimize a particular functionality. There are two structures for geometric objects. The one organizes the geometry spatially enabling spatial queries on the scene graph, such as picking, collisions, culling etc. The other structure is a state snapshot of the scene graph, known as render bin, which is associated with each view and is used by the renderer thread. There is also a structure associated with behaviors that spatially organizes behavior nodes, and a behavior scheduler thread that executes behaviors that need to be executed.

The thread scheduler is essentially in a big infinite loop implemented inside the Java® 3D. For each iteration, the thread scheduler runs each thread that needs to be run once, waiting for all threads to be completed before entering the next iteration. The behavior and the rendering threads may run once in a single iteration. The following operations are conceptually performed within this infinite loop.

*while(true)*        
*{*        
*process input*

*if(there is a request for exit)*        
*break*

*perform any behaviors*

*transverse scene graph and render visible objects*        
*}*

Whenever a node of the scene graph is modified a message is generated with a value associated with it and any state necessary to reflect the specific changes, and queued with all other messages by the thread scheduler. At each iteration the messages are processed and the various structures are updated accordingly. The update time is very fast when the messages are very simple, which is typically the case. In the current implementation the rendering thread and the behavior thread can run concurrently. In particular, the behavior scheduler and therefore the {{% resource_link "73b50d82-a0f0-4764-bc4c-f593327d6586" "*processStimulus*" %}} method of a {{% resource_link "3400e6ea-e523-4f65-81ce-6968a6a727ec" "*Behavior*" %}} object, can run concurrently with the renderer. However, a new frame will not start until both the rendering of the previous frame and the behavior scheduler are done.

Finally it offers level-of-detail ({{% resource_link "ecb6efe2-23f9-4a3e-bd64-9992701d05a6" "*LOD*" %}}) capabilities to further improve performance using a {{% resource_link "ecb6efe2-23f9-4a3e-bd64-9992701d05a6" "*LOD*" %}} object. An LOD leaf node is an abstract class that operates on a list of Switch group nodes to select one of the children of the Switch nodes. The {{% resource_link "ecb6efe2-23f9-4a3e-bd64-9992701d05a6" "*LOD*" %}} class is extended to implement various selection criteria, such as the {{% resource_link "746f4635-bda8-40d2-93d2-a76af15633f7" "*DistanceLOD*" %}} subclass.