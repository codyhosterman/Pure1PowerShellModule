<!-- wp:paragraph -->
<p>To help our customers I have written a module that makes it easy to connect to the Pure1 REST API with PowerShell.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>The module is called&nbsp;<a href="https://www.powershellgallery.com/packages/Cody.PureStorage.Pure1">Cody.PureStorage.Pure1</a></p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>There are a couple of places you can download this. The best option is the&nbsp;<a href="https://www.powershellgallery.com/packages/Cody.PureStorage.Pure1">PowerShell gallery</a>! This allows you to use&nbsp;<a href="https://docs.microsoft.com/en-us/powershell/module/powershellget/install-module?view=powershell-6">install-module</a>&nbsp;to automatically install the module. </p>
<!-- /wp:paragraph -->

<!-- wp:image {"id":5304} -->
<figure class="wp-block-image"><img src="https://www.codyhosterman.com/wp-content/uploads/2019/01/image-59.png" alt="" class="wp-image-5304"/></figure>
<!-- /wp:image -->

<!-- wp:paragraph -->
<p>As of the 1.0 release of the Pure1 REST, this module is pretty much feature complete in version 1.4.0.0+ of this module. If there is something not natively supported,  I made one "new-PureOneRestOperation" that makes it simple to run any REST operation you want to Pure1.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>To install:</p>
<!-- /wp:paragraph -->

<!-- wp:preformatted -->
<pre class="wp-block-preformatted">install-module Cody.PureStorage.Pure1</pre>
<!-- /wp:preformatted -->

<!-- wp:paragraph -->
<p>To load the module:</p>
<!-- /wp:paragraph -->

<!-- wp:preformatted -->
<pre class="wp-block-preformatted">import-module Cody.PureStorage.Pure1 </pre>
<!-- /wp:preformatted -->

<!-- wp:paragraph -->
<p>To update:</p>
<!-- /wp:paragraph -->

<!-- wp:preformatted -->
<pre class="wp-block-preformatted">update-module Cody.PureStorage.Pure1</pre>
<!-- /wp:preformatted -->

<!-- wp:paragraph -->
<p>Use either get-help or get-command to see the details:</p>
<!-- /wp:paragraph -->

<!-- wp:image {"id":5345} -->
<figure class="wp-block-image"><img src="https://www.codyhosterman.com/wp-content/uploads/2019/01/image-69.png" alt="" class="wp-image-5345"/></figure>
<!-- /wp:image -->

<!-- wp:paragraph -->
<p><strong>Comment on Versioning</strong></p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Versions numbering w.x.y.z (for example 1.2.0.0)</p>
<!-- /wp:paragraph -->

<!-- wp:list -->
<ul><li>W is iterated for large updates</li><li>X is iterated for new cmdlets</li><li>Y is iterated for new functions to existing cmdlets</li><li>Z is iterated for bug fixes</li></ul>
<!-- /wp:list -->

<!-- wp:heading -->
<h2>Latest version 1.5.1.0 (June 7th, 2019)</h2>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>Cmdlets:</p>
<!-- /wp:paragraph -->

<!-- wp:list -->
<ul><li>New-PureOneRestConnection </li><li>Get-PureOneArrays </li><li>New-PureOneRestOperation </li><li>Get-PureOneArrayTags </li><li>Set-PureOneArrayTags </li><li>Remove-PureOneArrayTags </li><li>Get-PureOneArrayNetworking </li><li>Get-PureOneMetricDetails </li><li>Get-PureOneMetrics </li><li>Get-PureOneVolumes </li><li>Get-PureOnePods </li><li>Get-PureOneVolumeSnapshots </li><li>Get-PureOneFileSystems </li><li>Get-PureOneFileSystemSnapshots </li><li>Get-PureOneArrayBusyMeter</li></ul>
<!-- /wp:list -->

<!-- wp:paragraph -->
<p><br><br></p>
<!-- /wp:paragraph -->