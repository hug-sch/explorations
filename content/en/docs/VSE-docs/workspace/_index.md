---
title: "Video Editor Workspace"
linkTitle: "Workspace"
weight: 100
tags:
- VSE
- workspace
---
Workspaces are essentially predefined window layouts aimed at a specific use case. Each Workspace consists of a set of **Areas or Windows** containing **Editors**, and is geared towards a specific task such as video editing or modeling. The Video Editing workspace is a smart combination of five editors. Together they provide you with all the necessary tools to edit your videos.

{{< figure src="images/video-editing-workspace.svg" caption="Figure 1: Default Video Editing workspace  with 5 editors" alt= "Video Editing workspace" width="80%" >}}

(1) [File browser]({{< ref filebrowser >}} "About File Browser"): you can navigate your file system for easily adding assets (clips, images, sounds, ...) to your timeline by dragging and dropping the files. If you select multiple files, they will be added one after the other to the timeline. You can customize (sorting, filtering, ...) the file browser, so that you have an optimal overview of your assets. Of course, there are more methods to add content to your timeline. [todo] add link to internal document]

(2) & (4) Video Sequencer: the areas (2) and (4) both contain the Video Sequence Editor; respectively with type Preview and type Sequencer. The Preview is self-explanatory. It shows you the image of the current frame in the Sequencer Timeline. The Sequencer type is probably the area in the workspace that you'll use the most. The Sequence Editor has three view types: *Sequencer*, *Preview*, and *Sequencer & Preview* (see :doc:`Video Sequence Editor <../../../video_sequencer/index>` for more information.

(3) Properties: are organized into several categories, which can be chosen via tabs (the icons column to its left). Not all categories are relevant in the Video Sequencer. By default only the following are shown: Active Tool, Render Properties, View Layer Properties, Scene Properties, World Properties, and Texture Properties. Most of the time, you will use only the Render Properties.

(5) Timeline: only the header of this editor is visible; so you have to drag the horizontal top border to reveal the time units and eventual keyframes. The [Timeline editor](https://docs.blender.org/manual/en/latest/editors/timeline.html?highlight=timeline) is also used in other workspaces. The use of this Timeline Editor within the Video Editor workspace is rather limited and a case could be made to remove it from the workspace. Its functions can easily be overtaken by the Sequencer (see figure 2), which is right on top of it in the Video Editing Workspace.

It is possible to create multiple instances of any view type in single workspace; so, the Video Sequencer occupy two areas in the workspace. You can switch easily between the Sequencer and the Preview with the {Ctrl + Tab} shortcut.

The built-in Video Editing workspace is very handy and it can be customized easily. Each editor area can be sized, moved, replaced or removed from the workspace. As example, an alternative workspace with auto-installed add-ons can be download from [tin2tin's github](https://github.com/tin2tin/Sequence_Editing>). A screenshot is provided in figure 2.

{{< figure src="https://raw.githubusercontent.com/tin2tin/Sequence_Editing/main/Sequence_Editing.png" caption="Figure 2: A customized Video Editing Workspace." alt= "A customized Video Editing Workspace" width="80%">}}

Please, note that the Timeline editor is removed and that the Playback controls are placed in the header of the Sequencer. Several add-ons are automatically installed (e.g. Transform tools), together with some new operators (e.g. Remove Gap after ...). Last but not least, the Properties editor is also removed and the project settings are placed in the Preview sidebar, where they can easily toggled on/off with the N-key.

With the View Type selector (see figure 1) you can choose if the Video Sequence Editor contains only the Sequencer or only the Preview or both.

{{< figure src="editor-view-types.svg" caption="Figure 3: Three view types for the Video Sequence Editor" alt= "View Types" width="80%" >}}

Note that any area within the Blender main window can contain any Editor and that the same Editor can occur multiple times within the main window. So, theoretically, you can rebuild the combined Sequencer/Preview, starting from an empty workspace and placing two Video Sequence Editors on top of each other. The bottom editor has View Type Sequencer and the top one has type Preview.

The VSE is composed of multiple areas (see figure 2). They are described in more detail in the next sections. Figure 2 shows the combined view *Sequencer/Preview*. You can select this view with the View Type selector. This view can contain the following areas:

{{< figure src="editor-vse-overview.svg" caption="Figure 2: Sequence Editor main view: Header (red), Preview (Yellow), Sequencer (blue), Properties (Grey), Panels & Tabs (Yellow), Toolbar (Purple)" alt= "Main view of Sequencer" width="80%" >}}


- Sequencer: area for the montage of the strips.
- Properties: shows the properties of the active strip. Is divided into panels and tabs. Toggle on or off with :{N} key.
- Toolbar: collection of icons. Clicking the icons will perform an operation on the selected strips in the sequencer. Toggle on or off with :{T} key.
- Preview: shows the output of the sequencer at the time of the playhead.
- Header: with the menu and buttons. This header changes slightly depending on the selected view (see below).

