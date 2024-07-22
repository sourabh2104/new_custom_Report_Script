# Custome1 Frappe App

## Overview

This Frappe app contains two Doctypes: `Task` and `Project`, under the module `Custome1`. Additionally, it includes a Script Report based on the `Task` Doctype.

## Doctypes

### Task

- **Fields:**
  - **Date** (type: Date)
  - **Task Created Count** (type: Int)
  - **Project** (type: Link, linked with `Project` Doctype)

### Project

- **Fields:**
  - **Project Name** (type: Data)
  - **Start Date** (type: Date)
  - **End Date** (type: Date)
  - **Status** (type: Select, options: Planned, In Progress, Completed)
- **Naming:**
  - By field name
- **Auto name:**
  - Project

## Report

### Script Report

- **Ref Doctype:**
  - Task
- **Standard:**
  - Yes
- **Module:**
  - Custome1
- **Report Type:**
  - Script Report

## Screen Recording

Here is a screen recording of the report:

![Report Screen Recording](![Screencastfrom07-20-2024044850PM-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/c2bd0c7f-8036-4588-884a-59a9d0b4e78b)
)


![Report Screen Recording](![Screencastfrom07-20-2024044850PM-ezgif com-video-to-gif-converter(1)](https://github.com/user-attachments/assets/682ee3bc-d2d7-442b-87ad-ead90387becb)
)


![Report Screen Recording](![Screencastfrom07-20-2024044850PM-ezgif com-video-to-gif-converter(2)](https://github.com/user-attachments/assets/203d7573-f087-4de7-9052-8fb3657f94ac)
)


## Installation

To install the `Custome1` Frappe app, follow these steps:

1. Clone the repository:
   ```bash
   git clone "https://github.com/sourabh2104/new_custom_Report_Script"


2. Change to the app directory:
    ```
    cd custome1
    ```

3. Install the app:
   ```
   bench install-app custome1
   ```

4. Add the app to your site:
   ```
   bench --site <your_site_name> install-app custome1
   ```


## Usage

  1.Create new entries in the Task and Project Doctypes from the Frappe Desk.
    Access the Script Report from the Reports section under the Custome1 module.

## License

  This project is licensed under the MIT License - see the LICENSE file for details.
  Contributing

  Please read CONTRIBUTING.md for details on our code of conduct and the process for submitting pull requests.

  
  ## Authors

    Sourabh - Initial work - https://github.com/sourabh2104
   
