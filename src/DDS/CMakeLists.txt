# Version chosen arbitrarily
CMAKE_MINIMUM_REQUIRED(VERSION 3.0)

# We don't need to add translations as the parent directory's CMakeLists has included this folder.

###############
## Installation

INSTALL(FILES
        ${CMAKE_CURRENT_SOURCE_DIR}/__init__.py
        ${CMAKE_CURRENT_SOURCE_DIR}/DDSDefinitions.py
        ${CMAKE_CURRENT_SOURCE_DIR}/DDSFile.py
        ${CMAKE_CURRENT_SOURCE_DIR}/glstuff.py
        DESTINATION bin/plugins/data/DDS)