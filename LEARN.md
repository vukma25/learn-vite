# tailwind v4 cấu hình khác hoàn toàn so với version cũ
## cấu hình và cài đặt xem trên trang docs của tailwind
### hiện tại đang cấu hình với postcss

file .env không bị ignore bởi git nên file thêm vào .gitignore
.env.local tự động ignore bởi git
.env mode hiển thị khi ở mode cụ thể như .env.development || .env.development.local chỉ hiện thị khi đang trong trạng phát triển
tương tự khi ở chế độ production

độ ưu tiên của các biên môi trường
script(trong scripts của package.json) > mode local > mode > local > env thường