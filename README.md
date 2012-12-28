lsgvt
=====

List Gluster Volume Toplogy

This program shows a pretty graphical representation of a Gluster
volume's topology. It uses the fuse-<volname>.vol file for it's
source. If you do not give any parameters, it shows the topology
for all the volumes. Otherwise it will show the topology for the
given space-separated list of volume names.

For the location of the input files, it uses '/var/lib/glusterd/vols'.
If your distribution has another location, this should be changed in
variable 'volpath'
