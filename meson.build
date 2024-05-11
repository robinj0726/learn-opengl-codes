project('LearnOpenGL', 'cpp',
    default_options : ['default_library=static'])

# Add your project configuration and build settings here

# Add your subprojects here
glew_subproject = subproject('glew')
glfw_subproject = subproject('glfw')

# Add your source files and dependencies here
glew_dep = glew_subproject.get_variable('glew_dep')
glfw_dep = glfw_subproject.get_variable('glfw_dep')

# Add your build targets and installation rules here
hello_window_exe = executable('hello-window', 'hello_window.cpp',
                              dependencies: [glew_dep, glfw_dep])