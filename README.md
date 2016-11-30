# vagrant-caps

a non-comprehensive yet usuable all-in-one dev environment for "CAPS" -- chef, ansible, puppet and salt on ubuntu (trusty as of Nov 2016)

 * mounts anisble directory. Do ansible-playbook or ansible command within your vagrant instance. If you accidentally/intentionally delete the vagrant and haven't committed changes it's still on your host machine.
 * sets vagrant user's environment variables based on vagrant host's env vars. Make use of the same keys from your host machine.
 * installs ansible into vagrant user's virtualenv
 * personal .vimrc settings