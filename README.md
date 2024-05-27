# Association Translation App
Association Translation app for CENG599 Term Project METU 2023-2024 Spring Semester

Use below to create the translation web server.
pip install --upgrade pip
pip install -r requirements.txt
libretranslate --load-only uk,en --host 0.0.0.0 --port 10000 --debug
