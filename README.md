Physicist
### Hi there 👋

<!--
**glady12/glady12** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->@@ -1,33 +1,33 @@
import os,sys
import matplotlib.gridspec as gridspec
import matplotlib.pyplot as plt
import matplotlib.image as mpimg
import numpy as np

def logo():
    print " \n\n\n "
    print "      ___       ___           ___           ___"
    print "     /\__\     /\  \         /\  \         /\  \ "
    print "    /:/  /    /::\  \       /::\  \       /::\  \ "
    print "   /:/  /    /:/\:\  \     /:/\:\  \     /:/\:\  \ "
    print "  /:/  /    /::\~\:\  \   /:/  \:\  \   /:/  \:\  \ "
    print " /:/__/    /:/\:\ \:\__\ /:/__/_\:\__\ /:/__/ \:\__\ "
    print " \:\  \    \/__\:\/:/  / \:\  /\ \/__/ \:\  \ /:/  / "
    print "  \:\  \        \::/  /   \:\ \:\__\    \:\  /:/  / "
    print "   \:\  \       /:/  /     \:\/:/  /     \:\/:/  / "
    print "    \:\__\     /:/  /       \::/  /       \::/  / "
    print "     \/__/ __ _\/__/__ _ _ __\/____   ___ _\/__/ " 
    print "        | '_ ` _ \ / _` | '_ \| '_ \ / _ \ '__| "
    print "        | | | | | | (_| | |_) | |_) |  __/ | "
    print "        |_| |_| |_|\__,_| .__/| .__/ \___|_| "
    print "                        | |   | | "
    print "                        |_|   |_| "
    print (" \n\n\n ")
    print ("      ___       ___           ___           ___")
    print ("     /\__\     /\  \         /\  \         /\  \ ")
    print ("    /:/  /    /::\  \       /::\  \       /::\  \ ")
    print ("   /:/  /    /:/\:\  \     /:/\:\  \     /:/\:\  \ ")
    print ("  /:/  /    /::\~\:\  \   /:/  \:\  \   /:/  \:\  \ ")
    print (" /:/__/    /:/\:\ \:\__\ /:/__/_\:\__\ /:/__/ \:\__\ ")
    print (" \:\  \    \/__\:\/:/  / \:\  /\ \/__/ \:\  \ /:/  / ")
    print ("  \:\  \        \::/  /   \:\ \:\__\    \:\  /:/  / ")
    print ("   \:\  \       /:/  /     \:\/:/  /     \:\/:/  / ")
    print ("    \:\__\     /:/  /       \::/  /       \::/  / ")
    print ("     \/__/ __ _\/__/__ _ _ __\/____   ___ _\/__/ ") 
    print ("        | '_ ` _ \ / _` | '_ \| '_ \ / _ \ '__| ")
    print ("        | | | | | | (_| | |_) | |_) |  __/ | ")
    print ("        |_| |_| |_|\__,_| .__/| .__/ \___|_| ")
    print ("                        | |   | | ")
    print ("                        |_|   |_| ")
    return



logo()
comand='python mapingLAGO/AutoMap.py '
comand='python3 mapingLAGO/AutoMap.py '
comand2='python3 SitiosAlturas/plotalturas3.py '

for i in range(1, len(sys.argv)):
@@ -37,9 +37,9 @@ def logo():



print  "\n\n\ngenerando mapa..... "
print  ("\n\n\ngenerando mapa..... ")
os.system(comand) 
print "\n\n\ngenerando curva de alturas... \n\n\n"
print ("\n\n\ngenerando curva de alturas... \n\n\n")
os.system(comand2)

fig = plt.figure()

