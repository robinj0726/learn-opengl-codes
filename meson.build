project('LearnOpenGL', 'cpp',
    default_options : ['default_library=static'])

# Add your project configuration and build settings here

# Add your subprojects here
glfw_subproject = subproject('glfw')
glad_subproject = subproject('glad')

# Add your source files and dependencies here
glfw_dep = glfw_subproject.get_variable('glfw_dep')
glad_dep = glad_subproject.get_variable('glad_dep')

# Add your build targets and installation rules here
hello_window_exe = executable('hello-window', '01-hello_window.cpp',
                              dependencies: [glad_dep, glfw_dep])