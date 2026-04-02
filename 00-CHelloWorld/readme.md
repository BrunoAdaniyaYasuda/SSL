### Compilador seleccionado
- **Compilador:** GCC (MinGW64, MSYS2)
- **Versión del compilador:** 15.2.0 
- **Versión de C compilada:** C23

### b. Compilar desde la línea de comandos
```
gcc -std=c23 hello.c -o hello
```

### c. Ejecutar y verificar
```
./hello
Hello, World!
```

### d. Redirigir salida a output.txt
```
./hello > output.txt
```

### e. Compilar con make (crédito extra)
```
make ./hello
cc    hello.c   -o hello
```

### f. Ejecutar con make (crédito extra)
```
./hello

```
