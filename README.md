# StarChart — ดีไซน์ & Asset

> Repository รวบรวม **asset กราฟิก** และ **prototype** สำหรับแอป StarChart — ระบบ "ตารางดาว/ให้รางวัล" ธีมห้องเรียน (อยู่ในขั้นออกแบบ ยังไม่เริ่มพัฒนาโค้ด)

![Stage](https://img.shields.io/badge/Stage-Design%20%2F%20Prototype-orange)
![Type](https://img.shields.io/badge/Type-Assets%20%26%20Mockups-blue)

---

## ภาพรวม

Repository นี้เป็นพื้นที่เก็บ **สื่อกราฟิกและต้นแบบ (prototype)** ของแอป StarChart ยังไม่มีโค้ดโปรแกรม เนื้อหาหลักคือชุด UI asset และ asset ธีมห้องเรียน/ตารางเรียนที่เตรียมไว้ใช้ในขั้นพัฒนา รวมถึงไฟล์ต้นแบบที่ออกแบบด้วย Axure RP

> ⚠️ **หมายเหตุ:** ไฟล์ต้นแบบจริง (`.rp`) ยังไม่ได้ commit เข้ามา — ใน `document/` มีเพียง shortcut (`.lnk`) ที่ชี้ไปยังไฟล์บนเครื่องเดิม ควรเพิ่มไฟล์ `.rp` ตัวจริงหรือ export เป็น HTML/PDF เข้ามาแทน

## โครงสร้าง

```
starchart/
├── asset/
│   ├── FREEUIASSETPACK_BY@CAMTATZ/            # ชุด UI (ปุ่ม สไลเดอร์ checkbox ฯลฯ)
│   └── Classroom-elements-with-school-timetable/  # กราฟิกธีมห้องเรียน + ตารางเรียน
├── document/
│   └── starchart-prototype.rp.lnk            # (shortcut) ต้นแบบ Axure RP
└── README.md
```

## Asset ที่ใช้ และเครดิต / ลิขสิทธิ์

โปรเจกต์นี้ใช้ asset จากบุคคลที่สาม โปรดคงเครดิตไว้เมื่อนำไปใช้:

| Asset Pack | ผู้สร้าง | License |
|-----------|---------|---------|
| Platformer / UI Asset Pack #4 | Cam Tatz ([@CamTatz](https://twitter.com/CamTatz)) | Public Domain (ใช้ได้ทั้งงานส่วนตัวและเชิงพาณิชย์) |
| Classroom elements with school timetable | — | ตามไฟล์ License ในโฟลเดอร์ (ฟอนต์: **Amatic** by Vernon Adams) |

> ก่อนเผยแพร่/ใช้งานเชิงพาณิชย์ ควรตรวจสอบไฟล์ `License`, `free.txt`, `premium.txt` และ `Fonts.txt` ในแต่ละโฟลเดอร์ asset ให้แน่ใจว่าใช้ภายใต้เงื่อนไขที่ถูกต้อง

## สถานะโปรเจกต์

- [x] รวบรวม UI/graphic asset
- [x] ออกแบบ prototype (Axure)
- [ ] เพิ่มไฟล์ prototype ตัวจริงเข้า repo
- [ ] เริ่มพัฒนาแอป

## ขั้นตอนถัดไป (แนะนำ)

1. นำไฟล์ `.rp` ตัวจริงเข้ามา หรือ export prototype เป็น HTML/PDF เพื่อให้คนอื่นเปิดดูได้โดยไม่ต้องมี Axure
2. แยก asset ของบุคคลที่สามให้ชัด และเพิ่มไฟล์ `CREDITS.md`
3. เพิ่มไฟล์ `LICENSE` สำหรับส่วนที่เป็นงานของโปรเจกต์เอง
