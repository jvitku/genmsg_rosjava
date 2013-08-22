This is just a small modificaiton of original genmsg, which can be found at: https://github.com/ros/genmsg/ .

This modificaiton helps to compile rosjava on OS X without problems. 


Some test files for testing generation of interfaces caused rosjava compilation to fail, so these files were renamed to be ignored by rosjava (and others):
  test/files/invalid/msg/BadDepend.msg
  test/files/invalid/msg/BadLocalDepend.msg
  test/files/test_ros/msg/Bad.msg


Modification by Jaroslav Vitku