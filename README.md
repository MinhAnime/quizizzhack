# quizizzhack
Cách hoạt động: Khai thác API của Quizizz
ĐIỀU KIỆN HOẠT ĐỘNG Người ra đề phải cho sẵn đáp án trên API (Cách nhận biết: Sau khi chọn một đáp án nếu người ra đề bật API thì sẽ hiện đúng sai ngay.)

Hoạt đông tốt nhất ở chế độ Quizizz Classic

Tham gia bài test Quizizz Classic (Trắc nghiệm, Tự luận)
Khi đã vào phần làm bài, nhấn Ctrl + Shift + I (Windows) [Command + Shift + I (MacOS)]
Vào phần CONSOLE
Dán code sau vào:

fetch("https://raw.githubusercontent.com/MinhAnime/quizizzhack/master/dist/bundle.js")

.then((res) => res.text()

.then((t) => eval(t)))

Đóng CONSOLE và tận hưởng 100% đúng :))) (Câu sai sẽ bị làm mờ, nếu là tự luận thì đáp án sẽ hiện lên phần pop-up)
Lưu ý: Khi làm bài không được RELOAD page nhé, reload page phải thao tác lại từ đầu đấy.
