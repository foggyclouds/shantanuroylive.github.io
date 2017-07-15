Prerequisite – Chocolatey

You need to have Chocolatey installed on your machine. Chocolatey is the BEST way to install and keep applications updated on windows.

Open a command prompt with Administrator access
Install Chocolatey
@powershell -NoProfile -ExecutionPolicy Bypass -Command "iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1 && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"
Close the command prompt as Chocolatey will not be available until you close and reopen.
Install dependencies & Jekyll

Open a command prompt with Administrator access
Install Ruby
choco install ruby -y
image
Close and open a new command prompt with Administrator access
Install gem bundler
gem install bundler
Install Jekyll
gem install jekyll



Now you can use standard Jekyll commands to create a new site and serve it e.g.
jekyll new myblog
cd myblog
jekyll serve


added gem bundler which is a new requirement.
