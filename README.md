# manifest




Getting Started
---------------

To get started with the building process, you'll need to get familiar with [Git and Repo](http://source.android.com/source/using-repo.html).

To initialize your local repository, use a command like this:

    repo init -u git://github.com/OSNOS/manifest.git -b osnos-o

Then to sync up:

    repo sync  -f --force-sync --no-clone-bundle

Additionally, you can define the number of parallel download repo should do:

    repo sync -f -jX --force-sync --no-clone-bundle    ( X is the number of parallel download repo should do choose depending on your cpu )

 Compilation Of Rom
 ----------------------------------

From root directory of Project, perform following commands in terminal

	. build/envsetup.sh
   
    lunch osnos_$codename
   
	brunch $codename



For maintainership refer [**here**](https://github.com/OSNOS/android_vendor_osnos/blob/osnos-o/README.mkdn) 
