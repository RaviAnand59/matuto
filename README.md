# 📖 Matuto [![by](https://img.shields.io/badge/by-Web3%20Philippines-7b3fe4.svg?longCache=true&labelColor=181717&style=flat-square)](https://web3philippines.org)

[![maintainer](https://img.shields.io/badge/maintainer-OSS%20Philippines-blue.svg?logo=github&labelColor=181717&longCache=true&style=flat-square)](https://ossph.org) [![installs](https://img.shields.io/chrome-web-store/users/gbdkfpagopdnedcmmohlpmogekmfpobp?style=flat-square&logo=Google%20Chrome&logoColor=%23fff&label=installs&labelColor=%23181717&color=%237b3fe4)](https://chrome.google.com/webstore/detail/matuto-learn-web3-in-ever/gbdkfpagopdnedcmmohlpmogekmfpobp) [![release](https://img.shields.io/github/release/web3phl/matuto.svg?logo=github&labelColor=181717&color=green&style=flat-square)](https://github.com/web3phl/matuto/releases) [![star](https://img.shields.io/github/stars/web3phl/matuto.svg?&logo=github&labelColor=181717&color=yellow&style=flat-square)](https://github.com/web3phl/matuto/stargazers) [![license](https://img.shields.io/github/license/web3phl/matuto.svg?&logo=github&labelColor=181717&style=flat-square)](https://github.com/web3phl/matuto/blob/main/license)

![screenshot](src/assets/screenshot.png)

Matuto is a simple browser extension that provides a glossary of terms and definitions related to web3, blockchain and cryptocurrencies when every time you open a new tab from your browser.

It's a Filipino word which means "to learn". Which is the goal of this project, to help people learn more about web3, blockchain and cryptocurrencies. 💜💙📖

## 📦 Download

| Browser     | Download                                                                                                        | Info                                                   |
| ----------- | --------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------ |
| **Chrome**  | [Get Now](https://chrome.google.com/webstore/detail/matuto-learn-web3-in-ever/gbdkfpagopdnedcmmohlpmogekmfpobp) | For chromium-based browsers such as Brave, Opera, etc. |
| **Edge**    | [Get Now](https://microsoftedge.microsoft.com/addons/detail/matuto/djbnlpmjbdflnjdcphaofhifcgigdbbe)            | For Microsoft Edge browser.                            |
| **Firefox** | [Get Now](https://addons.mozilla.org/en-US/firefox/addon/matuto/)                                               | For Firefox browser.                                   |

## ⚡ Demo

![demo](.github/assets/demo.gif)

## 💡 How to install

<!-- markdownlint-disable MD033 -->
<details>
<summary>Microsoft Edge</summary>
   <ol>
      <li>Go to the Microsoft Edge addon store <a href="https://microsoftedge.microsoft.com/addons/detail/matuto/djbnlpmjbdflnjdcphaofhifcgigdbbe" target="_blank">here</a>.</li>
      <li> Click "Get"</li>
      <li>Click "Add extension"</li>
      <li>In the top right corner go to: <br>
      <img src=".github/assets/how_to_install/edge/edge4.png"></img><br>Or just paste: edge://extensions/ into a search bar and skip to step 6</li>
      <li>Click "Manage extensions"</li>
      <li>Enable Matuto!<br><img src=".github/assets/how_to_install/edge/edge6.png"></img></li>
   </ol>
</details>

<details>
<summary>Google Chrome</summary>
   <ol>
      <li>Go to Chrome Web Store <a href="https://chrome.google.com/webstore/detail/matuto-learn-web3-in-ever/gbdkfpagopdnedcmmohlpmogekmfpobp" target="_blank">here</a></li>
      <li>Click "Add to Chrome"</li>
      <li>Click "Add extension"</li>
      <li>In the top right corner go to: <br>
      <img src=".github/assets/how_to_install/chrome/chrome4.png"></img><br> Or paste this: chrome://extensions/ into a search bar</li>
      <li>Make sure extension is enabled<br>
      <img src=".github/assets/how_to_install/chrome/chrome5.png"></img></li>
   </ol>
</details>

<details>
<summary>Mozilla Firefox</summary>
<ol>
      <li>Go to Firefox Addons <a href="https://addons.mozilla.org/en-US/firefox/addon/matuto/" target="_blank">here</a></li>
      <li>Click "Add to Firefox"</li>
      <li>Click "Add"</li>
      <li>In the top right corner go to: <br>
      <img src=".github/assets/how_to_install/firefox/firefox4.png"></img><br> Or paste this: about:addons into a search bar go to step 6</li>
      <li>Click "Manage extensions"</li>
      <li>Make sure Matuto is enabled!</li>
   </ol>
</details>

<details>
<summary>Brave</summary>
<ol>
      <li>Go to Chrome Web Store <a href="https://chrome.google.com/webstore/detail/matuto-learn-web3-in-ever/gbdkfpagopdnedcmmohlpmogekmfpobp" target="_blank">here</a></li>
      <li>Click "Add to Brave"</li>
      <li>Click "Add extension"</li>
      <li>In the top right corner go to "Manage extensions": <br>
      <img src=".github/assets/how_to_install/brave/brave4.png"></img><br> Or paste this: brave://extensions/ into a search bar</li>
      <li>Make sure Matuto extension is enabled!<br>
      <img src=".github/assets/how_to_install/brave/brave5.png"></img></li>
   </ol>
</details>
<!-- markdownlint-enable MD001 MD033 -->

## 📚 Documentation

Please visit the official documentation here: [docs.web3philippines.org/matuto](https://docs.web3philippines.org/matuto)

## 💻 Development

1. Install the packages:

   ```bash
   yarn install
   ```

2. Build the extension:

   ```bash
   yarn build
   ```

3. Turn on development mode in your browser and load the extension from the `dist` directory.

> **Note**: Everytime you made changes please run `yarn rebuild` to update the extension. Go to extension management page in your browser and reload the extension.
>
> We'll think of a better way to automate this process in the future.

## 📖 Source

Right now, some of the terms and definitions are taken from [Blocknative's Glossary](https://www.blocknative.com/glossary) with modifications. We'll add more terms and definitions in the future. Please consider contributing to this project. Thanks! 🙏✨

## 🎯 Contributing

Contributions are welcome, create a pull request to this repo and we will review your code. Please consider to submit your pull request to the `dev` branch. Thank you!

Read the project's [contributing guide](./contributing.md) for more info.

## 💬 Discussions

For any questions, suggestions, ideas, or simply you want to share your experience in using this project, feel free to share and discuss it with the [community](https://github.com/web3phl/matuto/discussions)!

## 🐛 Issues

Please report any issues or bugs by [creating a new issue here](https://github.com/web3phl/matuto/issues/new/choose), also make sure you're reporting an issue that doesn't exist. Any help to improve the project would be appreciated. Thanks! 🙏✨

## 📋 Code of Conduct

Read the project's [code of conduct](./code_of_conduct.md).

## 📃 License

This project is licensed under [GNU General Public License v3](https://opensource.org/licenses/GPL-3.0).

## 📝 Author

This project is developed and maintained by [Web3 Philippines® Protocol](https://web3philippines.org) and [Open Source Software Philippines](https://ossph.org) with the help of awesome [contributors](https://github.com/web3phl/matuto/graphs/contributors).

[![contributors](https://contrib.rocks/image?repo=web3phl/matuto)](https://github.com/web3phl/matuto/graphs/contributors)

---

Made 💻 with 💖 by [Web3 Philippines® Protocol](https://web3philippines.org) and [Open Source Software Philippines](https://ossph.org) 💜💙
