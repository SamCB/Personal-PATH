# Sam's Personal Path

I've got a directory in which I put short useful scripts I write, added to `$PATH`.

If you want to use all of these scripts:

1. clone this repo
2. add the following to your `.bashrc`/`.zshrc`/`.bash_profile` etc.
  ```bash
  export PATH=$PATH:<location of the personal path
  ```

Then either restart your terminal or `source` your `rc`/`profile` file and you're good to use the scripts from anywhere in your terminal.

Alternatively, nothing stopping you from just downloading the ones that are useful for you.

## Current Scripts:
- `timecalc` - for taking one or more time periods in the format h:mm, summing them and converting them to hours in decimal
- `tc` - a symlink for `timecalc`
- `aws_profiles` - show you what AWS profile you have set, what profiles are available from `~/.aws/credentials`, and remind you how to change it
