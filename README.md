# AVOtoken
dnf install python-avocado

make develop

avocado list

sudo curl https://avocado-project.org/data/repos/avocado-fedora.repo -o /etc/yum.repos.d/avocado.repo

sudo dnf repolist avocado 
...
repo id      repo name                          status
avocado      Avocado                            50

python-avocado-examples

sudo dnf install -y python2 git gcc python-devel python-pip libvirt-devel libffi-devel openssl-devel libyaml-devel redhat-rpm-config xz-devel
