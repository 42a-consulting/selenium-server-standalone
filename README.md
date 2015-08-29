# selenium-server-standalone
Composer distribution of Selenium Server Standalone, the browser automation framework.

## Add to your project

	composer require --dev 42a-consulting/selenium-server-standalone

## Updating to a new version
Execute the following command in PowerShell (requires git is availble on the command line)

	.\Update.ps1

This command will download a newer version from http://www.seleniumhq.org/download/
and automatically create a new git commit and tag.

### Update.ps1 usage

	.\Update.ps1 [-Force] [-NoCommit]
