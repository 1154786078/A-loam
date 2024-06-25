# A-loam

# The file A-LOAM-devel is an A-LOAM algorithm package which can be built in ubuntu20.04 and ros noetic environment.
# You should read the "readme.txt" in this file so you can understand how to install the raw A-LOAM.

# In our file,we change the CmakeLists.txt to ensure it can be built in our environment.
# A-LOAM can't save the results in kitti or tum format,so we add some lines to save the results in tum format including timestamped.

# You can run it in KITTI dataset or your own dataset,but take care of your LIDAR type,if not Velodyne or Ouster,it may have some issues
# However,our LIDAR type is LSLIDAR,it still have correct performance.

# So,just test it!
