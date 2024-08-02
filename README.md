# github-upload

[source](https://github.blog/open-source/git/bring-your-monorepo-down-to-size-with-sparse-checkout)

How to clone a repo with sparse checkout

- git clone --filter=blob:none --sparse %url of the github repo%
- cd sparse-checkout-example/
- git sparse-checkout init --cone
- git pull origin main
- git sparse-checkout set <dir1> /<dir2>
