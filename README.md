

### TEST
```bash
streamlit run app/processing.py
```

## run sever
```bash
python3 get_follower.py
```


## run stream camera
```bash
python3 stream_cam.py
```

note: có thể chọn các model để thử và sửa trong file main.py hàm load_model để test

link bcao


### Sử dụng app IP CAMERA trên android để stream camera
thay đổi ip trong code stream_cam.py đúng với ip hiển thị trong app

### gửi qua telegram
tạo file .env trong thư mục app trong đó có: TELEGRAM_TOKEN=token
                                              TELEGRAM_CHAT_ID=chat_id

## Chạy theo video path

terminal 1:

```bash
cd app
python3 server.py
```

terminal 2:

```bash
cd app
python3 stream_video.py
```
