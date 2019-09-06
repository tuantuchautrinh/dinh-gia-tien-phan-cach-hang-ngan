# Định giá tiền phân cách hàng ngàn
js hàm định giá tiền phân cách hàng ngàn

### <script>
### function format_curency(a) {
###   	a.value = a.value.replace(/(\d)(?=(\d{3})+(?!\d))/g, "$1.");
### }
### </script>

### <input  onChange="format_curency(this);" type="text">

Đoạn javascript trên khi chạy sẽ xuất hiện một textbox cho chúng ta nhập số tiền vào. Khi nhập xong và con trỏ rời khỏi textbox thì giá trị trong textbox sẽ hiển thị dạng tiền tệ với phân cách phần ngàn.

## Chú ý:

### Nếu các bạn muốn đổi dấu '.' thành dấu ',' trong phân cách phần ngàn thì các bạn có thể thay đổi "$1." thành "$1,"

### -- via: http://laptrinhphp.info/JavaScript/javascript-dinh-dang-tien-phan-cach-phan-ngan.html --
