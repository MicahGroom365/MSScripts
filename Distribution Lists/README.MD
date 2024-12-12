# Add User to Distribution List - GUI Script

## Overview
This repository contains a PowerShell script that provides a graphical user interface (GUI) to simplify adding users to distribution lists in Exchange Online. The script is designed for system administrators managing Microsoft 365 environments, enabling them to easily connect to Exchange Online, select a distribution list, and add users via a user-friendly interface.

---

## Features
- **GUI Interface:** A modern Windows Forms interface for easy interaction.
- **Dynamic Dropdown:** Automatically fetches all distribution lists for selection.
- **Validation:** Ensures required fields are filled before proceeding.
- **Error Handling:** Provides clear feedback on success or failure.
- **Custom Styling:** Enhanced layout with modern design elements.

---

## Prerequisites
1. **Exchange Online Management Module:** Ensure the module is installed.
   ```powershell
   Install-Module -Name ExchangeOnlineManagement
   ```
2. **Microsoft 365 Admin Privileges:** The script requires admin rights to manage distribution lists.
3. **PowerShell Version:** Ensure PowerShell 5.1 or higher is installed.

---

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/YourOrgName/AddUserToDistributionList.git
   ```
2. Navigate to the directory:
   ```bash
   cd AddUserToDistributionList
   ```
3. Run the script in PowerShell:
   ```powershell
   .\AddUserToDistributionList.ps1
   ```

---

## Usage Instructions
### Step 1: Connect to Exchange Online
- Upon running the script, it will automatically connect to Exchange Online.
- A message box will confirm successful connection or display an error if credentials are invalid.

### Step 2: Select a Distribution List
- The GUI displays a dropdown containing all available distribution lists.
- Choose a list from the dropdown menu.

### Step 3: Enter the Email Address
- Provide the email address of the user you want to add to the selected list.

### Step 4: Add the User
- Click the **Add User** button.
- A confirmation message will appear upon successful addition.
- If an error occurs, the GUI will provide details.

---

## Example Use Case
1. Launch the script.
2. Select the distribution list **"Marketing Team"**.
3. Enter the email address **"john.doe@example.com"**.
4. Click **Add User**.
   - Success: A confirmation message appears.
   - Failure: An error message provides troubleshooting details.

---

## Troubleshooting
- **Error: No Distribution Lists Found**
  - Ensure the account has permissions to view distribution lists in Exchange Online.
- **Error: Failed to Connect to Exchange Online**
  - Verify internet connectivity and that the Exchange Online Management module is installed.

---

## Customization
Feel free to modify the script to suit your organization's requirements:
- **Themes:** Adjust the form's background color or fonts.
- **Features:** Add additional validations or functionality for other tasks.

---

## Contributing
We welcome contributions to enhance this project. To contribute:
1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature/new-feature
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add new feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature/new-feature
   ```
5. Open a pull request.


---

**Happy Scripting!** 🚀
