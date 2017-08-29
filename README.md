# Sam's Personal Path

I've got a directory in which I put short useful scripts I write, added to `$PATH`.

If you want to use these scripts:

1. clone this repo
2. add the following to your `.bashrc`/`.zshrc`/`.bash_profile` etc.
  ```bash
  export PATH=$PATH:<location of the personal path
  ```

Then either restart your terminal or `source` your `rc`/`profile` file and you're good to use the scripts from anywhere in your terminal.

## Current Scripts:
- `timecalc` - for taking harvest times, summing them and converting them to a xero time
- `tc` - a symlink for `timecalc`
- `aws_profiles` - show you what AWS profile you have set, what profiles are available, and remind you how to change it
