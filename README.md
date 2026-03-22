# PROJECT-PM-TOOL

Simple single-page tool for HVAC technicians to build consistent PM, service-call, and quoted-repair notes, then copy/paste them into Unifix.

## What it does
- Guides the technician through structured fields by work type (PM, Service Call, Quoted Repair).
- Normalizes common spoken/dictated input (location, equipment codes, filter/belt parts).
- Generates a formatted report block ready to copy into another CRM.
- Stores local draft + visit history in browser localStorage for quick lookup.

## Basic usage
1. Open `index.html` in a browser.
2. Select the mode (`PM`, `SERVICE CALL`, or `QUOTED REPAIR`).
3. Fill in the required fields for that mode.
4. Click **Generate Report**.
5. Click **Copy Report** and paste into Unifix.

## Fast entry behavior
- For speed, most fields are optional and can be left blank.
- The tool only requires **Location** before report generation.
- Any blank fields are automatically filled with the existing defaults like `NONE`, `Not listed.`, or other mode-specific fallback text in the generated report.
