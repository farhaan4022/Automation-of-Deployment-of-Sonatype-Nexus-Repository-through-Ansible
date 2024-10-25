Install Java and net-tools:

Update apt repo and cache: Ensures the latest package lists are available.

Install Java 8: Installs the openjdk-8-jre-headless package.

Install net-tools: Adds the net-tools package for networking utilities.

Download and Unpack Nexus:

Download Nexus: Uses get_url to download the Nexus package.

Unpack Nexus: Unarchives the Nexus package into the specified directory.

Verify and rename: Finds the unarchived Nexus folder and renames it to a standard path.

Create Nexus User:

Create user and group: Ensures a user and group nexus exists.

Assign ownership: Changes ownership of Nexus directories to the nexus user.

Start Nexus:

Configure Nexus: Sets the run_as_user parameter.

Start Nexus: Initiates the Nexus application.

Verify Nexus:

Process check: Uses ps and netstat to verify Nexus is running and listening on the expected ports.The reason to upload the hosts file to show the ip address of the configuration and output is same
![Screenshot 2024-10-25 030727](https://github.com/user-attachments/assets/dd298a39-068a-4676-b449-afaaad7931f5)
