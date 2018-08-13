import zipfile
import os
print("make sure this is running in the same directory as your appx file")
appxfile=input("please enter the file name of the appx you want to unpack: ")
folder=appxfile.replace(".appx","")
folder=folder.replace("bundle", "")
if not os.path.exists(folder):
    os.makedirs(folder)
zip_ref = zipfile.ZipFile(appxfile, 'r')
zip_ref.extractall(folder)
zip_ref.close()
print ("Your Appx file was dumped to a new folder named " + folder)
