#---------------------------------------------
# Macro declared in "DeclareMRPTLib.cmake":
#---------------------------------------------
define_mrpt_lib_header_only(
	# Lib name
	graphslam
	# Dependencies
	mrpt-slam
	# And deps of the deps:
	mrpt-bayes
	mrpt-graphs
	mrpt-vision
	mrpt-scanmatching
	mrpt-maps
	mrpt-obs
	mrpt-opengl
	mrpt-base
	)

IF(BUILD_mrpt-graphslam) 

ENDIF(BUILD_mrpt-graphslam) 

