# xenonstack

# internsctl - Custom Linux Command

## Overview
- **`internsctl`** is a custom Linux command for system tasks.

## Version
- **Version:** v0.1.0

## Usage

### Getting CPU Information
- Command: `internsctl cpu`
- Shows CPU details like `lscpu`.

### Getting Memory Information
- Command: `internsctl memory`
- Displays memory info, similar to `free`.

### User Management
#### Creating a New User
- Command: `internsctl user create <username>`
- Adds a new user with Linux access.

#### Listing All Users
- Command: `internsctl user list`
- Lists all regular users.

#### Listing Users with Sudo Permissions
- Command: `internsctl user list --sudo-only`
- Lists users with sudo permissions.

### File Information
#### Getting Information about a File
- Command: `internsctl file getinfo <file-name>`
- Provides detailed file info.

#### Options for File Information
- File Size: `internsctl file getinfo --size <file-name>`
- Permissions: `internsctl file getinfo --permissions <file-name>`
- Owner: `internsctl file getinfo --owner <file-name>`
- Last Modified: `internsctl file getinfo --last-modified <file-name>`

### Help and Version
- Help: `internsctl --help`
- Version: `internsctl --version`

## Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd internsctl
