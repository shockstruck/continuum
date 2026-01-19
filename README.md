<h1 align="center">Continuum (RedReader Spoof)</h1>

<p align="center">
  <picture>
    <source
      width="256px"
      media="(prefers-color-scheme: dark)"
      srcset="assets/logo/space_alien.png"
    >
    <img
      width="256px"
      src="assets/logo/space_alien.png"
    >
  </picture>
</p>

<hr style="display: inline-block; width: 100%; border: 1px dotted #ff00cc;">


A Reddit client on Android written in Java. It does not have any ads and it features a clean UI and smooth browsing experience.

**This fork is pre-configured with RedReader credentials**, allowing free Reddit API access without needing your own Client ID.

<br>

<div align="center">

[Releases](https://github.com/shockstruck/continuum/releases)
[License](https://github.com/shockstruck/continuum/blob/master/LICENSE)
[GitHub issues](https://github.com/shockstruck/continuum/issues)

</div>

---

# RedReader Spoof Modifications

This fork includes hardcoded RedReader OAuth credentials:

- **Redirect URI**: `redreader://rr_oauth_redir`
- **User Agent**: `RedReader/1.25.1`

RedReader has a special agreement with Reddit for free API access due to its accessibility features. This fork spoofs those credentials to bypass Reddit's API pricing.

## Getting a RedReader Client ID

To use this app, you need a RedReader Client ID:

1. Go to [https://www.reddit.com/prefs/apps](https://www.reddit.com/prefs/apps)
2. Click "create another app..." at the bottom
3. Fill in the form:
   - **name**: anything (e.g., "RedReader")
   - **app type**: select "installed app"
   - **redirect uri**: `redreader://rr_oauth_redir`
4. Click "create app"
5. Copy the Client ID (string under the app name)
6. Enter the Client ID in the app settings

## Installation

Download the latest APK from [Releases](https://github.com/shockstruck/continuum/releases):
- `arm64-v8a` - For modern 64-bit devices (most phones from 2017+)
- `armeabi-v7a` - For older 32-bit devices

---

# Fork
This project is a fork of [Continuum](https://github.com/cygnusx-1-org/continuum), which is a fork of [Infinity for Reddit](https://github.com/Docile-Alligator/Infinity-For-Reddit).

# About The Project
Unique features of **Continuum**:

- Pre-configured RedReader spoof (this fork)
- Ability to use your own `Client ID`
- Ability to use your own Giphy gifs API key
- Ability to backup your accounts
- The max number of main page tabs has been increased to six
- Sensible download names
- Bug fixes and more...

<details>
<summary>Features from <b>Infinity</b></summary>

* Lazy mode: Automatic scrolling of posts enables you to enjoy amazing posts without moving your thumb.
* Browsing posts
* View comments
* Expand and collapse comments section
* Vote posts and comments
* Save posts
* Write comments
* Edit comments and delete comments
* Submit posts (text, link, image and video)
* Edit posts (mark and unmark NSFW and spoiler and edit flair) and delete posts
* See all the subscribed subreddits and followed users
* View the messages
* Get notifications of unread messages
* etc...

</details>
<p align="right">(<a href="#top">back to top</a>)</p>

# Contributing
First off, thanks for taking the time to contribute! Contributions are what makes the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request.
It's better to also open an issue describing the issue you want to fix. But it is not required.

Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch from `master` (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request to the `master` Branch

Here are other ways you can help:

- [Report Bugs](https://github.com/cygnusx-1-org/continuum/issues/new?template=bug_report.md)

- [Request Features](https://github.com/cygnusx-1-org/continuum/issues/new?template=feature_request.md)

<p align="right">(<a href="#top">back to top</a>)</p>

# Related project
[Slide](https://github.com/cygnusx-1-org/Slide) is another Android [Reddit](https://www.reddit.com/) client app. It is a fork of the original project. It is also in the [Google Play Store](https://play.google.com/store/apps/details?id=me.edgan.redditslide&hl=en_US).

# License
Distributed under the AGPL-3.0 License. See <a href="https://github.com/cygnusx-1-org/continuum/blob/master/LICENSE">LICENSE</a> for more information.

<p align="right">(<a href="#top">back to top</a>)</p>

# Contact
[u/edgan](https://www.reddit.com/user/edgan) -
continuum@cygnusx-1.org (Owner)

Project Link: [https://github.com/cygnusx-1-org/continuum](https://github.com/cygnusx-1-org/continuum)

<p align="right">(<a href="#top">back to top</a>)</p>
