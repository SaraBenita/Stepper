# Stepper

Developed in in Java language in three UI interfaces: Console, Desktop and Client-Server application. 
JavaFX was used for the purpose of realizing the display and operation of the system as a graphical application and
in addition using the Http communication protocol for client-server development.                                                                                    An application that assembles various scenarios from common components that can be performed on a computer,
executes them, produces their results and collects information in order to display statistics of their progress.

# Flow Management System

## Overview
This project is a flow management system that allows administrators to manage flows and roles for users, while clients can run these flows with assigned permissions. The system comprises two applications: **Admin** and **Client**, each providing specific functionalities for managing and executing flows.

## Admin Application

### System Explanation
The system allows multiple users to interact with defined flows simultaneously, enabling real-time updates between admins and clients. Admins can upload and manage flow definitions, grant permissions to clients, and oversee the flow execution.

### Screens and Functionalities
1. **Screen 1: User Management**  
   - **Description:** Admins can view users, assign or remove roles, and save updates.  
   - **Features:**  
      - Left pane displays the user list.
      - Right pane displays roles, flows, and status.
      - Role updates are managed via "Available Roles" and "Selected Roles" lists.
      - Save changes with the **"Save Changes"** button and refresh with the **"Auto Updates"** button.
        <img src="./Screenshots/A1" alt="A1" width="800">

2. **Screen 2: Role Management**  
   - **Description:** Allows viewing and updating role information, managing flows for roles, and assigning roles to users.  
   - **Features:**  
      - Left pane displays the role list.
      - Right pane displays role-specific information.
      - Admins can add a new role via the **"New Role"** button and save with the **"Save"** button.

3. **Screen 3: Execution Overview**  
   - **Description:** Displays all executions in the system. Basic details are initially shown, with more details available upon row selection.

4. **Screen 4: Statistics**  
   - **Description:** Displays statistics on flow executions in tables and diagrams.

**General Note:** Saving updates is done with the **"Save"** button on Screens 1 and 2. To update displays, use the **"Update"** button to refresh information on other screens.

## Client Application

### Screens and Functionalities
1. **Screen 1: Flow Information**  
   - **Description:** Displays user details, roles, and flows. Clients can select flows to view more details.  
   - **Features:**  
      - Accordion layout shows flows available to the user.
      - **"Show More Details"** button provides additional flow information.
      - **"Execute Flow"** button initiates flow execution.

2. **Screen 2: Flow Execution**  
   - **Description:** Clients input required data, execute flows, and monitor execution progress.  
   - **Features:**  
      - Shows free inputs, step progress, and allows continuation or re-execution.
      - **"Continue Flow"** and **"Rerun"** buttons are available for extended actions.

3. **Screen 3: Execution Overview**  
   - **Description:** Displays all runs, with additional details available by selecting rows.
