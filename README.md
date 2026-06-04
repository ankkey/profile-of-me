# Chuyện của tớ

Bộ file này là một trang giới thiệu cá nhân tĩnh để đưa lên GitHub Pages.

## Cách dùng

1. Đưa toàn bộ các file trong thư mục này lên repository GitHub.
2. Vào `Settings` -> `Pages`.
3. Chọn branch chứa file `index.html`.
4. Mở link GitHub Pages mà GitHub tạo.

## Ảnh và video

Trang đang dùng các file:

```text
assets/sky.jpg
assets/portrait.jpg
assets/video.mp4
```

Nếu muốn thay ảnh hoặc video, giữ nguyên tên file để trang tự nhận.

## Chỉnh hiệu ứng trong Antigravity

Mở `script.js` và chỉnh phần:

```js
const animationConfig = {
  revealThreshold: 0.16,
  parallaxStrength: 48,
  cursorGlow: true,
};
```

- `revealThreshold`: section xuất hiện sớm/muộn khi cuộn.
- `parallaxStrength`: độ trôi của hình ảnh/khối trang trí.
- `cursorGlow`: bật/tắt ánh sáng chạy theo chuột.

Màu sắc và bố cục nằm trong `styles.css`, nội dung nằm trong `index.html`.
