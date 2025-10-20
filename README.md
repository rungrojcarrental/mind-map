  <div class="image-container">
    <a href="https://github.com/pripramot/i-studio">
      <p><img loading="lazy" src="https://cdn.hashnode.com/res/hashnode/image/upload/v1709320098585/ad7c1903-a3fb-4d9b-8408-dcba8d278bbf.png?auto=compress,format&amp;format=webp" alt="" class="image--center mx-auto"></p>
    </a>
  </div>

  <h4 align="center">
    <a href="https://mtify.hashnode.dev/">Get Started</a> |
    <a href="https://github.com/ai-jiraphinya/ai-jiraphinya/wiki">Docs</a> |
    <a href="https://nuxt-movies.vercel.app">By TMDB</a>
  </h4>
  <h1 align="center">Document Search By Mint</h1>
</p>

<p align="center">
  <a aria-label="Join the community on Slack" href="https://mtify.hashnode.dev">
    <img alt="" src="https://img.shields.io/badge/i_studio_hashnode-blue?link=https%3A%2F%2Fmtify.hashnode.dev">
  </a>
  <a aria-label="angular-movies-a12d3.web.app" href="https://angular-movies-a12d3.web.app">
    <img alt="" src="https://img.shields.io/badge/Mint_-angularmovies-red">
  </a>
  <a aria-label="Join the on Telegram" href="https://t.me/MintChatAI">
    <img alt="" src="https://img.shields.io/badge/Telegram_-%40Mint-%2326A5E4?style=flat&logo=telegram&link=https%3A%2F%2Ft.me%2FMintChatAI">
  </a>
  <a aria-label="Join the Mastodon" href="https://mastodon.social/@Mintify">
    <img alt="" src="https://img.shields.io/badge/Mastodon_-Jiraphinya-%236364FF?style=flat&logo=Mastodon">
  </a>
</p>
    

<!--


![Static Badge](https://img.shields.io/badge/i_studio_hashnode-blue?link=https%3A%2F%2Fmtify.hashnode.dev)
https://mtify.hashnode.dev/
<p align="center">
   <img src="https://res.cloudinary.com/mintmu/image/upload/v1707126516/ai-jiraphinya/jiraphinya_logo_svg.svg" width="256" height="256" alt="jiraphinya logo">
</p>

<p align="center">
  <a href="https://mtify.hashnode.dev">
    <img loading="lazy" src="https://cdn.hashnode.com/res/hashnode/image/upload/v1707950458022/9df4518d-5965-4179-8ea0-709300f11721.png?auto=compress,format&amp;format=webp" alt="" class="image--center mx-auto">
  </a>
-->

### support/ FRONT END , BACK END:ติดต่อเฮีย


# Gitmint Gittisak PDF Markdown

## เครื่องมือสร้าง Mind Map จากไฟล์ PDF

เว็บแอปพลิเคชันง่ายๆ ที่ช่วยแปลงเอกสาร PDF ของคุณให้กลายเป็น Mind Map แบบอินเทอร์แอกทีฟ (โต้ตอบได้) โดยใช้ AI อัจฉริยะอย่าง Gemini Pro จาก Google พัฒนาด้วย Next.js และ React Flow

## ฟีเจอร์เด่น

<strong>📄 อัปโหลดและประมวลผล PDF</strong>
  - รองรับการลากและวางไฟล์ (Drag & drop)
  - รองรับไฟล์ PDF ขนาดสูงสุด 5MB
  - แสดงสถานะการประมวลผลแบบเรียลไทม์

<br><strong>🧠 การวิเคราะห์ด้วย AI</strong>
  - สกัดประเด็นสำคัญจากเอกสารโดยอัตโนมัติ
  - จัดระเบียบเนื้อหาตามบริบทและความเชื่อมโยง
  - ขับเคลื่อนด้วย Gemini Pro จาก Google

<br><strong>🗺️ Mind Map แบบอินเทอร์แอกทีฟ</strong>
  - ย่อ/ขยายกิ่งก้าน (โหนด) ได้
  - ลากและย้ายตำแหน่งโหนดได้อิสระ
  - แอนิเมชันลื่นไหล สบายตา
  - มีแผนที่ขนาดเล็ก (Mini-map) ช่วยนำทาง
  - มีตารางพื้นหลัง (Grid) ช่วยให้ดูง่ายขึ้น

## เทคโนโลยีที่ใช้ (Tech Stack)

- **Framework**: Next.js 14 (App Router)
- **การแสดงผล Mind Map**: React Flow
- **การเชื่อมต่อ AI**: Google Gemini และ Vercel's AI SDK
- **การจัดสไตล์ (Styling)**: Tailwind CSS

## การเริ่มต้นใช้งาน (สำหรับนักพัฒนา)

1. โคลนโปรเจกต์ (Clone repository):

   ```bash
   git clone [https://github.com/rungrojcarrental/mind-map.git]

   ```
2. เข้าไปที่โฟลเดอร์โปรเจกต์:

    ```bash
    cd mind-map
    ```   

ติดตั้ง Dependencies (ส่วนเสริมที่จำเป็น):

Bash

npm install
# หรือ
yarn install
สร้างไฟล์ .env ที่โฟลเดอร์หลักของโปรเจกต์ และใส่ Google AI API Key ของคุณ:

ข้อมูลโค้ด
```bash
GOOGLE_GENERATIVE_AI_API_KEY=ใส่_API_Key_ของคุณที่นี่

```

รันเซิร์ฟเวอร์สำหรับพัฒนา:

```bash
npm run dev
# หรือ
yarn dev
```

เปิด http://localhost:3000 ในเบราว์เซอร์ของคุณ

รันเซิร์ฟเวอร์สำหรับพัฒนา:


```bash
npm run dev
# หรือ
yarn dev

```

## เปิด http://localhost:3000 ในเบราว์เซอร์ของคุณ

## วิธีใช้งาน (สำหรับผู้ใช้)

 - อัปโหลดไฟล์ PDF โดยการลากและวาง หรือกดปุ่มเลือกไฟล์

 - รอให้ AI วิเคราะห์เอกสารสักครู่

 - เริ่มใช้งาน Mind Map ที่สร้างเสร็จได้เลย:

### คลิกที่โหนด (จุด) เพื่อย่อ/ขยายกิ่ง ลากโหนดเพื่อจัดเรียงตำแหน่งใหม่ตามใจชอบ ใช้ Mini-map (แผนที่เล็ก) เพื่อเลื่อนดูภาพรวม ซูมเข้า-ออก หรือเลื่อนดูแผนที่ขนาดใหญ่ได้

การมีส่วนร่วม (Contributing)
เรายินดีต้อนรับทุกการมีส่วนร่วม! หากคุณมีไอเดียหรือต้องการแก้ไขปรับปรุง สามารถส่ง Pull Request เข้ามาได้เลยครับ

ใบอนุญาต (License)
โปรเจกต์นี้อยู่ภายใต้ใบอนุญาต MIT (ดูรายละเอียดเพิ่มเติมได้ที่ไฟล์ LICENSE)

## ขอบคุณ 

Vercel's AI SDK PDF Support สำหรับเครื่องมือประมวลผล PDF

React Flow สำหรับไลบรารีการแสดงผล Mind Map ที่ยอดเยี่ยม

Google Generative AI สำหรับพลังการวิเคราะห์ของ AI

Tailwind CSS สำหรับการออกแบบหน้าตาที่สวยงาม

## Usage

1. Upload a PDF document using the drag & drop interface or file picker
2. Wait for the AI to analyze the document
3. Explore the generated mind map:
   - Click nodes to expand/collapse branches
   - Drag nodes to rearrange the layout
   - Use the mini-map for navigation
   - Zoom and pan to explore larger maps

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- [Vercel's AI SDK PDF Support](https://vercel.com/docs/ai/ai-sdk/pdf-support) for the PDF processing
- [React Flow](https://reactflow.dev/) for the mind map visualization
- [Google Generative AI](https://ai.google.dev/) for the AI-powered analysis
- [Tailwind CSS](https://tailwindcss.com/) for the styling

## ไม่มีความจำเป็นใด จะต้องอธิบายให้คนทั้งโลกรับรู้ ในสิ่งที่คุณทำ เพราะ คนที่เคยดูถูกคุณ จะไม่เคยเชื่อในตัวคุณอยู่ดี

@สงวนลิขสิทธิ์ 2025 Gitmint Gittisak

