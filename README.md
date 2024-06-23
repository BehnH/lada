# Låda
Låda is an extension to ZFS snapshots for backing up to S3, and S3-compatible storage services.

> [!WARNING]  
> This is not anywhere near ready for production usage, and should be used with caution

## Usage

`lada status` shows the current status of any in-progress backup jobs, what snapshots are stored in S3, and information
on the local ZFS data

`lada backup` allows you perform a full or incremental backup of any snapshot

`lada restore` allows you to restore a snapshot from S3 to ZFS

`lada config` allows you to configure Låda

## Installing Låda

