# TTCT
In order to help readers to read TTCT source code quickly, we write the following guide.
## 1.Development tool
The current version of TTCT is written in C code and developed in IDE (Microsoft Visual Studio 2010 Professional version). The solution file (TTCT.sln) can be found in the root directory. One can open the file TTCT.sln by Visual Studio 2010, and generate the solution directly. No further setting is needed for compile the solution. If any errors on lack of basic libraries when compiling the solution, please install them from the IDE.

## 2.Folder structure in the package

**ttct_src_20230514:   ----- root directory**

**TTCT.sln** ----- Microsoft Visual Studio Solution

**TTCT:**    ----- Folder for workspace

- DES Procedure: ---- Detailed codes for TTCT procedures

- TTCT Console:  ---- Detailed codes for TTCT console

    ctct.c: --- main function of TTCT; readers can trace the code starting from the main function
    
- Graphviz: ---- package of dot tool used for drawing figures of DES transition graphs
- TTCT.vcxproj   ----- VC++ Project file (auto-generated)
- TTCT.vcproj.filters  ---- VC++ Project file (auto-generated)
- TTCT.vcxproj.user  ----- VC++ Project file (auto-generated)

## 3.Citing the Software
Since a lot of time and effort has gone into the development, please cite the following publications if you are using the TTCT for your own research:
- W. Wonham. Design Software: TTCT, Systems Control Group, ECE Dept., University of Toronto, Toronto, ON, Canada, 2023. 

## 4.Contact
If readers have any questions on reading source code, please send email to me (Renyuan Zhang, ryzhang@nwpu.edu.cn).
