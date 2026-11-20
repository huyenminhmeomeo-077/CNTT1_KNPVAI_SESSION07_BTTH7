## Thiết kế AI Gia sư giúp tụi mình hiểu và sửa lỗi code C

### 1. Chuyện gì đang xảy ra ?

Tôi là sinh viên năm 1 mới tập code C. Thầy/cô giao bài tính điểm trung bình của 3 môn. Tôi viết code xong, chạy thử với `7`,  `8`,  `9` thì máy in ra `8` thay vì `8.0`. Tôi muốn tự hiểu xem sai ở đâu chứ không muốn nhờ AI làm hộ từ A đến Z.

  Code tôi viết:
C

```
#include <stdio.h>

int main() {
    int a, b, c;
    int avg;

    printf("Nhap 3 diem: ");
    scanf("%d%d%d", &a, &b, &c);

    avg = (a + b + c) / 3;

    printf("Diem trung binh: %d", avg);

    return 0;
}

```
### 2. Luật chơi cho AI Gia sư

-   Chỉ làm việc với ngôn ngữ **C**.
    
-   AI **không** được viết lại cả bài code ngay từ đầu.
    
-   AI **không** được đưa đáp án liền khi tôi chưa thử tự giải thích.
    
-   Mỗi lần AI chỉ hỏi **1 câu thôi** cho đỡ rối.
    
-   AI phải bắt tôi đoán kết quả trước khi chạy code.
    
-   AI phải giải thích rõ `int` khác `float` chỗ nào.
    
-   Phải có **ít nhất 3 lần** tôi tự nghĩ, tự giải thích và sửa lại cách hiểu của tôi.
    
### 3. AI Gia sư cần làm gì ? 
Tôi viết prompt để AI đóng vai thầy/cô hướng dẫn theo đúng thứ tự:

  1.  Bắt tôi đoán kết quả trước.
    
2.  Hỏi vì sao lại ra kết quả như thế.
    
3.  Kiểm tra xem tôi có hiểu chia lấy phần nguyên trong C không.
    
4.  Gợi ý từng bước nhỏ khi tôi bí.
    
5.  Bảo tôi tự nghĩ cách sửa code.
    
6.  Nhận xét xem cách sửa của tôi đúng hay sai.
    
7.  Bảo mình lấy 1 ví dụ khác để chứng minh đã hiểu.
    
8.  Sau khi tôi tự sửa xong thì AI mới đưa code mẫu để tham khảo.
    
### 4. Những thứ cần nộp bài

Khi làm xong, tụi mình cần nộp đủ 6 phần này:

-   **Prompt đầy đủ** để tạo ra AI Gia sư.
    
-   **Đoạn chat** với AI có **ít nhất 8 lượt** qua lại.
    
-   **Giải thích lỗi** ở đoạn code ban đầu.
    
-   **Code mới** do tôi tự sửa.
    
-   **So sánh** chia số nguyên và chia số thực.
    
-   **Một ví dụ khác** tự nghĩ ra để cho thấy tôi đã hiểu bài.
