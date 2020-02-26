# Free Image Hosting Uploading
Upload unlimited images right here right now.

# Virus Scan
[https://www.virustotal.com/gui/file/65ddc3956ad486e44d6169b3aee4f3ec0886f19deeb0550b7a011bdc7802f0f6/detection](https://www.virustotal.com/gui/file/65ddc3956ad486e44d6169b3aee4f3ec0886f19deeb0550b7a011bdc7802f0f6/detection)

# Syntax
```
NA.CX.EXE "<path-to-image>"
```

# Error
- The program will return exit code 1.

# Usage
- Copy program standard output.
- Capture program standard output.

# Example
```
> NA.CX.EXE "test.png"
https://na.cx/i/test.png
>
```
```
# python
import subprocess
image_url_string = subprocess.run('''NA.CX.EXE "test.png"''', shell=True, stdout=subprocess.PIPE).stdout.decode()
print(image_url_string)
# https://na.cx/i/test.png
```
