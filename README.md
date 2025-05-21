[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

# KANBI

A lightweight, no-bullshit Kanban board application designed for simplicity and efficiency.

![KANBI Screenshot](images/example.jpg)

## About
KANBI helps you visualize your workflow, limit work-in-progress, and maximize productivity without the bloat of complex project management tools. It's designed to be straightforward, fast, and reliable, now with multi-board support.

## Core Philosophy
KANBI's ethos is centered around minimalism and practicality. We believe productivity tools should get out of your way and let you focus on what matters. The application adheres to these core principles:
- **Simplicity:** No unnecessary features or complex configurations.
- **Speed:** Optimized for performance.
- **Privacy:** Your data stays on your device with local storage.
- **Flexibility:** Customize your workflow and manage multiple projects across different boards.
- **Portability:** Export and import your board data easily.

## Features
- **Multiple Board Management:** Create, switch between, rename, and delete multiple KANBI boards to manage different projects or contexts.
- **Customizable Columns:** Create, edit, reorder, and customize the color of columns to match your workflow on each board. Each board includes a default "Archived" column.
- **Scrollable "Archived" Column:** A dedicated "Archived" column is automatically added to each board to store completed tasks, keeping your "Done" column tidy. Its task list scrolls vertically if it contains many items.
- **Intuitive Task Management:** Add, edit, set due dates, prioritize, and move tasks between columns using drag-and-drop.
- **Data Persistence:** All board data is automatically saved to your browser's local storage.
- **JSON Export/Import:** Manually export and import individual boards or all your KANBI boards as JSON files for backup or migration.
- **Responsive Design:** Works on desktop and mobile devices.

## Getting Started
1. Clone or download this repository. No dependencies or server required.
2. Open `index.html` in your web browser.
3. Familiarize yourself with the header controls:
    - **Boards Dropdown:** Manage your KANBI boards (create, switch, rename, delete).
    - **+Task / +Column Buttons:** Add tasks and columns to the active board.
    - **File Dropdown:** Import/Export your board data.
    - **Help Button:** Access detailed documentation.
4. Start organizing your tasks! Each new board comes with default columns, including a scrollable "Archived" column for completed tasks.

## Usage
See the built-in help documentation by clicking the "Help" button in the application, or view `kanbi-help.html` directly for detailed usage instructions on managing boards, columns, tasks, and the archiving feature.

## Data Storage & Backup

### Local Storage
Your KANBI data (all boards, columns, and tasks) is automatically saved to your browser's local storage as you make changes. This means:
- Your board data persists between sessions.
- Data is specific to the browser and user profile you are using.
- **Important:** Clearing your browser's site data or local storage will erase your KANBI boards.

### Manual Export & Import
For backups or transferring your KANBI data:
- Use the "File" dropdown menu in the application.
- **Export Active Board:** Saves the currently viewed board to a JSON file.
- **Export All Boards:** Saves all your KANBI boards into a single JSON file. This is recommended for regular backups.
- **Import Board(s):** Load data from previously exported KANBI JSON files. This can add new boards or replace existing ones (with confirmation).
- Exported files are typically saved to your browser's default "Downloads" directory.

### Data Management
- Export your boards regularly, especially before making significant changes or if KANBI is critical to your workflow.
- Manage your downloaded JSON backup files as you see fit.

## Limitations & Considerations
- **Browser-Specific Storage:** KANBI data is stored locally in your browser. It is not automatically synced across different browsers or devices. Use the export/import feature to move data.
- **Performance:** While KANBI is designed to be lightweight, having an extremely large number of tasks on a single board, or a very high number of boards, might eventually impact performance. The scrollable "Archived" column helps manage long lists of completed tasks within a board.
- **Mobile Compatibility:** While responsive, some mobile browsers might have limitations with file system operations (export/import).

## License
KANBI is licensed under the Apache License 2.0.

You may obtain a copy of the License at:
[https://www.apache.org/licenses/LICENSE-2.0](https://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

---
© 2025 John W. Little