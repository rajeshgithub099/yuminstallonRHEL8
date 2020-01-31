#Hii there are 2 repo i *rhel8* one is _AppStream_ & another is _BaseOS_
#before you configure *yum* in your system you must be _mount_ your cd permanently
__in the case of mine i prefer you create a directory *dvd* and _mount_ your cd on it__
#for _mount_ cd on your system command is *mount /dev/cdrom /dvd*
#Here is option named as _gpgcheck_ it means when you install your software from your cd then it check that *security key* of the package
#if you want to enabled it here is option *enabled* for yes its *1* or *yes*
#once you enabled _gpgcheck_ you must have to indicate a _gpgkey_
#_gpgkey_ means its a unique security key or identity ..all package under your cd have unique *gpgkey*
#Here is a location on RHEL8 where all *gpgkey* available thats _/etc/pki/rpm/RPM-GPG-KEY-redhat-release_
#_thanks for use my  repo_

