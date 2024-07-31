# XenVMAutoStart

XenVMAutoStart is a script designed to automatically start selected virtual machines on XenServer. The script accounts for the necessary delays to ensure correct startup of virtual machines. If a virtual machine does not start immediately, the script waits and attempts to start it again after 60 seconds.

## Features

- **Automated VM Startup**: Automatically starts a list of specified virtual machines.
- **Retry Mechanism**: Retries starting a VM every 60 seconds if it fails to start initially.
- **Host Availability Check**: Ensures XenServer host is available before attempting to start VMs.
- **Logging**: Logs all activities and actions taken by the script for easy monitoring.

## Requirements

- **Bash**: Ensure you have a Bash shell environment.
- **XenServer**: Ensure you have XenServer installed and configured properly.

## Installation

1. **Clone the Repository**:

    ```sh
    git clone https://github.com/your-username/XenVMAutoStart.git
    cd XenVMAutoStart
    ```

2. **Make the Script Executable**:

    ```sh
    chmod +x auto_start_vms.sh
    ```
