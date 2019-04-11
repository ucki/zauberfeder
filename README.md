# zauberfeder
My OSCP report template in LaTex

The basic idea is that every host gets a own folder (just copy the example).
While doing the machine the documentation goes into the file.

Steps to create a new host for the report:

1. copy the example folder and rename the folder to the machine name, ucki as a example.
2. go to host.tex in the folder ucki , change the \hostname from example to ucki  
3. write all the infos about the machine into the host.tex
4. toggle (%) if you needed a priv esc or not
5. overwrite the screenshots in the folder with the coresponding screenshots from the machine
6. Include the  \ucki\host.tex in your main document
7. Go through your pdf .. if you see solid color screenshots you have missed mandatory screenshots
