cmake_minimum_required(VERSION 3.7)
project(nlohmann-json)
install(
	FILES ${PROJECT_SOURCE_DIR}/json.hpp
	DESTINATION include/nlohmann)
