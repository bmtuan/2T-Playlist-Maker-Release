# Changelog

## v0.4.0 — 2026-11-26

- Đổi thứ tự bài trong playlist ngay ở màn Xem trước: kéo thả bằng tay nắm ⠿ ở đầu mỗi dòng
- Nút "Xáo lại thứ tự" để xáo ngẫu nhiên các bài của từng playlist
- Playlist có lặp: chỉ cần sắp các bài gốc, phần lặp tự đi theo thứ tự mới

## v0.3.0 — 2026-11-25

- Số lần lặp tùy chỉnh: phát các bài của mỗi playlist đúng N lần (A B C A B C…)
- Kết hợp với "Track / playlist" để lặp từng file thành video dài, VD mỗi file × 10 (khi đó bỏ qua Tối thiểu / Tối đa)
- Để "Track / playlist" = 0 thì app tự chọn số bài sao cho sau khi lặp vẫn nằm trong khoảng thời lượng

## v0.2.0 — 2026-11-21

- Loop cho đủ thời lượng: ít bài vẫn tạo được video dài, các bài trong playlist được lặp lại tới khi đạt thời lượng mong muốn (không vượt Tối đa)
- Chọn số track mỗi playlist (Track / playlist): mỗi playlist đúng N bài khác nhau, kết hợp với Loop để lặp N bài đó lên thời lượng mong muốn
- Tiêu đề, số bài và AI đặt tên tính theo số bài khác nhau, không đếm lần lặp

## v0.1.0 — 2026-11-20

Bản phát hành đầu tiên của 2T Playlist Maker.

- Ghép file âm thanh ngắn thành playlist dài (mặc định 1–2 giờ), đặt tên chuẩn SEO YouTube, kèm file mô tả có tracklist + timestamp
- Kích hoạt bằng license key (Licensify)
- AI đặt tiêu đề, mô tả, tags đi kèm license, không cần OpenAI API key
- Tự kiểm tra và cài bản cập nhật trong Cài đặt
- Giao diện gọn, không cần cuộn; danh sách file / xem trước / kết quả chia tab
