# Campus Academic Manager (CAM)

A console Java application for managing students, courses, and enrollments.  
Distinct version for project submission.

## Build & Run
```
cd src
javac -d ../out $(find . -name "*.java")
java -cp ../out edu.cam.cli.App
```

## Features
- Add/list students & courses
- Enroll students and record scores
- Transcript-style info shown in student details
- Builder, Singleton-like repository, enums, and more
