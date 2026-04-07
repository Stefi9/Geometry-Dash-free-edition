----Geometry-Dash-(free-edition)--setup----

How to run it?
Step 1: Press and hold the Windows key and press R to open the run box (WIN + R).
Step 2: In the run box, type in 'appwiz.cpl' without the quotes.
Step 3: Inside the window that pops up, you need to search for 'Microsoft Visual C++ Redistributable' without in quotes.
Step 4: You should see 4 programs. Microsoft Visual C++ Redistributable 10.x (x86), Microsoft Visual C++ Redistributable 10.x (x64), Microsoft Visual C++ Redistributable 14.x (x64) and Microsoft Visual C++ Redistributable 14.x (x86) [The x can be anything, what matters is the main version before x.]
Step 5: If you see all 4 programs, you can move over to step 6. If not, go to the folder 'Dependencies' and download all the versions you need to download. Then navigate to step 6.
Step 6: After that, open up the run box again (WIN + R) and type in 'dxdiag' without the quotes. 
Step 7: In the window that pops up, go to the 'System' tab and under 'DirectX version:' you need to have something higher than 9.0.
Step 8: In the 'System' tab in the window, if it doesn't show 9.0 or above, you need to download the DirectX .exe inside the 'Dependencies' folder, then go to step 9. If it show's 9.0 or above, go to step 9.
Step 9: Open up command prompt (not as administrator) by opening run again (WIN + R) and typing in 'cmd /c if exist %WinDir%\System32\OpenAL32.dll (echo You can move over to step 11.) else (echo You need to move over to step 10.) & pause' without quotes. It will say in the terminal, if you have it installed. Then move to the steps shown.
Step 10: If the terminal window show's, that you need to go to step 10, then execute 'OpenAL.exe' inside the 'Dependencies' folder.
Step 11: If the terminal window show's, that you need to go to step 11, then go to step 12.
Step 12: After all those steps, go and open another run box and type in 'optionalfeatures.exe' without quotes. Then, you need to see, if .NET Framework 4.8 is checked. If yes, go to step 13. If not, go and check the box and follow the instructions prompted (or the .NET Framework exe inside the 'Dependencies' folder).
Step 13: The final dependency, is XNA. Open up another run box and type in 'if exist %WinDir%\Microsoft.NET\assembly\GAC_MSIL\Microsoft.Xna.Framework (echo XNA is installed, go to step 15.) else (echo XNA is not installed, go to step 14.)' without quotes.
Step 14: If the terminal window show's, that you need to go to step 14, then go to step 16.
Step 15: If the terminal window show's, that you need to fo to step 15, then install the 'XNA service' exe in the 'Dependencies' folder. Then after that, go to step 16.

Step 16 (Final): You are all set! After the installation, you are done with the full installation! If you had all the things I asked you to install aready, then you can directly play the game.