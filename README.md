# Task Manager (v2) - Power Platform Solution

A Power Apps solution featuring a **task manager** application, provided by [Novalogix](https://www.youtube.com/@Novalogix-ltd) as a companion to a YouTube tutorial video. This solution includes a canvas app, model-driven app, custom tables, and custom pages.

## Video Tutorial

<!-- TODO: Replace the link below with the actual YouTube video URL -->
[![Watch the tutorial on YouTube](https://img.youtube.com/vi/ZXgv55ch9-4/maxresdefault.jpg)](https://youtu.be/ZXgv55ch9-4)

## Prerequisites

- A **Power Platform environment** (Developer, Sandbox, or Production)
- **Power Apps maker permissions**  - you need at least the Environment Maker or System Customizer security role

## How to Import the Solution

### 1. Download the solution

**Option A  - Download the ready-made ZIP from Releases (recommended)**

1. Go to the [Releases](../../releases) page of this repository
2. Download the `TaskManager_1_0_0_2.zip` file from the latest release
3. This file is ready to import  - proceed to step 2

**Option B  - Build the ZIP from source**

If you cloned or downloaded the repository source, you need to create the solution ZIP yourself:

1. Open the repository folder
2. Select all files and folders **inside** the folder (not the folder itself):
   - `[Content_Types].xml`
   - `customizations.xml`
   - `solution.xml`
   - `CanvasApps/`
3. Compress them into a `.zip` file (e.g. `TaskManager_1_0_0_2.zip`)

### 2. Import into Power Platform

1. Go to [make.powerapps.com](https://make.powerapps.com)
2. Select your target **environment** from the environment picker (top right)
3. In the left navigation, click **Solutions**
4. Click **Import solution** on the command bar
5. Click **Browse** and select the `.zip` file from step 1
6. Click **Next**, then **Import**
7. Wait for the import to complete  - you should see a success notification

### 3. Open the app

1. In the left navigation, click **Apps**
2. Find **Task Manager Mechanic - Tablet** in the list
3. Click on the app to open it, or click the three dots (**...**) and select **Edit** to open it in the Power Apps Studio

## Solution Details

| Property | Value |
|----------|-------|
| Solution Name | TaskManager |
| Version | 1.0.0.2 |
| Type | Unmanaged |
| Publisher | Colin Kelly-Cook (Novalogix) |

### Components

| Component | Type |
|-----------|------|
| Task Manager Mechanic - Tablet | Canvas App |
| Task Admin App | Model-Driven App |
| Custom Page Example | Custom Page |
| Task Admin | Custom Page |
| Asset, Location, Task, Work Item | Custom Tables |
| Task Priority, Work Item State | Option Sets |

## Support

If you found this useful, please consider supporting my work, it helps me keep creating free Power Platform content!

[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-ffdd00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://www.buymeacoffee.com/colin.kellycook)

## License

This solution is provided for **educational and demonstration purposes** as part of a Novalogix YouTube tutorial. Feel free to use it as a reference for your own projects.
