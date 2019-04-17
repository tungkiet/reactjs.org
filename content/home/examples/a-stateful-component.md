---
title: Một Stateful Component
order: 1
domid: timer-example
---

Ngoài việc lấy dữ liệu đầu vào (được truy cập qua `this.props`), một component có thể duy trì dữ liệu state bên trong (được truy cập qua `this.state`). Khi dữ liệu trạng thái component thay đổi, đánh dấu kết xuất sẽ được cập nhật bằng cách gọi lại `render()`.