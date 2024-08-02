# github-upload

[source] (https://github.blog/open-source/git/bring-your-monorepo-down-to-size-with-sparse-checkout)

How to clone a repo with sparse checkout

1.  git clone --filter blob:none --sparse %url of the github repo%
2. cd sparse-checkout-example/
3.  git sparse-checkout init --cone
4. git pull origin main
5. git sparse-checkout set <dir1> /<dir2>
