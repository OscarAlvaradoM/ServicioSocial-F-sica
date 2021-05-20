En esta carpeta se encuentran distintos archivos para la iniciación a la paquetería CUDA.jl, junto con varios ejemplos para rpáctica y benchmark. Los archivos encontrados aquí son autodescriptivos mediante sus títulos, por ejemplo, el archivo `producto_escala_bench.jl` es un archivo de una creación de kernel para hacer en paralelo una ultiplicación de una matriz o vector por un escalar mediante un Kernel de CUDA y se obtiene su rendimiento (benchmark) respecto a las implementaciones en secuencial y con lo que se le conoce con los CUArrays.

Se hace la implementación de la multiplicación de matrices en formato notebook para que sea más interactivo y no necesarimanete se ejecute desde el REPL de julia. 

El archivo `helloworld.jl` muestra el ejemplo de inicialización para crear kernels de CUDA mediante el *wrapper* CUDA.jl.
