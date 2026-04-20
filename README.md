# ngay-tan-the
Web truyện Gundam ngày tận thế
<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<title>Ngày Tận Thế</title>

<style>
body {
    margin:0;
    font-family: Arial;
    background:#0b0c1a;
    color:#eee;
    line-height:1.7;
}

nav {
    background:#111;
    padding:10px;
    text-align:center;
    position: sticky;
    top:0;
}
nav button {
    margin:5px;
    padding:10px 15px;
    background:#00ffe0;
    border:none;
    cursor:pointer;
    font-weight:bold;
}

.container {
    max-width:900px;
    margin:auto;
    padding:20px;
}

h1,h2 {
    color:#00ffe0;
}

.chapter {
    display:none;
    white-space:pre-line;
}

.active {
    display:block;
}

.character {
    background:#14152b;
    padding:15px;
    border-radius:10px;
    margin-bottom:20px;
}

img {
    width:100%;
    border-radius:10px;
    margin:10px 0;
}
</style>

<script>
function showChapter(id){
    let chapters = document.querySelectorAll(".chapter");
    chapters.forEach(c => c.classList.remove("active"));
    document.getElementById(id).classList.add("active");
}
</script>

</head>

<body>

<nav>
    <button onclick="showChapter('intro')">Nhân vật</button>
    <button onclick="showChapter('c1')">Chương 1</button>
    <button onclick="showChapter('c2')">Chương 2</button>
    <button onclick="showChapter('c3')">Chương 3</button>
    <button onclick="showChapter('c4')">Chương 4</button>
    <button onclick="showChapter('c5')">Chương 5</button>
    <button onclick="showChapter('end')">Chương cuối</button>
</nav>

<div class="container">

<!-- GIỚI THIỆU -->
<div id="intro" class="chapter active">
<h1>NGÀY TẬN THẾ</h1>
<p><i>Mùa đông năm 2070…</i></p>

<h2>Nhân vật</h2>

<div class="character">
<h3>Hồ Ngọc Diệp</h3>
<img src="https://images.unsplash.com/photo-1544005313-94ddf0286df2">
<p>Nữ – Tóc vàng – Phi công Gundam chính</p>
</div>

<div class="character">
<h3>Trương Thanh Huyền</h3>
<img src="https://images.unsplash.com/photo-1529626455594-4ff0802cfb7e">
<p>Con lai Việt Nhật – Bình tĩnh, quyết đoán</p>
</div>

<div class="character">
<h3>Phạm Hoàng Khanh</h3>
<img src="https://images.unsplash.com/photo-1500648767791-00dcc994a43e">
<p>Con lai Việt Úc – Trầm ổn</p>
</div>

<div class="character">
<h3>Châu Quốc Việt</h3>
<img src="https://images.unsplash.com/photo-1494790108377-be9c29b29330">
<p>Con lai Việt Trung – Ít nói</p>
</div>
</div>

<!-- CHƯƠNG 1 -->
<div id="c1" class="chapter">
<h1>Chương 1: Ngày đầu tiên</h1>
<p>
Tôi là Hồ Ngọc Diệp.

Sáng hôm đó, bầu trời xám đục như bị phủ một lớp tro bụi vô hình. Gió lạnh thổi qua sân huấn luyện rộng lớn của Học viện Phòng vệ Trái Đất, nơi mà từ nhiều năm trước, người ta đã chuẩn bị cho một điều mà ai cũng sợ gọi tên: ngày tận thế.

“Cậu là Diệp đúng không?”

Tôi quay lại. Một cô gái với mái tóc đen dài, ánh mắt bình tĩnh nhưng sắc bén đang nhìn tôi.

“Trương Thanh Huyền.” Cô ấy nói. “Tớ vừa từ Nhật về.”

Tôi gật đầu. Những người như cô ấy… như chúng tôi… đều là những người được chọn.

Không lâu sau, hai người còn lại xuất hiện.

Phạm Hoàng Khanh — cao, tóc nâu, ánh mắt trầm ổn.
Châu Quốc Việt — ít nói, nhưng ánh nhìn luôn quan sát mọi thứ.

Chúng tôi là một đội.

Và phía sau cánh cửa thép khổng lồ kia… là những cỗ máy khổng lồ — Gundam.
</p>
</div>

<!-- CHƯƠNG 2 -->
<div id="c2" class="chapter">
<h1>Chương 2: Dấu hiệu đầu tiên</h1>
<p>
Buổi huấn luyện đầu tiên chưa kết thúc thì còi báo động vang lên.

Âm thanh đó… không giống diễn tập.

“Mọi đơn vị vào vị trí! Vật thể không xác định xuất hiện ở tầng khí quyển!”

Tôi đứng chết lặng.

Không phải giả nữa rồi.

Tận thế… đến thật rồi.

Chúng tôi lao vào buồng điều khiển.

Khi hệ thống kích hoạt, cơ thể tôi như hòa làm một với Gundam. Từng chuyển động, từng nhịp tim… đều đồng bộ.

“Diệp, nghe rõ không?” Giọng Huyền vang lên trong bộ đàm.

“Rõ.”

“Khanh, Việt — đội hình chữ V!”

“Hiểu.”

Cửa hangar mở ra.

Bầu trời… không còn là bầu trời nữa.

Những sinh vật khổng lồ — như robot, nhưng méo mó và sống — đang rơi xuống từ không gian.
</p>
</div>

<!-- CHƯƠNG 3 -->
<div id="c3" class="chapter">
<h1>Chương 3: Ngày tận thế bắt đầu</h1>
<p>
Chúng tôi chiến đấu.

Không phải trong giả lập.

Mà là trong những con phố thật.

Những tòa nhà bị nghiền nát. Xe cộ cháy rụi. Thành phố… không còn là thành phố nữa.

Một con quái vật lao về phía tôi.

“DIỆP! TRÁNH RA!” — Khanh hét.

Tôi xoay người, kích hoạt lưỡi kiếm năng lượng.

XẸT—

Một nhát chém.

Nó gục xuống.

Nhưng ngay lập tức — ba con khác xuất hiện.

“Chúng đông quá…” Việt nói nhỏ.

“Không được lùi!” Huyền dứt khoát.

Tôi siết chặt cần điều khiển.

“Nếu đây là tận thế… thì chúng ta sẽ là người đứng đầu nó.”
</p>
</div>

<!-- CHƯƠNG 4 -->
<div id="c4" class="chapter">
<h1>Chương 4: Những ngày sau đó</h1>
<p>
Chúng tôi sống trong khu huấn luyện.

Ban ngày — chiến đấu.
Ban đêm — trở về ký túc xá.

Nhưng không ai ngủ ngon nữa.

Một đêm, tôi hỏi:

“Huyền… cậu có sợ không?”

Cô ấy im lặng một lúc.

“Có.”

“Nhưng nếu mình dừng lại… thì không còn ai bảo vệ được nữa.”

Khanh cười nhẹ: “Nghe như phim nhỉ.”

Việt chỉ nói một câu:

“Chúng ta là tuyến cuối rồi.”
</p>
</div>

<!-- CHƯƠNG 5 -->
<div id="c5" class="chapter">
<h1>Chương 5: Trận chiến lớn</h1>
<p>
Ngày thứ 7.

Một sinh vật khổng lồ — lớn hơn tất cả — xuất hiện.

Nó không chỉ là quái vật.

Nó… điều khiển những con khác.

“Đây chắc chắn là thủ lĩnh!” — Huyền nói.

“Vậy thì…” tôi hít sâu.

“Chúng ta kết thúc nó.”

Trận chiến kéo dài hàng giờ.

Gundam của Khanh bị hỏng một phần.

Việt bị đẩy lùi.

Huyền bị kẹt dưới đống đổ nát.

Tôi… là người còn đứng.

“Diệp…” giọng Huyền yếu dần. “Kết thúc nó đi…”

Tôi nhìn con quái vật.

Rồi lao lên.

Toàn bộ năng lượng dồn vào một đòn.

“VÌ TRÁI ĐẤT NÀY!”

ẦM—
</p>
</div>

<!-- CHƯƠNG CUỐI -->
<div id="end" class="chapter">
<h1>Chương cuối: Sau tận thế</h1>
<p>
Khi tôi tỉnh lại…

Bầu trời đã trong hơn.

Không còn sinh vật nào.

Chỉ còn lại chúng tôi.

Bị thương. Mệt mỏi.

Nhưng… còn sống.

Khanh cười:

“Chắc… chưa phải tận thế rồi.”

Huyền nhìn tôi:

“Nhưng nếu có lần nữa…”

Tôi mỉm cười.

“Chúng ta vẫn sẽ chiến đấu.”

Việt gật đầu:

“Đến khi không còn gì để mất.”

Người ta từng nghĩ tận thế là kết thúc.

Nhưng với chúng tôi…

Đó chỉ là ngày đầu tiên của một cuộc chiến mới.

Và tôi — Hồ Ngọc Diệp — sẽ tiếp tục chiến đấu.

Cho đến khi bầu trời thật sự bình yên.
</p>
</div>

</div>

</body>
</html>
