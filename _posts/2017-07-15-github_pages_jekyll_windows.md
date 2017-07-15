

-   Install chocolatey

```
@powershell -NoProfile -ExecutionPolicy Bypass -Command "iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1 && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"
```

-   Open Windows Powershell in Admin mode and run

```sh
choco install ruby -y
```

-   Close and open a new command prompt with Administrator access
-   Install gem bundler

gem install bundler

-   Install Jekyll

gem install jekyll

-   To create a new website

jekyll new github_techblog
