## LearnCSS


``` CSS
text-decoration: none;   /*ไม่แสดงเส้น link*/
cursor: pointer;
position: relative;
position: absolute;
text-transform: uppercase; /* แปลงข้อความให้เป็นตัวใหญ่ */
box-shadow: 0 0 5px rgba(0, 0, 0, 0.3);
border-radius: 0 8px 8px 0;
transition: all 0.45s ease;


transition-delay: 0s;
transition: width 1s ease 0s;
transition: width 1s ease 0s, height 1s ease 0s, background 1s ease 0s;
/*

transition-property: value;
transition-duration: value;
transition-delay: value;
transition-timing-function: value;

transition: [property] [duration] [timing-function] [delay];


CSS Transitions ทำอะไรได้บ้าง ?
Color
ค่อยๆ เปลี่ยนสี จากสีหนึ่งเป็นอีกสีหนึ่ง
Dimension
ค่อยๆ เปลี่ยนขนาด จากขนาดหนึ่งเป็นอีกขนาดหนึ่ง
Position
ค่อยๆ เปลี่ยนตำแหน่ง จากตำแหน่งหนึ่งเป็นอีกตำแหน่งหนึ่ง

Properties
สำหรับ properties ต่างๆ ที่ใช้ในการทำ CSS Transitions มีดังนี้

transition-property:
กำหนด property ที่จะใช้ transition
transition-duration:
กำหนดว่าจะให้ transition กินระยะเวลานานเท่าไร ค่า default คือ “0” คือไม่ทำ transition
transition-timing-function:
กำหนดรูปแบบของ speed ที่จะใช้กับ transition ค่า default คือ “ease”
transition-delay:
กำหนดเวลาที่จะเริ่มทำ transition ค่า default คือ “0” คือไม่มีดีเลย์

*/

overflow: hidden;
/*
Visible แสดงตัวอักษรที่อยู่ในกล่องทั้งหมด 
Hidden ซ่อนตัวอักษรที่ล้นกล่องออกมา 
Scroll ใช้ scroll bar แสดงผลตัวอักษรที่ล้นกล่อง 
Auto แสดงผลอัตโนมัติ คือถ้ามีข้อความล้นกล่องก็จะแสดง scroll ถ้าไม่มีก็จะแสดงกล่องธรรมดา 

https://www.hellomyweb.com/editor/css-overflow/
*/


-webkit-box-sizing: border-box; /* Firefox */
  box-sizing: border-box;
/*เพียงแค่เราเติม box-sizing: border-box; เข้าไปปุ้ป ความกว้างของ div ก็จะเท่ากับ width ที่เราตั้งไว้ เพราะมันจะบังคับให้ขนาดของ div กว้างเท่ากับ 200px ซึ่งเป็นขนาดที่รวม padding และ borders แล้ว*/

```


```CSS
/* การวัดขนาดจอ */

@media only screen and (max-width: 440px) {
    .snip .plan {
        width: 100%
    }
}

```