# DevOps Engineer Homework — Task D
##1. Pipeline Testing
I tested the Jenkins pipelines by triggering builds manually through Jenkins and reviewing the console output. I checked the execution of each stage and verified that the expected output files were generated correctly.

##2.RepoC Python Testing
I tested the Python script using sample Doxygen warning logs. I verified that the script correctly identified warning messages, ignored irrelevant lines.

##3.Advantages of Git LFS
Reduces the size of the Git repository and Makes downloading and updating the repository more efficient.

##4.Configuring Git LFS
1.provide links
https://git-lfs.com/

2. how to use git LFS
Step 1: Install Git LFS
```bash
git lfs install
```
Step 2: Configure File Tracking
```bash
git lfs track "*.pdf"
git lfs track "*.zip"
git lfs track "*.png"
```
Step 3: Commit Configuration
```bash
git add .gitattributes
git add .
git commit -m "Enable Git LFS for binary files"
git push
```

3.Are there other (easier) alternatives?
gitignore - ใช้ง่าย เก็บข้อมูลบน GitHub ไม่ได้ ลดไฟล์บน Git ได้
 หรือใช้ Cloud storage 

