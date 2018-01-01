# Rename photos to DateTime and organize in subfolders by Year/Month

exiftool '-FileName<DateTimeOriginal' -d %Y/%m/%Y%m%d_%H%M%S%%-c.%%e 
