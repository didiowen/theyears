---
{"dg-publish":true,"dg-path":"  /改編的載體。參考作品：濱口龍介《在車上》、契訶夫《凡尼亞舅舅》、村上春樹〈Drive My Car〉.md","dg-permalink":"drive-my-car","permalink":"/drive-my-car/","title":"改編的載體。參考作品：濱口龍介《在車上》、契訶夫《凡尼亞舅舅》、村上春樹〈Drive My Car〉","tags":["theatre","Chekhov"],"updated":"2026-04-29T21:39:12.046+08:00","dg-note-properties":{"title":"改編的載體。參考作品：濱口龍介《在車上》、契訶夫《凡尼亞舅舅》、村上春樹〈Drive My Car〉","date":{"created":"2024-12-19T12:19:50","updated":null},"tags":["theatre","Chekhov"],"status":"waiting"}}
---

up:: [[Area/Theatre/劇本閱讀與一點點（真的一點點）寫作練習\|劇本閱讀與一點點（真的一點點）寫作練習]]
# 改編的載體。參考作品：濱口龍介《在車上》、契訶夫《凡尼亞舅舅》、村上春樹〈Drive My Car〉

[Drive My Car劇本](https://www.dropbox.com/scl/fi/kilbkz715j1u2y54phn2p/drivemycar.pdf?rlkey=d5gr5n62ivzdujw1s3wjfpol1&dl=0)

[連結一](https://www.bilibili.com/video/BV1Jz4y1c74s/?spm_id_from=333.337.search-card.all.click])
[連結二](https://www.bilibili.com/video/BV1Ap421S7od/?spm_id_from=333.337.search-card.all.click)
[連結三](https://www.bilibili.com/video/BV1MK4y187DH/?spm_id_from=333.337.search-card.all.click)
[連結四](https://www.bilibili.com/video/BV1oS4y1e7e4/?spm_id_from=333.337.search-card.all.click)
[連結五](https://www.bilibili.com/video/BV12z421f7UZ/?spm_id_from=333.337.search-card.all.click)

本週作業：講一個好笑的段子讓大家笑。

[[Area/Reading/Uncle Vanya\|Uncle Vanya]]

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