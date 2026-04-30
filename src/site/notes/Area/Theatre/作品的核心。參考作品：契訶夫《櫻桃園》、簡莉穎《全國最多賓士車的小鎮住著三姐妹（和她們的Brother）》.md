---
{"dg-publish":true,"dg-permalink":"cherry-orchard","permalink":"/cherry-orchard/","title":"作品的核心。參考作品：契訶夫《櫻桃園》、簡莉穎《全國最多賓士車的小鎮住著三姐妹（和她們的Brother）》","tags":["theatre","Chekhov","Russia"],"dg-note-properties":{"title":"作品的核心。參考作品：契訶夫《櫻桃園》、簡莉穎《全國最多賓士車的小鎮住著三姐妹（和她們的Brother）》","date":{"created":"2024-12-31T11:58:38","updated":"NaN"},"tags":["theatre","Chekhov","Russia"]}}
---

up:: [[Area/Theatre/劇本閱讀與一點點（真的一點點）寫作練習\|劇本閱讀與一點點（真的一點點）寫作練習]]
# 作品的核心。參考作品：契訶夫《三姐妹》、簡莉穎《全國最多賓士車的小鎮住著三姐妹（和她們的Brother）》

[劇本](https://www.ibiblio.org/eldritch/ac/chorch.htm)

[連結一](https://www.bilibili.com/video/BV1UN411T7fc/?spm_id_from=333.337.search-card.all.click)
[連結二](https://www.bilibili.com/video/BV1j34y1e7H1/?spm_id_from=333.788.recommend_more_video.-1)
[連結三](https://www.youtube.com/watch?v=RtRaHdir4NE)
[連結四](https://www.youtube.com/watch?v=YHGWoRY-t8M)
[連結五](https://www.youtube.com/watch?v=enNCf84knxo)
[連結六](https://www.bilibili.com/video/BV1Hk4y1X7ve/?spm_id_from=333.788.recommend_more_video.1)
[連結七](https://www.youtube.com/watch?v=VKFjXlKgbw0)
[連結八](https://www.bilibili.com/video/BV171C5YDEPz/?spm_id_from=333.788.recommend_more_video.-1)

[[Area/Entertainment/The Cherry Orchard\|The Cherry Orchard (NT Live)]]

本週作業：說一個只有你家族知道的習俗，例如：在陌生人的車前面大合照。

```meta-bind-button
label: "Share"
style: default
id: "share"
actions:
  - type: updateMetadata
    bindTarget: share
    evaluate: false
    value: true
  - type: replaceSelf
    replacement: "<!-- more -->"
```
```meta-bind-button
label: "In Progress"
style: default
id: "progress"
hidden: true
actions:
  - type: updateMetadata
    bindTarget: status
    evaluate: false
    value: "in progress"
  - type: updateMetadata
    bindTarget: date.updated
    evaluate: true
    value: moment().format("YYYY-MM-DDTHH:mm:ss")
```
```meta-bind-button
label: "Finished"
style: default
id: "finished"
hidden: true
actions:
  - type: updateMetadata
    bindTarget: status
    evaluate: false
    value: "finished"
  - type: updateMetadata
    bindTarget: date.finished
    evaluate: true
    value: moment().format("YYYY-MM-DDTHH:mm:ss")
```
`BUTTON[progress, finished]`
```meta-bind-button
label: "Upload"
style: default
id: "upload"
actions:
  - type: updateMetadata
    bindTarget: date.updated
    evaluate: true
    value: moment().format("YYYY-MM-DDTHH:mm:ss")
  - type: command
    command: obsidian-mkdocs-publisher:share-one
```