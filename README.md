# การจัดการความรู้ยุคดิจิทัล: การประยุกต์ใช้ Generative AI เพื่อสร้างสรรค์คอนเทนต์และสื่อการสอน

Repo นี้รวบรวมไฟล์และตัวอย่างที่ใช้ประกอบการบรรยายหัวข้อ
**“การจัดการความรู้ยุคดิจิทัล: การประยุกต์ใช้ Generative AI เพื่อสร้างสรรค์คอนเทนต์และสื่อการสอน”**

## รายละเอียดการบรรยาย

| | |
|---|---|
| **วันที่** | 27 พฤศจิกายน 2569 |
| **เวลา** | 08.30–16.30 น. |
| **สถานที่** | ห้องประชุม 16/203 คณะเทคโนโลยีสารสนเทศ |
| **วิทยากร** | อ.วันฉัตร พูขุนทด |

## เนื้อหาบรรยาย

### แผนที่ AI ฉบับหน้าเดียว: ตั้งแต่โมเดลถึงเครื่องมือ

สรุปภาพรวม AI ในหน้าเดียว แบ่งเป็น 6 ส่วน

1. **Model Landscape** ใครเป็นใคร
2. **Model Type** แยกตามสิ่งที่รับเข้าและสร้างออก
3. **Flow** Prompt → Model → Output
4. **เปิดกล่องดำ** Transformer → LLM
5. **Skill** ล็อกผลลัพธ์ให้คงที่
6. **MCP** Model Context Protocol

| ไฟล์ | รูปแบบ |
|---|---|
| [index.html](lecture/ai-map-one-page/index.html) | หน้าเว็บ (เปิดในเบราว์เซอร์ สลับธีมสว่างและมืดตามเครื่อง) |
| [ai-map-one-page.png](lecture/ai-map-one-page/export/ai-map-one-page.png) / [.pdf](lecture/ai-map-one-page/export/ai-map-one-page.pdf) | ธีมสว่าง |
| [ai-map-one-page-dark.png](lecture/ai-map-one-page/export/ai-map-one-page-dark.png) / [.pdf](lecture/ai-map-one-page/export/ai-map-one-page-dark.pdf) | ธีมมืด |

## Skill ที่ใช้ในการบรรยาย

| Skill | ใช้ทำอะไร | โฟลเดอร์ |
|---|---|---|
| **lecture-clip-production** | ชุดผลิตรายวิชาและคลิปบรรยายออนไลน์: เริ่มวิชาใหม่จากคำอธิบายรายวิชา PLO และ CLO เขียน ตรวจ และส่งออก script คลิปบรรยาย รวมถึง quiz ใบงาน และคู่มือกิจกรรม | [skills/lecture-clip-production](skills/lecture-clip-production) |
| **motion-graphic-dsh-fast** | ปลั๊กอิน Motion graphics สำหรับ DeepSeek Harness: สร้างโมชันกราฟิกจากหัวข้อ ตั้งแต่บทพูด ภาพวาด SVG ดนตรีประกอบ จนถึง composition แบบ HTML ที่ render เป็น MP4 ด้วย HyperFrames มี 3 skill คือ `mg-fast`, `mg-hyperframes` และ `mg-hyperframes-cli` | [skills/motion-graphic-dsh-fast](skills/motion-graphic-dsh-fast) |

วิธีติดตั้งและสิ่งที่ต้องมีในเครื่องของ motion-graphic-dsh-fast ดูที่ [README ของปลั๊กอิน](skills/motion-graphic-dsh-fast/README.md)
ส่วน skill ของ HyperFrames ที่รวมมาในปลั๊กอินเป็นของโครงการ [HyperFrames](https://github.com/heygen-com/hyperframes) (Apache-2.0) ดูรายละเอียดที่ [ATTRIBUTION.md](skills/motion-graphic-dsh-fast/ATTRIBUTION.md)

## การดาวน์โหลดไฟล์

```bash
git clone https://github.com/Wanchatpookhuntod/lecture_ai_motion-video.git
```

หรือกดปุ่ม **Code → Download ZIP** บนหน้า GitHub
