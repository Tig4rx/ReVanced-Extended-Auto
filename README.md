###### 07/AUGUST/2023:
### Merged new upstream features...
* [Custom patch resources](https://github.com/nikhilbadyal/docker-py-revanced/issues/230) are now supported, with per-app configuration options available! For more information about this, [check here](https://github.com/Spacellary/ReVanced-Extended-Automated-Builder/blob/main/readme-history/README-ORIGINAL.md#global-config).

###### 15/JULY/2023:
### Merged upstream changes...
* Now with support for **RVX Reddit**.

Also supports the other Reddit clients, such as **RV Sync**.
* Read the [README-ORIGINAL.md](https://github.com/Spacellary/ReVanced-Extended-Automated-Builds/blob/main/readme-history/README-ORIGINAL.md) for more information about those.

###### 23/MARCH/2023:
### Builds are now automated!
Added simple scheduled action that checks for patch updates, and if an update is found, records the new version of patches for future reference and automatically triggers the workflow to build and release the new applications.

<hr>

### Feel free to fork this fork.
Let the 'forkception' begin!

### How to use this fork:

**Before running the workflows for the first time, you need to go the Settings page of the repository and under Actions, then General, change the "Workflow permissions" to "read and write".**

1. Go to the Actions page at the top.
2. Select the "Build & Release" action.
3. Click the "Run Workflow" drop-down button and run it. <br> <br> Optionally, select the "Update Checker" action, and **enable** it. It will periodically check for new `inotia00/revanced-patches` releases and trigger a new Build & Release when a new version is found. <br> <br> *As ReVanced Extended has been [discontinued](https://github.com/inotia00/revanced-documentation/wiki/Announcement) new patches aren't expected to be released. You may change the repository to watch for updates in the [update.yml [line 25]](.github/workflows/update.yml) workflow file.*

<br>

**It will take around 7 minutes to complete the Build & Release workflow.** Once that's completed:

1. Go to "Releases" at the bottom of your repository page (on mobile) or at the right (on Desktop).
2. Download your patched applications.

#### Set up to build:
* ReVanced Extended **YouTube** (latest supported).
* ReVanced Extended **YouTube Music** (latest) in the **arm64-v8a** architecture.
* ReVanced Extended **Reddit** (latest).
* ReVanced **Sync for Reddit** (latest).

###### Check [.env](https://github.com/Spacellary/docker-py-revanced/blob/main/.env) for a list of excluded patches and [options.json](https://github.com/Spacellary/docker-py-revanced/blob/main/apks/options.json) for patch options.
###### Complete and original README can be found [here](https://github.com/Spacellary/ReVanced-Extended-Automated-Builds/blob/main/readme-history/README-ORIGINAL.md).
