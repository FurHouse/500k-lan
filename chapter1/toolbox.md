# The Toolbox

To be able to test new stuff, a stable environment is required. At the moment,
my lab environment is made of the following components:

* _Foreman_: Lifecycle management. Foreman is used to provision servers, assign
nodes to groups and visualize Puppet report.

* _Puppet_: Configuration management. Puppet is used to describe the system
configuration of a (group) of server(s).

* _Hiera_: A key/value backend for Puppet. The configuration values for Puppet
modules are stored in Hiera. Used to seperate data and code. Hiera data is
maintained in a git repository.

* _Libvirt_: Virtualization API. Libvirt is used to manage QEMU/KVM. Foreman
controls Libvirt.

![workflow](http://bla/bla/bla "Fancy workflowdiagram aligned in the middle")
