import os
import shutil

FILE_CATEGORIES = {
  "Images": [".jpg", ".jpeg", ".png", ".gif", ".bmp", ".svg"],
  "Documents": [".pdf", ".docx", ".txt", ".pptx", ".xlsx"],
  "Music": [".mp3", ".wav", ".aac"]
  "Videos": ["mp4", "mkv", ".mov"]
  "Archives": [".zip", ".tar", ".gz", ".rar"],
}

folder_path = input("Enter folder path to organize: ").strip()
files = [f for f on os.listdir(folder_path) if os.path.isfile(os.path.join(folder_path, f))]

for file in files:
  file_ext = os.path.splitext(file)[1].lower()
  moved = False
  for category, extensions in FILE_CATEGORIES.items():
    if file_ext in extensions :
    category_path = os.path.join(folder_path, category)
    os.makedirs(category_path, exist_ok=True)
    shutil.move(os.path.join(folder_path, file), os.path.join(other_path, file))
    




