# quake2_texture_fix
 quake2 bsp compiler converted to fix maps with capitals in there names that cause max_gltextures
 
 run compiler with -onlytextures and complete file name
 
 qbsp3_tex.exe -onlytextures "d:\games\quake2\baseq2\maps\yourmap.bsp"
 
 it will only write a new file if there is an issue
 new file will be named yourmap_fix.bsp
 checksum will be different so its renamed in case map has been released already
 
 
files obtained form GTKRadiant1.6.4 src
