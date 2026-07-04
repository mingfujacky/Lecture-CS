---
marp: true
theme: default
class: default
size: 16:9
paginate: true
header: 國立陽明交通大學 電子與光子學士學位學程
headingDivider: 1
style: |
  section::after {
    content: attr(data-marpit-pagination) '/' attr(data-marpit-pagination-total);
  }
  
  .small-grid {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 1rem;
  }
  .small-grid img {
    width: 50%;
  }
  .middle-grid {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 1rem;
  }
  .middle-grid img {
    width: 75%;
  }
  .grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 10px;
  }
  .grid img {
    width: 100%;
  }
  .red-text {
    color: red;
  }
  
  .blue-text {
    color: blue;  
  }

  .small-text {
    font-size: 0.50rem;
  }
---
# Introduction to Computer
> Computer (計算機 / 電腦) is a tool to support people to compute.

> A computer is a programmable device designed to store, retrieve, and process data to solve complex computational problems.

> A computer is a machine that can be programmed to automatically carry out sequences of computations such as arithmetic and logical operations. (Wikipedia)

[![What is a Computer?](https://i.ytimg.com/vi/lqChlibJYpA/mqdefault.jpg)](https://youtu.be/lqChlibJYpA?si=PzRWP_kgrMWdEgOn)

# Memorabilia of Computer
- 3000 BCE, Abacus (算盤)
- 1642, Blaise Pascal, mechanical adding machine (加法器)
- 1801, Joseph-Marie Jacquard, Jacquard loom (緹花織布機), use punch cards to control the weaving of patterns, introducing programming concept and data storage.
- 1937, Alan Turing, Turing machine (圖靈機), 證明了只要一組簡單的讀寫規則，加上無限的記憶體(紙帶)，就能夠執行任何複雜的演算法
[![圖靈機](https://i.ytimg.com/vi/fBqVKCyvXbM/mqdefault.jpg)](https://youtu.be/fBqVKCyvXbM?si=NU4m5K9lqVmwW1nB)

# Evolution of Computers
![w:900 evolutions of computers](asset/image/ch00_computer_generations.png)

# Personal Computer (PC)
- 1975, Altair 8800, the first personal computer (PC)
- 1977, Apple II, the first successful personal computer (PC)
- 1981, IBM open the PC architecture, PC become the most mainstream product
- 1981, Microsoft launch MS-DOS 1.0 (Microsoft Disk Operating System)
- 1984, Apple Macintosh, the first personal computer (PC) with GUI
- 1985, Microsoft launch Windows 1.0
![w:200 MSDOS 1.0](asset/image/ch00_MSDOS1.0.jpeg)

# Internet and World Wide Web (WWW)
[![Internet and WWW](https://i.ytimg.com/vi/M-01ii4zX_k/default.jpg)](https://youtu.be/M-01ii4zX_k?si=RToY4p15JAIXuwAB)
- 1969, ARPANET, an early computer network to transmit sensitive military data.
- 1989, World Wide Web (WWW), Tim Berners-Lee.
- 1993, Browsers: Mosaic, Netscape Navigator and Internet Explorer.
- 2000, dot com company boom and bust
- 2004, social media platforms: YouTube, Facebook
- 2007, smartphones, iPhone and Android
- 2010, IoT (internet of things)
- 2023, AI ChatGPT

# Common Architecture of Computers
The arithmetic logic unit and the control unit together are called the Central Processing Unit (CPU). CPU)。
