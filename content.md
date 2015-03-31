{{#template name="content"}}

#### Screenshot

![Screenshot of Meteor 1.1 on Windows](/image.png)

### Special Thanks

Thank you to Tom Wijsman and Stephen Darnell for their work on the community Windows port that was previously hosted on this page.

### Virtualized Solutions

There are currently two published Vagrant-based solutions for near fully automating provisioning of a headless virtualized Linux VirtualBox environment that will run Meteor and allow for the editing of the apps using Vagrant's Synced Folders. This allows for the use of Windows development tools from the local Windows host, and the live updating aspects of Meteor are preserved through to the Linux VM. These solutions require some pre-requisite installation.

#### Vagrant Shell Provisioning

Gabriel Pugliese has posted a guide for how to provision Meteor on Linux with Vagrant's Shell Provisioning. These may be more accessible to users familier with Linux and Shell scripts. This solution is easier to tweak through the straight forward shell commands than the Chef alternative.

[Vagrant Shell Provisioning Guide](http://goo.gl/clpKa)

#### Vagrant Chef Provisioning

Matthew Sullivan is maintaining a set of Vagrant files, Chef cookbook, and guide for provisioning Meteor on Linux with Vagrant. This Chef solution is a slightly more automated and configurable than the shell solution, however likely not as simple to tweak beyond the provided configuration parameters as the Shell solution.

[GitHub Repository: Vagrant Chef Provisioning](https://github.com/shoebappa/vagrant-meteor-windows)

{{/template}}