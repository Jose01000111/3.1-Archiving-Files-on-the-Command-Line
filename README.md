### 3.1 🗂️ Archiving Files on the Command Line (weight: 2)

**Weight:** 2  
**Description:** Archiving files in the user home directory  

**Key Knowledge Areas:**  
- 📁 Files, directories  
- 🗄️ Archives, compression  

**Partial List of Key Knowledge / Notes:**  
- **tar** 🛠️: Combines multiple files into a single archive (`.tar`).  
  - Example: `tar -cvf archive.tar file1 file2` → **c**reate, **v**erbose, **f**ile  
- **Common tar options** ⚙️:  
  - `-c` → create archive  
  - `-x` → extract archive  
  - `-t` → list archive contents  
  - `-v` → verbose output  
  - `-f` → specify filename  
- **gzip** 🔧: Compress `.tar` or individual files → `.tar.gz`  
  - Example: `tar -czvf archive.tar.gz file1`  
- **bzip2** 🧩: Higher compression → `.tar.bz2`  
  - Example: `tar -cjvf archive.tar.bz2 file1`  
- **xz** ❄️: Strong compression → `.tar.xz`  
  - Example: `tar -cJvf archive.tar.xz file1`  
- **zip** 📦: Creates compressed archive directly → `.zip`  
  - Example: `zip archive.zip file1 file2`  
- **unzip** 🗃️: Extract `.zip` archive  
  - Example: `unzip archive.zip`  

**⚡ Quick Tips / Practice Focus:**  
- 🆚 Know the difference between `tar` vs `zip` workflows  
- 🔄 Practice combining archiving + compression in one command  
- 👀 List contents of archives without extracting (`tar -tf archive.tar`)  
- 📝 Remember: gzip/bzip2/xz compress after archiving, zip does both in one
