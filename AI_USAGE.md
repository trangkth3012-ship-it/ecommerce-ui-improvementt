# AI_USAGE.md — Báo Cáo Phân Tích UI/UX Website TH True Mart

## 1. Thông Tin Chung
* **Công cụ AI sử dụng:** Gemini
* **Mục đích sử dụng:** Hỗ trợ phân tích giao diện và trải nghiệm người dùng (UI/UX) của website thương mại điện tử **TH true mart** ([https://thtruemart.vn/](https://thtruemart.vn/)) tại 5 khu vực trọng tâm: Trang chủ, Danh mục sản phẩm, Chi tiết sản phẩm, Tìm kiếm và Giỏ hàng.

---

## 2. Prompt Đã Sử Dụng

```text
Bạn là chuyên gia phân tích nghiệp vụ và thiết kế trải nghiệm người dùng cho website thương mại điện tử.
Tôi đang khảo sát website: TH true mart – https://thtruemart.vn/. 
Hãy giúp tôi lập bảng phân tích các khu vực:
1. Trang chủ
2. Danh mục sản phẩm
3. Chi tiết sản phẩm
4. Tìm kiếm
5. Giỏ hàng

Với mỗi khu vực, hãy nêu:
- Mục đích của chức năng
- Thành phần giao diện cần có
- Điểm thuận tiện đối với khách hàng
- Một vấn đề có thể phát sinh
- Một đề xuất cải tiến
```

---

## 3. Kết Quả Do AI Đề Xuất

| Khu vực | Mục đích | Thành phần giao diện | Điểm thuận tiện | Vấn đề có thể phát sinh (AI gợi ý) | Đề xuất cải tiến (AI gợi ý) |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **1. Trang chủ** | • Thu hút sự chú ý.<br>• Điều hướng nhanh đến danh mục/ưu đãi.<br>• Xây dựng niềm tin thương hiệu. | Header/Mega Menu, Banner Slider, Khối danh mục nổi bật, Sản phẩm Bán chạy/Mới nhất, Cam kết chất lượng, Footer. | Bố cục trực quan, nhận diện thương hiệu rõ ràng (màu xanh tươi mát). Giúp tiếp cận nhanh sản phẩm chủ lực. | Trang chủ bị quá tải thông tin, nhiều banner động gây nhiễu cho người mua nhanh. | Tối ưu hóa phân cấp thị giác (visual hierarchy) theo dạng Z/F-pattern để làm nổi bật sản phẩm cốt lõi. |
| **2. Danh mục sản phẩm** | • Duyệt sản phẩm theo phân loại logic.<br>• Lọc thu hẹp phạm vi tìm kiếm. | Breadcrumb, Bộ lọc đa tiêu chí (giá, dung tích, hương vị), Sắp xếp, Lưới sản phẩm (Grid), Phân trang/Xem thêm. | Lọc sâu theo đặc tính F&B (dung tích, đóng gói lốc/thùng) giúp tiết kiệm thời gian. | Bộ lọc phản hồi chậm hoặc tải lại trang (full reload) gây ngắt quãng trải nghiệm. | Áp dụng kỹ thuật lọc không đồng bộ (AJAX filtering) để cập nhật kết quả tức thì. |
| **3. Chi tiết sản phẩm** | • Cung cấp đầy đủ thông tin để thuyết phục mua.<br>• Kích thích thêm giỏ hàng/mua ngay. | Ảnh/Video, Tên/SKU/Giá, Chọn thuộc tính (dung tích/hương vị), Số lượng & Nút Mua, Mô tả/Dinh dưỡng, Sản phẩm liên quan. | Minh bạch thông tin dinh dưỡng và thành phần – yếu tố then chốt của ngành F&B. | Thiếu phần đánh giá/review thực tế từ người đã mua hàng, giảm social proof. | Bổ sung module Đánh giá & Bình luận kèm ảnh thực tế, tích hợp khối FAQ ở dưới. |
| **4. Tìm kiếm** | • Tìm chính xác sản phẩm nhanh chóng.<br>• Gợi ý từ khóa thông minh. | Ô tìm kiếm trên Header, Gợi ý từ khóa hot, Khung Auto-suggest dropdown (ảnh, tên, giá), Trang kết quả tìm kiếm. | Hỗ trợ tìm kiếm nhanh, giảm bớt thời gian gõ phím. | Kém thông minh khi gặp lỗi chính tả/viết tắt, trả về kết quả "Không tìm thấy". | Tích hợp công nghệ tìm kiếm mờ (fuzzy search) và cơ chế gợi ý từ đồng nghĩa ("Ý bạn là..."). |
| **5. Giỏ hàng** | • Rà soát lại sản phẩm đã chọn trước thanh toán.<br>• Điều chỉnh số lượng/xóa linh hoạt. | Danh sách sản phẩm (ảnh, giá, số lượng), Tăng/giảm số lượng, Mã giảm giá, Tóm tắt đơn hàng, Nút "Thanh toán". | Hiển thị rõ các khoản phí, thay đổi số lượng trực tiếp không cần đổi trang. | Khách hàng dễ quên mốc giá trị đơn hàng để được Free Shipping. | Hiển thị thanh tiến trình (progress bar) tính số tiền còn thiếu để đạt mốc Miễn phí vận chuyển. |

---

## 4. Kiểm Tra, Đánh Giá Và Điều Chỉnh Thực Tế

Sau khi đối chiếu trực tiếp giao diện và trải nghiệm thực tế trên website [https://thtruemart.vn/](https://thtruemart.vn/), tôi đánh giá kết quả từ AI như sau:

### 4.1. Những điểm ĐỒNG TÌNH và XÁC NHẬN thực tế
* **Trang chủ (Bố cục & Nhận diện):** Đồng tình hoàn toàn với nhận định bố cục trực quan, màu sắc xanh lá đặc trưng giúp tiếp cận nhanh các chương trình khuyến mãi và dòng sản phẩm chính.
* **Chi tiết sản phẩm (Thiếu Đánh giá/Review):** Xác nhận đúng thực tế. Trang chi tiết sản phẩm của TH true mart cung cấp rất tốt thông tin dinh dưỡng và quy cách, nhưng hiện tại **chưa có tính năng Đánh giá & Bình luận (Review/Rating)** từ người mua thực tế.
* **Tìm kiếm (Tính tiện lợi):** Xác nhận thanh tìm kiếm đặt ở vị trí dễ thấy trên Header, hỗ trợ tìm kiếm nhanh tiện lợi.
* **Giỏ hàng (Đề xuất tiến trình Free Shipping):** Đề xuất hiển thị thanh tiến trình mua thêm để đạt mốc Miễn phí vận chuyển là rất thực tế và nâng cao trải nghiệm mua sắm.

### 4.2. Những điểm KHÔNG ĐỒNG TÌNH / ĐÃ SỬA ĐỔI so với AI
1. **Trang chủ — Nhận định quá tải thông tin:** 
   * **Không đồng tình.** Thực tế kiểm tra cho thấy trang chủ TH true mart được thiết kế khá tối giản, khoảng trắng hợp lý, phân khu rõ ràng, không bị rối mắt hay quá tải thông tin như AI dự đoán.
   * **Điều chỉnh:** Giữ nguyên thiết kế bố cục hiện tại, không cần thu gọn hay cắt giảm khối thông tin.
2. **Danh mục sản phẩm — Bộ lọc thuộc tính:**
   * **Không đồng tình một phần.** AI gợi ý trang có bộ lọc đa tiêu chí linh hoạt (dung tích, bao bì, hương vị...), nhưng thực tế website chủ yếu phân loại theo cây danh mục cố định, bộ lọc thuộc tính nâng cao chưa phong phú.
   * **Điều chỉnh:** Đưa việc bổ sung "Bộ lọc thuộc tính F&B chuyên sâu" thành đề xuất cải tiến thay vì coi đó là tính năng đã có.
3. **Tìm kiếm — Lỗi xử lý sai chính tả:**
   * **Không đồng tình.** AI đánh giá công cụ tìm kiếm kém thông minh và hay trả về lỗi khi gõ sai, tuy nhiên thực tế công cụ tìm kiếm của trang hoạt động khá ổn định với các từ khóa thông dụng.
   * **Điều chỉnh:** Bỏ qua vấn đề lỗi chính tả, chuyển hướng cải tiến sang việc hiển thị hình ảnh sản phẩm (thumbnail) rõ nét hơn ở khung gợi ý nhanh.

---

## 5. Kiến Thức HTML/CSS Đã Hiểu Và Giải Thích ĐƯỢC

Qua việc đối chiếu giao diện TH true mart, tôi đã nắm vững các kỹ thuật HTML/CSS được ứng dụng để dựng nên các khu vực trên:

### 5.1. Cấu trúc Semantic HTML5 & Layout
* **HTML Semantic Tags:** Website sử dụng các thẻ chuẩn như `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>` giúp phân chia bố cục rõ ràng và tối ưu SEO.
* **Flexbox (Header & Navigation):**
  ```css
  .header-container {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  ```
  *Giúp căn chỉnh Logo, Thanh tìm kiếm và Giỏ hàng nằm thẳng hàng trên một dòng ngang.*

* **CSS Grid (Danh sách sản phẩm):**
  ```css
  .product-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 20px;
  }
  ```
  *Giúp các thẻ sản phẩm tự động chia cột linh hoạt và co giãn tương thích trên nhiều màn hình (Responsive Design).*

### 5.2. Định dạng thành phần UI
* **Thẻ sản phẩm (Product Card):**
  * Sử dụng cấu trúc HTML gồm `<div class="product-card">` chứa `<img>`, `<h3 class="title">`, `<span class="price">` và `<button class="btn-add">`.
  * Hiệu ứng rê chuột (Hover effect):
    ```css
    .product-card {
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }
    
    .product-card:hover {
      transform: translateY(-5px);
      box-shadow: 0 8px 16px rgba(0, 0, 0, 0.1);
    }
    ```

* **Thanh Header cố định (Sticky Header):**
  ```css
  .site-header {
    position: sticky;
    top: 0;
    z-index: 1000;
  }
  ```
  *Giúp menu chính luôn ghim lại ở mép trên màn hình khi người dùng cuộn chuột xuống dưới.*
