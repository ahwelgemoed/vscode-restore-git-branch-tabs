# Restore Git Branch Tabs

Restore opened tabs on a per git branch basis.

Opened editors are saved for each branch in the workspace. Switching branches saves the currently opened editors and restores the editors that were opened when last editing the new branch.

This extension was heavily based off of the work done by [Eric Amodio](https://github.com/eamodio), specifically his [Restore Editors](https://github.com/eamodio/vscode-restore-editors/blob/master/README.md) extension.

![preview](images/preview.gif)

## Features

- Automatically saves editors when a git repository is detected in the workspace.

- `Clear Saved Editors` command (`restoreGitBranchTabs:clear`) to clear all saved editors for every known branch.

- `Load Saved Editors` command (`restoreGitBranchTabs:load`) to manually load saved editors for the current branch.

- `Save Opened Editors` command (`restoreGitBranchTabs:save`) to manually save all open editors for the current branch.

## Extension Settings

| Name | Description
| ---- | -----------
|`restoreGitBranchTabs.debug` | Enable debug mode
|`restoreGitBranchTabs.outputLevel` | Specifies the verbosity of the output channel
