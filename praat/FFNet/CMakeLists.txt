add_praat_subdir(SOURCES
	FFNet.cpp
	FFNet_Eigen.cpp FFNet_Matrix.cpp FFNet_PatternList.cpp
	FFNet_ActivationList_Categories.cpp FFNet_PatternList_ActivationList.cpp
	FFNet_PatternList_Categories.cpp
	praat_FFNet_init.cpp manual_FFNet.cpp
INCLUDE_DIRS
	kar melder sys dwtools fon dwsys stat gram
)
