![Static Chicken](app_icon.jpg)


This repository is used to distribute DCS Kneeboard files.

# DCS Kneeboard Help

Welcome to the DCS Kneeboard app! This guide helps you get the most out of your digital kneeboard for Digital Combat Simulator flights.

## What is DCS Kneeboard?

This app replaces your physical kneeboard with a powerful digital version on your tablet or phone. View checklists, procedures, maps, and mission-specific data right beside you in the cockpit.

## Managing Your Kneeboard Documents

The core of the app is managing your kneeboard pages.

*   **Viewing Documents:** Supports common formats like PDFs and images (JPG, PNG, GIF).
*   **Organizing Content:** Documents are organized by:
    *   **Aircraft:** Content specific to the module you're flying (e.g., F/A-18C checklists).
    *   **Terrain:** Maps are further organized by the DCS terrain they belong to (Caucasus, Syria, etc.).
    *   **Tabs:** Standard kneeboard tabs Checklists, Weapons, Threats, Maps and Controls.
*   **Customization:** You can reorder pages in each tab to match your workflow.
*   **Adding Content:** Use the Import features (see below) to add your own PDFs, images, or entire kneeboard packages.

## Kneeboard Extractor: Current Mission Kneeboard Files

This feature lets you pull kneeboard files directly from your *current* DCS mission running on your PC.

*   **Purpose:** Grabs images (like briefing images, map markers, target photos) that are embedded in the active DCS mission.
*   **How it Works:** The app connects over your local network to a small **DCS Kneeboard Helper** application running on the same PC as DCS.
*   **Setup:**
    1.  Download and run the **DCS Kneeboard Helper** application on your PC.
    2.  In this Kneeboard app, go to **Settings**.
    3.  Enter the **IP Address** of your PC running DCS and the **Port** number displayed by the Helper application.
    4.  Test the connection.
*   **Usage:**
    1.  Ensure the Helper App is running on your PC.
    2.  Start a mission in DCS.
    3.  In the Kneeboard app, navigate to the Checklists tab.
    4.  Press the **Mission Extractor button**.
*   **Result:** The app will contact the Helper, download any available kneeboard images for the current mission, and add them to your kneeboard library, usually under the current aircraft and a relevant category (e.g., "Mission"). 
Existing extracted kneeboard files will be removed when extraction is executed.

## Importing & Exporting Kneeboards

Manage your kneeboard content efficiently.

*   **Importing:**
    *   **From Files:** Add individual PDF or image files directly using the local file picker.
    *   **From URL:** Import PDF, image, or ZIP files directly from a web URL.
    *   **From DCS User Files:** Import ZIP files directly from the user files section on the DCS page. Note that rar files are **not** supported.
    *   **From ZIP Archive:** Import entire kneeboard packages shared by others or from your backups. The app understands the standard folder structure (Aircraft > Category > Theme > Files). You can choose to overwrite existing documents or merge the imported content.
*   **Exporting:**
    *   **Full Export:** Creates a `.zip` archive containing all your selected documents and the folder structure. Ideal for complete backups or transferring your setup to another device.
    *   **Structure-Only Export:** Creates a `.zip` archive with only the folder structure (Aircraft > Category > Theme) based on your owned modules/terrains. Useful for creating a template or sharing a standard layout with squadron mates without including specific documents.

## Themes: Light, Dark, Both

Choose the theme that works best for your cockpit environment:

*   **Light:** Bright background, dark text. Add your day kneeboard files to this mode.
*   **Dark:** Dark background, light text. Add your night kneeboard files to this mode.
*   **Both:** Use this for for files for which you don't have night and day versions. These will be shown for both theme modes.

## Modules & Terrains

The app is designed with DCS modules and terrains in mind:

*   **Aircraft Modules:** Content is primarily organized by the aircraft it relates to. You can manage which modules you own in the settings, which can influence import/export behavior.
The chosen aircraft in the menu will determine the content of the tabs Checklist, Weapons, Threats and Controls
*   **Terrains:** Map documents are linked to specific DCS terrains, ensuring you see relevant maps for your flight area.
The chosen Terrain in the menu will determine the content of the Maps tab.
