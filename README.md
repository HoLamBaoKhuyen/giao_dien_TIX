# giao_dien_TIX

#một vài ghi chú về css
alt + shift + f

phân tích bố cục
chỉnh từ ngoài vào trong

 khi gắn absolute thì mất hết mặc định
------------
buổi 4
nhấn alt để sửa 1 lần nhiều chỗ
đặt tên class BEM
__ child : quan hệ cha con
--modify : class="header header--green"
class header--green được tạo ra sau

viết dính là cùng cấp, cách
------
ctrl shift p  -> auto chọn run
để thêm prefixer
autoprefixer
------
bôi đen sau đó
ctrl + d:


--------
sửa format code
có cần bấm ra hình ảnh
nút back to top
viền bản đồ
chuyển đổi background
-----------
bootstrap
margin là m-số (số từ 0 đến 1)
container là nội dung đẩy vào chính giữa
một khi dùng absolute thì ko cần dùng thêm display
data-ride dùng để auto chạy hình
d- để chỉnh display
w-0/25/50/75/100 là width
font-weigth-line
display-1/2/3/4 chỉnh font weight font size
----
để tạo lưới grid trong bootstraps, dùng row
.btn
.btn-màu
----------
>576 col-sm
>768 col-md
>992 col-lg
>1200 col-xl
-------
b4-$ -> enter
fa5-scc
-------
đặt tên _theme là file ẩn

mixin: text, btn, input...
splitting: theme, mixin, functions, header, footer, item

-----------------------------
JS
mở vsCode
-link -> cmd
gõ "code ."
--------
onClick="function()" gán vào thẻ
.style để chỉnh bên css
.innerHTML để chỉnh nội dung
.toLocalString đổi số thành chuỗi 10000 -> 10.000
--------
trong js dấu '/' là chia hết chứ ko phải chia lấy dư
Math.floor(num) -> làm tròn xuống
Math.round
Math.ceil

----------
chuyển thành chuỗi JSON khi lưu vào local storage
Lưu: setItem
Lấy: getItem

--------
function ABC(arr)
var arr || argument //nếu ko có truyền vào arr thì hàm nhận giá trị argument
hoặc
if(!arr){
arr = argument;
}
--------------
s=''||1 -> s = 1;
s=1||'' -> s = 1;
s=''&&1 -> s = '';
s=1&&'' -> s = '';
----------
var tmp = new RegExp(/^[A-Za-z ]+$/); //text only
tmp.test('khuyen) -> true;
tmp.test('khuyen123') -> false;
var tmp = new RegExp(/^[A-Za-z0-9 ]+$/); //text and number only
----------------
Task
- id
 title
- status
- changeStatus()
- add
- delete
- update (cho them but chi)
- render (2 ham render)
	+ render task da hoan thanh
	+ render task chua hoan thanh
	+ truoc khi render phải lọc ra task nào đã và chưa hoàn thành
----------------
1. mô hình
2. APIs
3. HTTP
4. axios
5. asynchronous
6. thực hành
7. promise
	+ pending
	+ resolve
	+ reject
-----------------
Những gì cần làm:
1. Giao diện
2. Phân rã lớp đối tượng
- Question: 
