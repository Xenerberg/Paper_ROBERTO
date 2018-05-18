Compilation commands:

bibtex root
latex root   
dvips root
ps2pdf root.ps root.pdf
okular root.pdf &


Figures:
1. note that the text in the figures is introduced with latex texts in the Text files
2. to regenerate them, go to:
	i. /volume/USERSTORE/f_deosim/Phillip/svn/icra17/EKF_Motion_parameter_Est/Paper_Roberto: script_plot_Target_motion.m or script_plot_joint_motion_2subplots.m
	ii. /home/lampo/ROBOTPROJECTS/TECSAS/SIMULATOR/src/PATH_PLANNING_DEOS_SIM_ptp_nonzero_vel/DATA: Plot_joints_vel_IROS_RAL.m


git instructions:

1. do 'git pull' when starting working
2. after changes do:
	0. git status
	i. git add namefile
	ii. git commit -m 'message'
	iii. git push
3. verify in repository if changes are there
	i. go to http://rmc-github.robotic.dlr.de/ in Firefox
	ii. go to Paper_RAL Repo
	iii. check contents
