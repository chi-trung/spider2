# spider2

Menu script Luau cho Roblox **Ouwland** — bản mã hóa (Ouwland Toolkit · Auto Farm).

## Loadstring

Chạy trong executor:

```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/chi-trung/spider2/main/main.luau"))()
```

## Tính năng — tab Auto Farm

- Bám dưới lòng đất ngay dưới chân quái, mặt hướng lên trên (sticky, không rơi/reset)
- Tự động đánh + tự xoay vòng skill **Z X C V B** mỗi lượt (bật/tắt được)
- Tự chuyển mục tiêu gần nhất khi con hiện tại chết
- Grace 6s sau khi giết: **nhặt đồ rơi (phím T, tự tạt lại gần drop)** + mở rương, xong mới chuyển quái
- Lọc boss theo máu: chỉ farm quái có MaxHealth ≥ ngưỡng (mặc định 3000)
- Slider độ sâu (2–15, mặc định 8) · slider ngưỡng máu tối thiểu (0–10000)
- Nút: chuyển mục tiêu ngay · dừng & nổi lên mặt đất

## Cấu trúc

| File | Mô tả |
| --- | --- |
| `main.luau` | Payload đã mã hóa (XOR + hex) — **không sửa tay** |
| `README.md` | Tài liệu này |
