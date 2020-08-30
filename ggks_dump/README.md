# 灭共视频转录数据
本文件夹下以csv格式保存了灭共视频部分转录数据，包含 *videos.csv* 以及 *files/(数字).csv*

## 人工校对
本站现召集义工对转录文字进行人工校对，请有意者：
1. [在这里登记认领](https://docs.google.com/spreadsheets/d/1KHBNZro4Z0ncBMk3zrHdST04fS3YeuP7MloZ9bD-4l0/edit?usp=sharing)。
2. 登记后下载对应文件，可直接在proofed列修改。请勿改动其他列。
3. 校对完的数据可通过pull requests发回，也可以将文件发送至*G-Talent技术社区*的*中国特色*，还可以发送邮件至*zhongguotese419@gmail.com*。
4. 各位义工记得[登记自己的工时记录](https://forms.gle/nj6AfGTrHSkofLr59)。

## 文件格式
### videos.csv
| 列 | 描述 |
| --- | --- |
| id | 视频的编号，与 *(数字).csv* 的文件名对应 |
| title | 视频的标题 |
| description | 视频的描述 |
| date | 视频发布的日期 |
| youtube_url | 视频的网址 |
| youtube_id | 视频在YouTube上的ID |

### files/(数字).csv
**文件名对应 _videos.csv_ 的id**
| 列 | 描述 |
| --- | --- |
| id | 句子的编号 |
| index | 当前句子在该视频中的序号 |
| content | 由Google转录的文字 |
| proofed | 由程序根据[ourhimalayas](https://github.com/ourhimalayas/txt)整理的文字校对的结果 |
