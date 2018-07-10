HM Base
=======

[![CircleCI](https://circleci.com/gh/humanmade/hm-base.png)](https://circleci.com/gh/humanmade/hm-base)

Standard WordPress layout for Human Made projects.

**Replace this readme in your project; you can use [the readme generator](https://humanmade.github.io/readme-creator/) for this.**

### Setup Instructions.

* Create an empty directory for your project. In terminal, navigate to this directory.
* Clone the repository `git clone --recursive git://github.com/humanmade/hm-base.git .`
* Remove the hm-base remote. `git remote rm origin`
* Add the remote for your new project `git remote add origin [url]`
* Push to the new remote `git push origin master`
	* Local site: `mv wp-config-sample.php wp-config-local.php`, then add your local database settings.

Done!

### Notes

* HM Base sets the MU Plugins directory to `plugins-mu` instead of `mu-plugins` for consistency.

## Contribution guidelines ##

see https://github.com/humanmade/hm-base/blob/master/CONTRIBUTING.md
