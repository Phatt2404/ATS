# ÁN TRONG SƯƠNG

Ứng dụng React/Vite cho quy trình chọn thẻ nhân vật và kiểm tra chủ sở hữu.

## Chạy local
```bash
npm install
npm run dev
```

## Luồng chơi
1. Chọn một trong các thẻ nhân vật còn lại.
2. Xác nhận chủ sở hữu: người chơi khác / người chơi hiện tại / không ai sở hữu.
3. Nếu người chơi khác sở hữu: chủ sở hữu xòe hai lá bài Địa điểm và Hung khí, rồi chọn một lá để cho người chơi hiện tại xem.
4. Nếu người chơi hiện tại hoặc không ai sở hữu: chọn lại; thẻ nhân vật vừa kiểm tra bị loại khỏi lượt hiện tại.
5. Kết thúc để hiện màn hình mời mọi người tiếp tục ván chơi.

Thứ tự thẻ được xáo khi tải trang và lưu thứ tự gần nhất trong localStorage để tránh lặp nguyên thứ tự giữa hai lần tải liên tiếp.
