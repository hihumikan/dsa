# RRC (RemoteLinkCat)

## Abstract
RRC is a utility tool that uses the SSH protocol to synchronize files and directories on a remote server to a local directory while automatically uploading changes to a specified Git repository. This tool can be used in various scenarios, including file backups, remote server synchronization, and version control for Git repositories.

## Features
**SSH Connectivity:** rrc establishes a secure connection to remote servers using the SSH protocol.

**Remote and Local Synchronization:** It allows you to synchronize files and directories on a remote server with a local directory. It supports copying from remote to local, uploading from local to remote, and bidirectional synchronization.

**Automatic Upload to Git Repositories:** It offers an option to automatically commit and push changes to a Git repository when modifications occur, ensuring a reliable history of file changes.

**File Filtering:** Provides file filtering options to control file synchronization and Git uploads. You can specify particular file types, extensions, file sizes, and more.

**Scheduled Synchronization:** Offers scheduling options to periodically execute file synchronization and Git uploads, supporting automation.

**Security:** rrc uses SSH for communication, ensuring data encryption and security.

## Differences from FTP

rrc and FTP are different tools and protocols designed for different purposes and use cases.

rrc is primarily designed to assist version control and collaboration. Its main purpose is to record changes, such as source code or text files, and manage software projects with collaboration from multiple developers. RRC is not primarily a file synchronization tool but rather a tool for tracking changes within Git repositories. While Git uses secure protocols like SSH to enhance security, it is primarily designed as a version control tool and is suitable for software development and code versioning.

**FTP (File Transfer Protocol)**, on the other hand, is a file transfer protocol with the main purpose of transferring and sharing files between different computers. It is widely used for tasks like uploading and downloading files for websites. FTP is primarily used for file synchronization and transfer, allowing you to copy files from remote servers to local computers or vice versa.

In summary, RRC is geared towards version control and collaboration, primarily used for code and text files. FTP, on the other hand, is focused on file transfer and synchronization, commonly used for file transfer and backup purposes.

