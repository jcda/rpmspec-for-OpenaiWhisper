# rpmspec-for-OpenaiWhisper

this is a rpm packaging around whisper for a podman instance I am using for a partner, as this is something that can be useful for anyone, I decided to put it in the whild.


I am downloading th python package from https://pypi.org/project/openai-whisper/#files and package it using the following steps:

sudo dnf install -y rpmdevtools rpmlint
rpmdev-setuptree
install the rpm.dev file as a non privileged user,
cd rpmbuild/SPEC
rpmbuild -ba whisper.spec


