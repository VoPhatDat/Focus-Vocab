# 🚀 Focus Vocab

Một con app học từ vựng do chính tui build để tự học (nói thẳng: vừa học vừa code 😏).

Không quảng cáo.
Không hiệu ứng màu mè gây nghiện.
Chỉ có: **học – nhớ – quên – kéo lại**.

---

## 🧠 Nó làm được gì?

* 📚 Quản lý từ vựng bằng file JSON
* 🃏 Flashcard để ôn nhanh
* ⌨️ Terminal mode để gõ lại (Active Recall thật sự)
* 📊 Phân loại: Từ mới / Tạm nhớ / Nhớ tốt / Chưa nhớ
* 🔥 Memory Decay Engine (không ôn = tụt level)
* 🛡 Resilience: ôn đúng nhiều → ít bị tụt lại
* 🏆 Rank system theo số từ đã thuộc

---

## 🎯 Triết lý

* Nhìn quen ≠ Nhớ
* Không gõ được = Chưa thuộc
* Không ôn = Chắc chắn quên

App này không cho bạn “ảo tưởng học giỏi”. Nó bắt bạn học thật.

---

## 🗂 Cách dùng

1. Import file JSON từ vựng
2. Chọn mode:

   * Flashcard → ôn nhanh
   * Terminal → gõ lại (hardcore mode)
3. Học mỗi ngày
4. Đừng để Memory Engine kéo bạn xuống 😈

---

## 📦 Cách tạo file JSON

App dùng format cực đơn giản, chỉ cần đúng 4 field:

```json
[
  {
    "word": "allocate",
    "ipa": "/ˈæl.ə.keɪt/",
    "translation": "phân bổ (nguồn lực, ngân sách)",
    "pos": "v"
  },
  {
    "word": "budget",
    "ipa": "/ˈbʌdʒ.ɪt/",
    "translation": "ngân sách",
    "pos": "n"
  }
]
```

👉 Lưu ý:

* Không cần id
* Không cần stats
* Chỉ cần đúng 4 field là chạy
* Có thể import hàng trăm từ một lần

---

## 🌐 Demo

👉 https://focus-vocab.netlify.app/

---

## ⚙️ Tech

* HTML
* TailwindCSS
* Vanilla JS
* LocalStorage
* Một chút logic chống quên tự chế

---

## 📌 Mục tiêu

Dùng để:

* Học TOEIC nghiêm túc
* Build vốn từ thật sự (không phải nhìn cho quen)
* Tạo hệ thống học phù hợp với chính mình

---

Nếu bạn muốn học thật → cứ clone về mà dùng.

Còn nếu bạn chỉ muốn lướt flashcard cho vui…
thì app này sẽ làm bạn thấy “khó chịu” đấy 😌
