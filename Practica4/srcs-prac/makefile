## *********************************************************************
##
## prácticas IG GIM (15-16) - makefile para las prácticas
## (Septiembre de 2015)
##
##  requiere:
##    glut (paquete freeglut)
##    opengl
##    package libjpeg-dev
##    opcionalmente: glew
##
## *********************************************************************

## ---------------------------------------------------------------------
## unidades a enlazar y nombre del binario ejecutable

target_name	:= prac
units_loc   := main practica1 Objeto3D MallaInd MallaPly MallaRevol MallaBarrida practica2 practica3 NodoGrafoEscena base brazo1 cilindro brazo2 tetraedro figura estructura practica4 Material MaterialEstandar Textura FuenteLuz ColeccionFL MaterialLata MaterialTapasLata MaterialPeonMadera MaterialPeonBlanco MaterialPeonNegro ContextoVis Lata Escena FuentePosicional FuenteDireccional
### nota: añadir a 'units_loc' los módulos practica2 practica3, etc.....

units       := jpg_imagen jpg_memsrc jpg_readwrite\
               shaders matrices-tr\
               file_ply_stl\
               aux

## ---------------------------------------------------------------------
## aspectos configurables

opt_dbg_flag  := -g
exit_first    := -Wfatal-errors
warn_all      := -Wall
extra_inc_dir := /opt/local/include

srcs_dir      := ../srcs
include_dir   := ../include
objs_dir      := ../objs

## ---------------------------------------------------------------------
## invocar las definiciones y targets en el archivo 'include.make'

include include.make
