
cmake_minimum_required(VERSION 3.1)
Project(Test)
set(MAINSRC
	src/main.cpp
)

#========== main executable =================
add_executable(
	test
	${MAINSRC}
)

