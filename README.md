- Give a directory to organize
- list all the files in the directory and organize them in the follwing format

The following Folders will be created for every type of file
Compressed Folder
	- Compressed Files
Documents Folder
	- Text Files
	- Data Files
	- Spreadsheet Files
	- Page Layout Files
Audio Folder
	- Audio Files
Video Folder
	- Video Files
Image Folder
	- 3D Image Files
	- Raster Image Files
	- Vector Image Files
Developer Folder
	- Developer Files
	- CAD Files
	- Database Files
	- Web Files
	- Plugin Files
	- Font Files
Misc Folder
	- Executable Files
	- Game Files
	- GIS Files
	- System Files
	- Settings Files
	- Encoded Files
	- Disk Image Files
	- Backup Files
	- Misc Files

If a folder is empty, then that folder will not be created

How to program:

	- Create a list of all file types that will be in each folder
	- Ask the user for a directory
	- List all the files in the directory
	- Group elements of the list into folder lists by file extension
	- Make sure to delete elements of a list once moved
	- Make a folder for every folder list
	- If a folder list is empty, don't create that folder
	- Using the shutil.move method, move all files in each folder to their respective folders
	- Print completed afterwards
	