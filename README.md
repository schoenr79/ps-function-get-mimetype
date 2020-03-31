# PowerShell Function Get-MimeType
A PowerShell function to retrieve the MIME-Type of a file

# About the Project
This quick PS function, i found very helpful for my scripts. Sometimes you need to check the MIME-Type of a file.

Because it's very awful to crawl the local registry for the correct MIME-type. The function Get-MimeType uses the the _"System.Web"_ assembly of
the .NET Framework to gather the correct MIME-Type. 

If you put a not existing file to the function you wil get a "false" string as return value.
