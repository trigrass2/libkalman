check_PROGRAMS=kalman sample-data kf-nonlinear ukf-nonlinear attitude
kalman_SOURCES=kalman.cpp
kalman_CXXFLAGS=-I../matrix/ -I../.. -I../include
kf_nonlinear_SOURCES=kf-nonlinear.cpp
kf_nonlinear_CXXFLAGS=--std=c++11 -I../matrix/ -I../.. -I../include
ukf_nonlinear_SOURCES=ukf-nonlinear.cpp
ukf_nonlinear_CXXFLAGS=--std=c++11 -I../matrix/ -I../.. -I../include
ukf_nonlinear_LDFLAGS=-ldl
sample_data_SOURCES=sample-data.cpp
sample_data_CXXFLAGS=-I../matrix/ -I../.. -I../include
attitude_SOURCES=attitude.cpp
attitude_CXXFLAGS=--std=c++11 -I../matrix/ -I../.. -I../include
TESTS=$(check_PROGRAMS)
EXTRA_DIST=kalman.in
