This sample app for provide an initialize for other samples or other projects

# Thêm thư mục **STATIC_ROOT** vào **settings.py**

```python
STATIC_ROOT = os.path.join(BASE_DIR, "static/")
```

Chạy lệnh `python manage.py collectstatic`, thư mục static sẽ tự động được tạo ra, nếu không có define trên thì khi chạy lệnh này sẽ báo lỗi.

Tất cả các file static sẽ được copy vào trong thư mục này. Tên thư mục có thể đặt tùy ý.
