# Dự án NER Y Tế (PhoBERT + CRF)

Đây là dự án nhận diện thực thể y tế...

## Hướng dẫn cài đặt

1.  Clone repo này: `git clone ...`
2.  **Tải file model:** Tải các file model đã huấn luyện tại: https://drive.google.com/drive/u/0/folders/1Hp9ajj2YmyalQGOI78JHd3zpMZ0GavVg
3.  **Quan trọng:** Đặt 3 file model (`model.pt`, `crf_model.pkl`, `crf_preprocessor.pkl`) vào thư mục `models/best_model/`.
4.  Cài đặt thư viện: `pip install -r requirements.txt`
5.  Chạy server: `uvicorn api_server:app --host 127.0.0.1 --port 8001`
6.  Mở file `static/index.html` bằng Live Server.