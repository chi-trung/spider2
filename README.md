# spider2

Menu script Luau cho Roblox **Ouwland** — bản mã hóa (Ouwland Toolkit · Auto Farm).

## Loadstring

Chạy trong executor:

```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/chi-trung/spider2/main/main.luau"))()
```

## Tính năng — tab Auto Farm

- Bám dưới lòng đất ngay dưới chân quái, mặt hướng lên trên (sticky, không rơi/reset)
- Tự động đánh, tự chuyển mục tiêu gần nhất khi con hiện tại chết
- Grace 3s sau khi giết: tự mở rương + nhặt loot rồi mới chuyển
- Slider độ sâu (2–15, mặc định 8)
- Nút: chuyển mục tiêu ngay · dừng & nổi lên mặt đất

## Cấu trúc

| File | Mô tả |
| --- | --- |
| `main.luau` | Payload đã mã hóa (XOR + hex) — **không sửa tay** |
| `README.md` | Tài liệu này |
