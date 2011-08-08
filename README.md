phix-manual
===========

phix is a general-purpose, easily-extensible command-line tool for PHP. It has the advantage of being framework-agnostic, allowing you to create your own command-line tools today that will not break when you upgrade or switch frameworks.

This is the docbook source code for the online manual for phix.

Development Environment
-----------------------

If you want to patch or enhance this component, you will need to create a suitable development environment:

    # phing
    sudo pear channel-discover pear.phing.info
    sudo pear install --alldeps phing/phing

    # phix
    sudo pear channel-discover pear.phix-project.org
    sudo pear install --alldeps stuartherbert/phix

You can then clone the git repository:

    # phix-manual
    git clone git://github.com/stuartherbert/phix-manual.git

Then run phing to see the targets available:

    # rebuilding the manual
    phing lint
    phing compile
