# V3 — Kiểm tra chất lượng

- Video: **60,000 giây**, 1.800 frame, 1080 × 1920, 30fps, H.264; âm thanh AAC 48kHz, dài 60 giây.
- Giải mã toàn bộ file: đạt; quét khung đen: không phát hiện khoảng đen theo ngưỡng quét. Mức đỉnh âm thanh: -2.4 dBFS; mức trung bình: -13.7 dBFS.
- Rà hình: 60 ảnh xuyên suốt timeline, trung điểm của cả 23 shot, các đoạn ứng viên bổ sung, bố cục cảnh kết ở kích thước xuất. Các ảnh này được lưu trong thư mục QC cục bộ.
- Typewriter: kiểm tra 251 frame nguồn và 251 frame đã giải mã. Các glyph được đặt theo kerning và tọa độ cố định; ký tự cũ không bị vẽ lại khi thêm ký tự mới. Kiểm tra độ ổn định nét chữ đạt, có dung sai cho nhiễu biên do nén H.264. OCR trên frame cuối đọc đúng câu chúc và ngày.
- Câu chúc và ngày hiện đầy đủ tại **57,733 giây**; giữ nguyên **2,267 giây** cuối. Không tiếp tục gõ trong khoảng 58–60 giây.
- Nhạc dùng đúng MP3 được cung cấp, đoạn liên tục 41,755102–101,755102 giây, không đổi tốc độ. Dùng dữ liệu onset, nhịp khoảng 79,13 BPM và ước lượng phách nhấn để hỗ trợ điểm cắt. Ước lượng phách nhấn từ năng lượng bass không tương đương xác nhận cấu trúc ô nhịp bằng tai.
- Giới hạn: môi trường không hỗ trợ lượt phát nghe/xem thời gian thực. Báo cáo này xác nhận giải mã, thông số, kiểm tra hình trích xuất và kiểm tra animation; không tuyên bố đã nghe/xem liền mạch toàn bộ video.

Thông số máy đọc: `quality_control/verification_summary.json`. Chi tiết animation: `typewriter_validation.json`.
