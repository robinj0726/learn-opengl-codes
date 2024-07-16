# learn-opengl-codes

- [Learn OpenGL 中文版](https://learnopengl-cn.github.io/)
- [Learn OpenGL](https://learnopengl.com/Getting-started/OpenGL)

### Add Dependencies

for glfw,

```console
meson wrap install glfw
```

for glad, refer to [mesonbuild subprojects](https://mesonbuild.com/Subprojects.html)

## Build on Windows

```console
meson build --backend=vs
```
