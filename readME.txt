# ✈️ TripDesk

> **Your all-in-one travel control center.**  
> A lightweight, reusable personal OS built to streamline your journeys—from pre-trip packing lists and flight/hotel logs to day-by-day itineraries and real-time utilities. One fixed architecture, endless destinations.

---

## 📌 Architecture

TripDesk 采用模块化设计的固定架构。每次开启新旅程时，可使用agent直接替换您的旅行信息，或手动修改代码，需要一张poster.png插图，除此之外，您无需重构任何视图。

```text
TripDesk/
├── 🧳 Pre         # 行前准备、清单管理
├── 🎫 Log         # 机酒预订、关键凭证
├── 🗺️ Plan        # 逐日行程、路线规划
└── 📝 Memo        # 汇率换算、备忘设置