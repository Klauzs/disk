# disk
new method of partition

Welcome to the disk wiki!

# disk is a package for creating partitions with disk partitions you can create quickly and easily .disco is an alternative to cfdisk!

the disc has been created to compete with fdisk
model:

disk

-b boot partition

-c common partition

-s swap partition

-d data slice(data partition)

-db Partition databases

!creating a partition:

disk -b p1 [990Mb]

disk -c p2 [20Gb]

disk -s p3 [1500Mb]

!formatting partition to another type:

format p1 ext4

format p2 swap

format p3 ext4

!Partitions are active in as they are created but not to take risks we do:

p1&boot

!active partition to boot and mount it automatically
