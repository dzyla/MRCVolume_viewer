# MRCVolume viewer
Preview mrc volume in a simple viewer!

## Requirements
Python 3+ / numpy / vtkplotter / mrcfile / easygui (optional)

## How to
run the script via command line or double click the file (windows). Script should automatically guess the starting threshold value of the volume to create the isosurface. It can be changed with the slider at the botton and the color with one at the top. For more functionality coming from VTKplotter click h:


 Press: i     print info about selected object            
        m     minimise opacity of selected mesh           
        .,    reduce/increase opacity                     
        /     maximize opacity                            
        w/s   toggle wireframe/solid style                
        p/P   change point size of vertices               
        l     toggle edges line visibility                
        x     toggle mesh visibility                      
        X     invoke a cutter widget tool                 
        1-3   change mesh color                           
        4     use scalars as colors, if present           
        5     change background color                     
        0-9   (on keypad) change axes style               
        k     cycle available lighting styles             
        K     cycle available shading styles              
        o/O   add/remove light to scene and rotate it     
        n     show surface mesh normals                   
        a     toggle interaction to Actor Mode            
        j     toggle interaction to Joystick Mode         
        r     reset camera position                       
        C     print current camera info                   
        S     save a screenshot                           
        E     export rendering window to numpy file       
        q     return control to python script             
        Esc   close the rendering window and continue     
        F1    abort execution and exit python kernel      
 Mouse: Left-click    rotate scene / pick actors          
        Middle-click  pan scene                           
        Right-click   zoom scene in or out                
        Cntrl-click   rotate scene perpendicularly        

Check out documentation at:  https://vtkplotter.embl.es  |

