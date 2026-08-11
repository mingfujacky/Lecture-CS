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
> Computer is a tool to support people to compute.

> A computer is a machine that can be programmed to automatically carry out sequences of computations such as arithmetic and logical operations. (Wikipedia)

[![What is a Computer?](https://i.ytimg.com/vi/lqChlibJYpA/mqdefault.jpg)](https://youtu.be/lqChlibJYpA?si=PzRWP_kgrMWdEgOn)

# Computing Tool Foundation
- 3000 BCE, Abacus (算盤)
- 1642, Blaise Pascal, mechanical adding machine (機械式加法器)
- 1801, Joseph-Marie Jacquard, Jacquard loom (緹花織布機), use punch cards (打孔卡片) to control the patterns, introducing programming concept and data storage.
- 1937, Alan Turing, Turing machine (圖靈機), 圖靈機不是一個真正的「機器」，而是「理論數學」的模型。證明了只要一組簡單的讀寫規則，加上無限的記憶體(紙帶)，就能夠執行任何複雜的演算法.

# Modern Computer Development
The core of modern computer evolution lies in the electronization of hardware and the adoption of binary computation, enabling optimal efficiency in data storage, processing, and transmission.
![w:700 evolutions of computers](asset/image/ch00_computer_generations.png)

# Moore's Law (摩爾定律)
- Moore's law is the observation that the number of transistors in an integrated circuit (IC) doubles about every two years, with minimal increase in cost.

# Personal Computer (PC)
- 1975, Altair 8800, the first personal computer (PC)
- ![w:400 PC Story](asset/image/ch00_pc_story.png)

- [![PC Story](https://i.ytimg.com/vi/Aq1IANgRV0k/mqdefault.jpg)](https://youtu.be/Aq1IANgRV0k?si=dkngmyoSRG-UIhvi)

- 1981, Microsoft launch MS-DOS 1.0 (Microsoft Disk Operating System)
- 1985, Microsoft launch Windows 1.0


# The Evolution of the Internet (1)
[![Internet and WWW](https://i.ytimg.com/vi/M-01ii4zX_k/mqdefault.jpg)](https://youtu.be/M-01ii4zX_k?si=RToY4p15JAIXuwAB)

# The Evolution of the Internet (2)
- 1969, ARPANET, a U.S. research network funded by ARPA.
- 1983, TCP/IP becomes the common Internet protocol.
- 1989, Tim Berners-Lee proposes the World Wide Web at CERN.
- 1993, Mosaic popularizes graphical web browsing
- 1994–1995, Netscape Navigator and Internet Explorer.
- 2000–2001, dot-com bubble boom and bust.
- 2004–2005, social media expands: Facebook and YouTube.
- 2007–2008, smartphones and app stores: iPhone, Android, mobile apps.
- 2010s, IoT, cloud computing, and mobile broadband expand.
- 2022–2023, ChatGPT launches and generative AI becomes mainstream.

# General Architecture of Computers
The general architecture of today's computers is based on the von Neumann Model (馮紐曼模式), which is based on the concept of **stored program**, including four subsystems
- Memory: store data and programs
- Arithmetic Logic Unit (ALU): perform arithmetic and logical processing
- Control Unit (CU): direct other subsystems and tells them what to do.
- Input／Output: keyboard, mouse, screen, printer

> ALU + CU = CPU (Central processing Unit)

# von Neumann Model
![w:600 von Neumann Model](asset/image/ch00_von_neumann_model.png)

[![von Neumann Model](https://i.ytimg.com/vi/VTabBKNdlFc/default.jpg)](https://youtube.com/shorts/VTabBKNdlFc?si=S8mdNVJBDVd6PTlP)

