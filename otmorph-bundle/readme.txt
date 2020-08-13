This plugin will not run automatically run on GPU, to have it run on your GPU please do : 


TO USE CUPY (GPU computing) 

If you have cuda installed on your computer, first you must know which version of cuda is installed ('nvcc --version' in the command prompt),
then in bundle_info.xml in dependency, uncomment (remove <! -- - and  <--!> around) the line '<Dependency name="cupy-cuda102" version=">=0.1"/>' you must make sure that
the number after cuda is the same as your cuda version number (in my case v10.2 and 'cupy-cuda102') 

When done, restart chimeraX and re-run both "devel" commands 





