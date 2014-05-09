This repository is designed to be used in conjuction with the MaidSafe
super-project at https://github.com/maidsafe/MaidSafe

When configuring the super-project, this repository is cloned into the build
root and can then be used by the 'CI_<Test type>_<Build type>.cmake' scripts to
run Continuous Integration tests.

The contents of this repository are kept separate from the super-project in
order to allow updating these without the need to update the super-project, and
vice-versa.  This means when testing these scripts, running a Continuous or
Nightly won't cause any git operations to be invoked on these scripts, making
maintenance less painful.
