# MyTwitter Powershell Module

[![Join the chat at https://gitter.im/MyTwitter/MyTwitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/MyTwitter/MyTwitter?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
- - -
The MyTwitter Powershell module is a module created to interact with Twitter.  It uses Twitter's OAuth API to tweet, send direct messages and hopefully more functionality is to come!

For instructions on getting started with this module visit https://adamtheautomator.com/twitter-module-powershell/.

09/30/14 - Added proper special character handling/escaping function and integrate.  

09/30/14 - Fixed exporting the Set-OAuthAuthorization function so that operator can manually set up registry entries by calling the function.  

09/30/14 - Fixed syntax error line 87 from master pull missing colon.

10/08/14 - Added Pester test for Split-Tweet function. I would suggest we create more tests later.
![ScreenShot](https://raw.githubusercontent.com/MyTwitter/MyTwitter/master/PesterSplitTweet.gif)

03/14/15 - Fixed Bitly Authentication within the Get-ShortUrl function.

# Install
You can install this module directly from the PowerShell Gallery using:
<pre>
Install-Module MyTwitter
</pre>
To install the module including all source code you can also just run in a PowerShell v3 or higher the following command:
<pre>
iex (New-Object Net.WebClient).DownloadString("https://gist.githubusercontent.com/stefanstranger/2138dc710576bc40b64b/raw/bfd25a0e7363e9a1906908b0695ebcffaa508276/InstallMyTwitterModule.ps1")
</pre>
