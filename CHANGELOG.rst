^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package ros_buildfarm
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Forthcoming
-----------
* fix navigation bar in the wiki to list the packages which are part of a meta package (`#193 <https://github.com/ros-infrastructure/ros_buildfarm/pull/193>`_)
* add check if any upstream project is in progress to prevent notification email for jobs known to fail and being retriggered anyway (`#194 <https://github.com/ros-infrastructure/ros_buildfarm/pull/194>`_)
* add subsections for "build", "build tests" and "run tests" in devel jobs (`#195 <https://github.com/ros-infrastructure/ros_buildfarm/pull/195>`_)
* fix environment for tests in devel and pull request jobs (`#196 <https://github.com/ros-infrastructure/ros_buildfarm/pull/196>`_)
* add "Queue" view to see all queued builds without the overhead of a job list (`#197 <https://github.com/ros-infrastructure/ros_buildfarm/pull/197>`_)
* fix reconfigure devel views (`#200 <https://github.com/ros-infrastructure/ros_buildfarm/pull/200>`_)
* wrapper script for "git clone" to retry in case of network issues (`#201 <https://github.com/ros-infrastructure/ros_buildfarm/pull/201>`_)

1.0.0 (2016-02-01)
------------------
* This is the first stable release. Please look at the git commit log for more information.