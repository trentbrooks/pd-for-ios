
Edit - this fork of libpd is up to date with libpd master as of 3rd April 2015. Includes the recent fixes for 64 bit/arm64 compatibilty for ios.

After cloning the pd-for-ios repository, please make sure to cd into the
pd-for-ios folder and say
  git submodule init
  git submodule update
These two commands install the dependencies from libpd.  After the initial
setup, say
  git pull
  git submodule update
whenever you want to sync with the GitHub repositories.

