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
# Digital Data Representation
- Data type
- Binary notation
- Conversion of various base
- Integer notation
- Floating-point notation
- Character notation

# Bit and Bit Patterns
- Bit (binary digit) is the most basic unit of information in computing and digital communication. 
- Bit represents a logical state with one of two possible values. It could be represented as 1/0, true/false, yes/no, or on/off.
- Bit patterns are used to represent information.
  – Numbers
  – Text characters
  – Images
  – Sound
  – Others

# Byte (8 bits = 1 byte)
- Byte is a unit of digital information that most commonly consists of eight bits. (8 bits = 1 byte)
- Historically, the byte was the number of bits used to encode a single character of text in a computer and for this reason it is the smallest addressable unit of memory in many computer architectures. 
- N bits can be used in 2<sup>n</sup> different combinations to represent 2<sup>n</sup> different objects. 
- 8 bits generate 256 different objects (bit patterns), which is enough to represent every letter (52 uppercase and lowercase), numbers (0 to 9 for a total of 10) and punctuation.
- In ASCII, one character is represented by 8 bits.

# Unit of Size
| Unit| Full Name | Exact Bytes | Approximate Bytes | Example |
| --- | --- | --- | --- | --- |
| KB | Kilobyte | $2^{10}$ | $10^3$ | The size of this file is about 238 KB. |
| MB | Megabyte | $2^{20}$| $10^6$ | The size of this image is about 3.6 MB. |
| GB | Gigabyte | $2^{30}$| $10^9$ | The capacity of this DVD is 4.7 GB. |
| TB | Terabyte | $2^{40}$ | $10^{12}$ | This high-capacity disk can store 20 TB of data. |

# Data Types
- Data type: numbers, text, sound, image ... etc.
- The encoded string is stored on a computer, and when it is displayed or printed, it is decoded into the original data format.
- Digitization of images:
Taking a black-and-white photo as an example, a small part of the photo records the gray scale (0~255) of each square, and each square can be represented by eight digits (eight zeros and 1s can have 256 combinations).

#

https://youtu.be/mAMTXJJQBDI?si=8OFtSegqQM9_s0S9