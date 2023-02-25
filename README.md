<!DOCTYPE html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />

    <!-- Bootstrap CSS -->
    <link
      rel="stylesheet"
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/css/bootstrap.min.css"
      integrity="sha384-fG5z5I23YaYjr98P5gJG/0ov/HiHmSzvXY8DLmdfIZNzJLXdQSmrSTwK8jF0/zxO"
      crossorigin="anonymous"
    />

    <title>Hello, world!</title>
  </head>
  <style>
    /* Style the table */
    table {
      width: 100%;
      border-collapse: collapse;
    }

    /* Style the table header */
    th {
      background-color: #f2f2f2;
      text-align: left;
      padding: 8px;
    }

    /* Style the table rows */
    tr:nth-child(even) {
      background-color: #f2f2f2;
    }

    /* Style the table cells */
    td {
      padding: 8px;
      border: 1px solid #ddd;
    }

    /* Responsive styles for small screens */
    @media screen and (max-width: 600px) {
      /* Hide the table header */
      th {
        display: none;
      }

      /* Make the table rows stack on top of each other */
      tr {
        border-bottom: 1px solid #ddd;
        display: block;
        margin-bottom: 10px;
      }

      /* Style the table cells in the stacked rows */
      td {
        border-bottom: 1px solid #ddd;
        display: block;
        text-align: right;
      }

      /* Add a label for each cell in the stacked rows */
      td:before {
        content: attr(data-label);
        float: left;
        font-weight: bold;
        text-transform: uppercase;
      }
    }
  </style>
  <body>
<div class="container-md">
    <table class="table">
      <thead>
        <tr>
          <th scope="col">ข้อ</th>
          <th scope="col">คำตอบ</th>
        </tr>
      </thead>
      <tbody>
        <!-- 5.1 -->
        <tr>
          <td>5.1</td>
          <td>
            เมื่อ mitogen ผูกกับ mitogen receptor บนผิวเซลล์
            เซลล์จะรับรู้สัญญาณและส่งต่อไปยัง Intracellular signaling pathway
            เมื่อ mitogen receptor ถูกกระตุ้น จะมีการเปิด ปิดสถานะของโปรตีนต่าง
            ๆ ที่มีผลต่อการแบ่งเซลล์
          </td>
        </tr>
        <!-- 5.2 -->
        <tr>
          <td>5.2</td>
          <td>
            ยีนของ Rb protein ที่ถูก transcription และ translation
            มีหน้าที่ควบคุมการเข้าสู่สถานะการแบ่งเซลล์ ป้องกันการเกิดมะเร็ง
            และควบคุมการตอบสนองต่อการส่งสัญญาณของเซลล์ (cell signaling)
            รวมถึงหน้าที่ในการควบคุมการสร้างเลือดและสมดุลเซลล์ด้วย
          </td>
        </tr>
        <!-- 5.3 -->
        <tr>
          <td>5.3</td>
          <td>
            ยังไม่ได้สรุป<br />
            จากภาพที่แสดงการเจริญเติบโตของเซลล์แบบแบ่งตัวและการคัดลอกเอนไซม์ DNA
            จะเห็นว่าเส้นใย DNA มีการแบ่งตัวออกเป็นสองเส้น และส่วนของเอนไซม์ DNA
            ที่คัดลอกออกมานั้นก็มีการแยกตัวกันออกเป็นสองชุดหากเกิดความเสียหายต่อเอนไซม์
            DNA ซึ่งอาจเกิดจากสิ่งต่างๆ เช่น สารเคมี, รังสี, หรือความเครียดต่างๆ
            ก็จะทำให้การคัดลอกและเจริญเติบโตของเอนไซม์ DNA ถูกยับยั้ง
            ซึ่งอาจส่งผลให้ระบบ Cell cycle ถูกหยุดชะงัก
            หรือแย่งแย้งกันของสารเคมีที่เป็นส่วนประกอบของระบบ cell cycle เช่น
            cyclin และ CDK (Cyclin-dependent kinase)
            ทำให้การแบ่งตัวของเซลล์ไม่สามารถเกิดขึ้นได้
            ซึ่งจะส่งผลให้เกิดการหยุดชะงักของการแบ่งตัวของเซลล์
            ซึ่งสามารถส่งผลกระทบต่อการเจริญเติบโตและการทำงานของเซลล์ต่อไปได้
          </td>
        </tr>
        <!-- 5.4 -->
        <tr>
          <td>5.4</td>
          <td>
            ยังไม่ได้สรุป<br />
            Protein p21
            เป็นหนึ่งในสารสัญญาณที่มีประโยชน์ในการควบคุมการแบ่งตัวของเซลล์
            โดยมีหน้าที่ป้องกันเซลล์ไม่ให้แบ่งตัวเมื่อเกิดความเสี่ยงต่อการเจ็บป่วย
            เช่น กรณีที่เอนไซม์ DNA เสียหาย
            ซึ่งเป็นเหตุการณ์ที่อาจส่งผลกระทบต่อสุขภาพของเซลล์ ดังนั้นหาก
            protein p21 สูญเสียการทำงานไปแล้วแต่ DNA ไม่เสียหาย
            จะทำให้เซลล์แบ่งตัวได้ตามปกติ แต่หาก DNA มีความเสียหายแล้วไม่มี
            protein p21 ที่มาป้องกันการแบ่งตัวของเซลล์
            เซลล์จะเข้าสู่สถานะซ่อมแซม DNA ก่อนที่จะแบ่งตัวต่อไป
            โดยทำให้เกิดการหยุดชะงักของ cell cycle ในช่วง G1 phase และ S phase
            จนกว่าเอนไซม์ DNA จะถูกซ่อมแซมเสร็จสมบูรณ์ หลังจากนั้น cell cycle
            จะดำเนินต่อไปได้ตามปกติและเซลล์จะแบ่งตัวเมื่อถึงเวลาที่เหมาะสมในช่วง
            G2 phase และ M phase ต่อไป
          </td>
        </tr>
        <!-- 5.5 -->
        <tr>
          <td>5.5</td>
          <td>
            การตอบสนองต่อสัญญาณกระตุ้นให้เริ่มแบ่งเซลล์:
            เป็นขั้นตอนแรกที่เกิดขึ้นในการแบ่งเซลล์
            โดยเมื่อมีสัญญาณกระตุ้นเข้ามา เช่น สารสังเคราะห์ได้
            จะทำให้เซลล์รับรู้และเริ่มเตรียมตัวเพื่อทำการแบ่งเซลล์
            <br />
            การจำลอง DNA (chromosome): เป็นการสร้างโมเดลของโครโมโซม
            เพื่อศึกษาและวิเคราะห์โครโมโซมว่ามีลักษณะอย่างไร
            มีส่วนประกอบอะไรบ้าง และเป็นอย่างไรในแต่ละช่วงของการแบ่งเซลล์
            <br />
            การแบ่ง DNA (chromosome): เป็นขั้นตอนที่เกิดขึ้นในการแบ่งเซลล์
            โดยโครโมโซมจะถูกแบ่งออกเป็นสองชุด
            โดยมีการสลับและรวมเอาเพื่อนกันกับโครโมโซมที่สำเร็จการแบ่งก่อนหน้านี้
            ซึ่งจะสร้างเป็นเซลล์ลูกสองเซลล์
            <br />
            การแบ่ง cytoplasm: เป็นขั้นตอนสุดท้ายของการแบ่งเซลล์
            โดยเซลล์ลูกจะแบ่งแยกจากกันด้วยการสร้างกล้ามเนื้อโครงการแบ่ง
            (contractile ring) ที่จะดึงเอาเม็ดเล็กๆ ๆ จากส่วนกลางของเซลล์
            จนกว่าเซลล์จะแบ่งแยกออกเป็นเซลล์ลูกสองเซลล์ที่แยกกันได้สมบูรณ์
          </td>
        </tr>
        <!-- 5.6 -->
        <tr>
          <td>5.6</td>
          <td>
            TNF (Tumor necrosis factor)
            เป็นโปรตีนชนิดหนึ่งที่เป็นส่วนสำคัญในการกระตุ้นการเกิดอัตโนมัติของเซลล์
            (apoptosis) ในเซลล์ต่างๆในร่างกาย การกระตุ้นการทำลาย DNA ใน
            apoptosis โดย TNF เกิดขึ้นโดยการเชื่อมต่อ TNF receptor บนผิวเซลล์
            เมื่อ TNF เชื่อมต่อกับ TNF receptor
            จะทำให้เกิดสัญญาณภายในเซลล์ที่เรียกว่า TNF receptor-associated death
            domain (TRADD)
            และต่อมาจะกระตุ้นการเชื่อมต่อกับส่วนอื่นๆของสัญญาณภายในเซลล์ เช่น
            Fas-associated death domain (FADD) และ caspases เป็นต้น เมื่อ
            caspases ถูกกระตุ้นให้เปิดตัว
            จะทำให้เกิดการตัดสินใจของเซลล์ในการเริ่มต้นกระบวนการทำลาย DNA ใน
            apoptosis โดย caspases จะตัดขั้วที่สำคัญของสารสังเคราะห์ DNA เช่น
            PARP (poly (ADP-ribose) polymerase) ซึ่งเป็นส่วนสำคัญในการซ่อมแซม
            DNA ทำให้เซลล์เสียชีวิตและก่อให้เกิดการทำลายของเซลล์ (apoptosis)
          </td>
        </tr>
      </tbody>
    </table>
</div>
    <!-- Optional JavaScript; choose one of the two! -->

    <!-- Option 1: Bootstrap Bundle with Popper -->
    <script
      src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/js/bootstrap.bundle.min.js"
      integrity="sha384-OkwVN8eMxJjKlOZQ4N/mO9XN4eHJrp+5yBfS/5hpxghHV7x3qjKuZmVhoHY9Xwxm"
      crossorigin="anonymous"
    ></script>

    <!-- Option 2: Separate Popper and Bootstrap JS -->
    <!--
    <script src="https://code.jquery.com/jquery-3.6.0.min.js" integrity="sha384-4oVp4TU4CVQ+TZ6m9PTgS4e7SQ8S8L4pGgzI1kVpFnXTjhXV/cjM9NhXQ2Ia8jWm" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@2.10.2/dist/umd/popper.min.js" integrity="sha384-F4oxq2m9jBA8inmF5/bvZw/eHtDn/LLgAgt2HD45BXtjYcN1hXttxLTpJNbevLop" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/js/bootstrap.min.js" integrity="sha384-5xwRZd5z/ZSjKry08+sRxDAj4M2QORqFc4nB6WxhqJquKZ+QoxqTWjjC8VV1hJ/C" crossorigin="anonymous"></script>
    -->
  </body>
</html>
