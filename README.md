# centos-rpm-unison251
CentOS 7 RPM Specfile for a modern 25.1.x
[Unison](https://www.cis.upenn.edu/~bcpierce/unison/) version, based on
[unison248 (#1544239)](https://bugzilla.redhat.com/show_bug.cgi?id=1544239#c2).


## Usage
There are pre-built binary packages for CentOS 7 available on [RaBe
miscellaneous package
repository](https://build.opensuse.org/project/show/home:radiorabe:misc), which
can be installed as follows:

```bash
# Add RaBe Misc repository
curl -o /etc/yum.repos.d/home:radiorabe:misc.repo \
     http://download.opensuse.org/repositories/home:/radiorabe:/misc/CentOS_7/home:radiorabe:misc.repo
 
# Install Unison
yum install unison-text

# Install the GTK frontend
yum install unison-gtk
```
