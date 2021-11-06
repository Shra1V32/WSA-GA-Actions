# Windows Subsystem for Android with GApps Automated Workflow
This repository is for creating a Wsa Package with your own desired GApps automatically just with a click!. All you need is your WsaPackage URL and GApps URL and you're good to go.

## Steps for Usage:
* First of all fork this repo
* Then, In your-forked-repo, Head over to Actions tab
* Tap on WSA-GA-Actions at the left side of the page.
* Tap on 'Run Workflow'
* Enter your WsaPackage URL and GApps URL (Make sure that you choose the right architecture), Also if you want ARM64 architecture packaged zip, Specify it in the 3rd field of inputs.
* Then Tap on Run Workflow and you'll see that there will be workflow being run.
* Once the Workflow completes successfully, Check the logs  and scroll all the way to the bottom, You'll see that there will be a file uploaded with the link starting with transfer.sh. And that's it there you go.

Please do star my repo, If you've really liked my work :)

## Credits
* [ADeltaX](https://github.com/ADeltaX) and WSA-Community for their work on [WSAGAScript](https://github.com/WSA-Community/WSAGAScript)
* transfer.sh
* GitHub for their GitHub Actions