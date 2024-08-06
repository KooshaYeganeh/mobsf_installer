
# 🛡️ MobSF Installation Script

This script automates the installation of the Mobile Security Framework (MobSF) on Kali Linux. MobSF is a framework for automated mobile application security testing, including static and dynamic analysis.

## 📋 Prerequisites

- **Kali Linux OS**
- **Root or sudo access** to install packages

## 🚀 Installation Steps

1. **Clone the Repository** :octocat:

   Clone this repository to your local machine:
   ```bash
   git clone https://github.com/your-repo/mobsf-install-script.git
   ```

2. **Navigate to the Script Directory** :file_folder:

   Change into the directory containing the script:
   ```bash
   cd mobsf-install-script
   ```

3. **Make the Script Executable** :wrench:

   Change the permissions of the script to make it executable:
   ```bash
   chmod +x install_mobsf.sh
   ```

4. **Run the Script** :arrow_right:

   Execute the script to install MobSF:
   ```bash
   ./install_mobsf.sh
   ```

## 🛠️ What the Script Does

1. **Updates Package List** :package:
   Ensures your package list is up-to-date.

2. **Installs Git** :package:
   Required to clone the MobSF repository.

3. **Installs Python 3.8** :snake:
   Installs Python 3.8 (or Python 3.9 if preferred).

4. **Installs JDK** :coffee:
   Installs the latest version of JDK.

5. **Installs Dependencies** :gear:
   Installs necessary dependencies for MobSF.

6. **Clones MobSF Repository** :arrow_down:
   Clones the MobSF GitHub repository.

7. **Sets Up MobSF** :package:
   Runs the MobSF setup script to configure the environment.

8. **Provides Instructions** :information_source:
   Gives you the command to run MobSF and access its web interface.

## 🏃‍♂️ Running MobSF

After the script completes, you can start MobSF with the following command:
```bash
./run.sh 127.0.0.1:8000
```

Access the MobSF web interface in your browser at:
[http://127.0.0.1:8000](http://127.0.0.1:8000)

## 📝 Notes

- You may change the port number from `8000` to another available port if needed.
- Ensure that all commands in the script run successfully to avoid issues during MobSF setup.

## 🛠️ Troubleshooting

If you encounter issues, verify the following:

- All required packages are installed.
- You have sufficient permissions to execute the script.
- The MobSF setup script completes without errors.

For more information, consult the [MobSF GitHub repository](https://github.com/MobSF/Mobile-Security-Framework-MobSF).

