# Awesome oCIS

An opinionated list of awesome [ownCloud Infinite Scale](https://github.com/owncloud/ocis) apps, extensions, services and other resources.

## Attention please!

> :warning: While we are proud to present you these resources, we can't give any guarantees that they will work for you or that they will be stable. Feel free to open issues in the respective, linked repositories or contribute to the projects in any other way.

If you'd like to contribute to this list, please feel free to make a pull request. 

## Table of Contents

* [Viewers & Editors](#viewers--editors)
* [File Actions](#file-actions)
* [File Sidebar Panels](#file-sidebar-panels)
* [Global Progress Bars](#global-progress-bars)

---

## ownCloud Apps and Extensions

Please follow the steps provided in our [developer documentation](https://owncloud.dev/services/web/#web-apps) if you want to install any of the
following apps and extensions. For some of them there are released artifacts, others still need to be built from source code.

> :information_source: The app and extension installation as described in the developer documentation linked above is available in `oCIS v6.0.0` or later. 

### Viewers & Editors


* [3D Model Viewer](https://github.com/saw-jan/web-app-3dmodel-viewer) - View 3D models based on [three.js](https://threejs.org)
* [Arcade](https://github.com/fschade/ocis-arcade) - Play NES games based on [nes-vue](https://github.com/taiyuuki/nes-vue)
* [Dicom Viewer](https://github.com/owncloud/web-app-dicom-viewer) - Preview medical images based on [Cornerstone3D](https://www.cornerstonejs.org)
* [Draw.io](https://github.com/owncloud/web/tree/master/packages/web-app-draw-io) - View and edit [draw.io](https://www.draw.io) diagrams
* [EPub Reader](https://github.com/owncloud/web/tree/master/packages/web-app-epub-reader) - Read eBooks in .epub format using [epub.js](https://github.com/futurepress/epub.js)
* [GPX Viewer](https://github.com/dschmidt/web-app-gpx-viewer) - Render GPX files in a map view with [Leaflet](https://leafletjs.com)
* [PDF Viewer](https://github.com/owncloud/web/tree/master/packages/web-app-pdf-viewer) - Read PDFs utilizing native browser pdf rendering 
* [Presentation Viewer](http://github.com/JankariTech/web-app-presentation-viewer) - Render markdown presentations with [reveal.js](https://revealjs.com)
* [Preview](https://github.com/owncloud/web/tree/master/packages/web-app-preview) - View images, watch videos and listen to audio files
* [Text Editor](https://github.com/owncloud/web/tree/master/packages/web-app-text-editor) - Edit markdown and plain text file types using [TOAST UI Editor](https://ui.toast.com/tui-editor) 

### File Actions

* [Cast](https://github.com/owncloud/web-extensions/tree/main/packages/web-app-cast) - Send images and videos from your ownCloud to your Chrome Cast.

### File Sidebar Panels

* [Audio Information](https://github.com/owncloud/web/blob/2137305f8ded7f845dc262c424b196742c76c9a0/packages/web-app-files/src/composables/extensions/useFileSideBars.ts#L166) - See audio file information like duration, author or title
* [EXIF / Image Information](https://github.com/owncloud/web/blob/2137305f8ded7f845dc262c424b196742c76c9a0/packages/web-app-files/src/composables/extensions/useFileSideBars.ts#L145) - See EXIF information of photos

### Global Progress Bars

* [Nyan Cat](https://github.com/owncloud/web-extensions/tree/main/packages/web-app-progress-bars) - A JS+CSS only Nyan Cat progress bar for the global loading state. 