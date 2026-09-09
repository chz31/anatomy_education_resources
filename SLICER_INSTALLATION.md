# Installing 3D Slicer and Opening the Teaching Scene

This guide explains how to install 3D Slicer and open the provided `.mrb` teaching scene. No previous experience with medical-imaging software is required.

## 1. Check your computer

3D Slicer is available for Windows, macOS, and Linux. For this teaching scene, a computer with at least 8 GB of memory is recommended. Basic visualization works with integrated graphics, although a dedicated graphics card may make complex 3D scenes more responsive.

Current officially supported operating systems include:

- Windows 11
- macOS 14 (Sonoma) or later
- Ubuntu 22.04 or later and several other current Linux distributions

Older systems may still run Slicer but are not necessarily tested. See the official [3D Slicer system requirements](https://slicer.readthedocs.io/en/latest/user_guide/getting_started.html#system-requirements) for current details.

## 2. Download 3D Slicer

1. Go to the official download page: <https://download.slicer.org/>
2. Select the **Stable Release**. Do not select the Preview Release unless your instructor specifically asks you to use it.
3. Download the installer for your operating system.

> **Important:** Download Slicer only from the official 3D Slicer website. The Stable Release is more thoroughly tested and is the recommended option for this activity.

## 3. Install Slicer

### Windows

1. Double-click the downloaded `.exe` installer.
2. Follow the installation prompts. The default options are appropriate for most users.
3. After installation, open **3D Slicer** from the Windows Start menu.

If you can choose the installation location, use a path containing only standard English letters and characters. Some Python components may not work correctly when the installation path contains non-English characters.

### macOS

1. Double-click the downloaded `.dmg` file.
2. Drag `Slicer.app` into the **Applications** folder.
3. Open Slicer from the Applications folder.

Do not run Slicer directly from the opened `.dmg`; moving it to Applications is necessary for normal operation. If macOS prevents installation or opening on an institution-managed computer, contact your local IT support rather than changing security settings yourself.

### Linux

1. Download the appropriate `.tar.gz` archive.
2. Extract the archive to a folder where you have write permission.
3. Open the extracted folder and run the `Slicer` executable.

Some Linux distributions require additional system packages. Consult the official [installation instructions](https://slicer.readthedocs.io/en/latest/user_guide/getting_started.html#installing-3d-slicer) if Slicer does not start.

## 4. Download the teaching scene

1. Download the provided 3D Slicer scene to a folder on your computer: `ADD_SCENE_DOWNLOAD_URL`
2. Confirm that the filename ends in `.mrb`.
3. Wait until the download is complete before opening it.

> **Do not unzip the `.mrb` file.** An MRB file is a self-contained Slicer data bundle containing the scene, CT volume, segmentations, and display settings.

If the file is stored in OneDrive, make sure it is fully downloaded to the computer and not available online only.

## 5. Open the `.mrb` scene

1. Start 3D Slicer.
2. Drag the `.mrb` file from your file browser into the Slicer window.
3. If Slicer asks how to load the file, accept the option to load it as a scene or Slicer data bundle.
4. Wait while the CT volume and segmentations load. A large scene may take a minute.

Alternatively, use **File > Add Data**, select the `.mrb` file, and follow the prompts to load it.

After loading:

- Open the **Data** module to see the CT volume and segmentation nodes.
- Use the **eye icons** to show or hide structures.
- Follow the accompanying tutorial video for basic rotation, zooming, slice navigation, and segment visibility controls.
- Use the [3D Anatomy Study Guide](3D_ANATOMY_STUDY_GUIDE.md) for suggested structures and relationships to examine.

## 6. No extensions are required

You do **not** need to install TotalSegmentator or any Slicer extensions to view the prepared teaching scene. The segmentations have already been generated and saved in the `.mrb` file.

## Troubleshooting

### The `.mrb` file will not open

- Confirm that the file is fully downloaded.
- Confirm that its extension is `.mrb`, not `.zip`, `.html`, or `.mrb.zip`.
- Start Slicer first and then drag the file into the application window.
- Try **File > Add Data** and select the file manually.
- Download the scene again if the original download may be incomplete.

### The scene opens, but I cannot see a structure

- Open the **Data** module and click the eye icon beside the relevant volume or segmentation.
- Expand a segmentation to find individual structures.
- Check both the 3D view and the axial, sagittal, and coronal slice views.
- A structure may be hidden behind another segment; temporarily hide the obstructing structure or reduce its opacity.

### Slicer is slow

- Close other memory-intensive programs.
- Hide structures that you are not currently examining.
- Avoid displaying every segmentation at the same time.
- If enabled, turn off volume rendering when it is not needed.

### Installation is blocked

If you are using an institution-managed computer and cannot install or run Slicer, contact your institution's IT support. Do not attempt to bypass institutional security restrictions.

## Additional help

- [Official 3D Slicer Getting Started guide](https://slicer.readthedocs.io/en/latest/user_guide/getting_started.html)
- [Official data loading and saving guide](https://slicer.readthedocs.io/en/latest/user_guide/data_loading_and_saving.html)
- [3D Slicer community forum](https://discourse.slicer.org/)

For questions specific to this teaching scene or activity, contact Dr. Chi Zhang.
