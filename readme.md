# <img src="source/icon.png" width="45" align="left"> Friendly GitHub [![Build Status](https://travis-ci.org/Hermanya/friendly-github.svg?branch=master)](https://travis-ci.org/Hermanya/friendly-github)

[link-cws]: https://chrome.google.com/webstore/detail/friendly-github/phnhnfjginnlmbjlcdnjoochcceapfjb "Version published on Chrome Web Store"
[link-amo]: https://addons.mozilla.org/en-US/firefox/addon/friendly-github-/ "Version published on Mozilla Add-ons"
[link-travis]: https://travis-ci.org/hermanya/friendly-github

> Browser extension that makes GitHub a better Social Network

Whether we like it or not, GitHub is de-facto the Social Network for programmers. Let's make it less anti-social.

My hope is that GitHub will notice and implement some of these much needed improvements. So if you like any of these improvements, please email [GitHub support](mailto:support@github.com) about doing it.

GitHub Enterprise is also supported. More info in the options.

---

## Install

I have not published this extension anywhere yet. You'll have to either install it from sources, or [subscribe to this issue for Chrome](https://github.com/Hermanya/friendly-github/issues/1) and [this for Firefox](https://github.com/Hermanya/friendly-github/issues/2).

- [**Chrome** extension][link-cws] [<img valign="middle" src="https://img.shields.io/chrome-web-store/v/phnhnfjginnlmbjlcdnjoochcceapfjb.svg?label=%20">][link-cws]
- [**Firefox** add-on][link-amo] [<img valign="middle" src="https://img.shields.io/amo/v/friendly-github.svg?label=%20">][link-amo]
- **Opera** extension: Use [this Opera extension](https://addons.opera.com/en/extensions/details/download-chrome-extension-9/) to install the Chrome version.

## Highlights

<table>
	<tr>
		<th width="50%">
			Show stargazers you know
		</th>
		<th width="50%">
			Show followers you know
		</th>
	</tr>
	<tr><!-- Prevent zebra stripes --></tr>
	<tr>
		<td>
			<img src="https://user-images.githubusercontent.com/2906365/41952167-901fad48-799c-11e8-97d1-70d363629b86.png">
		</td>
		<td>
			<img
			src="https://user-images.githubusercontent.com/2906365/42009293-b1503f62-7a57-11e8-88f5-9c2fb3651a14.png">
		</td>
	</tr>
</table>

<table>
	<tr>
		<th width="50%">
			Reaction avatars showing <i>who</i> reacted to a comment
		</th>
		<th width="50%">
			TBD
		</th>
	</tr>
	<tr><!-- Prevent zebra stripes --></tr>
	<tr>
		<td>
			<img src="https://user-images.githubusercontent.com/1402241/34438653-f66535a4-ecda-11e7-9406-2e1258050cfa.png">
		</td>
		<td>
			<img
			src="">
		</td>
	</tr>
</table>

### More info at a glance

- [Full names of comment authors are shown next to their username.](https://cloud.githubusercontent.com/assets/170270/16172068/0a67b98c-3580-11e6-92f0-6fc930ee17d1.png)

### UI improvements

- Show followers you know
- Suggest similar user profiles
- Show stargazers you know

And [many more…](source/content.css)

## Customization

Most features can be disabled if they are JavaScript-based *(Experimental)* and you can override the CSS with your own in the extension options.

We're happy to receive suggestions and contributions, but be aware this is a highly opinionated project. There's a very high bar for adding options. Users will always disagree with something. That being said, we're open to discussing things. If something doesn't make the cut, you can [build your customized Friendly GitHub locally](contributing.md#workflow), rather than installing it from the Chrome Store.

## Contribute

See the [contribution guide](contributing.md) and join the [contributors](https://github.com/hermanya/friendly-github/graphs/contributors)!

## Related

- [Refined GitHub](https://github.com/sindresorhus/refined-github) - Improves GitHub
- [Awesome browser extensions for GitHub](https://github.com/stefanbuck/awesome-browser-extensions-for-github) - Awesome list
- [Octo Linker](https://github.com/octo-linker/chrome-extension/) - Navigate across files and packages
- [Notifier for GitHub](https://github.com/sindresorhus/notifier-for-github-chrome) - Shows your notification unread count
- [Do Not Merge WIP for GitHub](https://github.com/sanemat/do-not-merge-wip-for-github) - Prevents merging of incomplete PRs
- [Contributors on GitHub](https://github.com/hzoo/contributors-on-github) - Shows stats about contributors
- [Hide Files on GitHub](https://github.com/sindresorhus/hide-files-on-github) - Hides dotfiles from the file browser
- [Twitter for GitHub](https://github.com/bevacqua/twitter-for-github) - Shows a user's Twitter handle on their profile page
- [OctoEdit](https://github.com/DrewML/OctoEdit) - Markdown syntax highlighting in comments
- [GitHub Custom Tab Size](https://github.com/lukechilds/github-custom-tab-size) - Set custom tab size for code views *(Friendly GitHub hard-codes it to 4)*
- [Show All GitHub Issues](https://github.com/sindresorhus/show-all-github-issues) - Shows both Issues and Pull Requests in the Issues tab
- [Notifications Preview for GitHub](https://github.com/tanmayrajani/notifications-preview-github) - See your notifications on hover on all pages
- [Refined Twitter](https://github.com/sindresorhus/refined-twitter) - Improves Twitter
- [GitHub Issue Link Status](https://github.com/bfred-it/github-issue-link-status) - Colorize issue and PR links to see their status (open, closed, merged)
- [GitHub Follow](https://github.com/staff0rd/github-follow-extension) - Follow file renames on GitHub

## License

MIT
