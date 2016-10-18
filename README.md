# ghost-slack-hooks

slack hooks for [gh-ost](https://github.com/github/gh-ost)


## Usage

```sh
git clone https://github.com/wistia/ghost-slack-hooks.git
echo MY_SLACK_WEBHOOK_URL > .slack_url
gh-ost --hooks-path=hooks --hooks-hint=<SLACK_NAME>
```
