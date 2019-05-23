# Pure1PowerShellModule

Please go here for more information on the module

https://www.codyhosterman.com/scripts-and-tools/pure1-rest-api/pure1-powershell-module/

The best way to install this is via the PowerShell Gallery

To install:

install-module Cody.PureStorage.Pure1

To load the module:

import-module Cody.PureStorage.Pure1 

To update:

update-module Cody.PureStorage.Pure1

Use either get-help or get-command to see the details.

Latest version 1.5.0.0 (May 23rd, 2019)

Cmdlets:

New-PureOneRestConnection
Get-PureOneArray
New-PureOneRestOperation
Get-PureOneArrayTag
Set-PureOneArrayTag
Remove-PureOneArrayTag
Get-PureOneArrayNetworking
Get-PureOneMetricDetail
Get-PureOneMetric
Get-PureOneVolume
Get-PureOnePod
Get-PureOneVolumeSnapshot
Get-PureOneFileSystem
Get-PureOneFileSystemSnapshot
Get-PureOneArrayBusyMeter

NOTE: Previous versions of this module used plurals in the cmdlets. This is not a best practice and will be deprecated. Old names are still supported but will be entirely deprecated in a future release. Please updates any use of these cmdlets to use the proper names. So if you used get-pureOneArrays, please change it to get-pureOneArray.

When importing the module you will see the following warning until the cmdlet name changes have been fully deprecated:

"WARNING: All pluralized cmdlets in the Pure1 module will be deprecated in a future release. Please update any scripts.
Example: change get-pureonearrays to get-pureonearray"

This can be suppressed by adding -WarningAction SilentlyContinue
