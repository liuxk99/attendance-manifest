# attendance-manifest

## Configuration Management
### ssh configuration
~/.ssh/config
```
Host github
	Hostname github.com
	User git
	IdentityFile ~/.ssh/$private_key
```
You should replace $private_key with your own private key file for github account.

### Download source code
```
repo init -u github:liuxk99/attendance-manifest --repo-url=~/bin/git-repo --no-repo-verify
repo init --config-name
repo sync
repo start dev --all
```
