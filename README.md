## Installation and Usage Guide

### Step 1: Create a Workspace
1. Open your terminal or command prompt.
2. Create a new workspace folder:
   ```
   mkdir workspace
   cd workspace
   ```
3. Clone the project into the workspace:
   ```
   mkdir src
   cd src
   git clone https://github.com/linguanliang/gczb.git
   ```

---

### Step 2: Run the Project
1. Use the following commands to start the project based on its type:
   - For a frontend project:
     ```bash
     source ./devel/setup.bash
     roslaunch gczb gczb_rviz_gaz.launch
     ```


---