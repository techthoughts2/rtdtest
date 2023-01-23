# PowerShell Module Project

## Description

This PowerShell module contains a collection of useful cmdlets for automating common tasks.

![A duck](../media/duck.png)

## Installation

To install this module, copy the entire folder to one of the following locations:

- `$env:USERPROFILE\Documents\WindowsPowerShell\Modules` for the current user
- `$env:ProgramFiles\WindowsPowerShell\Modules` for all users

Then, in PowerShell, run `Import-Module <ModuleName>` to import the module.

## Usage

To view all cmdlets in the module, run `Get-Command -Module <ModuleName>`.

To view the help for a specific cmdlet, run `Get-Help <CmdletName> -Full`.

## Examples

```powershell
PS C:> Get-Command -Module <ModuleName>
```

## Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License.
