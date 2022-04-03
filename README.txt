`mdvl-umlet` package for UMLet, a tool to create UML Diagrams.
See <https://www.umlet.com/> and <https://github.com/umlet/umlet>.

Please prefer using the official Debian package if sufficient. See
<https://packages.debian.org/bullseye/umlet> and
<https://tracker.debian.org/pkg/umlet>.

This package builds only the `umlet-standalone` variant.

Install Debian packaging tools, a JDK, Ant and Maven and then create the package
as follows:

	$ ant package

To only compile the jar, use

	$ ant build

instead.
