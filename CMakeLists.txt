find_package( OpenGL REQUIRED )
find_package( GLU    REQUIRED )
find_package( SDL2   REQUIRED )

add_subdirectory (SDL2)
add_subdirectory (SDL2OGL)
#add_subdirectory (SDL2OGL3)

add_subdirectory (GLView)
add_subdirectory (Vis3D)